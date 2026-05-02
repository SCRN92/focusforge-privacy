---
title: Delete your NearbyOpen account
layout: default
---

# Delete your NearbyOpen account and data

You can delete your NearbyOpen account and all associated data at any time. This page explains how, what gets deleted, and what (if anything) is retained.

## How to delete in the app

1. Open **NearbyOpen** on your Android device.
2. Tap the **Settings** tab (gear icon, bottom right).
3. If you are signed in, scroll to **Delete account** and tap it.
4. Confirm in the dialog. Your account is deleted immediately.

If you are not signed in, there is no NearbyOpen account to delete — the app does not store personal data on Google's servers for signed-out users.

## What gets deleted

When you tap **Delete account**, the following are erased immediately:

- Your Firebase Authentication record (your sign-in identity).
- Your favorites list (synced to Firestore under your user ID).
- Your recently viewed places (synced to Firestore under your user ID).
- Your saved preferences (units, theme, etc.).

After a successful deletion you are signed out and the app returns to its anonymous state.

## What may be retained

- **Crash reports** sent to Firebase Crashlytics are anonymous (we do not attach your Firebase user ID to them) and are retained according to Firebase's default retention period (currently 90 days), then deleted automatically.
- **Aggregated analytics** counted via Firebase Analytics (e.g. "N users searched for places today") are anonymized and cannot be linked back to your account.
- **Advertising identifiers** used by AdMob are managed by Google and your device-level Ad-ID controls — see [Google Play services](https://support.google.com/googleplay/android-developer/answer/6048248) for details on resetting or removing them.

## Can't access the app?

If you've uninstalled NearbyOpen and cannot delete your account from inside the app, email **[arash.gholami.92@gmail.com](mailto:arash.gholami.92@gmail.com)** with the email address you used to sign in. We will delete your account and confirm by email within 30 days.

[Back to NearbyOpen home](./)
