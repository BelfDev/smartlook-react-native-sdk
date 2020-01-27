# Smartlook React Native SDK

The documentation for React Native SDK can be found at https://smartlook.github.io/docs/sdk/react-native/

Core of the React Native SDK is based on native SDKs for Android and iOS

This repository serves as an issue tracker.

# Changelog
All notable changes to this project will be documented here.

## [0.23.0] - 2020-01-27
### Changed
- iOS: podspec moved to root folder of the bridge, making bridge installation easier
- iOS: removed all references to `UIWebView` (https://developer.apple.com/news/?id=12232019b)


## [0.18.0] - 2019-10-8
### Changed
- iOS - RN 0.6.0 and higher: Smartlook now integratind via Cocoapods. Latest version of native Smartlook SDK is always used. https://smartlook.github.io/docs/sdk/react-native/#ios
- iOS - RN before 0.6.0: no longer directly supported. `Smartlook.framework` removed from the npm package, must be downloaded and added to the Xcode project manually. https://smartlook.github.io/docs/sdk/react-native/#ios


## [0.7.0] - 2019-05-23
### Changed
- Improved handling of application lifecycle


## [0.6.0] - 2019-04-11
### Changed
- **Breaking changes:** iOS SDK is no longer available via Pods but is provided as a bundle in the npm package - integration steps are described in the documentation mentioned above
