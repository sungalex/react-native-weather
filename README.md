# React Native Weather

- This project is a fork of a Weather App ([Nomad Coder's `왕초보를 위한 React Native 101`](https://nomadcoders.co/react-native-fundamentals/)) for learning React Native

- Install Expo Mobile App for iOS(Expo Go) or Android(Expo)

## Installation

```bash
npm install --global expo-cli
npm install expo-location
```

## Create EXpo App

- This project was created by `expo-cli` as shown below

```bash
expo init react-native-weather --npm
```

## Starting Expo App

- Expo login

```bash
expo login
```

- Run App

```bash
npm run start
```

## Create [OpenWeather](https://api.openweathermap.org/) API Key file

- `api_key.js` file is as below

```js
export const API_KEY = "API_KEY";    # replace "API_KEY" to your OpenWeather API Key
```
