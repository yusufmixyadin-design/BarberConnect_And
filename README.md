# BarberConnect Android MVP (starter project)

This is a starter Android project for the BarberConnect barber marketplace.
It is a **prototype**, not a production-ready app or signed APK.

## Features in this starter
- Black & gold theme
- English / Somali language toggle (simple in-app labels)
- Barber directory sample cards
- Barber profile / services
- Booking form prototype
- Commission concept shown in the owner dashboard

## Build
1. Install Android Studio (latest stable).
2. Open this folder as a project.
3. Let Gradle sync.
4. Run on an Android emulator or phone.

To make a distributable APK: Android Studio -> Build -> Build APK(s).
For production, add a backend, authentication, database, verified barber accounts,
booking conflict prevention, payments/payouts, privacy policy, and app signing.

## Important
The barber names and prices are demo data. No bookings or payments are sent to a server.

\n## Build APK with GitHub Actions (no laptop needed)\n
1. Create a GitHub repository and upload this project folder's contents.
2. Make sure the project root (`build.gradle`, `settings.gradle`, and `app/`) is at the repository root.
3. Open **Actions** and select **Build BarberConnect APK**.
4. Tap **Run workflow** (or push to `main`/`master`).
5. When it finishes, open the workflow run and download the **BarberConnect-debug-apk** artifact.

The workflow builds a debug APK. This is a test install package, not a signed release for publishing.
