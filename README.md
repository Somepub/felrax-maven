# Felrax Android SDK Maven repository

This public repository contains compiled Android SDK artifacts. The Felrax
source repository remains private. Artifacts are distributed under the
[Felrax Proprietary SDK License](LICENSE).
Third-party dependency notices are in [THIRD_PARTY_LICENSES.html](THIRD_PARTY_LICENSES.html).

For Gradle, add the repository and dependency:

```kotlin
repositories {
    google()
    mavenCentral()
    maven("https://somepub.github.io/felrax-maven/")
}

dependencies {
    implementation("io.github.somepub:felrax-android-sdk:0.1.0-beta1")
}
```

The repository contains the full SDK and its plugin API, IME, camera, runtime,
and native-host dependencies. The `-sources.jar` files contain license and
release information, not private source code. Every published version is
immutable; fixes are released under a new version.
Public Maven artifacts for the Felrax Android SDK
