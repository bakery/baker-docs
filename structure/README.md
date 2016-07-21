# Project structure

Once you've done installing dependencies and running setup as described in the [Installation section](/gettingstarted/installation.md), you will end up with a whole lot of files. Let's go over the project structure to make sure you know where things are.

## High level overview

The root of your project should be looking smth like this

```markdown
├── LICENSE
├── README.MD
├── app                             **React Native application lives here**   
├── baker                           **Baker internals** 
├── node_modules
├── package.json
├── server                          **Application server**
└── settings -> app/settings
```