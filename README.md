# Healther — Android Reference Lock

Healther Android app project built from user-approved UI references (60 light + 60 dark).
The locked source package is stored as `payload/healther-source.tar.xz`, with an integrity check in the workflow.

**Build:** open **Actions** → **Build Healther APK** → **Run workflow**.
After a successful run download the `Healther-debug-APK` artifact and extract `app-debug.apk`.

**Status:** reference layout is browser-tested, but Android compile and real-device / Galaxy Watch / Health Connect integration are being verified.
Health data must be granted via Health Connect and is not present in this repository.
**Never commit personal health exports or private tokens.**

## Source integrity
Archive SHA-256: `81bcae6a98c0cc3cad86772612103b32a814dc8d5bfb41bed00de5db87460142`.
The workflow restores the original source tree unchanged before compiling; design references are never modified.

This repository is currently public. If you prefer the design sources private, change the repository visibility in **Settings → General → Danger Zone**.
