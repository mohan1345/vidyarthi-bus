# Vidyarthi Bus

Vidyarthi Bus is an Android project for a student bus companion app. The app is intended to help students review route information, crowd status, offline running details, and reporting flows for bus travel.

## Project Structure

- `app/` contains the Android application module.
- `designs/` contains HTML design prototypes for the planned app screens.
- `gradle/` contains the Gradle wrapper and version catalog files.

## Requirements

- Android Studio
- JDK 11 or newer
- Android SDK with the configured compile SDK installed

## Build

On Windows:

```powershell
.\gradlew.bat assembleDebug
```

On macOS or Linux:

```bash
./gradlew assembleDebug
```

## Design Screens

The `designs/` folder includes prototypes for splash, home dashboard, route selection, live crowd, report status, history, offline mode, shared contacts, and settings screens.
