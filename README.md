# phonegap-googlemaps-plugin
This plugin helps you leverage [Google Maps Android SDK v2](https://developers.google.com/maps/documentation/android/) and [Google Maps SDK for iOS](https://developers.google.com/maps/documentation/ios/) with your JavaScript.
[PhoneGap Build](http://build.phonegap.com/) and [Apache Cordova](http://cordova.apache.org/) are supported.

> Note: The pluglin is a fork of [Nipher](https://github.com/Nipher/phonegap-googlemaps-plugin) version forked from  [wf9a5m75](https://github.com/wf9a5m75/phonegap-googlemaps-plugin)

## Installation 

### Cordova CLI
Use the following command to install from npmjs repository (requires cordova 5.0+)
```
cordova plugin cordova-plugin-armsoft-googlemaps --variable API_KEY_FOR_ANDROID="YOUR_API_KEY_FOR_ANDROID" --variable API_KEY_FOR_IOS="YOUR_API_KEY_FOR_IOS"
```

To fetch the latest version from GitHub, use
```
cordova plugin add https://github.com/roberthovhannisyan/phonegap-googlemaps-plugin --variable API_KEY_FOR_ANDROID="YOUR_API_KEY_FOR_ANDROID" --variable API_KEY_FOR_IOS="YOUR_API_KEY_FOR_IOS" 
```

### PhoneGap Build
Add this to your config.xml:
```xml
<gap:plugin name="cordova-plugin-armsoft-googlemaps" source="npm">
    <param name="API_KEY_FOR_ANDROID" value="YOUR_API_KEY_FOR_ANDROID" />
    <param name="API_KEY_FOR_IOS" value="YOUR_API_KEY_FOR_IOS" />
</gap:plugin>
```

### API Keys
To get your iOS API key, follow Step 5 of [this guide](https://developers.google.com/maps/documentation/ios/start)
To configure Android, follow [this guide](https://developers.google.com/maps/documentation/android/signup)

## Documentation

Full documentation for the plugin can be found on wf9a5m75/phonegap-googlemaps-plugin [Wiki Pages](https://github.com/wf9a5m75/phonegap-googlemaps-plugin/wiki)
