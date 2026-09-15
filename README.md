# The Islamic Dilemma — Production Android Releases

Stable Android releases for **The Islamic Dilemma**, an offline-first research application for examining the Qur'an's relationship to the Torah and Gospel.

## Current release

Download the latest stable APK from the [releases page](https://github.com/mcographics/Islamic-Dilemma-Production/releases/latest). The matching AAB and SHA-256 sidecars are included for verification and future managed-distribution decisions.

- Package: `com.majesticcreations.islamicdilemma`
- Current stable version: `0.2.1`
- Android version code: `20001`
- Release tag: `v0.2.1`
- Update channel used by the stable app: `mcographics/Islamic-Dilemma-Production`
- Patch focus: reliable offline Bible full-text search loading and results

## Verification

Compare the downloaded artifact with its `.sha256` sidecar before installing. The APK is signed with the stable production identity. The AAB is prepared for future managed distribution; it has not been uploaded to Google Play from this repository.

## Important boundaries

The app packages its core research material locally and has no account or cloud synchronization. External references and update checks require network access. Saved research remains local to the device. The research archive is an ongoing source-driven project and should not be treated as a finished encyclopedic scholarly corpus.

The historical test-build channel is separate: [Islamic-Dilemma-Test-Builds](https://github.com/mcographics/Islamic-Dilemma-Test-Builds).