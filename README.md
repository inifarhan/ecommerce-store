pqzofzdsda# Ecommerce Store

![Ecommerce-store](https://i.postimg.cc/YSMCQFmq/ecommerce-store-1.png)

### [Live Site](https://ecommerce-store-delta-eight.vercel.app)

## Introduction
E-commerce store allows the user to buy the product with [Stripe](https://stripe.com/) payment that you make in [Ecommerce-admin](https://github.com/inifarhan/ecommerce-admin).
The content in this application is dynamically customized in the [Ecommerce-admin](https://github.com/inifarhan/ecommerce-admin) too.

### Tech Stack 💻 :
- NextJS
- React
- TailwindCSS
- Stripe
- HeadlessUI

### Cloning the repository

```shell
git clone https://github.com/inifarhan/ecommerce-admin.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
// The url of the Ecommerce-admin
NEXT_PUBLIC_API_URL=[ecommerce_admin_url]/api/[storeId]

// Example
NEXT_PUBLIC_API_URL=http://localhost:3000/api/84933d40-da29-484a-a993-4e3ae0016617
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
