# React Native App

This is a React Native app that uses React Navigation for handling navigation between screens. The app has three screens: LoginScreen, ProductsScreen, and ProductDetailScreen.

## Prerequisites

Before running the app, make sure you have the following installed:

- Node.js
- Expo CLI (`npm install --global expo-cli`)

## Installation

1. Clone the repository:



git clone https://github.com/your-repo/react-native-app.git


2. Navigate to the project directory:



cd react-native-app


3. Install the dependencies:



npm install


## Running the App

To run the app, use the following command:



expo start
the login credanetial are :: username : admin
password  :: password

This will start the Expo development server and display a QR code in the terminal. You can then use the Expo app on your mobile device to scan the QR code and run the app, or you can use an emulator/simulator.

## App Structure

The app is structured as follows:



react-native-app/
├── App.js
├── babel.config.js
├── package.json
├── screens/
│ ├── LoginScreen.js
│ ├── ProductDetailScreen.js
│ └── ProductsScreen.js
└── ...


- `App.js`: This is the entry point of the app and sets up the navigation stack.
- `babel.config.js`: This file configures the Babel transpiler for the app.
- `screens/`: This directory contains the screen components for the app.
  - `LoginScreen.js`: This is the initial screen that the user sees when the app starts.
  - `ProductsScreen.js`: This screen displays a list of products.
  - `ProductDetailScreen.js`: This screen shows the details of a selected product.

## Navigation

The app uses React Navigation for handling navigation between screens. The navigation stack is set up in `App.js` using the `createStackNavigator` function from `@react-navigation/stack`.

The navigation stack has three screens:

1. `LoginScreen`: This is the initial screen and is set as the initial route using the `initialRouteName` prop.
2. `ProductsScreen`: This screen is displayed after the user logs in.
3. `ProductDetailScreen`: This screen is displayed when the user selects a product from the `ProductsScreen`.

The `headerShown` option is set to `false` for the `LoginScreen` to hide the header, while the `title` option is used to set the header titles for the `ProductsScreen` and `ProductDetailScreen`.

## Dependencies

The app uses the following dependencies:

- `react-native-gesture-handler`: This library provides native-driven gesture management APIs for building better cross-platform React Native apps.
- `@react-navigation/native`: This is the core React Native navigation library.
- `@react-navigation/stack`: This library provides a way to transition between screens and manage navigation history.
- `expo`: This is the Expo SDK, which provides access to the system's capabilities from JavaScript.

Feel free to modify this README file ac
