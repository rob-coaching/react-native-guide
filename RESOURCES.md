# React Native resources

## Pre-Requisites / Installation

Installation for Ubuntu (version 20 and higher)
https://www.educative.io/answers/how-to-install-android-studio-in-ubuntu

In short we need the following requirements:

- Java (needed to use Android Studio)
- Android Studio (needed to create an Android Emulator)
- Android Devuce Manager (comes with Android studio => used to setup Android Emulators)
- Android SDK (needed to bundle & run apps for the Android emulatur)

## Startup

Once you have all that parts setup you can create an emulator inside the Android Device Manager.

Then all it takes to run your React native application will be:

- start your emulator from the Android Device Manager
- start your app to run in the emulator
  - `npm start` => now you can choose source where to run, Android Emulator or Browser)
  - `npm run android` => launch directly in emulator
 
Once the script executes, a specific app called "Expo" will get installed on the Android Emulatur.
Now your gets bundled and will get launched inside that Expo App.
The Expo App will be able to understand the React Native JS code and execute it on the emulator as it your app was a native Android App.

Therefore the name "React Native".

Enjoyyyyy.

## Cousrses

Great React Native course on Udemy (by Academind):

https://www.udemy.com/course/react-native-the-practical-guide

Very clear, concise and easy to follow.
