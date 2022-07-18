# Museu - BD2

EP da disciplina Banco de Dados 2: criação de um modelo de Museu, utilizando JDBC e PostgreSQL.

## Folder Structure

- `src`: códigos fonte Java
- `lib`: pasta das dependências
- `bin`: arquivos compilados

## Project Structure (MVC Pattern)

- `connection`: conexão com o PostgreSQL
- `model`: camada que possui a lógica da aplicação
    - `dao`: responsável por trocar informações com o SGBD e fornecer operações CRUD e de pesquisas
    - `bean`: classes unidade do sistema
- `view`: camada de visualização/interação com o usuário