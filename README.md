# Enquetes

Este é um projeto de enquetes desenvolvido durante a NLW Expert da @Rocketseat, utilizando JavaScript, TypeScript, Docker, Fastify, Prisma, PostgreSQL, Redis e Zod.

## Regras de Negócio

- O usuário pode votar apenas uma vez em uma enquete.
- É possível trocar o voto da enquete.

## Requisitos Necessários

- Node.js v16 ou superior
- Docker

## Instruções de Instalação

1. Clone o repositório do GitHub:

```
git clone https://github.com/Vitinho163/NLW-Expert-Polls.git
```

2. Instale as dependências:

```
npm install
```

3. Suba os containers Docker:

```
docker-compose up -d
```

4. Edite o arquivo `.env.example` para `.env` e adicione o usuário e senha do banco de dados. Por exemplo:

```
DATABASE_URL="postgresql://docker:docker@localhost:5432/polls?schema=public"
```

5. Execute a aplicação:

```
npm run dev
```

## Estrutura do Projeto

![Estrutura do Projeto](https://imgur.com/4WR6SUV.png)

## Demonstração

[![Demonstração de uso](https://imgur.com/oyCF7dJ.png)](https://youtu.be/F2yJQvvs4GM)

## Autor

- **Feito por [João Victor](https://github.com/Vitinho163)**.

## Professor

- **[Diego Fernandes](https://github.com/diego3g)**
