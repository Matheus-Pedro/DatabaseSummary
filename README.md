## SQL

**SQL (Structure Query Language)**, ou Linguagem de Consulta Estruturada, é uma linguagem utilizada para gerenciar e manipular bancos de dados relacionais. **SQL** é case-insensitive, o que significa que não diferencia maiúsculas de minúsculas em comandos, embora nomes de tabelas, colunas e outros elementos possam ser sensíveis à capitalização dependendo do SGBD.

## SGBD

**SGBD (Sistema Gerenciador de Banco de Dados)**, em inglês **DBMS (Data Base Management System)**, é um software que permite a criação, manipulação e administração de bancos de dados. Ele fornece as ferramentas necessárias para realizar operações como inserção, consulta, atualização e exclusão de dados.

## Operadores

Em comandos SQL, como o **WHERE**, é comum utilizar operadores lógicos para estabelecer condições, que podem resultar em verdadeiro ou falso. Estes operadores são familiares para quem já programa e funcionam da seguinte forma:

| **Operador** | **Descrição** |
| --- | --- |
| **=** | *IGUAL* |
| **>** | *MAIOR QUE* |
| **<** | *MENOR QUE* |
| **>=** | *MAIOR QUE OU IGUAL* |
| **<=** | *MENOR QUE OU IGUAL* |
| **<>** | *DIFERENTE DE* |
| AND | *OPERADOR LÓGICO “E”* |
| OR | *OPERADOR LÓGICO “OU”* |

Além dos operadores lógicos, existem operadores específicos do **SQL** que podem ser utilizados com o **WHERE**:

| **Operador** | **Descrição** |
| --- | --- |
| BETWEEN | INTERVALO ENTRE DOIS VALORES |
| IN | “DENTRO” DE UMA LISTA DE VALORES |
| LIKE | LOCALIZAR UM VALOR, UTILIZADO COM % E _ |

## CRUD

CRUD é um acrônimo para as quatro operações básicas de persistência em um banco de dados: **Create, Read, Update, Delete**.

- **Create:** Criar novos registros no banco de dados.
- **Read:** Ler ou consultar os registros existentes.
- **Update:** Atualizar registros existentes.
- **Delete:** Excluir registros.

## Comandos SQL

Aqui estão alguns dos comandos SQL mais utilizados:

- **INSERT INTO:** Insere novos dados no banco de dados (Create).
- **SELECT:** Extrai dados do banco de dados (Read).
- **UPDATE:** Atualiza dados existentes no banco de dados (Update).
- **DELETE:** Remove dados do banco de dados (Delete).

Outros comandos importantes:

- **CREATE DATABASE:** Cria um novo banco de dados.
- **ALTER DATABASE:** Modifica um banco de dados existente.
- **CREATE TABLE:** Cria uma nova tabela no banco de dados.
- **ALTER TABLE:** Modifica uma tabela existente.
- **DROP TABLE:** Exclui uma tabela do banco de dados.
- **CREATE INDEX:** Cria um índice para melhorar o desempenho das consultas.
- **DROP INDEX:** Exclui um índice.

Comandos SQL adicionais:

- **SELECT DISTINCT:** Retorna registros distintos, eliminando duplicatas.
- **WHERE:** Filtra registros com base em uma condição.
- **SELECT COUNT:** Retorna o número de registros.
- **SELECT TOP:** Retorna os primeiros N registros.
- **GROUP BY:** Agrupa registros que têm valores iguais em colunas especificadas.
- **MIN, MAX, SUM, AVG:** Funções de agregação que retornam o valor mínimo, máximo, soma e média, respectivamente.
- **JOIN:** Combina registros de duas ou mais tabelas com base em uma condição relacionada.
- **UNION:** Combina os resultados de duas ou mais consultas SELECT em um único conjunto de resultados, eliminando duplicatas.
- **HAVING:** Filtra os resultados de grupos de registros, usado com **GROUP BY**.
- **ORDER BY:** Ordena os resultados de uma consulta em ordem ascendente ou descendente.
- **INNER JOIN:** Retorna registros que têm valores correspondentes em ambas as tabelas.
- **LEFT JOIN (ou LEFT OUTER JOIN):** Retorna todos os registros da tabela à esquerda e os registros correspondentes da tabela à direita.
- **RIGHT JOIN (ou RIGHT OUTER JOIN):** Retorna todos os registros da tabela à direita e os registros correspondentes da tabela à esquerda.
- **FULL JOIN (ou FULL OUTER JOIN):** Retorna registros quando há uma correspondência em uma das tabelas.

## Referências

- https://www.w3schools.com/sql/