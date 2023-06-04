# contact-app-using-react-native
# Step 1: Set up React Native Environment

1.Install Node.js: Download and install Node.js from the official website (https://nodejs.org

2.Install React Native CLI: Open a command prompt and run the following command:
                
                npm install -g react-native-cli
                
 # Step 2: Create a New React Native Project

1.Open a command prompt and navigate to the directory where you want to create the project.

2.Run the following command to create a new React Native project

                 npx react-native init contactapp-master
                 
3.Once the project is created, navigate to the project directory:
                 
                 cd contactapp-master
                 
# Step 3: Install Required Libraries and Plugins

1.Install React Navigation: React Navigation is a popular library for handling navigation in React Native. 
           
           npm install @react-navigation/native
           
npm install react-native-reanimated react-native-gesture-handler react-native-screens react-native-safe-area-context @react-native-community/masked-view

2.Install the required dependencies for React Navigation:

           npm install @react-navigation/stack

3.Install React Native Contacts: React Native Contacts is a library that allows access to the device's contacts.
         
         npm install react-native-contacts

4.Install React Native Modal: React Native Modal is a component for displaying modals and popups.
              
              npm install react-native-modal
              
   ## Libraries and Plugins

The following libraries and plugins are used in this app:

- React Navigation: A library for handling navigation in React Native.
- React Native Contacts: A library for accessing device contacts.
- React Native Modal: A component for displaying modals and popups.

## Prerequisites

Before running the app, make sure you have the following installed:

- Node.js: https://nodejs.org
- Android SDK: Follow the React Native documentation for setting up the Android development environment: https://reactnative.dev/docs/environment-setup


## Running the App

Follow the steps below to run the app on an Android device or emulator:

1. Start the Metro Bundler:

    npx react-native start

2. In a new command prompt, run the app on a connected Android device or emulator:

    npx react-native run-android


If successful, the app should launch on your Android device or emulator. You will be able to view and search contacts, and tap on a contact to view their details in a popup.

## Building the APK

To build a release APK for distribution, follow the steps below:

1. Generate a signing key. Refer to the React Native documentation for instructions: https://reactnative.dev/docs/signed-apk-android
2. Update the `android/app/build.gradle` file with your signing configuration.
3. Open a command prompt and navigate to the project directory.
4. Run the following command to generate the APK:
  cd android
./gradlew assembleRelease

5. Once the build process completes, the APK file will be located at `android/app/build/outputs/apk/release/app-release.apk`.


    

