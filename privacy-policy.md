# Privacy Policy

**Last Updated:** July 30, 2026

**App Name:** MinteCalc  
**Company:** 3MD FAMILY (PTY) LTD  
**Contact:** support@mintecalc.com  
**Website:** https://mintecalc.com

---

## Introduction

Welcome to MinteCalc! This Privacy Policy explains how 3MD FAMILY (PTY) LTD ("we," "us," or "our") collects, uses, discloses, and safeguards your information when you use our mobile application MinteCalc (the "App"). Please read this Privacy Policy carefully.

By downloading, accessing, or using the App, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree with the terms of this Privacy Policy, please do not access or use the App.

---

## Information We Collect

### 1. Information You Provide Directly

- **Google Sign-In (optional, for Backup & Restore):** MinteCalc does **not** create username/password accounts of its own. If you choose to use the optional Backup & Restore feature, you sign in with your Google account. Authentication is handled by Google — we never receive, store, or have access to your Google password. When you sign in, an authentication record is created for the App via **Firebase Authentication**, containing your **email address, display name, profile photo URL, and a unique user ID (UID)**. We use this record solely to keep you signed in across app launches and to associate you with your own backup; it is not used to build a profile of you. See "Account & Data Deletion" below for how to remove it.
- **User Content:** Any data, notes, calculations, or settings you create within the App are stored **locally on your device** (using platform-specific storage: SharedPreferences on Android, UserDefaults on iOS). If you enable backup, this data is stored in **your own Google Drive account** in a hidden application data folder (`appDataFolder`) — not on our servers.
- **Payment Information:** If you purchase a Pro Upgrade, payment is processed entirely through the Apple App Store or Google Play Store. We do not directly collect or store your payment card details. Purchase validation is handled by RevenueCat (see "Third-Party Services" below).
- **Feedback and Support Emails:** If you use the in-app "Send Feedback" or "Report a Bug" options, the App pre-fills an email that includes your app version, device model, and basic app-usage statistics to help us diagnose issues. You can see and edit this information in the email before choosing to send it.

### 2. Information Collected Automatically

When you use the App, we and our service providers may automatically collect certain information, including:

- **Device Information:** Device type, operating system version, unique device identifiers (including advertising identifiers, where permitted), and mobile network information.
- **Usage Data:** Information about how you interact with the App, including features used, session duration, and in-app actions.
- **Crash Reports and Diagnostics:** Technical information about crashes and performance issues. If you are signed in for backup, crash reports may include a pseudonymous user identifier (your Firebase UID) — never your email address — to help us investigate account-related issues such as backup failures.
- **Push Notification Tokens:** If you allow notifications, a push registration token is created by Firebase Cloud Messaging so the App can receive notifications (see "Notifications" below).

### 3. Information We Do NOT Collect

- **Calculation Data:** We do not collect, store, or transmit any of your calculations, notes, or results to our servers.
- **Currency Conversion History:** We do not track or store which currencies you convert or the amounts.
- **Note Calculator Data:** Your item names, prices, quantities, and calculations remain entirely on your device (or in your own Google Drive backup if enabled).
- **Precise Location:** The App does not request or collect precise (GPS) location data.

### 4. Information Collected by Third-Party Services

We use the following third-party services that may collect information:

