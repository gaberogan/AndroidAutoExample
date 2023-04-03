# AndroidAutoExample

Run `yarn`

Install Android Auto DHU, see guide: https://developer.android.com/training/cars/testing#test-auto

Run Android Auto DHU from your android SDK folder (open Android Studio SDK manager to see location)

e.g. /Users/gabe/Library/Android/sdk/extras/google/auto/desktop-head-unit --usb

Connect a physical Android device to your computer, make sure USB Debugging is enabled first

Run `npx react-native start` in the root folder of this project to start the Metro JS bundler

Run `adb reverse tcp:8081 tcp:8081` to expose Metro on port 8081 to the device

Run the app on the device