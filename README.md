# PRIME LEADER Mobile Optimizer v1.0

Build-ready Android project reconstructed from the supplied legacy APK UI.

## Included
- PRIME LEADER dark/crimson glass UI
- Dashboard/device scanner with real device RAM/storage/battery/display data
- Junk/RAM clean action (Android-limited, no root)
- Performance profiles and safe optimization UI
- Free Fire / Free Fire MAX launcher
- Gaming/GFX configuration UI
- Thermal & battery monitor
- Synthetic benchmark (clearly labeled synthetic)
- Restore/defaults UI
- Local activation key: `leaderm1`
- Battery optimization and overlay permission shortcuts
- No KeyAuth, Discord webhook, telemetry, credential collection, or hidden network payloads
- Package: `com.primeleader.mobileoptimizer`

## Online build (GitHub Actions)
1. Create a new GitHub repository.
2. Upload the entire project folder.
3. The included `.github/workflows/android.yml` builds a debug APK automatically.
4. Open the workflow run and download the `prime-leader-debug-apk` artifact.

The project intentionally has no Gradle wrapper because the build can install Gradle on the hosted runner.
