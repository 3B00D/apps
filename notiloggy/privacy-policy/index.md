---
layout: default
title: NotiLoggy Privacy Policy
permalink: /notiloggy/privacy-policy/
---

# NotiLoggy Android App Privacy Policy

**Last updated:** 13-02-2026  
**Effective date:** 13-02-2026

NotiLoggy ("we," "our," or "the app") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and safeguard information when you use the NotiLoggy Android application.

---

## 1. Overview

NotiLoggy is a notification history app that captures and stores notifications on your device for your own reference. We prioritize your privacy: **notification content is stored only on your device and is never transmitted to our servers or third parties** for purposes other than advertising (see Section 4).

---

## 2. Data Stored on Your Device

### 2.1 Notification Data
When you grant Notification Access, the app captures and stores:
- Notification title, body, and subtext
- App package name
- Timestamp

For notifications received while the app is running, we may also keep **in memory** (not persisted to the database) the intent or link that the original app associated with the notification. This allows you to tap a notification in NotiLoggy to open the source app, an external URL, or another app—depending on what the original notification was designed to do. **Tapping a notification may launch other apps or open links.** This behavior is handled entirely on your device; we do not transmit intent or link data to our servers or any external service.

**Storage:** All notification data is stored **locally on your device** in an **encrypted database** (SQLCipher). We do not upload, transmit, or share this data with our servers or any external service.

**Retention:** You control how long notifications are kept (1 day, 1 week, or 1 month). Older notifications are automatically deleted. You can also clear all notifications at any time in Settings → Data.

### 2.2 App Preferences
The app stores the following preferences locally, in encrypted storage where possible:
- Theme (light/dark/system)
- Language
- Notification retention period
- Excluded apps (apps whose notifications you choose not to store)
- App lock pattern (if enabled)
- Premium/trial status and purchase information (for Remove Ads)

**Storage:** Preferences are stored on your device using Android's EncryptedSharedPreferences or equivalent secure storage.

---

## 3. Permissions We Use

| Permission | Purpose |
|------------|---------|
| **Notification Access** | To capture and display notification history. Required for core functionality. |
| **Foreground Service** | To keep the app running in the background so it can receive notifications when the app is closed. |
| **Biometric** | Optional; used only if you enable app lock with fingerprint/face unlock. |
| **Post Notifications** | To show the persistent "notification capture active" indicator (Android 13+). |

We request permissions only when needed and explain why each is required.

---

## 4. Third-Party Services

### 4.1 Google AdMob (Advertising)
The app displays banner advertisements provided by Google AdMob via Firebase. When ads are shown:
- **AdMob** may collect device identifiers, IP address, app interactions, and usage data to deliver and measure ads.
- **Consent:** In regions that require it (e.g., EEA, UK), we use Google's User Messaging Platform (UMP) to obtain your consent before showing personalized ads. You can choose to limit or refuse personalized advertising.
- **Privacy:** AdMob's data practices are governed by [Google's Privacy Policy](https://policies.google.com/privacy) and [Google Ads Privacy](https://policies.google.com/technologies/ads).

**Note:** Notification content is **never** shared with AdMob or any ad network.

### 4.2 Google Play Billing
If you purchase "Remove Ads" (premium), the transaction is processed by Google Play. Google collects payment and purchase information according to [Google Play's terms and privacy policy](https://policies.google.com/privacy). We receive only confirmation that your purchase is valid; we do not receive your payment details.

### 4.3 Firebase
The app uses Firebase to support AdMob advertising. Firebase may collect analytics and crash data. See [Firebase Privacy](https://firebase.google.com/support/privacy).

---

## 5. Data We Do NOT Collect

- We do **not** transmit notification content to our servers or any third party.
- We do **not** sell your personal data.
- We do **not** use notification content for advertising targeting.

---

## 6. Your Rights and Choices

### 6.1 Access and Deletion
- **Clear notifications:** Settings → Data → Clear all notifications
- **Excluded apps:** Choose which apps' notifications to exclude in Settings
- **Retention:** Set how long notifications are kept (1 day, 1 week, 1 month)

**Note:** Some apps (such as banking and finance apps) may use system-level restrictions that prevent their notifications from being captured by notification listener apps. These notifications will not appear in NotiLoggy regardless of your settings.

### 6.2 Advertising
- **Limit Ad Tracking:** Use your device's "Limit ad tracking" or "Opt out of Ads Personalization" setting. The app and AdMob will respect this.
- **Remove Ads:** Purchase the premium "Remove Ads" option to stop seeing ads entirely.

### 6.3 GDPR (EEA/UK)
If you are in the European Economic Area or UK:
- We process data based on your consent (e.g., ad consent) or to perform our contract with you (provide the app).
- You have the right to access, rectify, erase, restrict processing, and data portability where applicable.
- You may withdraw consent at any time (e.g., for personalized ads).
- You may lodge a complaint with your supervisory authority.

### 6.4 CCPA (California)
If you are a California resident:
- We do not sell your personal information.
- You have the right to know, delete, and opt out of the sale of personal information (we do not sell).

---

## 7. Data Security

- Notification data is stored in an **encrypted database** (SQLCipher).
- Sensitive preferences use **EncryptedSharedPreferences** (Android Keystore).
- We follow Android security best practices and do not hardcode secrets.

---

## 8. Children's Privacy

NotiLoggy is not directed at children under 13. We do not knowingly collect personal information from children. If you believe a child has provided us with data, please contact us and we will delete it.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of material changes by updating the "Last updated" date and, where appropriate, through an in-app notice or app store listing. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 10. Contact Us

If you have questions about this Privacy Policy or your data, please contact us at:

**Email:** usefullabsapps@gmail.com

---

*This privacy policy applies to the NotiLoggy Android application.*
