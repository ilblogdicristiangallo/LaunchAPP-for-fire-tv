# LaunchAPP-for-fire-tv
Fire TV app that auto-launches a selected app on boot.

<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>LaunchAPP Banner</h1>
    <img src="https://raw.githubusercontent.com/ilblogdicristiangallo/LaunchAPP-for-fire-tv/aa901d1f1128557c255eef33e58a177383824f98/ScreenShot/banner_tv.png" alt="LaunchAPP Banner">
</body>
</html>

LaunchAPP is a lightweight Fire TV utility that automatically starts a user-selected application right after the device boots (power on or restart). The app provides a simple setup screen to choose one of the installed apps, saves the selection, and triggers the launch during the next boot sequence so the target app opens as soon as the Fire TV is ready.

Key features:

Select any installed app to be launched at startup
Persistent configuration (your selection is saved)
Auto-launch on boot (after reboot/power cycle)
Built with Flutter with a native Android implementation via MethodChannel
Notes / limitations:

Some Fire OS versions may restrict boot-time auto-start behavior; you may need to open LaunchAPP once after install and ensure system settings allow it to run at startup.
This project is intended for Fire TV devices (Fire OS / Android TV-based environments).
