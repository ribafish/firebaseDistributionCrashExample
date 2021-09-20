# Example project for Firebase App Distribution plugin crashing when using Gradle configuration cache

## Steps to reproduce:

1. Run `./gradlew clean assembleRelease`
2. Run `./gradlew appDistributionUploadRelease`
3. Observe the crash report after running `appDistributionUploadRelease` with configuration cache enabled in `gradle.properties`
