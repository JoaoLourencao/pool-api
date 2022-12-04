### Create new API with node, typescript, fastify and prisma

# Run
- npm init -y                       --- Create new javascript project
- npm i typescript -D               --- install typescript dev dependencie
- npm i fastify                     --- help us place requests (get, post, etc)
- npm i tsx -D                      --- automate compile ts code to js and execute
- npm i prisma -D .                 --- help us with command line tools, show tables, create table, etc
- npm i @prisma/client              --- ORM help us connect to database

# Alter
- alter tsconfig.json targe "es2016" to "es2020"

# Create
- new file /src/server.ts
- new script on package.json scripts: "dev": "tsx watch src/server.ts"    ---- watch parameter to watch the code changes


# Prisma Commands
- npx prisma init --datasource-provider SQLite       ---- create the database schema using SQLite
- npx prisma migrate dev                             ---- database versioning
- npx prisma studio                                  ---- see the database on browser