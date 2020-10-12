# Momo Mobile Application

### Prerequisites

* [NPM](https://www.npmjs.com/) - Package manager
* [Node](https://nodejs.org/en/)
* [Android Studio](https://developer.android.com/studio/) - Android IDE used for Android projects
* [Visual Code](https://code.visualstudio.com/downloadhttps://code.visualstudio.com/download)


## Setup and Installing

This project was created with [React Native](https://facebook.github.io/react-native/).

* Go inside the directory [momo-mobile-app].
* Change directory `cd MomoProject`.
* `npm install` to install the dependencies.
* Make sure to install Android Studio to run the app on the emulator. Open this [link](https://facebook.github.io/react-native/docs/getting-started) and select React Native CLI Quickstart and follow the steps indicated there.
* Have an Android emulator running or a device connected.
* To run the app, `npx react-native run-android` and then wait out for the app to be built on your device.

## Troubleshooting

Build may fail upon setup, try to follow the steps below:

* Delete `/android/build` folder.
* Go back to the root directory and delete `node_modules`
* `npm cache clear --force`
* `npm install`
* `react-native link`
* `react-native run-android`



## Learn More

You can learn more in the [Getting Started with React Native](https://facebook.github.io/react-native/docs/getting-started).
