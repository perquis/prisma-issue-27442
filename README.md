# Prisma Issue 27442

This repository contains a minimal reproduction of the issue described in [Prisma Issue 27442](https://github.com/prisma/prisma/issues/27442). It seems that the problem is not related with `prismaSchemaFolder` feature nor the `prisma` package version, but rather with the `prisma generate` command not generating the migration files correctly.

## Steps to Reproduce

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm ci` to install the dependencies with all migrations.

## Environment

- Node.js version: 22.13.0
- Prisma version: 6.6.0
- Database: PostgreSQL 16-alpine (used in Docker v28.2.2)
