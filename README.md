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

## Verifique se as 3 imagens subiram:
```bash
# db
# schedule-api
# schedule-web
$ docker ps

```
### OBS: caso as 3 não apareçam, repita o comando 'docker-compose up -d'


## Acesse a aplicação pelo browser: localhost:8082

#
## Aplicações:
- WEB -> https://github.com/BioJJ/schedule-web
- API -> https://github.com/BioJJ/schedule-api

## Technologies used
The technologies or tools listed below figure between the most relevant on the development of this project:

- Docker version 19.03.12
- Docker-compose version 1.27.4


FRONTEND
 ### "dependencies":
   - "@angular/animations": "~9.1.0",
   - "@angular/cdk": "^9.2.0",
   - "@angular/common": "~9.1.0",
   - "@angular/compiler": "~9.1.0",
   - "@angular/core": "~9.1.0",
   - "@angular/forms": "~9.1.0",
   - "@angular/material": "^9.2.0",
   - "@angular/platform-browser": "~9.1.0",
   - "@angular/platform-browser-dynamic": "~9.1.0",
   - "@angular/router": "~9.1.0",
   - "rxjs": "~6.5.4",
   - "tslib": "^1.10.0",
   - "zone.js": "~0.10.2"
 
 ### "devDependencies": 
   - "@angular-devkit/build-angular": "~0.901.0",
   - "@angular/cli": "~9.1.0",
   - "@angular/compiler-cli": "~9.1.0",
   - "@angular/language-service": "~9.1.0",
   - "@types/node": "^12.11.1",
   - "ts-node": "~8.3.0",
   - "tslint": "~6.1.0",
   - "typescript": "~3.8.3"
  

BACKEND
- java 8
- Java Spring boot 2.4.RELEASE<
- Postgress
- Flyway
  

## Stay in touch

- Author - https://www.linkedin.com/in/jefferson-coelho/
- Website - https://github.com/BioJJ
- Twitter - https://twitter.com/bio_jefferson


