![](https://i.imgur.com/xG74tOh.png)

## Exercício realizado na aula de Consultas SQL, do curso de Back end da [Cubos Academy](https://cubos.academy/).

### Tecnologias e ferramentas usadas
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

Também foi feito uso do [BeeKeeper](https://www.beekeeperstudio.io/) para gerencimento do banco de dados.

Neste exercício, foi usada a função SELECT para realizar consultas em bancos de dados, seguindo as instruções abaixo: 


1 - Selecione apenas os compositores e o identificador de todos os registros da tabela `musicas`.

2 - Selecione as composições e o tempo de cada composição, de todos os registros da tabela `musicas`, onde o tempo seja maior que 4 minutos.

3 - Selecione os compositores e suas composições que tenham identificadores entre 47 e 123.

4 - Selecione todos os registros com todos os campos da tabela `musicas`, onde o compositor não seja nulo, o tempo seja menor que 5 minutos e o nome do compositor seja diferente de `Bach`.

5 - Selecione as composições e o tempo de cada composição, de todos os registros da tabela `musicas`, onde o compositor seja `Mozart` ou `Bach`.

6 - Selecione todos os registros com todos os campos da tabela `musicas` e faça uma ordenação pelo identificador em ordem decrescente.

7 - Selecione todos os registros com todos os campos da tabela `musicas` e faça uma ordenação pelo tempo de execução de cada música, da que leva mais tempo a ser executada para a que leva menos tempo.

8 - Selecione as 5 composições, com todos os campos da tabela `musicas`, nas quais sejam as 5 composições mais rápida em tempo de execução.

9 - Selecione as 10 composições, com todos os campos da tabela `musicas`, nas quais sejam as 10 composições que mais demora em tempo de execução.

10 - Selecione 10 registros, com todos os campos da tabela `musicas`, de forma que esses 10 registros sejam os que tenham menor tempo de execução com exceção dos 5 primeiro mais rápidos.

11 - Seguindo o conceito de paginação de resultados, sabendo que cada página retorna apenas 10 resultados, faça a listagem dos registros que correspondam a página 4.

12 - Seguindo o conceito de paginação de resultados, sabendo que cada página retorna apenas 12 resultados, faça a listagem dos registros que correspondam a página 6.

13 - Selecione todos os compositores da tabela `musicas` de forma que os resultados não sejam repetidos e não esteja nulo.

14 - Selecione os compositores e as composições da tabela `musicas` de forma que os resultados não sejam repetidos.

15 - Selecione todos os campos da tabela `musicas` e os registros que o nome do compositor comece exatamente com `Bra`, isso significa que se a primeira letra não form maiúscula está incorreto.

16 - Selecione todos os campos da tabela `musicas` e os registros que o ritmo possua a última palavra igual a `troppo` independente do restante do texto que antecede, mas que seja exatamente a última palavra do texto.

17 - Faça uma busca nos registros da tabela `musicas` e retorne somente os registros que possua em qualquer posição do texto, da composição, a palavra `quartet`, independente de ser maiúscula ou minúscula.

18 - Faça uma busca nos registros da tabela `musicas` e retorne somente os registros que não possua a palavra `quintet` na coluna composição, independente de ser maiúscula ou minúscula.

![](01/image.png)
---
###### tags: `exercícios` `lógica` `banco de dados` `sql` `postgres`
