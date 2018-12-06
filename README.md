# CircleCI Demo IONIC App
IONIC 3.0 Continuous Integration using CircleCI 2.0 


[![CircleCI](https://circleci.com/gh/CircleCI-Public/circleci-demo-react-native.svg?style=svg)]

## Building and running locally

1. Run `npm install` to install the node dependencies.
2. Run `ionic serve` to run the app in development mode.

### Running the Android app in the Android emulator.

1. Run `ionic cordova platform add android` to create platform add to the project
2. Run `ionic cordova run android` to start the app in the Android emulator.

## Building on CircleCI

This example is ready to be built on CircleCI. Once you have copied or
forked the repository, navigate to the CircleCI web interface, choose
**Projects** and then **Add project**. Select a project and click
**Start building**.

Try pushing some changes to your repo to see how a JS job runs, and
then it will install the dependecies and android sdk get run concurrently. Once it is done, it will generate an apk to download from the artifacts. 

