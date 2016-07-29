# Scaffolding components

Pure Components (a.k.a. Presentational Components) do not have direct access to the app data - the data comes from their parent component (using props). Refer to Dan Abramov's [article](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.jfhjwnlv3) for more details.

**Note:** We do NOT separate components and containers into different sub-directories. Both components and containers reside within /components directory. This is because the nature of your component might change as you are building your app and having a single directory for containers and pure components will save you from migrating import paths.
