# Floating R

A standalone Android floating-link utility.

## Features

- Draggable floating `R` button
- Single tap opens the saved HTTP/HTTPS link
- Double tap within 100 ms opens the link editor
- Link persists using SharedPreferences
- Overlay permission is requested only when enabling the feature
- Foreground service keeps the overlay alive
- No dependency on another app

## Build on GitHub

1. Create a new GitHub repository.
2. Upload the contents of this project.
3. Push to the `main` branch, or open:
   **Actions → Build Floating R APK → Run workflow**
4. When the workflow finishes, open the workflow run.
5. Download the `Floating-R-debug` artifact.
6. Extract the ZIP and install `app-debug.apk`.

## Important

Android may show a notification while the floating service is running. This is normal for a foreground service.

The first time you press **Enable Floating R**, Android will ask for
"Display over other apps" permission. Grant it for the R button to appear.
