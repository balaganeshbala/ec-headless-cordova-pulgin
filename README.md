# PhoneGap app integration 
JusPay has a native android and iOS client which can be used by PhoneGap applications. To get started, you first need to download the code for the plugin.

## Installation 
This requires phonegap/cordova CLI 5.0+

Add the plugin to your phonegap/cordova apps using these commands.

```sh
$ phonegap plugin add juspay/ec-headless-cordova-plugin
```
(or)
```sh
$ cordova plugin add juspay/ec-headless-cordova-plugin
```


## Dependencies 

#### For Android 

To add or change ec-hl-cordova-plugin specific dependencies, refer this file. 
```sh
platforms/android/ec-hl-cordova-plugin/<appname>-_plugin-dependencies.gradle
```

#### For iOS 

Minimum supporeted iOS version: 10.0

If you are getting the pod error like `Failed to install 'ec-hl-cordova-plugin': Error: pod: Command failed with exit code 1` while installing "ec-hl-cordova-plugin" for ios, please update `platform :ios` to '10.0' in the Podfile and run the command `pod install`.
