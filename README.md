# xignite-maven-repo
Unofficial, maven-compatible source of Xignite java sdk releases.
See the official [Xignite java sdk repository](https://github.com/Xignite/JavaSDK), for documentation and old releases.

# Gradle

repositories {
    maven { url "https://raw.github.com/massaroni/xignite-maven-repo/master/mvn/releases" }
}

dependencies {
    compile 'com.xignite:xignite-sdk:1.0.2.0'
}
