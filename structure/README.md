# Project structure

Once you've done installing dependencies and running setup as described in the [Installation section](/gettingstarted/installation.md), you will end up with a whole lot of files. Let's go over the project structure to make sure you know where things are.

## High level overview

The root of your project should be looking smth like this

```
├── LICENSE
├── README.MD
├── app                             <-- React Native application
├── baker                           <-- Baker internals
├── node_modules
├── package.json
├── server                          <-- Application server
└── settings -> app/settings        <-- Share app settings with the server
```

## app/src directory overview

```
├── components        <-- all application components/containers go here   
│ └── App             <-- every component/container gets its own directory
│ ├── index.js
│ ├── index.test.js
│ └── styles.js
├── reducers.js
├── sagas
│ └── index.js
├── settings.js
├── setup.js
├── store.js
└── tests.js
```