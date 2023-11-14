# Used commands when setting up environment

## NestJS

```shell
npm install -g @nestjs/cli
npm i --save-dev @swc/cli @swc/core
npm i --save-dev @types/express
npm i --save-dev @types/jest
npm i --save-dev @types/mocha
npm i @nestjs/config
```

## Authentication

```shell
# Input sanitizing
npm i class-validator class-transformer

# Password hashing https://github.com/P-H-C/phc-winner-argon2
npm i argon2

# JWT(JSON Web Token) https://jwt.io/
npm i @nestjs/jwt passport-jwt
npm i --save-dev @types/passport-jwt

# OAuth2.0 https://www.passportjs.org/
npm i @nestjs/passport passport-oauth2
```

## Database Interaction (Prisma ORM)

Would prefer to later on change to raw SQL queries to avoid an extra abstraction layer and possible performance losses

```shell
npm i @prisma/client
npx prisma init
```

CRUD API

- C reate
- R ead
- U pdate
- D elete
