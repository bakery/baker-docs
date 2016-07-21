# Running server

Baker's application server is based on Express with Parse Server, Parse Dashboard and GraphQL endpoints attached. Server script supports 3 modes: standard, watch and debug.

## Running server in standard mode

```bash
cd server && npm run server
```

## Running server in watch mode

In watch mode, the server will automatically restart when you change any javascript file in the server directory

```bash
cd server && npm run server-watch
```