#### Firebase Authentication (Google)
Used only if you sign in for Backup & Restore. Stores your email address, display name, profile photo URL, and a unique user ID so you stay signed in across app launches. For more information, see [Firebase Privacy and Security](https://firebase.google.com/support/privacy).

#### Google Analytics for Firebase
We use Google Analytics for Firebase to understand how users interact with our App. This service may collect:
- App usage patterns and user behavior (e.g., which features are used)
- Device and demographic information
- Session and engagement data

For more information, please review [Google's Privacy Policy](https://policies.google.com/privacy).

#### Firebase Crashlytics
We use Firebase Crashlytics to collect crash reports and diagnostic data to improve App stability. This service collects:
- Crash logs and stack traces
- Device state at the time of crash
- Device identifiers and, for signed-in users, a pseudonymous user ID

For more information, please review [Firebase Privacy and Security Documentation](https://firebase.google.com/support/privacy).

#### Firebase Cloud Messaging (Push Notifications)
If you grant notification permission, Firebase Cloud Messaging generates a push registration token for your device and the App may subscribe you to broad notification topics (such as "all users", "free users", or "pro users") so we can send service and feature announcements. Topics are based only on whether you have a Pro subscription — no other profiling is involved. You can withdraw notification permission at any time in your device settings.

#### Firebase Remote Config
We use Firebase Remote Config to deliver configuration settings to the App (for example, feature switches and notification schedules) without requiring an app update. This service uses Firebase installation identifiers and does not collect personal content.

#### Currency Exchange Rate Delivery (Firebase Hosting)
Currency exchange rates are delivered to the App as static files from our own Firebase Hosting endpoint. Fetching these files is a standard web request (your IP address is visible to the hosting provider, as with any web download) and requires no personal information.

#### ExchangeRate-API
The underlying currency exchange rates are sourced from ExchangeRate-API ([https://www.exchangerate-api.com](https://www.exchangerate-api.com)). Your device does not communicate with ExchangeRate-API directly, and we do not share any of your personal information with them. For more information, please review [ExchangeRate-API's Terms of Use](https://www.exchangerate-api.com/terms).

#### Google AdMob
We use Google AdMob to display advertisements in the App (for non-Pro users). AdMob may collect:
- Advertising identifiers
- Device information
- Coarse location data (if permitted)
- User interaction with advertisements

AdMob may use this information to serve personalized advertisements. For more information about how Google uses your data for advertising, please visit [Google's Advertising Privacy Policy](https://policies.google.com/technologies/ads).

**Rewarded Ads:** Some optional features can be temporarily unlocked by voluntarily choosing to watch a rewarded advertisement. These ads are only shown when you explicitly choose to watch them and are served through the same AdMob service described above.

**App Tracking Transparency (iOS):** On iOS, the App asks for your permission through Apple's App Tracking Transparency prompt before the advertising identifier is used for tracking. If you decline, you will still see ads, but they will not be personalized using your advertising identifier.

**Your Ad Choices:** You can opt out of personalized advertising by adjusting your device settings (Android: "Delete advertising ID" / iOS: App Tracking Transparency) or by visiting [Google's Ads Settings](https://adssettings.google.com/).

#### RevenueCat
We use RevenueCat to manage and validate in-app purchases and subscriptions. When you make (or restore) a purchase, RevenueCat receives your purchase receipt/token from the app store, a randomly generated app user identifier, and basic device information in order to confirm your entitlement to Pro features across sessions and devices. RevenueCat does **not** receive your name, email address, or payment card details from us. For more information, please review [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy).

---

## Google Drive Integration

### Backup and Restore

MinteCalc offers the ability to back up and restore your App data using your own Google Drive account. Please note:

- **User Control:** You have full control over your backups. Backup files are stored in your personal Google Drive account, not on our servers.
- **Limited Scope:** The App requests only the `drive.appdata` scope, which grants access to a hidden, app-specific data folder. We **cannot** see, read, or modify any other files in your Google Drive.
- **Data Access:** We only access this hidden folder to create, read, and delete the backup files you manage through the App.
- **Authentication:** Google Drive integration requires you to authenticate with your Google account. We do not store your Google account credentials.
- **Data Responsibility:** Since backups are stored in your personal Google Drive, you are responsible for managing and securing your Google account. We are not responsible for any data loss or unauthorized access to your Google Drive account.

### Google API Services — Limited Use Disclosure

MinteCalc's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the **Limited Use** requirements. Specifically: data obtained through Google Sign-In and the Google Drive API is used only to provide the user-facing Backup & Restore feature; it is never sold, never used for advertising, and never transferred to third parties except as necessary to provide that feature or as required by law.

For more information about Google Drive's privacy practices, please review [Google's Privacy Policy](https://policies.google.com/privacy).

---

## Notifications

The App can send two kinds of notifications, both optional:

- **Local (scheduled) notifications** — for example, backup reminders, feature tips, and milestone messages. These are scheduled on your device; the schedule is controlled by remote configuration.
- **Push notifications** — occasional service or feature announcements delivered via Firebase Cloud Messaging.

Notifications are only sent if you grant notification permission, and you can withdraw permission at any time in your device settings. Where available, individual notification categories can also be adjusted in the App's settings and (on Android) per-channel in system settings.

---

## How We Use Your Information

We use the information we collect for the following purposes:

- **To Provide and Maintain the App:** Ensuring the App functions correctly and providing core features, including keeping you signed in for Backup & Restore.
- **To Improve the App:** Analyzing usage patterns and crash data to enhance performance and user experience.
- **To Process Transactions:** Validating purchases and managing Pro entitlements (subscriptions and lifetime purchases).
- **To Display Advertisements:** Serving ads to non-Pro users through Google AdMob.
- **To Send Notifications:** Delivering optional reminders, tips, and announcements if you have granted permission.
- **To Communicate with You:** Responding to support inquiries and sending important updates about the App.
- **To Comply with Legal Obligations:** Fulfilling legal requirements and protecting our rights.

---

## Pro Upgrade (Subscriptions and Lifetime Purchases)

When you purchase a Pro Upgrade, your payment is processed through the respective app store (Apple App Store or Google Play Store). We do not directly collect or store your payment card details. Purchase validation and entitlement management are performed by RevenueCat as described above. Please review the privacy policies of [Apple](https://www.apple.com/legal/privacy/) and [Google](https://policies.google.com/privacy) for information about how they handle payment data.

Pro subscribers enjoy an ad-free experience, and data collection related to advertising (AdMob) does not apply while an active Pro entitlement is present.

---

## Data Sharing and Disclosure

We do not sell your personal information, and we do not share it with third parties for their own marketing purposes. We may share information in the following circumstances:

- **Service Providers (Processors):** Google/Firebase (authentication, analytics, crash reporting, notifications, remote configuration, hosting), Google AdMob (advertising), and RevenueCat (purchase validation) process data on our behalf as described in this policy.
- **Legal Requirements:** We may disclose information if required by law, regulation, legal process, or governmental request.
- **Protection of Rights:** We may disclose information to protect our rights, privacy, safety, or property, or that of our users or the public.
- **Business Transfers:** In the event of a merger, acquisition, or sale of assets, information may be transferred as part of that transaction.

---

## Data Security

We implement reasonable security measures to protect your information from unauthorized access, alteration, disclosure, or destruction. However, no method of transmission over the Internet or electronic storage is 100% secure. While we strive to protect your personal information, we cannot guarantee its absolute security.

---

## Data Retention

- **Local Data (on your device):** Stored until you clear the App's storage or uninstall the App.
- **Google Drive Backup (optional):** Stored in your personal Google Drive account until you delete it using the **"Delete Data & Sign Out"** option in the App (Settings → Backup & Restore), or remove the App's access at [https://myaccount.google.com/permissions](https://myaccount.google.com/permissions).
- **Firebase Authentication Record (email, name, photo URL, UID):** Retained while you remain signed in or until deletion. See our [Account & Data Deletion](account-deletion) page for how to have it deleted.
- **Analytics & Crash Data:** Retained by Firebase Analytics and Crashlytics according to their standard retention periods, after which it is deleted or aggregated.
- **Purchase Records:** Retained by the app stores and RevenueCat as needed to maintain your entitlement (e.g., to restore purchases on a new device) and to meet legal/accounting obligations.

---

## Children's Privacy

The App is not directed at children under the age of 13 (or the applicable age of digital consent in your jurisdiction), and we do not knowingly collect personal information from children. If we become aware that we have inadvertently collected personal information from a child, we will take steps to delete such information promptly.

---

## Your Rights and Choices

Depending on your jurisdiction (including under the GDPR, UK GDPR, CCPA/CPRA, and South Africa's POPIA), you may have rights regarding your personal information, including:

- **Access:** Request access to the personal information we hold about you.
- **Correction:** Request correction of inaccurate or incomplete information.
- **Deletion:** Request deletion of your personal information (see [Account & Data Deletion](account-deletion) for self-service options).
- **Portability:** Request a copy of information you provided in a portable format.
- **Objection / Restriction:** Object to or request restriction of certain processing.
- **Opt-Out:** Opt out of personalized advertising (see "Your Ad Choices" above). We do not sell or "share" personal information as defined by the CCPA/CPRA.

To exercise these rights, please contact us at **support@mintecalc.com**. We will respond within the timeframe required by applicable law. You will not be discriminated against for exercising any of these rights.

---

## International Data Transfers

Your information may be transferred to and processed in countries other than your country of residence (for example, on Google and RevenueCat infrastructure). These countries may have data protection laws that differ from your country. Where required, transfers rely on appropriate safeguards such as standard contractual clauses implemented by our service providers.

---

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of material changes by posting the new Privacy Policy at this address and updating the "Last Updated" date, and, where appropriate, through an in-app notice. Your continued use of the App after any changes constitutes your acceptance of the updated Privacy Policy.

---

## Contact Us

If you have any questions or concerns about this Privacy Policy or our data practices, please contact us at:

**3MD FAMILY (PTY) LTD**  
Email: support@mintecalc.com  
Website: https://mintecalc.com

---

## Disclaimer

THE APP IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED. TO THE FULLEST EXTENT PERMITTED BY APPLICABLE LAW, 3MD FAMILY (PTY) LTD DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT.

3MD FAMILY (PTY) LTD DOES NOT WARRANT THAT THE APP WILL BE UNINTERRUPTED, ERROR-FREE, OR SECURE, OR THAT ANY DEFECTS WILL BE CORRECTED. YOUR USE OF THE APP IS AT YOUR SOLE RISK.

IN NO EVENT SHALL 3MD FAMILY (PTY) LTD BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, OR PUNITIVE DAMAGES ARISING OUT OF OR RELATED TO YOUR USE OF OR INABILITY TO USE THE APP, EVEN IF WE HAVE BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

---

*This Privacy Policy is effective as of July 30, 2026.*
