# Pro Notes

<p align="center">
  <strong>A focused space for handwritten notes, sketches, and ideas.</strong><br />
  Built for Android with Kotlin and Jetpack Compose.
</p>

<p align="center">
  <a href="https://github.com/ItzNikk/pro-notes-android"><img src="https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white" alt="Android" /></a>
  <img src="https://img.shields.io/badge/Language-Kotlin-7F52FF?logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?logo=jetpackcompose&logoColor=white" alt="Jetpack Compose" />
  <img src="https://img.shields.io/badge/Min%20SDK-24-6C6C6C" alt="Minimum SDK 24" />
</p>

---

## Your ideas, on the page

Pro Notes is an Android note-taking app designed around a natural pen-and-paper workflow. Write with a stylus, shape your workspace around the way you work, and keep your notebook library close at hand.

## Highlights

- **Stylus-first writing** — optionally reserve ink input for an active stylus, with adjustable palm rejection and left-handed support.
- **Natural pen gestures** — circle to select, draw and hold to recognize shapes, scribble to erase, and hold to erase.
- **Flexible page navigation** — choose horizontal or vertical page movement and pull to add a page.
- **A workspace that fits** — dock the writing toolbar where it works best for you.
- **Privacy controls** — hide app content from screenshots and recent-app previews, and add a confidentiality mark to PDF exports.
- **Local library tools** — see notebook, page, and stroke totals, manage the trash, and reset local notes when needed.

## Screenshots

<!-- Add current app screenshots here. Suggested: library, writing canvas, and settings. -->

<p align="center">
  <em>Screenshots coming soon</em>
</p>

## Getting started

### Requirements

- Android Studio with Android SDK 36
- JDK 11
- Android device or emulator running Android 7.0 (API 24) or newer

### Build and run

1. Clone the repository:

   ```bash
   git clone https://github.com/ItzNikk/pro-notes-android.git
   cd pro-notes-android
   ```

2. Open the project in Android Studio and allow Gradle to sync.
3. Select the `app` run configuration and launch it on a device or emulator.

The app uses Gradle Kotlin DSL and Jetpack Compose. If your local setup has the Android SDK and JDK configured, you can also build from the project root:

```bash
./gradlew assembleDebug
```

On Windows:

```powershell
.\gradlew.bat assembleDebug
```

## Project structure

```
app/
  src/main/java/com/example/
    ui/          # Compose screens and components
    model/       # Notebook and page models
    viewmodel/   # UI state and actions
```

## Current status

Pro Notes is under active development. Features and screens may change as the app evolves. The repository currently targets Android 7.0+ and uses Jetpack Compose for its interface.

## Contributing

Ideas, bug reports, and thoughtful improvements are welcome. Open an issue to discuss a change before starting substantial work, then submit a pull request with a concise description of what changed.

## License

No license file is currently included. Until a license is added, all rights are reserved by the repository owner.
