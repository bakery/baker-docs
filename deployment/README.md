# Deploying your app

Baker supports 2 types of deployments: mobile app deployment through Fastlane and application server deployment using Heroku 

## Deploying application server to Heroku

```
heroku create name-of-your-app
npm run deploy:server
```

## Pushing mobile application with Fastlane 

**app/fastlane** directory contains some setup for [Fastlane](https://github.com/fastlane/fastlane). Please refer to this [excellent article](https://dbanck.svbtle.com/deploying-a-react-native-app-with-fastlane) by Daniel Banck for details on how to push your app through Fastlane. 