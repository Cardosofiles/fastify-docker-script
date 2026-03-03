# 🚀 Fastify Docker Generator Script
 ![CodeRabbit Pull Request Reviews](https://img.shields.io/coderabbit/prs/github/Cardosofiles/fastify-docker-script?utm_source=oss&utm_medium=github&utm_campaign=Cardosofiles%2Ffastify-docker-script&labelColor=171717&color=FF570A&link=https%3A%2F%2Fcoderabbit.ai&label=CodeRabbit+Reviews)

![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Fastify](https://img.shields.io/badge/fastify-%23000000.svg?style=for-the-badge&logo=fastify&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)


Um script shell automatizado para gerar rapidamente uma estrutura robusta de API **Fastify** com **TypeScript**, **Docker**, **Prisma 7 (Driver Nativo)**, **PostgreSQL**, **ESLint 9** e **Prettier**.

## 🔥 Funcionalidades

Este script configura automaticamente um novo projeto com as seguintes tecnologias e práticas:

- **Node.js** com **TypeScript** (ES2022/NodeNext)
- **Fastify** como framework web
- **Prisma 7** com **Native Driver** para PostgreSQL
- **Docker Compose** para banco de dados PostgreSQL
- **Zod** para validação de ambiente e tipos
- **Swagger UI** configurado automaticamente
- **ESLint 9 (Flat Config)** e **Prettier** para linting e formatação
- **Estrutura de pastas** organizada (routes, services, utils, lib)

## 📋 Pré-requisitos

Antes de executar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (recomendado v20+)
- [pnpm](https://pnpm.io/) (Gerenciador de pacotes utilizado)
- [Docker](https://www.docker.com/) e Docker Compose

## 🚀 Como usar

1. **Clone este repositório** ou baixe o arquivo do script.

2. **Dê permissão de execução** ao script:

   ```bash
   chmod +x src/script.sh
   ```

3. **Execute o script**:

   ```bash
   ./src/script.sh
   ```

4. **Siga as instruções**:
   - Digite o nome do seu projeto quando solicitado.
   - O script criará a pasta, instalará as dependências e configurará tudo.

## 📂 Estrutura Gerada

O script cria uma estrutura pronta para produção:

```text
meu-projeto/
├── src/
│   ├── lib/          # Configuração do Prisma
│   ├── routes/       # Rotas da API
│   ├── utils/        # Utilitários (env, etc)
│   └── server.ts     # Entrypoint da aplicação
├── prisma/
│   ├── schema.prisma # Schema do banco de dados
│   └── migrations/   # Migrações do banco
├── docker-compose.yml
├── .env
├── package.json
└── tsconfig.json
```

## 👤 Autor

Desenvolvido por **Cardosofiles**.

- 🌐 **Website:** [cardosofiles.com.br](https://www.cardosofiles.com.br/pt)
- 🐙 **GitHub:** [@Cardosofiles](https://github.com/Cardosofiles)
- 💼 **LinkedIn:** [Gabriel Cardoso](https://www.linkedin.com/in/Cardosofiles/)

---
