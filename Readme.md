# Introdução ao comandos SQL

## Conceito

A linguagem SQL é o recurso que usamos para conversar com nosso banco de dados relacional, por meio dela que criamos as tabelas, colunas e realizamos consultas a dados.

## Organização

A linguagem SQL é organizada em subconjuntos, cada um com propósitos bem definidos:

![image](https://user-images.githubusercontent.com/62342894/173424870-5e531cb6-cd81-4b29-91e7-e30747444b39.png)


# Principais comandos

![image](https://user-images.githubusercontent.com/62342894/173424979-196be365-ae16-4546-a841-95eacd3ca331.png)
![image](https://user-images.githubusercontent.com/62342894/173425007-15cd95df-18e0-4f8e-a3ff-e774a28b2b6f.png)
![image](https://user-images.githubusercontent.com/62342894/173425021-89d90a41-2f3a-43a1-9334-4e993336446e.png)

## Join SQL

A cláusula JOIN permite que os dados de várias tabelas sejam combinados com base na relação
existente entre elas.

Por meio dessa cláusula, os dados de uma tabela são usados para selecionar os dados pertencentes à outra tabela

### INNER JOIN

A cláusula INNER JOIN permite usar um operador de comparação para comparar os valores de colunas provenientes de tabelas associadas. Por meio desta
cláusula, os registros de duas tabelas são usados para que sejam gerados os dados relacionados de ambas

![image](https://user-images.githubusercontent.com/62342894/173425142-ab872d4e-b4da-49b5-a58b-17a8ac149b28.png)

### LEFT JOIN

A cláusula LEFT JOIN ou LEFT OUTER JOIN permite obter não apenas os dados relacionados de duas tabelas, mas também os dados não relacionados encontrados na
tabela à esquerda da cláusula JOIN. Caso não existam dados relacionados entre as tabelas à esquerda e a direita do JOIN, os valores resultantes de todas as colunas da lista de seleção da tabela à direita serão nulos.

![image](https://user-images.githubusercontent.com/62342894/173425302-3415e421-82c5-4405-bd0c-648e22ca7143.png)

### RIGHT JOIN

Ao contrário do LEFT JOIN, a cláusula RIGHT JOIN ou RIGHT OUTER JOIN retorna todos os dados encontrados na tabela à direita de JOIN. Caso não existam
dados associados entre as tabelas à esquerda e à direita de JOIN, serão retornados valores nulos.

![image](https://user-images.githubusercontent.com/62342894/173425362-e509b3ad-8646-47d0-8571-13c8fb3c6ad7.png)

### FULL JOIN

Todas as linhas de dados da tabela à esquerda de JOIN e da tabela à direita serão retornadas pela cláusula FULL JOIN ou FULL OUTER JOIN. Caso uma linha de dados não esteja associada a qualquer linha da outra tabela, os valores das colunas a lista de seleção serão nulos.

Caso contrário, os valores obtidos serão baseados nas tabelas usadas como referência.

![image](https://user-images.githubusercontent.com/62342894/173425422-96864680-ae18-4540-9908-9ab53050b168.png)










