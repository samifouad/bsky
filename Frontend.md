The Bluesky app is written in [React Native](https://reactnative.dev/) and is powered by the [Expo](https://expo.dev/) framework. Expo uses [React Native for Web](https://necolas.github.io/react-native-web/) to compile the web app for Bluesky.

Why isn't the web app using React? This build strategy has been [proven to work at Twitter](https://giuseppegurgone.com/twitter-html) and allows for a lot of code sharing between all platforms.

Expo also provides a service called [EAS](https://expo.dev/eas) that allows developers to automate building for different platforms, as well as submitting their apps to the mobile app stores. So when to developer provides EAS credentials, submitting an app to the App Store is as easy as pushing code to GitHub.