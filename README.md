smart-extension-api
===================

Just a maven binary repo for Sony Smart Extras API.

Define one of this repositories:

* ```https://raw.github.com/goncharov/smart-extension-api/master/```
* ```http://dl.bintray.com/goncharov/smart-extension-api```

and declare the needed version in the dependencies:

* 2.1 (```com.sonyericsson.extras.liveware:utils:2.1```)
* 2.0 (```com.sonyericsson.extras.liveware:utils:2.0```)
* 1.0.4 (```com.sonyericsson.extras.liveware:utils:1.0.4```)

For Gradle use build script like that (tested with ```New Build System 0.6.3```):

```groovy
repositories {
    maven { url 'https://raw.github.com/goncharov/smart-extension-api/master/' }
}

dependencies {
    compile 'com.sonyericsson.extras.liveware:utils:2.1'
}
```

