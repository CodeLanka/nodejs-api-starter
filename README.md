# nodejs-api-starter

Starting point for secured Node.js API

How to use this repository.

- Clone this repository.
- Rename `.env.example` to `.env`
- Add your config to `.env`
- Install dependencies `npm i` or `yarn install` or simply `yarn`
- Run the project using `npm start` or `yarn start`
- Visit the server by `http://localhost:3080`
- Now try to get JWT token by sending a `POST` request using Postman to end-pont `http://localhost:9080/auth`

```json
{
  "email": "admin@somemail.com",
  "password": "pass"
}
```
