# Privacy Policy / Datenschutzerklärung

**Meetup App**
Last updated: February 2025

---

## 1. Data Controller (Verantwortlicher)

Within the meaning of the EU General Data Protection Regulation (GDPR / DSGVO):

**Lukas Klingebiel**
Gundolfstr. 11
69120, Heidelberg, Germany
lukas.klingebiel+Meco@gmail.com

---

## 2. Overview

Meetup is a social coordination app that helps friends plan and navigate to shared meeting points. This privacy policy explains what personal data is collected, how it is used, and your rights under the EU General Data Protection Regulation (DSGVO) and applicable German law (BDSG, TDDDG, DDG).

This privacy policy applies specifically to the Meetup iOS application. It is available in the Apple App Store listing and within the app itself.

### Our Commitment to Your Privacy

**We have no intention of selling, monetizing, or analyzing your personal data for any purpose beyond operating the app and fixing bugs.** Your data exists solely to make meetup coordination work — showing your friends where you are and when you'll arrive. That is the only reason we collect it.

Specifically:
- Your data is **never sold** to any party, under any circumstances
- Your data is **never used for advertising**, profiling, or marketing
- Your data is **never analyzed** for behavioral insights, market research, or statistical purposes
- The only "analysis" we perform is reading **anonymous crash reports** (via Apple MetricKit) to identify and fix bugs that affect app stability
- We do **not** build user profiles, segment audiences, or derive insights from your usage patterns
- We operate **no servers of our own** — we have no means to access, aggregate, or mine your data at scale. All data resides in your personal iCloud account under Apple's infrastructure

---

## 3. Data We Collect

### 3.1 Profile Data

| Data | Required | Purpose | Legal Basis |
|---|---|---|---|
| Display name | Yes | Identify you to other participants | Art. 6(1)(b) DSGVO — contract performance |
| Phone number | No | Allow friends to reach you | Art. 6(1)(a) DSGVO — consent |
| iCloud Record Name | Automatic | Uniquely identify your iCloud account within the app | Art. 6(1)(b) DSGVO — contract performance |

Your iCloud Record Name is a pseudonymous identifier assigned by Apple. It is not your Apple ID, email address, or real name.

### 3.2 Location Data

| Data | When Collected | Precision | Legal Basis |
|---|---|---|---|
| Precise GPS coordinates (latitude/longitude) | Only during active live tracking | Adaptive (see below) | Art. 6(1)(a) DSGVO — consent |
| Estimated time of arrival (ETA) | During live tracking | Calculated from your position | Art. 6(1)(a) DSGVO — consent |

**Location collection is strictly opt-in.** The app requests your permission before accessing location data, and you can revoke this permission at any time in your device settings.

**Adaptive tracking frequency:**
- When you are close to the meetup (< 10 min ETA): updates approximately every 30 seconds at best accuracy
- When moderately far (10–30 min ETA): updates approximately every 2 minutes at reduced accuracy (~100 m)
- When far away (> 30 min ETA): updates only on significant location changes

**Background location:** When you start live tracking, the app requests "Always" location permission to continue updating your ETA while the app is in the background (e.g., while you are navigating with another app). A blue location indicator is displayed in your status bar whenever background tracking is active. You can stop tracking at any time from within the app or the Live Activity on your lock screen.

**Location data is not stored historically.** Only your most recent location is kept. Each update overwrites the previous one.

### 3.3 Meetup Data

When you create or participate in a meetup, the following data is processed:

- Meetup title, date/time, and status
- Place suggestions (name, address, coordinates) and votes
- Participant list with names and attendance status
- Chat messages and emoji reactions
- ETA feedback ("5 min early" / "5 min late")

### 3.4 Diagnostics

| Data | Purpose | Legal Basis |
|---|---|---|
| Crash reports (call stacks, app version) | Diagnose and fix app crashes | Art. 6(1)(f) DSGVO — legitimate interest |
| Performance metrics (hang durations, disk exceptions) | Improve app stability | Art. 6(1)(f) DSGVO — legitimate interest |

Diagnostics are collected via Apple MetricKit. They contain no personal data, user content, or location information — only technical stack traces and performance counters.

### 3.5 Data We Do NOT Collect

