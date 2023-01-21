# Version Checker
![](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)

A kotlin library for android platform to efficiently check the build version of android device which reduces the effort to continuously writing if cases.

## Installation

In settings.gralde
```groovy
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
```

In project build.gradle

```groovy
dependencies {
    implementation 'com.github.PawanRoy1997:VersionChecker:1.0.0'
}
```

## Usage

Instead of
```kotlin
if(Build.VERSION.SDK_INT > Build.VERSION_CODES.JELLY_BEAN_MR1){
    // Do Some work here
}
```

Use
```kotlin
if(isAboveJELLY_BEAN_MR1){
    // Do Some work here
}
```
