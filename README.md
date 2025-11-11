## Food Palace App

This is a mobile application built in React Native using [TheMealDB API](https://www.themealdb.com/).

## Features

1. Search meals
2. Browse meal categories
3. Browse single meals, ingredients, and how to prepare.

## Stack

1. React native expo
2. React navigation for routing
3. Nativewind (tailwindcss for mobile) for styling

### How to run

At the time of writing this README, the app is about 1 year old. If you are reading this is the future, or if you are coming from the Youtube video, please check the versions used.

1. Clone the repository:

`git clone https://github.com/sankthomas/food-palace-yt`

2. Update the following packages to the versions below (as of 11th November 2025):

- react: 19.1.0
- expo: 54.0.23,
- expo-status-bar: 3.0.8,
- nativewind: 4.2.1,
- prettier-plugin-tailwindcss: 0.5.11,
- react: 19.1.0,
- react-native: 0.81.5,
- react-native-reanimated: 4.1.1,
- react-native-safe-area-context: 5.4.0,
- react-native-screens: 4.16.0,
- tailwindcss: 3.4.17

> [Read the updated docs on Nativewind](https://www.nativewind.dev/docs/getting-started/installation) to install the current version Nativewind, i.e v4 at the time of writing this.

To update a package:
`npm i react@19.1.0`. Do the same for the other packages listed above.

> When you clone the repository, these are the versions you will have in your local. Therefore, you don't need to do anything more.

3. Run the app using `npm run start` or any of the other scripts available in `package.json`

### Reason for the update

1. Following the video I created about this app, the Expo SDK updated to SDK 54 which would not run the app on your mobile phone with the version I used in the video.
2. Updating the SDK to version 54 in order to keep up with Expo breaks other packages.

- It was basically a cascading thing, where installing one version of a package breaks another, so you need to install the "almost" latest version of the other package.
