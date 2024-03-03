- instalar typescript
  npm i -D typescript

- cria o tsconfig.json
  npx tsc --init

npx tsc src/index.ts

- instalar fastify
  npm i fastify

- instalar pacote para resolver conflitos
  npm install -D @types/node

- converte o código para js de forma automatizada
  npm install tsx -D

- instalar o eslint
  npm i eslint @rocketseat/eslint-config -D

- adicionar knex
  npm install knex --save

- adicionar o drive do banco de dados
  npm install knex sqlite3

- criar tabela
  npm run knex -- migrate:make name-migrate
  npm run knex -- migrate:rollback

- executar migrations
  npm run knex -- migrate:latest

- lib zod - env
  npm i zod

- instalar para lidar com os cookies no fastify
  npm i @fastify/cookie

- instalar vitest - ferramente da testes
  npm i vitest -D
  npm i supertest -D

- ferramenta para deploy
  npm i tsup -D
