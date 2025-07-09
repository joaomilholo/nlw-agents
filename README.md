# NLW Agents

Este é o backend do projeto **NLW Agents**, desenvolvido durante o evento da Rocketseat.

## Tecnologias e Bibliotecas

- **Node.js** + **TypeScript**
- [Fastify](https://fastify.dev/) — servidor HTTP rápido e eficiente
- [Zod](https://zod.dev/) — validação de esquemas
- [drizzle-orm](https://orm.drizzle.team/) — ORM para PostgreSQL
- [drizzle-seed](https://github.com/drizzle-team/drizzle-seed) — seed de banco de dados
- [postgres](https://github.com/porsager/postgres) — driver PostgreSQL
- [@fastify/cors](https://github.com/fastify/fastify-cors) — CORS middleware

## Padrões de Projeto

- **Type-safe**: Uso de TypeScript e validação com Zod.
- **Schema-first**: Definição de schemas de banco de dados e validação centralizada.
- **Modularização**: Rotas e schemas organizados em módulos.

## Setup e Configuração

1. **Clone o repositório e acesse a pasta do servidor:**
   ```sh
   git clone <repo-url>
   cd nlw-agents/server