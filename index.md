
---
# Privacy Policy for FlexGrabber Pro

**Last Updated:** November 1, 2026

FlexGrabber Pro ("we," "our," or "us") respects your privacy. This Privacy Policy explains how our application handles your data.

---

## 1. AccessibilityService API Disclosure
FlexGrabber Pro uses Android's **AccessibilityService API** to provide its core functionality.

* **Purpose:** The API is used strictly to perform automated on-screen taps and gestures based on your configured filters, helping reduce physical hand strain and repetitive motion fatigue.
* **No Data Collection:** The AccessibilityService API does **NOT** collect, read, store, or transmit any personal data, passwords, sensitive screen content, messages, or keylog inputs.
* **Local Processing:** All actions performed by the service take place locally on your device in real time.

---

## 2. Information Collection and Account Authentication
FlexGrabber Pro is designed to collect only the minimal data necessary to provide user accounts, manage trials, and enable referral rewards:

* **Google Sign-In & Authentication:** When you authenticate using Google Sign-In, we process your Google User ID (UID), email address, and basic profile identifier via Firebase Authentication to create and secure your account.
* **Account & Referral Data:** We store your user identifier, referral code, referral statistics, and reward credit expiry timestamps in Google Cloud Firestore to maintain your account state and reward allocations across sessions.
* **Local Settings & Filters:** Your personal configuration preferences (such as station filters, time windows, and pay thresholds) remain stored exclusively on your device and are never transmitted to external servers.

---

## 3. Third-Party Services
We do not sell, rent, monetize, or share your personal data with third-party advertisers or data brokers. The application relies on trusted Google infrastructure strictly to deliver app functionality:

* **Google Play Services & Billing:** To handle subscription verification, in-app purchases, and licensing.
* **Google Firebase (Authentication & Cloud Firestore):** To manage secure user sign-in and sync referral rewards and trial states.

---

## 4. Device Identifiers and Anti-Fraud Verification
To provide and enforce our free trial access, prevent unauthorized multi-account trial abuse, and maintain subscription integrity, FlexGrabber Pro processes a cryptographic hash of your Android device identifier (`Settings.Secure.ANDROID_ID`).

* **Purpose:** Fraud prevention, trial access management, and subscription state verification.
* **Storage:** We do not store raw hardware serial numbers or your plain Android ID. The value is irreversibly hashed (SHA-256) on your device before transmission and securely stored in Google Cloud Firestore.
* **Retention:** This record is retained solely to track legitimate trial eligibility and prevent repeated trial resets on the same physical hardware.
* **Third Parties:** We never sell, share, or use this identifier for advertising, commercial profiling, or third-party tracking.

---

## 5. Permission Control and Data Deletion
* **Managing Permissions:** You can enable or disable the Accessibility Service at any time via your device settings (**Settings > Accessibility > Installed Apps > FlexGrabber Pro**).
* **Local Preferences Deletion:** Clearing app storage in your device settings or uninstalling the app permanently removes all locally saved filter settings.
* **Account and Data Deletion Requests:** You have the right to request deletion of your account and associated Firebase data. To request the removal of your user record and stored identifiers, contact us at the email below. We process verified deletion requests promptly within 30 days.

---

## 6. Contact Us
If you have any questions regarding this Privacy Policy or your data, please contact us at:

* **Email:** FlexGrabberPro@gmail.com
