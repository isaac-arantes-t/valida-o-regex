# valida-o-regex
trabalho de front end atividade passada em sala.

Neste código, a validação dos campos de nome, e-mail e telefone é realizada utilizando expressões regulares, também conhecidas como regex. As expressões regulares são padrões de texto que descrevem um conjunto de strings possíveis de forma concisa e flexível. Elas são aplicadas aos valores inseridos nos campos do formulário para garantir que estejam em conformidade com os critérios desejados antes do envio do formulário.

Para o campo de nome, a expressão regular ^[a-zA-ZÀ-ú\s']+$ valida se o nome contém apenas letras, espaços e apóstrofos. Ela verifica cada caractere do nome para garantir que esteja dentro desse conjunto de caracteres permitidos.

Já para o campo de e-mail, a expressão regular ^[^\s@]+@[^\s@]+\.[^\s@]{2,}$ verifica se o e-mail possui pelo menos um "@" e termina com ".com" ou ".br". Isso é feito analisando os caracteres antes e depois do "@" e garantindo que o domínio tenha pelo menos dois caracteres após o ponto.

Por fim, para o campo de telefone, a expressão regular ^[0-9]{2} [0-9]{4,5}-[0-9]{4}$ valida se o telefone está no formato comum de números de telefone no Brasil, como "xx xxxx-xxxx" ou "xx xxxxx-xxxx". Ela verifica cada parte do número de telefone, incluindo o DDD e os dígitos separados por hífen.

Essas expressões regulares são essenciais para garantir a integridade e a validade dos dados inseridos no formulário, contribuindo para uma melhor experiência do usuário e para a precisão das informações recebidas.
