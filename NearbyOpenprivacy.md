---
title: Privacy Policy
permalink: /privacy/
layout: default
---

# Privacy Policy for NearbyOpen

**Effective date:** 2 May 2026
**Last updated:** 2 May 2026

NearbyOpen is operated by **Arash** as a sole-developer publisher. This page explains what personal data the app collects, why, who we share it with, and how you can exercise your rights over it.

If you have any question, write to **[gh89412197@gmail.com](mailto:gh89412197@gmail.com)**.

---

## 1. Who is the data controller

Arash, contact email **gh89412197@gmail.com**. The app's package name on Google Play is `com.scorpion.nearbyopen`.

## 2. What we collect, why, and on what legal basis

| Data | What it is | Why we need it | Legal basis (GDPR) | Where it is stored |
|---|---|---|---|---|
| **Authentication identifiers** | Anonymous Firebase UID; or, if you sign in, your email address (email/password) and your Google account display name + email (Google sign-in). | Identify your favorites and Pro entitlement across sessions and devices. | Performance of contract (art. 6(1)(b)) | Google Firebase Authentication |
| **Approximate / precise location** | Latitude + longitude from the device's fused-location provider, only while the app is open. | Search for places open near you. | Consent (art. 6(1)(a)) — system permission prompt | Held only in app memory; sent to Google Places API to perform the search; **not stored against your account** |
| **Favorites** | The IDs, names, and addresses of places you tap "favorite" on. | Sync favorites across your devices. | Performance of contract | Google Firestore (region: nam5), keyed by your Firebase UID |
| **Recently viewed places** | Last 30 days of places you opened in detail. | Show a "Recently viewed" shortcut on your device. | Legitimate interest (art. 6(1)(f)) — local UX | Local Room database on your device only — never uploaded |
| **Loyalty (Open Points)** | Streak day count, points balance, last-open date. | Power the in-app loyalty programme. | Legitimate interest | Local DataStore preferences on your device only — never uploaded |
| **In-app purchase receipt** | Google Play purchase token + product ID after you buy Pro. | Unlock Pro entitlement and acknowledge the purchase to Google. | Performance of contract | Google Play Billing; copy stored in your Firestore document |
| **Crash diagnostics** | Stack traces, device model, OS version, app version, anonymous install ID. May include your Firebase UID if you are signed in. | Diagnose and fix crashes. | Legitimate interest | Firebase Crashlytics |
| **Usage analytics** | App-open, screen-view, and feature events. Aggregated, no place-level personal content. | Understand which features are used so we can improve them. | Consent (off by default in Settings → Privacy → "Crash + usage analytics") | Firebase Analytics |
| **Advertising data** (free users only) | Google Advertising ID, IP, coarse location, device info — handled by AdMob, **not** read by us directly. | Serve ads in the free tier. Pro users see no ads. | Legitimate interest, with opt-out via Settings → Privacy → "Personalised ads" | Google AdMob |

We do **not** collect: contacts, photos, microphone, SMS, call logs, biometrics, files outside the app's sandbox, or any health/financial data beyond the Google Play purchase receipt.

## 3. Who we share data with (third parties)

The app uses the following processors. Each has its own privacy policy, which we link to:

- **Google Firebase** (Authentication, Firestore, Crashlytics, Analytics) — [policies.google.com/privacy](https://policies.google.com/privacy)
- **Google Maps Platform** (Maps SDK, Places API) — [policies.google.com/privacy](https://policies.google.com/privacy)
- **Google Play Services & Google Play Billing** — [policies.google.com/privacy](https://policies.google.com/privacy)
- **Google AdMob** (free tier only) — [support.google.com/admob/answer/6128543](https://support.google.com/admob/answer/6128543)

We do **not** sell your personal data, and we do not share it with any third party other than the processors listed above.

## 4. Where your data is processed

All data above is processed on Google infrastructure, which means it may be stored or processed in any country where Google operates data centres (including the United States and the European Union). Google provides Standard Contractual Clauses for international transfers under GDPR.

## 5. How long we keep it

- **Authentication, favorites, purchase receipt:** as long as your account exists. Email us to request deletion.
- **Crash diagnostics:** retained by Firebase Crashlytics for 90 days by default.
- **Usage analytics:** retained by Firebase Analytics for 14 months, then aggregated.
- **Local data on your device** (recently viewed, loyalty points): cleared when you uninstall the app or clear app storage.

## 6. Your rights

Depending on where you live, you have some or all of the following rights:

- **Access** — request a copy of the personal data we hold about you.
- **Rectification** — ask us to correct inaccurate data.
- **Erasure ("right to be forgotten")** — ask us to delete your account and associated Firestore records. Email us; we'll process within 30 days.
- **Restriction / objection** — ask us to stop processing for a specific purpose (e.g. analytics).
- **Data portability** — receive your data in a machine-readable format.
- **Withdraw consent** — turn off "Crash + usage analytics" or "Personalised ads" any time in Settings → Privacy. Revoke location permission via Android system Settings.
- **Lodge a complaint** with your local data-protection authority.

To exercise any right, email **gh89412197@gmail.com** from the address associated with your account. We may ask for confirmation to verify identity.

### California residents (CCPA)

We do not sell or share your personal information for cross-context behavioural advertising, and we do not collect sensitive personal information beyond what is listed above.

### Children

NearbyOpen is **not directed at children under 13**, and we do not knowingly collect personal data from anyone under 13. If you believe a child has provided data, email us and we will delete it.

## 7. Security

Network traffic between the app and our processors uses HTTPS / TLS 1.2+. Firestore reads and writes are gated by Firebase Security Rules so that one user's data cannot be read by another. Authentication tokens are managed by the Firebase Android SDK and stored in private app storage.

## 8. Permissions the app requests

| Permission | When | Why |
|---|---|---|
| `ACCESS_COARSE_LOCATION` / `ACCESS_FINE_LOCATION` | At runtime, only when you tap "Allow location" on the home screen. | Centre the map on you and search nearby. |
| `INTERNET`, `ACCESS_NETWORK_STATE` | Always. | Talk to Google APIs. |
| `com.android.vending.BILLING` | Always. | Power the Pro purchase flow via Google Play Billing. |

## 9. Changes to this policy

We will update this page when material changes happen. The "Last updated" date at the top will reflect the most recent revision. Significant changes (e.g. a new processor, a new category of data) will be announced in-app via a one-time dialog.

## 10. Contact

Arash
**[gh89412197.com](mailto:gh89412197@gmail.com)**
