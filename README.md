# Android Packages

Published Maven repository for the Erik Android artifacts.

## Current artifact versions

- Flutter host module AARs: `1.0.1`
- Native Erik Android SDK AAR: `1.0.0`

## Base repository URL

`https://raw.githubusercontent.com/suhailp-eccentric/android-packages/main`

## Gradle example

```groovy
repositories {
    google()
    mavenCentral()
    maven { url = uri("https://raw.githubusercontent.com/suhailp-eccentric/android-packages/main") }
}
```

## Native Android SDK

```groovy
dependencies {
    implementation "com.eccentric:erik-android-sdk:1.0.0"
}
```

## Flutter host module AARs

```groovy
dependencies {
    debugImplementation "com.example.erik_flutter_host_module:flutter_debug:1.0.1"
    releaseImplementation "com.example.erik_flutter_host_module:flutter_release:1.0.1"
    profileImplementation "com.example.erik_flutter_host_module:flutter_profile:1.0.1"
}
```
