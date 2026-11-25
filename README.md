# Flixster

Android movie browser app built in Kotlin using The Movie Database (TMDB) `now_playing` API, `AsyncHttpClient`, and `Glide`.

---

## Demo

<p align="center">
  <img src="Walkthrough.gif" width="480" alt="Flixster app walkthrough" />
</p>

---

## Features

- Fetches currently playing movies from the TMDB REST API (`MainActivity.kt` + `Movie.kt`).
- Displays movie titles, overviews, and poster artwork inside a `RecyclerView` (`MovieAdapter.kt`).
- Responsive layouts for both **portrait** (`res/layout/`, poster image) and **landscape** (`res/layout-land/`, backdrop image beside details).
- Placeholder graphics and image caching via Glide.

---

## Tech Stack

- **Language:** Kotlin
- **Networking:** `com.codepath.libraries:asynchttpclient`
- **Image Loading:** Glide (`placeholder.png` fallback)
- **UI:** `RecyclerView`, ConstraintLayout

---

## Running Locally

1. Clone this repository and open it in **Android Studio**.
2. Sync Gradle and allow dependencies to download.
3. Run the `app` configuration on an Android emulator or physical device.
