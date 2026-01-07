# MinteCalc — Account and Data Deletion

**Last Updated:** January 7, 2026

**App Name:** MinteCalc  
**Company:** 3MD FAMILY (PTY) LTD  
**Contact:** support@mintecalc.com  
**Website:** https://mintecalc.com

---

This page explains how to delete your MinteCalc data and revoke any associated access.

## Important: MinteCalc Does Not Create Accounts

MinteCalc does **not** create or maintain user accounts on our servers. We do **not** store your calculations, notes, settings, or any personal content on MinteCalc servers.

| Data Type | Where It's Stored | Who Controls It |
|-----------|-------------------|------------------|
| Calculations, notes, settings | Your device (local storage) | You |
| Backup data (Pro, optional) | Your Google Drive (`appDataFolder`) | You |
| Google credentials | Google's servers (OAuth) | Google |
| Payment info | Apple/Google Play Store | Apple/Google |

---

## Who Needs to Do What?

### Free Users (Never Signed In with Google)

If you have **never upgraded to Pro** and have **never signed in with Google**, MinteCalc has **no cloud data** associated with you. Your data exists only on your device.

**To delete your data:** Simply clear the app's storage or uninstall MinteCalc (see instructions below).

### Pro Users (Signed In with Google for Backup)

If you **have** signed in with Google to use the Backup & Restore feature, your backup data is stored in your own Google Drive's hidden app folder. You can delete this data and sign out using the steps below.

---

## Step 1: Delete Your Google Drive Backup Data (Pro Users)

If you used the Backup & Restore feature, MinteCalc stores backup data in your Google Drive **application data folder** (`appDataFolder`). This folder is hidden and not visible in your regular Google Drive file list.

### How to Delete:

1. Open **MinteCalc**
2. Navigate to **Settings → Backup & Restore**
3. Tap **"Reset Data & Sign Out"** (button at the bottom of the screen)

### What Happens:

✅ Your MinteCalc backup file(s) are **permanently deleted** from your Google Drive `appDataFolder`  
✅ You are **signed out** of Google within MinteCalc  
✅ This action is **immediate**—deletion happens instantly via Google's infrastructure  

> **Note:** After signing out, backup/restore features will be unavailable until you sign in again.

---

## Step 2: Delete Local App Data (On Your Device)

The "Reset Data & Sign Out" button removes your **cloud backup** and signs you out, but it does **not** remove local app data stored on your device.

### To Completely Delete Local Data:

**Option A: Clear App Storage (keeps app installed)**

- **Android:** Go to **Settings → Apps → MinteCalc → Storage → "Clear Storage"** or **"Clear Data"**
- **iOS:** Go to **Settings → General → iPhone Storage → MinteCalc → "Offload App"** or **"Delete App"**

**Option B: Uninstall the App (complete removal)**
- Uninstall MinteCalc from your device
- This removes all local data including calculations, notes, and settings

> **Note:** Exact menu wording may vary by device manufacturer and OS version.

---

## Remove MinteCalc’s access to your Google Account (optional)

If you want to additionally remove MinteCalc’s Google account access (OAuth permission):

1. Visit: https://myaccount.google.com/permissions
2. Find **MinteCalc**
3. Select **Remove access**

---

## Request help/contact

If you cannot access the app and need assistance understanding the deletion steps, contact us:

- Email: **support@mintecalc.com**
- Subject: **MinteCalc data deletion request**
- Include: the Google account email you used to sign in (Pro backup), and the approximate date you enabled backup.

We will respond within **30 days**.

---

## Summary: What MinteCalc Can and Cannot Delete

| Data | Can MinteCalc Delete It? | How to Delete |
|------|--------------------------|---------------|
| Cloud backup (Google Drive) | ✅ Yes, via "Reset Data & Sign Out" | Settings → Backup & Restore → Reset Data & Sign Out |
| Local app data | ❌ No (stored on your device) | Clear app storage or uninstall |
| Google OAuth permission | ❌ No (managed by Google) | [Google Account Permissions](https://myaccount.google.com/permissions) |
| Payment/subscription | ❌ No (managed by app stores) | Apple App Store or Google Play Store |

### Why We Can't Delete Some Data

MinteCalc does **not** operate its own user account system or servers that store your content. Your data is stored either:
- **Locally** on your device (you control it)
- **In your Google Drive** (you control it, we just provide the backup feature)
- **With Google/Apple** (authentication and payments)
