# Android Packages

Published Maven repository for the Erik Android artifacts.

## Base repository URL

`https://raw.githubusercontent.com/suhailp-eccentric/android-packages/main`

## Gradle example

```groovy
repositories {
    google()
    mavenCentral()
    maven { url = uri("https://jitpack.io") }
    maven { url = uri("https://raw.githubusercontent.com/suhailp-eccentric/android-packages/main") }
}
```
