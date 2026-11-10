# Safari Glass 26 (starter project)

A free Android browser starter for the Samsung Galaxy A35. It uses Android WebView for real web browsing and a custom translucent, rounded interface inspired by iOS 26.

## Build
1. Install Android Studio on a Windows, Mac or Linux computer.
2. Open this folder as an existing Android Studio project.
3. Allow Gradle sync to finish.
4. Connect the Galaxy A35 with USB debugging enabled, or use Android Studio's APK build menu.
5. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

The APK will be under `app/build/outputs/apk/debug/`.

## Current features
- Real web browsing through Android WebView
- Search/address bar
- Back, forward, reload
- Multiple tabs (basic tab switcher)
- Bookmarks and browsing history
- Share current page
- Desktop-site user-agent toggle
- Rounded translucent interface

## Important limitations
- This is an early starter, not a finished production browser.
- The glass styling uses translucent surfaces; true system-level refraction varies by Android version/device.
- This is not Apple's Safari and does not use Apple's browser engine.
- No private/incognito mode is implemented yet. Do not treat ordinary tabs as private.
- No built-in ad blocker, password manager, download manager, sync, or certificate/security UI yet.
- Do not use it for sensitive accounts until the app has been thoroughly tested.
- It does not bypass Qustodio or any other parental controls.
