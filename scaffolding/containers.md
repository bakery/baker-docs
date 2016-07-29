# Scaffolding Containers

Container Components \(a.k.a. Containers\) connect to application state using the [connect function](https://github.com/reactjs/react-redux/blob/master/docs/api.md#connectmapstatetoprops-mapdispatchtoprops-mergeprops-options) from React Redux. Refer to Dan Abramov's [article](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.jfhjwnlv3) for more details.

**Note:** We do NOT separate components and containers into different sub-directories. Both components and containers reside within \/components directory. This is because the nature of your component might change as you are building your app and having a single directory for containers and pure components will save you from migrating import paths.

## Running container generator

Container generator is based on [Component generator](/scaffolding/components.md) which you already might be familiar with

```
npm run generate
? Choose the generator to use
  Component
❯ Container
  Navigation
  Saga
  Model
```