- We do **not** use advertising identifiers (IDFA)
- We do **not** track you across other apps or websites
- We do **not** use analytics SDKs (no Firebase, Google Analytics, Amplitude, etc.)
- We do **not** access your photos, camera, or microphone
- We do **not** collect health, fitness, or financial data
- We do **not** perform device fingerprinting
- We do **not** use cookies or comparable tracking technologies

---

## 4. How Your Data Is Shared

### 4.1 With Other Meetup Participants

When you join a meetup, the following data becomes visible to all other participants in that meetup:

- Your display name
- Your attendance status (e.g., "accepted", "on the way", "arrived")
- Your current location and ETA (only while live tracking is active)
- Chat messages you send
- Place suggestions you make and your votes
- ETA feedback you submit

**Meetups are shared via Apple CloudKit Sharing (CKShare).** When the meetup creator shares a meetup link, anyone who accepts the link gains read/write access to the meetup and all associated data (participants, chat, places, ETA feedback).

### 4.2 With Apple

Your data is stored in Apple's iCloud infrastructure (CloudKit). Apple acts as a data processor on our behalf. Apple's handling of iCloud data is governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

The following Apple services process data in connection with this app:

| Service | Data Processed | Purpose |
|---|---|---|
| **CloudKit (iCloud)** | All app data (profiles, meetups, chat, locations) | Persistent storage and cross-device sync |
| **MapKit** | Source and destination coordinates | ETA calculation |
| **Apple Push Notification Service (APNs)** | Device token, subscription metadata | Real-time update notifications |
| **MetricKit** | Crash diagnostics, performance data | App stability monitoring |
| **ActivityKit** | Meetup title, destination, participant ETAs | Live Activity on lock screen and Dynamic Island |

### 4.3 With Third Parties

**We do not share, sell, rent, trade, or transfer your personal data to any third parties — and we never will.** There are no third-party SDKs, analytics providers, advertising networks, or external services integrated in this app. All data processing uses exclusively Apple's first-party frameworks.

We do not engage in data brokerage, behavioral advertising, or any form of data monetization. Your personal data has no commercial value to us beyond enabling the app to function as intended.

---

## 5. International Data Transfers

Apple Inc. is headquartered in the United States. Your data stored in iCloud (CloudKit) may be transferred to and processed on servers located in the United States or other countries outside the European Economic Area (EEA).

These transfers are safeguarded by:
- **Standard Contractual Clauses (SCCs)** approved by the European Commission (Art. 46(2)(c) DSGVO)
- Apple's technical and organizational security measures, including encryption in transit and at rest

