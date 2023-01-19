# Dependências do projeto:

- fastify - É um gerenciador de rotas, semelhante ao express, porém mais performático.
- @fastify/cors - É um pacote para integração do fastify com cors.
- @prisma/client - É o client do prisma, o que permite acessar um banco de dados.

## Dependências de desenvolvimento:

- typeScript - Permite utilizar tipagem estática ao JS e ajuda na prevenção de erros.
- tsc - Um interpretador de typeScript do Node.
- prisma - Um orm para gerenciamento de banco de dados que utiliza TS

## Comandos Prisma:

- pnpm prisma init - Inicia o Prisma e gera o arquivo "schema.prisma", que é onde são definidas as models do banco de dados.
- pnpm prisma migrate dev - Cria uma migration com as alterações feitas no schema.
- pnpm prisma studio - Abre no navegador uma interface gráfica que permite a navegação no banco de dados, criar novas tabelas e alterar dados.
