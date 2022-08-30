fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios getTeamNames

```sh
[bundle exec] fastlane ios getTeamNames
```



### ios create_keys

```sh
[bundle exec] fastlane ios create_keys
```



### ios download_keys

```sh
[bundle exec] fastlane ios download_keys
```

Download keys

### ios buildAdHoc

```sh
[bundle exec] fastlane ios buildAdHoc
```

Build Ad Hoc

### ios build

```sh
[bundle exec] fastlane ios build
```

Build

### ios app_center

```sh
[bundle exec] fastlane ios app_center
```

App Center

### ios firebase

```sh
[bundle exec] fastlane ios firebase
```

Deploy to Firebase Distribution

### ios tf

```sh
[bundle exec] fastlane ios tf
```

Upload to Test Flight

### ios tf_external

```sh
[bundle exec] fastlane ios tf_external
```

Upload to Test Flight - External

### ios inc

```sh
[bundle exec] fastlane ios inc
```

Increment Build Number

### ios incVersionAuto

```sh
[bundle exec] fastlane ios incVersionAuto
```

Incrementando Numero de version Automaticamente

### ios getDevCert

```sh
[bundle exec] fastlane ios getDevCert
```

Get Cert for development

### ios getDisCert

```sh
[bundle exec] fastlane ios getDisCert
```

Get Cert for distribution

### ios CreateCert

```sh
[bundle exec] fastlane ios CreateCert
```

Create a type cert

### ios getProvisioningProfileDev

```sh
[bundle exec] fastlane ios getProvisioningProfileDev
```

Gets provisionilg profiles development with sigh

### ios getProvisioningProfileAdHoc

```sh
[bundle exec] fastlane ios getProvisioningProfileAdHoc
```

Gets provisionilg profiles AdHoc with sigh

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
