This repository contains a React Native Expo app that allows you to build and run a web & mobile application for both iOS and Android platforms. The app is developed using React Native, Expo, and various additional libraries.

Prerequisites
Before getting started, make sure you have the following installed on your machine:

Node.js and npm (Node Package Manager)

Clone this repository to your local machine using the following command:
git clone https://github.com/mdshoaibakhtar/Falconstar.git

Install the required dependencies by running the following command:
npm install

Start the react-native-app:
npx expo start

This will open the Expo Developer Tools in your default web browser.

To run the app on a physical device or emulator, follow the instructions provided in the Expo Developer Tools.
1.You can run builded web application in your localhost
2.You will get a QR code to open in your current device.
3.For android you need to install expo go android app and then scan the QR
4.For ios you can simply scan the QR by opening your camera


Project Structure
The project structure is organized as follows:

App.js: The main entry point of the application.
components/: This folder contains reusable components used throughout the app.
screens/: This folder contains the different screens of the application.
assets/: This folder is used to store static assets such as images, fonts, etc.
constants/: This folder holds constant values or configuration settings used across the app.
styles/: This folder contains the global styles and themes used in the app.


Development
To start developing, you can modify the existing components or create new ones in the components/ folder.
Add new screens in the screens/ folder to extend the app's functionality.
Use the constants/ folder to store constant values or configuration settings.
Update the global styles and themes in the styles/ folder to maintain consistency throughout the app.