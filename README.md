# TaskApplication-deploy


## Description

Tarefa: 

-aplicação WEB que implemente um CRUD (Listar, Adicionar, Editar e Excluir) de uma agenda de contatos, conforme as definições abaixo:

 

1. Dados dos Contatos: Nome, Sexo, Telefone, Email;

2. A arquitetura deve obedecer a separação entre o backend e o frontend;

3. O Backend deve ser uma API de serviços no padrão Web Service REST com troca de arquivos em formato JSON e deve ser implementada em linguagem JAVA ou Python;

4. Os dados devem ser armazenados em banco de dados (MySQL, Postgres ou Sql server express) em uma tabela CONTATOS;

## Running the app

```bash
# development
$ docker-compose up -d


```

#
## Aplicações:
- WEB -> https://github.com/BioJJ/schedule-web
- API -> hhttps://github.com/BioJJ/schedule-api

## Technologies used
The technologies or tools listed below figure between the most relevant on the development of this project:

- Docker version 19.03.12
- Docker-compose version 1.27.4


FRONTEND
   - "axios": "^0.21.1",
   - "bootswatch": "^4.6.0",
   - "classnames": "^2.2.6",
   - "primeicons": "^4.1.0",
   - "primereact": "^6.0.0",
   - "react": "^17.0.1",
   - "react-dom": "^17.0.1",
   - "react-router-dom": "^5.2.0",
   - "react-scripts": "4.0.1",
   - "react-transition-group": "^4.4.1",
   - "toastr": "^2.1.4",
   - "web-vitals": "^0.2.4"

BACKEND
   - "cors": "^2.8.5",
   - "dotenv-flow": "^3.2.0",
   - "express": "^4.17.1",
   - "knex": "^0.21.16",
   - "pg": "^8.5.1"
 

## Stay in touch

- Author - https://www.linkedin.com/in/jefferson-coelho/
- Website - https://github.com/BioJJ
- Twitter - https://twitter.com/bio_jefferson




 api:
      image: biojj/task-api
      container_name: task-api
      expose: 
        - 3333
      ports: 
       - 3333:3333
      depends_on: 
       - db
      env_file: 
       - ./.env
