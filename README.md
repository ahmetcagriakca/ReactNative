React Native initialize

npm install -g react-native-cli

react-native init albums

  Run instructions for iOS:
    • cd c:\Projects\Git\ReactNative\albums && react-native run-ios
    - or -
    • Open ios\albums.xcodeproj in Xcode
    • Hit the Run button

  Run instructions for Android:
    • Have an Android emulator running (quickest way to get started), or a device connected.
    • cd c:\Projects\Git\ReactNative\albums && react-native run-android

#start react native commands 

react-native start
react-native run-android

# expo init
cd ..
expo init ExpoAwesomeProject

cd ExpoAwesomeProject
npm start


https://stackoverflow.com/questions/44446523/unable-to-load-script-from-assets-index-android-bundle-on-windows

(in project directory) mkdir android/app/src/main/assets
react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res
react-native run-android


Errors:
Emulator: CPU acceleration status: Unable to open HAXM device: ERROR_FILE_NOT_FOUND

https://stackoverflow.com/questions/51402409/android-studio-emulator-error-emulator-cpu-acceleration-status-unable-to-open


