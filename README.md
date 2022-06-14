## Description

A simple social media API built with Nest.js, Prisma, & PostgreSQL.

## TODO
- Tests
- <s>Add new features (post, comment)</s>
- etc...

## Installation

```bash
$ pnpm install
```

## Running the app

This app needs some environment variables, see .env.example file.

```bash
# initialize dev-db
docker-compose up -d

# create a migration
npx prisma migrate dev

# development
$ pnpm start

# watch mode
$ pnpm start:dev

# production mode
$ pnpm start:prod
```