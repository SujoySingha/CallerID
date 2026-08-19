# Bangladesh Caller ID (Truecaller Integration Boilerplate)

A modern Android Kotlin application that detects incoming calls in real-time using `CallScreeningService`, queries Truecaller Search API with an installation token, caches results in a local Room database, and displays a Heads-up Notification overlay.

## Setup Instructions
1. Open this project in Android Studio (Giraffe / Hedgehog / Iguana / Ladybug).
2. Sync Project with Gradle Files.
3. Obtain your Truecaller Installation ID token via `npx truecallerjs login` with your Bangladeshi (+880) mobile number.
4. Launch the app and paste the token in Settings.
5. Grant the **Call Screening & Spam** default app role when prompted in the app.
