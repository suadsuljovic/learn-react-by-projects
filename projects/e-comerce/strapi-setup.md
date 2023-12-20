## Setup strapi for e-commerce

Here you can find Strapi [docs](https://docs.strapi.io/)

## Create project

How to create quick project:

```bash
npx create-strapi-app@latest my-project --quickstart
```

If you get any errors install strapi globally first then create a poject:

```bash
npm i -g create-strapi-app@latest
```

```bash
npm create-strapi-app my-project --quickstart
```

Create strapi project with template for blog:

```bash
npx create-strapi-app@latest my-project --quickstart --template ecommerce
```

## Start the project

You can start the project by going into project directory and running the command:

```bash
npm run develop
```

## Understanding strapi API

You can get all the information about how the Strapi API works [here](https://docs.strapi.io/dev-docs/api/rest)

Simplified example:

Your Collection determines how the API will look like. If we have the collection name Products, the api should look like this:

| Method   | URL                         | Description           |
| -------- | --------------------------- | --------------------- |
| `GET`    | `/api/Products`             | Get a list of entries |
| `POST`   | `/api/Products`             | Create an entry       |
| `GET`    | `/api/Products/:documentId` | Get an entry          |
| `PUT`    | `/api/Products/:documentId` | Update an entry       |
| `DELETE` | `/api/Products/:documentId` | Delete an entry       |
