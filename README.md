# Expo CLI Android Build Failure with react-native-reanimated

This repository demonstrates a bug and its solution related to Android builds in Expo CLI when using the `react-native-reanimated` library.  The bug manifests as a failure during the Android build process, often with errors related to missing native libraries or linking issues. The solution involves verifying native module configurations and potentially adjusting build settings.

## Bug
The `bug.js` file contains a simple React Native component that uses `react-native-reanimated`.  Attempting to build the Android version of this app using the Expo CLI results in a build failure.  Specific error messages can vary but will generally indicate problems with the native Android module integration.

## Solution
The `bugSolution.js` file presents a corrected version with added steps to ensure successful native module linking.  This often involves verifying Android build configurations in your `android` directory and ensuring that any necessary dependencies are correctly configured. 