# HNG Mobile Showcase

Welcome to the **HNG Mobile Showcase** project! This repository contains the code for the mobile app developed as part of the HNG internship program.

## GitHub Repository

You can find the GitHub repository for this project at the following link:

[HNG Mobile Showcase GitHub Repo](https://github.com/kay4371/hng-mobile-showcase)

## HNG Backlinks

This app showcases HNG's Hire Pages and links to resources for mobile developers:

- [HNG React Native Developers](https://hng.tech/hire/react-native-developers)
- [HNG Flutter Developers](https://hng.tech/hire/flutter-developers)
- [HNG Kotlin Developers](https://hng.tech/hire/kotlin-developers)
- [HNG Mobile Developers](https://hng.tech/hire/mobile-developers)
- [HNG Android Developers](https://hng.tech/hire/android-developers)
- [HNG iOS Developers](https://hng.tech/hire/ios-developers)

## Clone, Build, and Run the App

### Prerequisites

- Node.js (>=12.0.0)
- npm (>=6.0.0) or yarn
- React Native CLI installed

### Steps to Run the App

1. **Clone the repository:**
2. **Install dependencies:**

Run the following command to install the required dependencies:
   First, clone the repository to your local machine:
   npm install
   or
   yarn install

3. Run the app on an emulator or device:

For Android:

npx react-native run-android

For iOS (Mac users only):
npx react-native run-ios


Deploy to Appetize.io

Steps to Deploy:

Build your app for release:

For Android, generate the APK:

cd android && ./gradlew assembleRelease

The APK file will be located in android/app/build/outputs/apk/release/.

For iOS, generate the IPA (on Mac):

xcodebuild -workspace ios/YourApp.xcworkspace -scheme YourApp -sdk iphoneos -configuration AppStoreDistribution archive -archivePath YourApp.xcarchive

Upload the .apk or .ipa file to Appetize.io:

Go to Appetize.io

Upload your .apk (Android) or .ipa (iOS) file.

Copy the generated link.

Update the README with the Appetize.io link:

Add the following section to your README:


   ```bash
   git clone https://github.com/kay4371/hng-mobile-showcase.git
   cd hng-mobile-showcase



   ## Live Preview

Click the link below to try the app on Appetize.io:

👉 [View on Appetize.io](https://appetize.io/app/b_drihaeahy2yf4ljsrojtu4m7ai)

Or embed directly here:

<iframe width="320" height="640" src="https://appetize.io/embed/b_drihaeahy2yf4ljsrojtu4m7ai" frameborder="0" scrolling="no"></iframe>


