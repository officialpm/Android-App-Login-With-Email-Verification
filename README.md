# Android Login App (Email / OTP Verification)

A sample **Android (Java)** app demonstrating a basic authentication flow with **registration**, **login**, and **email/OTP verification**.

> This is a portfolio/learning project.

## Tech stack

- Android (Java)
- Gradle
- Networking: **Volley**

## Backend/API

The app is wired to a hosted backend URL in:

- `app/src/main/java/com/parth/login/helper/Functions.java`

Example (current):

```java
private static String MAIN_URL = "https://medicaljava.000webhostapp.com/login/";
```

If that endpoint is unavailable, replace it with your own backend.

## Run locally

1. Open the project in **Android Studio**.
2. Let Gradle sync.
3. Run on an emulator or physical device.

## Project structure

- `app/` — Android app module
- `gradle/`, `gradlew*` — Gradle wrapper

## Notes / Security

This code is for demo/learning. Don’t ship it as-is for production auth.

## License

No license specified.
