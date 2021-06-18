<div align="center">
  <p></p>
  <h1>React Native App</h1>
  <p></p>
  <sup>
    <a href="https://github.com/mcnamee/react-native-starter-kit/actions">
      <img src="https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fmcnamee%2Freact-native-starter-kit%2Fbadge%3Fref%3Dmaster&style=flat" alt="builds" />
    </a>
    <a href="/LICENSE">
      <img src="https://img.shields.io/github/license/mcnamee/react-native-starter-kit?style=flat-square" alt="license" />
    </a>
  </sup>
  <br />
</div>

---

## 👋 Intro


The project is _super_ helpful to kick-start your next project, as it provides a lot of the common tools you may reach for, all ready to go. Specifically:

- __Flux architecture__
    - [Redux](https://redux.js.org/docs/introduction/)
    - Redux Wrapper: [Rematch](https://github.com/rematch/rematch)
- __Routing and navigation__
    - [React Native Router Flux](https://github.com/aksonov/react-native-router-flux) for native mobile navigation
- __UI Toolkit/s__
    - [Native Base](https://nativebase.io/) for native mobile
- __Deployment strategy__
    - [Both manual and automated strategies](documentation/deploy.md)
- __Splash Screen + Assets__
    - [React Native Splash Screen](https://github.com/crazycodeboy/react-native-splash-screen)
- __Structure__
- __Firebase Notification__
    - [React Native Firebase](https://github.com/invertase/react-native-firebase)
- __Countly Bridg SDK__
    - [React Native Countlu Bridge](https://github.com/Countly/countly-sdk-react-native)
---

## 🚀 Getting Started

 - Install [React Native Debugger](https://github.com/jhen0409/react-native-debugger/releases) and open before running the app
 - Install `eslint`, `prettier` and `editor config` plugins into your IDE
 - Ensure your machine has the [React Native dependencies installed](https://facebook.github.io/react-native/docs/getting-started)

```bash
# Install dependencies
yarn install && ( cd ios && pod install )
```

#### iOS

```bash
# Start in the iOS Simulator
npx react-native run-ios --simulator="iPhone 11"
```

#### Android

```bash
# Start in the Android Simulator
#  - Note: open Android Studio > Tools > AVD > Run a device
#  - Example device specs: https://medium.com/pvtl/react-native-android-development-on-mac-ef7481f65e47#d5da
npx react-native run-android
```

---

## 👊 Further Help?

This repo is a great place to start. But...if you'd prefer to sit back and have your new project built for you or just need some consultation, and I can organise a quote.
