# Prisma & Hasura for quick API development


- Prisma is great for modeling the database using its custom SDL. Prisma also 
helps in handling migrations.
- Hasura does a wonderful job of generating graphQL and REST endpoints given 
any database.

Here we model the database using prisma and expose the endpoints using Hasura.


There are three main directories:

1. prisma - this contains the prisma schema.
2. postgres - this cointain the docker compose for the postgres db, which prisma populates and hasura connects to.
3. hasura - this contains the docker compose for hasura
