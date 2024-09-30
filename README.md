# projeto 17 mysql all for one

Um projeto com o codinome All For One para praticar todos os conceitos de SQL usando o banco de dados Northwind.

## Habilidades
    Entender como a linguagem de consulta estruturada (SQL) é usada;
    Compreender como as tabelas se encaixam no conceito de banco de dados;
    Montar um ambiente de desenvolvimento local para praticar SQL;
    Entender como usar o MySQL Workbench.
    Compreender o que é uma query SQL e quais são seus tipos de comando;
    Gerar valores com SELECT;
    Selecionar colunas individualmente com SELECT;
    Renomear e gerar colunas em uma consulta com AS;
    Concatenar colunas e valores com CONCAT;
    Remover dados duplicados em uma consulta com DISTINCT;
    Contar a quantidade de resultados em uma consulta com COUNT;
    Limitar a quantidade de resultados em uma consulta com LIMIT;
    Pular resultados em uma consulta com OFFSET;
    Ordenar os resultados de uma consulta com ORDER BY.
    Filtrar resultados de consultas com o WHERE.
    Utilizar operadores booleanos e relacionais em consultas.
    Criar consultas mais dinâmicas e maleáveis com LIKE.
    Fazer consultas que englobam uma faixa de resultados com IN e BETWEEN.
    Encontrar e separar resultados que incluem datas
    Inserir dados em tabelas com INSERT
    Atualizar dados em tabelas com UPDATE
    Apagar dados em tabelas com DELETE


# Como executar

**1. Clone o repositório**
```shell
    git clone git@github.com:CalebeLAR/trybe_17_mysql_all_for_one.git
```

**2. rodando o docker**
```shell
    docker compose up -d
```

## Requisitos

### 1 - Exiba apenas os nomes dos produtos na tabela `products`.

![requisito 01](<images/Screenshot from 2024-09-30 14-12-50.png>) 

### 2 - Exiba os dados de todas as colunas da tabela `products`.

![requisito 02](<images/Screenshot from 2024-09-30 14-12-54.png>) 

### 3 - Escreva uma query que exiba os valores da coluna que representa a _primary key_ da tabela `products`.

![requisito 03](<images/Screenshot from 2024-09-30 14-12-59.png>) 

### 4 - Conte quantos registros existem na coluna `product_name` da tabela `products`.

![requisito 04](<images/Screenshot from 2024-09-30 14-13-04.png>) 

### 5 - Monte uma query que exiba os dados da tabela `products` a partir do quarto registro até o décimo terceiro.

![requisito 05](<images/Screenshot from 2024-09-30 14-13-09.png>) 

### 6 - Exiba os dados das colunas `product_name` e `id` da tabela `products` de maneira que os resultados estejam em ordem alfabética dos nomes.

![requisito 06](<images/Screenshot from 2024-09-30 14-13-13.png>) 

### 7 - Mostre apenas os ids dos 5 últimos registros da tabela `products` (a ordernação deve ser baseada na coluna `id`).

![requisito 07](<images/Screenshot from 2024-09-30 14-13-17.png>) 

### 8 - Faça uma consulta que retorne três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'.

![requisito 08](<images/Screenshot from 2024-09-30 14-13-22.png>) 

### 9 - Mostre todos os valores de `notes` da tabela `purchase_orders` que não são nulos.

![requisito 09](<images/Screenshot from 2024-09-30 14-13-26.png>) 

### 10 - Mostre todos os dados da tabela `purchase_orders` em ordem decrescente, ordenados por `created_by` em que o `created_by` é maior ou igual a 3.

![requisito 10](<images/Screenshot from 2024-09-30 14-13-33.png>) 

### 11 - Exiba os dados da coluna `notes` da tabela `purchase_orders` em que seu valor de `Purchase generated based on Order` é maior ou igual a 30 e menor ou igual a 39.

![requisito 11](<images/Screenshot from 2024-09-30 14-13-37.png>) 

### 12 - Mostre as `submitted_date` de `purchase_orders` em que a `submitted_date` é do dia 26 de abril de 2006.

![requisito 12](<images/Screenshot from 2024-09-30 14-13-44.png>) 

### 13 - Mostre o `supplier_id` das `purchase_orders` em que o `supplier_id` seja 1 ou 3.

![requisito 13](<images/Screenshot from 2024-09-30 14-13-48.png>) 

### 14 - Mostre os resultados da coluna `supplier_id` da tabela `purchase_orders` em que o `supplier_id` seja maior ou igual a 1 e menor ou igual 3 

![requisito 14](<images/Screenshot from 2024-09-30 14-16-16.png>) 

### 15 - Mostre somente as horas (sem os minutos e os segundos) da coluna `submitted_date` de todos registros da tabela `purchase_orders`.

![requisito 15](<images/Screenshot from 2024-09-30 14-16-20.png>) 

### 16 - Exiba a `submitted_date` das `purchase_orders` que estão entre `2006-01-26 00:00:00` e `2006-03-31 23:59:59`.

![requisito 16](<images/Screenshot from 2024-09-30 14-16-24.png>) 

### 17 - Mostre os registros das colunas `id` e `supplier_id` das `purchase_orders` em que os `supplier_id` sejam tanto 1, ou 3, ou 5, ou 7.

![requisito 17](<images/Screenshot from 2024-09-30 14-16-28.png>) 

### 18 - Mostre todos os registros de `purchase_orders` que tem o `supplier_id` igual a 3 e `status_id` igual a 2.

![requisito 18](<images/Screenshot from 2024-09-30 14-16-32.png>) 

### 19 - Mostre a quantidade de pedidos que foram feitos na tabela `orders` pelo `employee_id` igual a 5 ou 6, e que foram enviados através do método(coluna) `shipper_id` igual a 2.

![requisito 19](<images/Screenshot from 2024-09-30 14-16-35.png>) 

### 20 - Adicione à tabela `order_details` um registro com `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129.

![requisito 20](<images/Screenshot from 2024-09-30 14-16-40.png>) 

### 21 - Adicione com um único `INSERT`, duas linhas à tabela `order_details` com os mesmos dados do  requisito 20.

![requisito 21](<images/Screenshot from 2024-09-30 14-16-44.png>) 

### 22 - Atualize todos os dados da coluna `discount`, na tabela `order_details`, para 15.

![requisito 22](<images/Screenshot from 2024-09-30 14-16-48.png>) 

### 23 - Atualize os dados da coluna `discount` da tabela `order_details` para 30, onde o valor na coluna `unit_price` seja menor que 10.0000.

![requisito 23](<images/Screenshot from 2024-09-30 14-16-55.png>) 

### 24 - Atualize os dados da coluna `discount` da tabela `order_details` para 45, onde o valor na coluna `unit_price` seja maior que 10.0000 e o id seja um número entre 30 e 40.

![requisito 24](<images/Screenshot from 2024-09-30 14-16-59.png>) 

### 25 - Delete todos os dados em que a `unit_price` da tabela `order_details` seja menor que 10.0000.

![requisito 25](<images/Screenshot from 2024-09-30 14-17-04.png>) 

### 26 - Delete todos os dados em que a `unit_price` da tabela `order_details` seja maior que 10.0000.

![requisito 26](<images/Screenshot from 2024-09-30 14-17-08.png>) 

### 27 - Delete todos os dados da tabela `order_details`.

![requisito 27](<images/Screenshot from 2024-09-30 14-17-13.png>)


