# Yeongju Lee

**Android Engineer** · Seoul, South Korea

I build native Android for devices, not just app stores. Most of my work sits close to the hardware — embedded Android on custom devices, wearables, multi-display systems — where reliability and performance matter more than following the latest UI trend. Shipping to Google Play since 2022.

## Experience

**Android Software Engineer — TJ Media** · Apr 2025 – present

Working on the Android software built into music and karaoke hardware.

- Rewrote the OTA updater from Java to Kotlin (~95%), migrating the core off `AsyncTask` onto Coroutines and removing thread and Context leaks.
- Built the music-score settings system in MVVM and Clean Architecture, bridging the app to a native `.aar` scoring engine — a module I own end to end, coordinating seven song types across three displays.
- Diagnosed settings-menu jank caused by cross-process `ContentProvider` reads on the hot path and replaced them with a thread-safe in-memory cache.

**Android Software Engineer — L&H Labs** · May 2024 – Aug 2024

- Built real-time phone-to-watch BLE synchronisation for a non-standalone Wear OS companion, with the watch running as a GATT server over a custom 8-byte protocol.
- Shipped around 59 Wear OS screens in Jetpack Compose on a Hilt/MVVM StateFlow architecture, including custom cardiac charts drawn on Canvas.
- Wrote unit tests for the Retrofit layer using Robolectric and Hilt, alongside instrumentation tests.

## Projects

**TookTook** — a social fishing-log app, currently in development. Encrypted token storage (Tink AEAD over DataStore, key held in the Android Keystore), Kakao login with silent refresh, and an off-main-thread image pipeline (downsample, EXIF, WebP) behind the catch-record flow.

**Peekabook** — a book-sharing app live on Google Play. I led the Android development: onboarding, Kakao login, book CRUD, and barcode search with CameraX and ML Kit.
[Play Store](https://play.google.com/store/apps/details?id=com.sopt.peekabookaos) · [App Store](https://apps.apple.com/kr/app/%ED%94%BC%EC%B9%B4%EB%B6%81/id6446477224)

## Tech

Kotlin · Java · Jetpack Compose · Coroutines & Flow · MVVM / Clean Architecture · Hilt · Retrofit / OkHttp · JUnit / Robolectric · BLE · Wear OS · GitHub Actions · Git

## Background

B.Eng. in Media Technology with a double major in Computer Science, The Catholic University of Korea. Grand Prize (x2) and Android Part MVP across national hackathons (SOPT, GDSC).

## Contact

- [LinkedIn](https://www.linkedin.com/in/2zerozu/)
- Email: yungju9982@naver.com
