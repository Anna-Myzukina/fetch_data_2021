# fetch_data_2021

## 2 approaches to fetch data from APIs in Flutter

## Getting Started:

To start developing mobile apps with Flutter you need to:

1. Download and install the Flutter SDK.
2. Update your PATH with the Flutter SDK.
3. Install Android Studio with the Flutter and Dart plugins, or your favorite editor.
4. Install an Android emulator, an iOS simulator (requires a Mac with Xcode), or use a physical device.

For more information about Flutter installation, see [Get Started: Install](https://flutter.dev/docs/get-started/install). To set up an editor, see [Get Started: Set up an editor](https://flutter.dev/docs/get-started/editor?tab=androidstudio). When installing an Android emulator, feel free to use the default options such as a Pixel 3 phone with the latest System Image. It's recommended but not required to enable VM acceleration. After the above 4 steps have been completed, you can return to the codelab. To complete this codelab, you only need to install Flutter for one platform (Android or iOS).

### Ensure your Flutter SDK is in the right state
Before proceeding with this codelab, make sure that your SDK is in the right state. If the Flutter SDK was installed previously, then use flutter upgrade to ensure that the SDK is at the latest state.


    flutter upgrade
 
Running flutter upgrade will automatically run flutter doctor. If this a fresh Flutter install and no upgrade was necessary, then run flutter doctor manually. It will report if there are any dependencies you need to install to complete the setup. Feel free to ignore the check marks that are not relevant for you (for example Xcode if you do not intend to develop for iOS).


    flutter doctor
    
Frequently Asked Questions
Where is Dart's SDK located within /flutter folder?
How do I accept Android licenses?
How do I create an Android virtual device in Android Studio?

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
