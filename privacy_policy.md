# My Cow Farm – Privacy Policy

**Effective Date:** April 2026  
**Developer:** Rajesh Raju  
**Contact:** mycowfarm.app@gmail.com  

---

## 1. Introduction

My Cow Farm ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, store, and protect your information when you use the My Cow Farm mobile application ("App").

By using the App, you agree to the practices described in this policy.

---

## 2. Information We Collect

### a) Farm & Livestock Data

You enter and manage the following data within the App:

- Cow records (name, tag number, breed, date of birth, weight, status)
- Calf and breeding records
- Daily milk production entries (quantity, session, price per litre)
- Milk sales and buyer information
- Health records, vaccinations, and deworming logs
- Feed inventory and daily feed entries
- Farm expenses, income, loans, and insurance records
- Staff, shed, maintenance, and equipment records
- Reminders and notes

This data is stored locally on your device and, if you choose, synced to your Firebase cloud backup.

### b) Google Account Information (Optional)

If you sign in with Google, we receive:

- Your display name
- Your email address
- Your profile photo URL

This information is used solely to identify your personal cloud backup space in Firebase Firestore. We do not share this with any third parties.

### c) Device & Usage Data

We do **not** collect analytics, crash reports, advertising identifiers, or usage statistics.

---

## 3. How We Use Your Information

We use your information to:

- Display and manage your farm records within the App
- Calculate milk production, income, expenses, and profit/loss reports
- Provide optional cloud backup and multi-device sync via Firebase Firestore
- Identify your personal cloud storage using your Google UID

We do **NOT**:

- Sell your data to any third party
- Use your data for advertising
- Access your data without your action

---

## 4. Data Storage

### Local Storage

All farm data is stored in a local SQLite database on your device. It is accessible only by this App and is protected by your device's operating system security.

### Cloud Storage (Optional)

If you sign in with Google and enable sync, your data is stored in Firebase Firestore under a path unique to your Google User ID (`users/{uid}/...`). Firebase Security Rules ensure that only you — the authenticated user — can read or write your data. No other user or administrator can access it through the App.

---

## 5. Third-Party Services

This App uses the following Google/Firebase services:

| Service | Purpose |
|---|---|
| Firebase Authentication | Google Sign-In |
| Firebase Firestore | Optional cloud backup & sync |

These services are subject to Google's Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)

We do **not** use advertising SDKs, analytics platforms, or any other third-party data processors.

---

## 6. Data Security

- Local data is protected by your device's OS-level security
- Cloud data is protected by Firebase Security Rules (only your UID can access your data)
- All connections to Firebase are encrypted using TLS

No method of transmission over the internet is 100% secure. We encourage you to keep your device and Google account secure.

---

## 7. Data Retention & Deletion

Your data is retained until you choose to delete it or uninstall the App.

- **Local data:** Uninstalling the App removes all local data from your device.
- **Cloud data:** Use **"Delete All Data"** in the Backup & Sync screen to permanently delete all your data from Firebase Firestore.

We do not retain your data after deletion.

---

## 8. Your Rights

| Right | How to exercise it |
|---|---|
| Access | All data is visible directly in the App |
| Correction | Edit any record at any time within the App |
| Deletion | "Delete All" in Backup & Sync (cloud); uninstall App (local) |
| Portability | Data export feature planned in a future update |

For any concerns, contact us at **mycowfarm.app@gmail.com**.

---

## 9. Children's Privacy

This App is not directed at children under the age of 13. We do not knowingly collect personal information from children. If you believe a child has provided personal information, please contact us so we can delete it.

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Effective Date" above. Continued use of the App after changes constitutes your acceptance of the revised policy.

---

## 11. Contact Us

If you have any questions or concerns about this Privacy Policy:

**Developer:** Rajesh Raju  
**Email:** mycowfarm.app@gmail.com  

---

*This privacy policy applies to the My Cow Farm Android application published on the Google Play Store.*
