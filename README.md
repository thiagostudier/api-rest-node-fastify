# Node API Rest com Fastify

Este é um projeto de exemplo para criar uma API RESTful em Node.js utilizando o framework Fastify. Abaixo estão os comandos e passos utilizados durante o desenvolvimento do projeto.

## Comandos Utilizados:

1. **Instalar TypeScript:**

   ```bash
   npm i -D typescript
   ```

2. **Criar o `tsconfig.json`:**

   ```bash
   npx tsc --init
   ```

3. **Converter o código TypeScript para JavaScript:**

   ```bash
   npx tsc src/index.ts
   ```

4. **Instalar Fastify:**

   ```bash
   npm i fastify
   ```

5. **Instalar pacote para resolver conflitos:**

   ```bash
   npm install -D @types/node
   ```

6. **Instalar ferramenta para conversão de código TypeScript para JavaScript de forma automatizada:**

   ```bash
   npm install tsx -D
   ```

7. **Instalar ESLint:**

   ```bash
   npm i eslint @rocketseat/eslint-config -D
   ```

8. **Adicionar Knex:**

   ```bash
   npm install knex --save
   ```

9. **Adicionar o driver do banco de dados:**

   ```bash
   npm install knex sqlite3
   ```

10. **Criar tabela utilizando Knex:**

    ```bash
    npm run knex -- migrate:make name-migrate
    ```

11. **Executar rollback nas migrations:**

    ```bash
    npm run knex -- migrate:rollback
    ```

12. **Executar as migrations:**

    ```bash
    npm run knex -- migrate:latest
    ```

13. **Instalar a biblioteca Zod para validação de dados:**

    ```bash
    npm i zod
    ```

14. **Instalar pacote para lidar com cookies no Fastify:**

    ```bash
    npm i @fastify/cookie
    ```

15. **Instalar Vitest - Ferramenta de testes e Supertest:**

    ```bash
    npm i vitest -D
    npm i supertest -D
    ```

16. **Instalar ferramenta para deploy:**
    ```bash
    npm i tsup -D
    ```
