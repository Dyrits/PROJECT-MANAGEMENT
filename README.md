# PROJECT-MANAGEMENT

A full-stack project management app: a GraphQL API backed by MongoDB, with a React frontend.

**Status: possibly unfinished - completeness has not been verified.**

## About The Project

An Express + express-graphql API using Mongoose with a MongoDB database (run via Docker Compose), plus a React + Apollo Client frontend built with Vite and TypeScript.

### Built With

- Node.js + Express + express-graphql (API)
- Mongoose + MongoDB (database, Docker Compose)
- React 18 + Vite + TypeScript + Apollo Client (frontend, in `client/`)

## Getting Started

### Prerequisites

- Node.js
- Docker and Docker Compose (for MongoDB)

### Installation

```sh
npm run boot    # copy .env.example to .env, start MongoDB, install dependencies and start the API
```

### Development

```sh
npm start                 # API with nodemon (server/index.js)
cd client && npm install
npm run dev               # frontend with Vite
```

## License

No license file is present in this repository.

## Contact

Dyrits - https://github.com/Dyrits
