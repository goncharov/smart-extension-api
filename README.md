smart-extension-api
===================

Just a maven binary repo for Sony Smart Extras API.

For Gradle use build script like that (tested with new android-build-system 0.5.6):

```groovy
repositories {
    maven { url 'https://raw.github.com/goncharov/smart-extension-api/2.0/' }
}

dependencies {
    compile 'com.sonyericsson.extras.liveware:utils:2.0'
}
```

