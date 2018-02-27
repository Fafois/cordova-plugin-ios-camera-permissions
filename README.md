## iOS 11 Camera Permissions Plugin for Apache Cordova

**Cordova / PhoneGap Plugin Permission Settings for NSCameraUsageDescription in iOS 11 by adding a declaration to the Info.plist file**

## Install

#### Latest published version on npm (with Cordova CLI >= 5.0.0)

```
cordova plugin add cordova-plugin-ios-camera-permissions --save
```

#### Latest version from GitHub

```
cordova plugin add https://github.com/Cordobo/cordova-plugin-ios-camera-permissions.git --save
```

#### Customising the message prompts

On installation you can customise the prompts shown by setting the following variables on installation.

- CAMERA_USAGE_DESCRIPTION for NSCameraUsageDescription

For example:
```
cordova plugin add cordova-plugin-ios-camera-permissions --variable CAMERA_USAGE_DESCRIPTION="your usage message" --save
```

## Platforms

Applies to iOS 10/11 only.

## License

[MIT License]