For details, see [Apple's Data Transfer Agreements](https://www.apple.com/legal/enterprise/data-transfer-agreements/datatransfer-eu-en.pdf).

---

## 6. Data Retention

| Data Category | Retention Period |
|---|---|
| User profile | Retained until you delete it or request deletion |
| Meetup data (title, date, status) | Retained until the meetup creator deletes the meetup |
| Chat messages and reactions | Retained until the meetup is deleted |
| Place suggestions and votes | Retained until the meetup is deleted |
| Participant records | Retained until removed by the meetup creator or meetup deletion |
| Location coordinates | Overwritten with each update; not retained after tracking stops |
| ETA feedback | Automatically expires and is deleted after 2 hours |
| Crash diagnostics | Processed by Apple MetricKit; not stored by us beyond processing |

All data is stored in your iCloud account. When a meetup is deleted, all associated child records (participants, messages, places, feedback) are deleted along with it.

**Account deletion:** When you delete your account through the app, the entire private CloudKit data zone containing all your records is permanently destroyed in a single operation. This includes your profile, every meetup you created, all associated messages, place suggestions, participant data, and ETA feedback. No data remains in the CloudKit private database after account deletion. Additionally, any data you contributed to other users' shared meetups (your messages, votes, and participant records) is removed on a best-effort basis.

---

## 7. Your Rights Under GDPR / DSGVO

You have the following rights regarding your personal data:

| Right | Description | How to Exercise |
|---|---|---|
| **Right of access** (Art. 15) | Request a copy of all personal data we hold about you | Contact us via email |
| **Right to rectification** (Art. 16) | Correct inaccurate data | Edit your profile within the app, or contact us |
| **Right to erasure** (Art. 17) | Request deletion of your personal data | Delete your meetups in the app, or contact us for full account erasure |
| **Right to restriction** (Art. 18) | Request that processing of your data be restricted | Contact us via email |
| **Right to data portability** (Art. 20) | Receive your data in a machine-readable format | Contact us via email |
| **Right to object** (Art. 21) | Object to processing based on legitimate interest | Contact us via email |
| **Right to withdraw consent** (Art. 7(3)) | Withdraw consent at any time (e.g., location, phone number) | Revoke location in device settings; remove phone number in app; or contact us |

We will respond to your request within **one month**. In complex cases, this period may be extended by two additional months, and we will inform you accordingly.

**Right to lodge a complaint:** You have the right to lodge a complaint with your local data protection supervisory authority. In Germany, this is the data protection authority (Landesdatenschutzbehörde) of your federal state. A list of all German supervisory authorities is available at [www.bfdi.bund.de](https://www.bfdi.bund.de).

---

## 8. Data Security

We implement the following technical and organizational measures to protect your data:

- **Encryption in transit:** All data is transmitted via Apple's encrypted iCloud/CloudKit infrastructure (TLS)
- **Encryption at rest:** iCloud data is encrypted on Apple's servers
- **No custom servers:** We do not operate any servers. All backend infrastructure is provided by Apple
- **Minimal data collection:** We collect only the data necessary for the app's core meetup coordination function (data minimization per Art. 5(1)(c) DSGVO)
- **No local sensitive storage:** The app does not store passwords, tokens, or sensitive data on your device outside of iCloud
- **Background location indicator:** iOS displays a visible indicator whenever the app accesses your location in the background

---

## 9. Contacts Permission

The app may request access to your device's contacts to help you invite friends to meetups. This permission is optional. Contact data is used solely to display names for invitation purposes and is **not** uploaded, stored, or transmitted to any server.

---

## 10. Push Notifications

The app uses Apple Push Notification Service (APNs) to deliver real-time updates about meetup changes, participant arrivals, and chat messages. Push notification content may include:

- Participant display names
- Chat message previews (first 50 characters)
- Meetup titles
- ETA update summaries

This content is visible on your lock screen. You can disable notifications at any time in your device's notification settings.

---

## 11. Live Activity and Dynamic Island

When you start live tracking, a Live Activity is displayed on your lock screen and (on supported devices) in the Dynamic Island. This shows:

- Meetup title and destination
- Your estimated time of arrival
- Up to 4 other participants' names, ETAs, and arrival status
- Interactive ETA feedback buttons

This information is visible to anyone with physical access to your device. The Live Activity ends when you stop tracking, arrive at the destination, or the meetup is completed.

---

## 12. In-App Purchases

The app may offer optional premium features via Apple's in-app purchase system (StoreKit). Purchases are processed entirely by Apple. We do not receive or store any payment information (credit card numbers, billing addresses, etc.). Apple's purchase terms apply: [Apple Media Services Terms](https://www.apple.com/legal/internet-services/itunes/).

---

## 13. Children's Privacy

This app is not directed at children under the age of 16 (the age of digital consent in Germany under § 8 BDSG in conjunction with Art. 8 DSGVO). We do not knowingly collect personal data from children under 16. If you believe a child under 16 has provided us with personal data, please contact us so we can delete it.

---

## 14. Changes to This Privacy Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last updated" date above. We encourage you to review this policy periodically. Material changes will be communicated through the app or the App Store listing.

---

## 15. Contact

For all privacy-related inquiries, requests, or complaints:

**Lukas Klingebiel**
Gundolfstr. 11
69120, Heidelberg, Germany
lukas.klingebiel+Meco@gmail.com

---

## 16. Supervisory Authority

If you believe your data protection rights have been violated, you have the right to lodge a complaint with:

**Der Bundesbeauftragte für den Datenschutz und die Informationsfreiheit (BfDI)**
Graurheindorfer Str. 153
53117 Bonn, Germany
Website: [www.bfdi.bund.de](https://www.bfdi.bund.de)

Or with the data protection authority (Landesbeauftragte/r für den Datenschutz) of your respective federal state.

---

*This privacy policy was drafted in accordance with the EU General Data Protection Regulation (DSGVO), the German Federal Data Protection Act (BDSG), the German Digital Services Act (DDG), the German Telecommunications Digital Services Data Protection Act (TDDDG), and Apple's App Store Review Guidelines.*
