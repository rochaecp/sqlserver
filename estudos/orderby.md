# SQL Server - DQL (Data Query Language)

## ORDER BY

~~~sql
SELECT 
    nome_produto, 
    preco
FROM 
    producao.produtos
WHERE 
    preco <= 30000
ORDER BY
    preco ASC, -- ASC (default)
    LEN (nome_produto) DESC
~~~