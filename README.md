# FakeGPS Lock

Pick a location on the map → LOCK ON → your phone's GPS will report that location.
All features are in the top-left hamburger (☰) menu.

## Features
- Lock ON/OFF, auto-stop timer, setup check
- Search, real location, favorites (export/import), history
- Joystick, speed presets, multi-point route (loop), roam mode
- Realistic drift, accuracy, altitude
- Map type (satellite/topo), dark map, keep screen on
- Copy / share link / Google Maps, session distance
- In-app update (GitHub Releases)

## Setup (one time)
1. Create a new **Public** repository on GitHub.
2. Upload all project files (or the whole project).
3. In `MainActivity.kt` set `UPDATE_REPO = "username/repo"` to your own.
4. Go to Actions tab → "Build APK" → download FakeGPSLock.apk from Releases.

## Phone settings (one time)
Settings → Developer options → Select mock location app → FakeGPS Lock
