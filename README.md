This repository provides easy access to ZoomUs android sdk.

Library includes sdk archives:
- commonlib.aar
- mobilertc.aar

### Usage

```gradle
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Now you can add dependency:
```gradle
dependencies {
    implementation 'com.github.zoom-us-community:jitpack-zoom-us:zoom-sdk-android-5.13.1.11014'
}
```

Note: You can use commit hash instead of Tag.


### Links
- [publishing](./docs/DEV.md)