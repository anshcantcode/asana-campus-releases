# ASANA Campus — Android pilot

[Open ASANA](https://asana-campus.pages.dev) · [Android releases](https://github.com/anshcantcode/asana-campus-releases/releases)

ASANA combines short, guided practice on your phone with an optional laptop camera studio. Accounts require a verified `@srmist.edu.in` address. Use the same account on both devices; approve the phone's first connection on the laptop.

## Install a pilot build

1. Open Releases on your Android phone and select the latest **pre-release**.
2. Download its APK. Compare its SHA-256 with the release's checksum file if you need to verify the download.
3. Open the APK and allow installation from your chosen browser when Android asks. You can turn that installation permission off afterward.
4. Open ASANA and sign in. Release builds connect to the public campus service automatically; there is no server-address setup.
5. Install future APKs from this repository over the existing release app. Keep the same installation to preserve device preferences.

A developer/debug build uses a different signing certificate and cannot be updated directly to a release build. Saved account progress belongs to the server; unfinished local work and device preferences do not.

## Pair with a laptop

Open [ASANA](https://asana-campus.pages.dev) on your laptop, sign in, and leave the page open. On your phone, select that laptop during practice setup and approve the request on the laptop. Camera access and Shared room video are separate, explicit choices. Reconnection must not resume movement until you choose Resume.

## Pilot status

This is an early pilot, not a validated 100–300 student rollout. Real SRM signup has been confirmed. Automated local pairing, privacy and catalogue checks are recorded; physical mobile-data pairing, sustained phone heat/haptics/speech, varied-movement cutouts and deployed cohort capacity remain acceptance gates. Release notes distinguish observed tests from pending tests.

The free backend may take about a minute to wake after inactivity. Optional room-video relay has a small, capped trial allowance; guidance and control fallback are designed separately from video. No uptime guarantee is made.

This repository contains distribution artifacts and installation notes. Private backend source, student records and service credentials are kept elsewhere. Runtime asset/license notices are included inside the application.
