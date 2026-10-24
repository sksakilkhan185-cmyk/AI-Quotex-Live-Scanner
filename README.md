# AI Quotex Live Scanner — starter project

This is a starter Android project for a movable floating panel and a GitHub Actions APK build.

## Important limitations
- The current `SCAN (DEMO)` button does **not** capture the screen or use an AI model.
- The displayed `NO TRADE` result is intentional. Do not use this starter as a trading signal tool.
- A real live-screen scanner needs Android MediaProjection consent flow, a foreground media-projection service, secure image processing, and an AI/chart-analysis backend or model.
- A confidence percentage must be calibrated and validated on historical data; it cannot promise an 80–90% win rate.
- Do not enter Quotex passwords or other account credentials into an untrusted app.

## Build APK using GitHub on a phone
1. Upload the project files to the root of your GitHub repository. Keep the folder structure exactly as shown.
2. Commit the files to the `main` branch.
3. Open the repository's **Actions** tab.
4. Select **Build Android APK**.
5. Tap **Run workflow** if it is not already running.
6. Open the completed workflow run and find **Artifacts**.
7. Download `AI-Quotex-Scanner-debug-apk.zip`, extract it on your phone, then install `app-debug.apk`.
8. If Android blocks installation, enable “Install unknown apps” for the app you used to open the APK, only if you trust the source.

## Repository layout
- `app/` — Android app source
- `.github/workflows/build-apk.yml` — cloud APK build workflow
- `README.md` — instructions

This is a prototype, not financial advice and not a verified market-prediction system.
