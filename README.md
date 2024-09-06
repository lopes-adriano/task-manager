# TaskManager

Este é um projeto de backend em Nestjs que permite a criação de tarefas e autenticação com JWT. O projeto utiliza TypeORM para conexão com o banco de dados PostgreSQL e Joi para validação de dados.

## Instruções para rodar o projeto

1. Crie o arquivo `.env` na raiz do projeto e adicione as variáveis de ambiente abaixo:

   - `DB_HOST`: endereço do banco de dados
   - `DB_PORT`: porta do banco de dados
   - `DB_USERNAME`: usuário do banco de dados
   - `DB_PASSWORD`: senha do banco de dados
   - `DB_DATABASE`: nome do banco de dados
   - `JWT_SECRET`: chave secreta para geração de tokens JWT

2. Execute o comando `npm install` para instalar as dependências do projeto

3. Execute o comando `npm run start:dev` para rodar o projeto em modo de desenvolvimento

4. Abra um navegador e acesse `http://localhost:3000` para acessar a API

## Comandos

- `npm run start`: roda o projeto em modo de produção
- `npm run start:dev`: roda o projeto em modo de desenvolvimento
- `npm run build`: compila o projeto para produção
- `npm run test`: roda os testes do projeto
- `npm run test:cov`: roda os testes do projeto com cobertura de código
- `npm run lint`: roda o linter do projeto
- `npm run format`: roda o formatador de código do projeto
