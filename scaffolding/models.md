# Scaffolding models

Models are server side components based on **Parse.Object** exposing GraphQL schema.  

## Running model generator

```
npm run generate
? Choose the generator to use (Use arrow keys)
  Component
  Container
  Navigation
  Saga
❯ Model
```

Baker will ask you to provide a name for the new model

```
? What should your model be called?
```

## Models directory overview

Models are added to **server/src/models** directory:

```
├── models
    ├── Example.js
    └── Todo.js
```
