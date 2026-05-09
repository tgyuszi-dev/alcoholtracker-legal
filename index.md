# Privacy Policy

**Last updated:** 2026-05-08

This Privacy Policy describes how Alcohol Tracker ("the App") handles information when you use it. By installing, opening, or otherwise using the App you accept this Policy in full. **If you do not agree, do not use the App.**

---

## 1. Use At Your Own Risk

The App is provided **"AS IS" and "AS AVAILABLE"** without any warranty of any kind, whether express, implied, statutory, or otherwise. To the maximum extent permitted by law:

- We make **no warranty** that the App will be uninterrupted, secure, error-free, accurate, or fit for any particular purpose.
- We make **no warranty** about the accuracy, completeness, timeliness, reliability, or availability of any data shown in the App, including but not limited to sobriety counts, current streak, longest streak, attempts, daily check-ins, daily reflections, milestones, drink logs, body metrics, statistics, money-saved estimates (total or current-streak, including any continuously ticking counter), birthday cards, or notifications.
- **You use the App entirely at your own risk.** You are solely responsible for your own decisions, actions, and outcomes — including health, financial, legal, social, and personal outcomes — that arise from or relate to your use of the App.

The App is **not** a medical device, not a substitute for professional medical, psychological, addiction, legal, financial, or any other advice, and must not be relied on for any such purpose. Always consult a qualified professional.

---

## 2. Your Responsibilities

By using the App you confirm and agree that:

- You are solely responsible for the **accuracy** of any data you enter (drink amounts, weight, dates, notes, profile information, country, language, monthly spending, currency, date of birth, daily check-ins, daily reflections, etc.).
- You are solely responsible for **safeguarding your Google account** used to sign in. Any activity under your account is your responsibility. We do not see, store, or manage your Google password.
- You are solely responsible for **what you share** with friends inside the App or with any other user, including which categories of data you opt to share via the privacy toggles in Settings (sobriety progress, drinks, body metrics, milestones, journey notes). Once shared, we cannot guarantee or control how others use it.
- You are solely responsible for **the legality of your use** of the App in your jurisdiction. You must not use the App where it is prohibited.
- You are solely responsible for **complying with applicable laws**, including data protection laws if you handle other people's data through the App.
- You are solely responsible for **backing up your own data**. We do not guarantee data preservation.
- You are responsible for **any device, network, or carrier costs** incurred by using the App.
- You are responsible for **any payments** you authorize through Google Play, including subscriptions, renewals, taxes, currency conversion, and refunds.
- You are responsible for the **interpretation of any number** the App displays, including streaks, money-saved estimates, milestone progress, or any value derived from your check-in history.

---

## 3. Information Processed By the App

The App processes only what is needed to operate. We minimize collection.

### 3.1 Account (Google Sign-In)
Authentication is handled by Google Sign-In via Firebase Authentication. We receive:

- Your Google **email address**
- Your Google **display name**
- A unique Firebase Authentication **user ID (UID)**

We do **not** receive or store your Google password. Your Google account, two-factor settings, and recovery options remain entirely under Google's control and policies.

### 3.2 Profile Information
- Display name (from Google, editable in Settings)
- Email (from Google)
- Profile picture (optional, encoded image)
- Country, language preference
- Date of birth (optional, used for the in-app birthday card)
- Optional monthly spending and currency for the money-saved feature
- Privacy / sharing toggles (see Section 5)

### 3.3 Data You Voluntarily Enter
- **Daily check-ins** — the calendar day on which you tap "I'm sober today". Your current streak, longest streak, attempts, and money-saved figures are derived from this set.
- **Daily reflections** — short text notes per day, kept locally on the device only (not uploaded to the cloud). The last 30 entries are retained; older ones are dropped automatically.
- Sobriety records (start/end dates, optional notes)
- Drink entries (type, quantity, date) — premium feature
- Body metrics (weight, unit preference) — premium feature
- Milestones derived from your records and check-ins

### 3.4 Social Features
- Friend connections (user IDs)
- Friend requests
- A `lastSeenAt` server timestamp written each time you open the App (visible to friends as relative activity)

### 3.5 Subscription State
- A single boolean indicating whether your account currently has an active premium subscription, plus a timestamp of when it last changed. Payment cards are **never** seen or stored by us — Google Play Billing handles all payment data.

### 3.6 Diagnostics
- Crash reports via Firebase Crashlytics (stack traces, device model, OS version, app version)
- Anonymized usage metrics via Firebase Analytics (sessions, screen views)
- We do **not** collect device location, contacts, microphone, camera (unless you tap the in-app "Take a Photo" action), or device identifiers beyond what Firebase / AdMob require.

### 3.7 Advertising (free tier)
- The free tier shows a banner ad on the dashboard served by Google AdMob. AdMob may collect a device advertising ID and limited diagnostic data under **its own policy** at https://policies.google.com/privacy. You consent to this by using the free tier.
- EU/UK/Switzerland users see a Google UMP consent dialog before any ad request is made.
- Premium subscribers see no ads.

