---
title: Project structure
permalink: /project-structure.html
---
# Project structure

Once you're done installing dependencies and running setup as described in the [Installation section](/gettingstarted/installation.html), you will end up with a whole lot of files.

Let's go over the project structure to make sure you know where things are. A lot of this stuff is auto-managed by Baker for you so you do not really have to worry about it much/at all.

Note: For a quick rationale for the monorepository approach, please refer to [Repository Structure Section](/note-on-the-repository-structure.md)

## High level overview

The root of your project should be looking smth like this

```
├── .baker                    <-- Baker internals
├── app                       <-- React Native application
├── ci                        <-- CI configuration   
├── server                    <-- Application server
└── settings -> app/settings  <-- Share app settings with the server
```

## app/src directory overview

```
├── components           <-- components/containers go here   
│ └── App                <-- every component gets its own directory
│     ├── index.js
│     ├── index.test.js
│     └── styles.js
├── sagas                <-- all sagas go into this directory
│ └── index.js           <-- sagas are registered here
├── state
│ └── action-types.js    <-- constants to use in actions and reducers
│ └── index.js           <-- Redux store setup happens here
│ └── reducers.js        <-- application reducers get registered here
├── settings.js          <-- js module for app/settings directory   
├── setup.js             <-- application setup
└── tests.js             <-- Test configuration
```

## server/src

```
├── graphql                 
│   ├── index.js         <-- GraphQL middleware 
│   └── schema.js        <-- GraphQL schema
├── index.js             <-- Application server entry point
├── models               <-- Parse models
│   └── Example.js
└── parse-server           
    └── index.js         <-- Parse Server setup
``` 
