# Deploying your app

- push with Fastlane

## Deploying application server to Heroku

```
heroku create name-of-your-app
npm run deploy:server
```

## Pushing mobile application with Fastlane 

**app/fastlane** directory contains some setup for [Fastlane](https://github.com/fastlane/fastlane). Please refer to this [excellent article](https://dbanck.svbtle.com/deploying-a-react-native-app-with-fastlane) by Daniel Banck for details on how to push your app through Fastlane. 