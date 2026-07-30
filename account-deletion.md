# MinteCalc — Account and Data Deletion

**Last Updated:** July 30, 2026

**App Name:** MinteCalc  
**Company:** 3MD FAMILY (PTY) LTD  
**Contact:** support@mintecalc.com  
**Website:** https://mintecalc.com

---

This page explains how to delete your MinteCalc data, your optional sign-in record, and any associated access. It applies to the MinteCalc app on both Android (Google Play) and iOS (App Store).

## What Data Exists, and Where

MinteCalc does **not** create username/password accounts and has **no servers of its own** — we store nothing ourselves. Your calculations, notes, and settings never leave your control. If you use the optional Backup & Restore feature and sign in with Google, Google keeps a minimal sign-in reference on its own infrastructure (see Step 3).

| Data Type | Where It's Stored | Who Controls It |
|-----------|-------------------|------------------|
| Calculations, notes, settings | Your device (local storage) | You |
| Backup data (optional) | Your Google Drive (`appDataFolder`) | You |
| Sign-in reference (email, name, profile photo URL, user ID) | Google's Firebase Authentication — never on MinteCalc servers (we don't operate any) | You — removed in-app via "Delete Data & Sign Out" (see Step 3) |
| Google credentials (password) | Google's servers (OAuth) | Google |
| Payment info | Apple App Store / Google Play Store | Apple/Google |
| Purchase entitlement record (anonymous ID + receipt) | RevenueCat | Us via RevenueCat — deletable on request |

---

## Who Needs to Do What?

### Users Who Never Signed In with Google

If you have **never signed in with Google** for Backup & Restore, MinteCalc has **no cloud data and no sign-in record** associated with you. Your data exists only on your device.

**To delete your data:** Simply clear the app's storage or uninstall MinteCalc (see Step 2 below).

### Users Who Signed In with Google (Backup & Restore)

If you **have** signed in with Google, two things exist: your backup data (in your own Google Drive) and a sign-in record (in Firebase Authentication). Steps 1 and 3 below cover both.

---

## Step 1: Delete Your Google Drive Backup Data (In-App)

If you used the Backup & Restore feature, MinteCalc stores backup data in your Google Drive **application data folder** (`appDataFolder`). This folder is hidden and not visible in your regular Google Drive file list.

### How to Delete:

1. Open **MinteCalc**
2. Navigate to **Settings → Backup & Restore**
3. Tap **"Delete Data & Sign Out"** (at the bottom of the screen) and confirm

### What Happens:

✅ Your MinteCalc backup file(s) are **permanently deleted** from your Google Drive `appDataFolder`  
✅ Your **sign-in reference** (email, name, profile photo URL, user ID) is **permanently removed** from Google's Firebase Authentication (see Step 3)  
✅ You are **signed out** of Google within MinteCalc  
✅ Deletion is **immediate** — it happens instantly via Google's infrastructure  

> **Security note:** if your sign-in session is old, the app may briefly ask you to re-select your Google account to confirm your identity before the sign-in record is deleted.

> **Note:** After signing out, backup/restore features will be unavailable until you sign in again. An internet connection is required for this step.

---

## Step 2: Delete Local App Data (On Your Device)

The "Delete Data & Sign Out" button removes your **cloud backup** and signs you out, but it does **not** remove local app data stored on your device.

### To Completely Delete Local Data:

**Option A: Clear App Storage (keeps app installed)**

- **Android:** Go to **Settings → Apps → MinteCalc → Storage → "Clear Storage"** or **"Clear Data"**
- **iOS:** Go to **Settings → General → iPhone Storage → MinteCalc → "Delete App"** (note: "Offload App" keeps your data)

**Option B: Uninstall the App (complete removal)**
- Uninstall MinteCalc from your device
- This removes all local data including calculations, notes, and settings

> **Note:** Exact menu wording may vary by device manufacturer and OS version.

---

## Step 3: Delete Your Sign-In Reference (Google Firebase)

MinteCalc has **no servers of its own and stores nothing itself**. When you use "Sign in with Google," Google's Firebase Authentication service keeps a minimal sign-in reference — your email address, display name, profile photo URL, and a unique user ID — on **Google's infrastructure**, purely so you stay signed in between app launches. We never see your password, and this reference is never used for anything else.

This reference is removed **automatically** when you tap **"Delete Data & Sign Out"** (Step 1) — no further action is needed.

You can also request removal by email at any time, without needing the app installed:

- Email: **support@mintecalc.com**
- Subject: **MinteCalc account deletion request**
- Include: the Google account email you used to sign in

We will remove the sign-in reference — and the anonymous purchase-entitlement reference held by RevenueCat, if any — within **30 days**, and confirm by reply.

> Deleting the sign-in reference never affects your Pro purchase: entitlements are tied to your app-store account and can always be restored with **"Restore Purchases."**

---

## Step 4: Remove MinteCalc's Access to Your Google Account (Optional)

To additionally revoke MinteCalc's Google account access (the OAuth permission itself):

1. Visit: https://myaccount.google.com/permissions
2. Find **MinteCalc**
3. Select **Remove access**

> Revoking access also deletes the hidden `appDataFolder` contents on Google's side, per Google Drive's app-data policy.

---

## Request Help / Contact

If you cannot access the app and need assistance with any deletion step, contact us:

- Email: **support@mintecalc.com**
- Subject: **MinteCalc data deletion request**
- Include: the Google account email you used to sign in (if applicable)

We will respond within **30 days**.

---

## Summary: What Can Be Deleted, and How

| Data | How to Delete | Where |
|------|---------------|-------|
| Cloud backup (Google Drive) | **"Delete Data & Sign Out"** | In-app: Settings → Backup & Restore |
| Local app data | Clear app storage or uninstall | Your device settings |
| Sign-in reference (Google Firebase) | **"Delete Data & Sign Out"**, or email us — removed within 30 days | In-app, or support@mintecalc.com |
| Purchase entitlement record (RevenueCat, anonymous) | Included in the deletion request above | support@mintecalc.com |
| Google OAuth permission | [Google Account Permissions](https://myaccount.google.com/permissions) | Google |
| Payment/subscription records | Managed by the app stores | Apple App Store / Google Play |

### Data We Retain After Deletion

- **Analytics and crash data** already collected by Firebase Analytics/Crashlytics is retained per their standard retention periods and is not linked back to you after your sign-in record is deleted.
- **Purchase records at the app stores** are controlled by Apple/Google and their retention rules; we cannot delete these.
