# HelloWorldApp

A simple Android application built with Jetpack Compose and Kotlin.

## Tech Stack

- **Language:** Kotlin
- **UI Framework:** Jetpack Compose
- **Architecture:** MVVM with Clean Architecture principles
- **Build System:** Gradle with Kotlin DSL
- **Min SDK:** 24 (Android 7.0)
- **Target SDK:** 34 (Android 14)

## Project Structure

```
HelloWorldApp/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/helloworldapp/
│   │   │   ├── data/           # Data layer (repository)
│   │   │   ├── ui/main/        # Main screen (ViewModel + Compose)
│   │   │   ├── theme/          # Material 3 theme (colors, typography)
│   │   │   ├── MainActivity.kt
│   │   │   └── Navigation.kt
│   │   └── res/                # Android resources
│   └── build.gradle.kts
├── gradle/                     # Gradle wrapper
├── build.gradle.kts           # Root build config
├── settings.gradle.kts
└── gradle.properties
```

## Features

- Jetpack Compose UI
- Material Design 3 theming
- ViewModel-based state management
- Edge-to-edge display support

## Build

```bash
./gradlew assembleDebug   # Debug APK
./gradlew assembleRelease # Release APK
```

## Run

Install the debug APK on a device/emulator:

```bash
./gradlew installDebug
```