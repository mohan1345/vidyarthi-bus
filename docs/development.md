# Development Guide

## Open the Project

Open the repository root in Android Studio:

```text
vidyarthi-bus-main/
```

Android Studio should detect the Gradle project from `settings.gradle.kts`.

## Common Commands

Build a debug APK:

```powershell
.\gradlew.bat assembleDebug
```

Run local unit tests:

```powershell
.\gradlew.bat testDebugUnitTest
```

Run Android lint:

```powershell
.\gradlew.bat lintDebug
```

## Local Files

Do not commit `local.properties`, Android Studio build output, APK files, signing keys, or generated Gradle folders. These are already covered by `.gitignore`.
