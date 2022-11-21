## Comfortable development

```bash
git clone --depth 1 https://github.com/velmurugan0411/nestjs-api.git my-nest-api
cd my-nest-api/
cp env-example .env
```

Change `DATABASE_HOST=postgres` to `DATABASE_HOST=localhost`


```bash
npm install

npm run migration:run

npm run seed:run

npm run start:dev
```