---

## 4. How Data Is Stored and Shared

- **On-device:** Room database and DataStore preferences.
- **Cloud:** Google Firebase (Authentication, Realtime Database, Crashlytics, Analytics) on Google's infrastructure.
- **Payments:** Google Play Billing.
- **Ads (free tier only):** Google AdMob, with consent gated through Google UMP where required.

These third parties operate under their own terms and privacy policies which you also accept by using the App. We are **not responsible** for the practices, security, availability, or actions of any third-party service. Any issue with Google, Firebase, AdMob, UMP, or Play Billing must be raised directly with the respective provider.

We do not sell data and do not share data with any other third parties beyond those listed above.

---

## 5. Friends and Sharing Toggles

If you connect with another user as a friend, that user can see only the categories you have opted to share via **Settings → Privacy**:

- Sobriety progress
- Drink calendar
- Body metrics
- Milestones
- Journey / recovery notes

You may toggle any of these off at any time. Removing a friend revokes future visibility but does **not** erase data the friend may have already viewed, screenshotted, exported, or memorized. We are not responsible for any such residual exposure or for the conduct of other users.

---

## 6. Data Retention and Deletion

- Account and tracking data are retained while your account exists.
- Daily reflections live only on the device and are cleared automatically when you log out.
- Crash reports and analytics may be retained by Firebase under Google's retention policies.
- You may delete your account at any time from **Settings → Delete account**. This permanently removes your profile, authentication credentials, daily check-ins, sobriety records, drink entries, body metrics, friendships, and friend requests. A server-side function cascades cleanup of edges held by other users (e.g. removes you from friends' lists).
- Anonymous reference identifiers may remain for technical reasons; these contain no personal data and cannot be linked back to you once your account record is deleted.
- We make **no guarantee** of the speed or completeness of deletion across backups, caches, or third-party systems beyond what is described above.

---

## 7. Security

We rely on Google Firebase's managed security (TLS in transit, server-side encryption at rest, authenticated database rules that restrict reads and writes to the authenticated owner with limited friend-readable exceptions for opted-in shared categories). **No system is perfectly secure.** We make no warranty against unauthorized access, breach, leak, loss, or corruption of data. You acknowledge and accept this risk.

You are solely responsible for the security of the Google account you use to sign in, including its password, recovery email, and any second-factor configuration.

---

## 8. International Transfers

Google's infrastructure may store and process data outside your country, including in the United States. By using the App you consent to such transfers.

---

## 9. Disclaimer and Limitation of Liability

To the maximum extent permitted by applicable law:

- The App is provided **without warranty of any kind**, express or implied, including but not limited to merchantability, fitness for a particular purpose, accuracy, non-infringement, security, or uninterrupted service.
- **We disclaim all liability** for any direct, indirect, incidental, special, consequential, exemplary, punitive, or any other damages — including but not limited to loss of profits, loss of data, loss of business, personal injury, emotional distress, relapse, missed milestones, incorrect statistics, miscalculated streaks or money-saved figures (whether displayed as a static value or a continuously ticking counter), ad mistargeting, account compromise, third-party access to your data, or any harm arising out of or relating to your use of or inability to use the App — even if we have been advised of the possibility of such damages.
- You agree to **indemnify and hold us harmless** from and against any claim, loss, damage, expense, or liability (including reasonable legal fees) arising from your use of the App, your violation of this Policy, your violation of applicable law, or your infringement of any third party's rights.
- **You assume full and sole responsibility** for any consequence resulting from data you record in the App or decisions you make based on the App.

If any part of this Section is held unenforceable in your jurisdiction, our liability is limited to the maximum extent that limitation is permitted by law, and in no event shall it exceed the total amount you have paid us (if any) for the App in the 12 months preceding the event giving rise to the claim. **For free-tier users this amount is zero.**

Some jurisdictions do not allow certain limitations of warranty or liability; in those jurisdictions the above limitations apply only to the extent permitted by law.

---

## 10. Changes to This Policy

We may update this Policy at any time without prior notice. Updates take effect when published. The "Last updated" date reflects the most recent version. **Your continued use of the App after any change constitutes acceptance** of the updated Policy. It is your responsibility to review this Policy periodically.

---

## 11. Contact

For account deletion requests or privacy questions:

**Email:** _gyula.tasnadi.1990@gmail.com_

We will respond at our discretion and within reasonable time. We make no guarantee of response time.

---

## 12. Governing Law and Severability

This Policy is governed by the laws of the jurisdiction in which the App publisher resides, without regard to conflict-of-law principles. If any provision of this Policy is found invalid or unenforceable, the remaining provisions remain in full force and effect.

---

By using the App you acknowledge that you have read, understood, and agreed to this Privacy Policy in full and that you accept all risk and responsibility for your use of the App.
