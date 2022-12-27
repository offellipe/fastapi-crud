# FASTAPI CRUD APPLICATION

## Orientações para baixar o projeto

O projeto tem algumas dependências como a versão do FastAPI, SQLAlchemy, etc. Todas elas estão em:

- Pipfile
- Pipfile.lock
Mas você tambem pode instalar tudo usando o comando que consta em "Como rodar a aplicação"

## Techs usadas no projeto
Essa aplicação foi desenvolvida as orientações do grande @diegoduartec. Nela, usamos tecnologias como:

- PostgreSQL
- Docker
- Python versão 3.11, porém as versões 3.6 + suportam as funcionalidades apresentadas aqui.
- SQLAlchemy
- Asyncio

# Como rodar a aplicação

1. Adicione o caminho do projeto em PYTHONPATH dentro do arquivo .env
2. Inicie a instância do banco de dados e do pgadmin
```sh
docker-compose up -d
```
3. Inicie o ambiente
```sh
pipenv shell
```
4. Instalando as dependências do Python
```sh
pipenv install
```
