# Crypto Portfolio Manager — Server

Mock REST API for the crypto portfolio manager, built during the Ironhack Web Development Bootcamp (2024). It serves portfolios and a seeded snapshot of coin market data from `db.json`, with full CRUD.

The React front end lives in [crypto-portfolio-client](https://github.com/jrobles-io/crypto-portfolio-client).

## Stack

- Node.js with json-server
- Morgan request logging
- CORS enabled for the client

## Resources

| Resource | Endpoints |
|---|---|
| `portfolios` | `GET/POST /portfolios`, `GET/PUT/PATCH/DELETE /portfolios/:id` |
| `coins` | `GET /coins`, `GET /coins/:id` |

json-server also supports filtering, sorting and pagination on these routes (for example `/coins?symbol=BTC`).

## Run locally

```bash
npm install
PORT=4000 npm run dev
```
