fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## iOS
### ios add_device
```
fastlane ios add_device
```
Lane to add a new device to provisioning profiles
If you want to add a new device run:

```
fastlane add_device
```

After the new device was added you can refresh your provisioning profile by running:
```
fastlane renew_profile
```
  
### ios refresh_profiles
```
fastlane ios refresh_profiles
```

### ios qa
```
fastlane ios qa
```
Builds a QA version of the application and distributes to HockeyApp
### ios deploy
```
fastlane ios deploy
```
Builds and publishes production to AppStore
### ios create_app
```
fastlane ios create_app
```
Creates the app in DevCenter and App Store Connect

----

## Android
### android qa
```
fastlane android qa
```
Builds a QA version of the application and distributes to HockeyApp
### android deploy
```
fastlane android deploy
```
Builds and signs a production release to distribute in Google Play Store

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
