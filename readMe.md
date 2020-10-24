## Node Setup

---

1) mkdir new directory
2) cd into new directory
3) run npm init (or npm init-y)
4) npm init -y
5) touch index.js 

## Express Setup

---

1) npm i express
2) express = require('express')
3) const app = express()
4) Create home route
5) nodemon command
6) echo "node_modules" >> .gitignore

## Types Of Routes

---

HTTP Verb | CRUD Mapping
----------|-------------
GET |	READ
POST | CREATE
PUT |	UPDATE
DELETE | DELETE

## Sequelize

---
1) Install the sequelize CLI tool
2) npm install pg sequelize
3) sequelize init
4) Open the config JSON
- Delete your username and password (MAC)
- Make dialect refer to Postgres
5) sequelize db:create userapp_development (desired name from config.json)
6) Create a model
7) Declare the name of the model and pass in the attributes you want to include
- EX: sequelize model:create --name user --attributes firstName:string,lastName:string,age:integer,email:string