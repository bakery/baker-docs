# Testing

Baker includes test setups for the following 
 
- React Native application
- Application server
- CI tests for both RN app and app server 
- Baker internals

## Testing your ReactNative application

RN tests use [Mocha](https://github.com/mochajs/mocha), [Enzyme](https://github.com/airbnb/enzyme) and [React Native Mock](https://github.com/lelandrichardson/react-native-mock). 

Baker will test anything within **app/src** directory (and its subdirectories) that looks like ***.test.js**. Generally speaking, you will not need to create any test suites manually since scaffolding feature takes care of creating tests for your components, actions and reducers.

To test your RN application, use the following command

```
npm run test:app
``` 