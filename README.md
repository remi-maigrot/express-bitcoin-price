# ₿ Express Bitcoin Price · Node.js / Express playground

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white)

A small **Express.js** server built to practise the fundamentals of back-end development with Node.js: routing, route and query parameters, middleware, sessions, form handling, static files and calling an external API (CoinDesk Bitcoin price) with Axios.

## ✨ What it covers

| Route | Concept |
|---|---|
| `GET /` | Session-based page view counter + custom logging middleware |
| `GET /bonjour/:name` | Route parameters |
| `GET /yo?prenom=&nom=` | Query parameters |
| `POST /form` | Form / JSON body parsing (`express.urlencoded`, `express.json`) |
| `GET /view/:id` | Dynamic lookup in an in-memory list |
| `GET /page` | Serving an HTML view with static assets (`/static`) |
| `GET /bitcoin` | Fetching the Bitcoin price from the CoinDesk API with Axios |
| `*` | Custom 404 handler |

## 🛠️ Stack

Node.js · Express 4 · express-session · Axios

## 🚀 Getting started

```bash
git clone https://github.com/remi-maigrot/express-bitcoin-price.git
cd express-bitcoin-price
npm install
node index.js        # or: npm run dev (requires nodemon)
```

The server listens on [http://localhost:3000](http://localhost:3000).

## 📝 Notes

Learning project from 2022. The CoinDesk v1 endpoint it calls has since been deprecated.
