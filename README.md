---
title: Privacy Policy
description: How Saling collects, uses, and protects your information.
---

# Privacy Policy

**Effective date:** July 19, 2026  
**Last updated:** July 19, 2026

Saling (“**Saling**,” “**we**,” “**us**,” or “**our**”) is a calm habit app for two people — one shared space, mutual visibility without judgment. This Privacy Policy explains what information we collect when you use the Saling iOS app and related services, how we use it, who we share it with, and the choices you have.

If you have questions, contact us at **[akhsani27@gmail.com](mailto:akhsani27@gmail.com)**.

---

## Summary

- **Built for pairs.** Your habits and check-ins are shared only with your partner in the same Space — not posted publicly.
- **Start anonymously.** You can use Saling without signing in. You may optionally link **Sign in with Apple** so your account survives device changes and invites are tied to you.
- **No ads. No cross-app tracking.** We do not sell your data or use it for advertising.
- **Minimal analytics.** Product analytics, when enabled, records event names and coarse properties only — never habit sentences, message text, or invite tokens.
- **You can delete your account** at any time in Settings.

---

## 1. Who this policy applies to

This policy applies to users of:

- The **Saling** iOS application (bundle ID `com.lazyneko.Saling`)
- Our backend services that power the app (hosted on **Supabase**)
- Invite links and any future web pages we operate for Saling

This policy does **not** cover third-party services you choose to share content to (for example, when you share a progress card through the iOS share sheet to Messages or WhatsApp). Those services have their own privacy policies.

---

## 2. Information we collect

### 2.1 Information you provide

| Data | Examples | Why we collect it |
|------|----------|-------------------|
| **Display name** | The name shown to your partner | Identify you in your Space and on invite cards |
| **Habits** | Habit name, sentence, schedule, size, method (check / quantity / session) | Core app functionality |
| **Check-ins & sessions** | Dates completed, quantities, session duration and outcome | Track progress for you and your partner |
| **Partner messages** | Short one-line messages you send in a Space | Lightweight communication between partners |
| **Space details** | Optional space name, member color | Organize your shared Space |
| **Invite content** | Personal invite line (up to 80 characters) | Let you customize an invite before sending |

### 2.2 Information from Sign in with Apple

If you choose to link **Sign in with Apple**, we receive:

- A stable **Apple user identifier** (`apple_sub`) stored in your profile
- Your **name**, if you allow Apple to share it (you can edit your display name in Settings)
- Your **email address**, if you allow Apple to share it — this may be an Apple **Hide My Email** relay address

We use Sign in with Apple so your partner knows it is really you when you send an invite, and so your account and history can persist across devices. We do not use your Apple ID for advertising.

### 2.3 Information collected automatically

| Data | Examples | Why we collect it |
|------|----------|-------------------|
| **Account identifiers** | Supabase auth user ID | Authentication, account recovery, and data access control |
| **App activity (analytics)** | Event names such as `checkin`, `invite_sent`, `progress_opened`; properties such as habit method, channel, or latency in milliseconds | Understand product usage and improve the app |

**Analytics privacy rule:** Event properties are limited to enums, IDs, booleans, and latency values. We do **not** send habit sentences, personal invite lines, message bodies, or health quantities in analytics events. Invite events never include invite tokens.

In current production builds, analytics may be logged locally for development only and may not leave your device. Before wider beta releases, we may enable a privacy-focused analytics provider (such as **TelemetryDeck**) under the same rules above.

### 2.4 Push notifications (when enabled)

If you enable notifications and we ship push delivery, we will store an **Apple Push Notification service (APNs) device token** so we can deliver partner-related alerts — for example, when your partner checks in or sends a tug.

We send **partner-framed** notifications only. We do not send marketing pushes, guilt-based “come back” messages, or ads.

### 2.5 What we do not collect (v1)

Saling v1 does **not** collect:

- Precise location
- Contacts from your address book
- Photos or camera data
- Browsing history
- Health or fitness data from HealthKit
- Financial or payment card data (in-app purchases are not active in v1)
- Advertising identifiers (IDFA) for tracking

---

## 3. How we use your information

We use the information above to:

- Create and manage your account and Space
- Sync habits, check-ins, sessions, and messages between you and your partner
- Process invites and pair you with a partner
- Send optional push notifications you have agreed to receive
- Operate, secure, debug, and improve the app
- Respond to support and privacy requests
- Comply with legal obligations

We do **not** use your information for:

- Selling or renting personal data
- Cross-app or cross-company advertising tracking
- Public social feeds, leaderboards, or discovery by strangers

---

## 4. Who can see your information

| Audience | What they can see |
|----------|-------------------|
| **You** | All of your own habits, check-ins, and settings |
| **Your partner** | Habits and check-in status in your shared Space, partner messages, and presence signals (for example, tugs). Some session outcomes marked “start only” are visible to you only |
| **Us (the developer)** | Data stored on our backend as needed to operate the service, subject to access controls |
| **The public** | Nothing by default. If you choose to share a progress image through the iOS share sheet, you control what leaves the app |

Row-level security on our database is designed so users can only access Spaces they belong to.

---

## 5. How we share information

We share information only as described below.

### 5.1 Service providers

We use trusted providers to run the app:

| Provider | Role | Data involved |
|----------|------|---------------|
| **Supabase** | Authentication, database, and API hosting | Account data, profiles, habits, check-ins, messages, invites, and related app data |
| **Apple** | Sign in with Apple, push notification delivery, TestFlight / App Store distribution | Identity tokens, device tokens (when push is enabled), and standard platform metadata |
| **Analytics provider** (when enabled, e.g. TelemetryDeck) | Product analytics dashboards | Event names and coarse properties only — no habit text or message bodies |

These providers process data on our behalf under their own terms and privacy policies. We do not authorize them to use your data for their own advertising.

### 5.2 Legal and safety

We may disclose information if we believe in good faith that it is necessary to:

- Comply with law, regulation, legal process, or governmental request
- Protect the rights, property, or safety of Saling, our users, or the public
- Detect, prevent, or address fraud, security, or technical issues

### 5.3 Business transfers

If Saling is involved in a merger, acquisition, or sale of assets, your information may transfer as part of that transaction. We will notify you of any material change in ownership or use of your personal information.

### 5.4 We do not sell your data

We do **not** sell your personal information.

---

## 6. Data retention

We keep your information while your account is active and as needed to provide the service.

When you **delete your account** in Settings, we permanently remove your profile and auth record, delete Spaces you solely own, and remove you from paired Spaces. Some partner-visible history may remain visible to your former partner only insofar as it was already part of a shared Space before you left or deleted your account — contact us if you need help with a specific situation.

We may retain limited logs or backups for a short period for security, fraud prevention, or legal compliance, after which they are deleted or anonymized.

---

## 7. Security

We use industry-standard measures to protect your data, including:

- Encrypted connections (HTTPS/TLS) between the app and our servers
- Authentication and row-level access controls in our database
- Minimal collection — we only store what the product needs

No method of transmission or storage is 100% secure. If you believe your account has been compromised, contact us at **[akhsani27@gmail.com](mailto:akhsani27@gmail.com)**.

---

## 8. Your choices and rights

Depending on where you live, you may have rights to access, correct, delete, or export your personal information, or to object to or restrict certain processing.

**In the app today, you can:**

- Edit your **display name** in Settings
- **Delete your account** in Settings (permanent)
- **Decline push notifications** in iOS Settings
- Choose what to share when using the **share sheet** for progress cards (including a privacy mode that shows only your own data)

**To exercise other privacy rights**, email **[akhsani27@gmail.com](mailto:akhsani27@gmail.com)** with the subject line “Privacy request.” We may need to verify your identity before fulfilling a request.

### California residents (CCPA / CPRA)

We do not sell personal information. California residents may request access to or deletion of personal information as described above.

### European Economic Area, UK, and Switzerland (GDPR)

Our legal bases for processing include:

- **Contract** — to provide the app you asked for
- **Legitimate interests** — to secure and improve the service, balanced against your rights
- **Consent** — where required (for example, optional notifications)

You may lodge a complaint with your local data protection authority. We use **Supabase** as our processor; data may be processed in the region configured for our Supabase project. See [Supabase’s privacy documentation](https://supabase.com/privacy) for details on their infrastructure and subprocessors.

---

## 9. Children’s privacy

Saling is not directed at children under 13 (or the minimum age required in your country). We do not knowingly collect personal information from children. If you believe a child has provided us personal information, contact us and we will delete it.

---

## 10. International users

Saling is operated from Indonesia. If you use the app from outside Indonesia, your information may be transferred to and processed in countries where our service providers operate, including the United States and other regions where Supabase or Apple maintain infrastructure. Those countries may have different data protection laws than your own.

Where required, we rely on appropriate safeguards for international transfers.

---

## 11. Changes to this policy

We may update this Privacy Policy from time to time. When we do, we will revise the “Last updated” date at the top. If changes are material, we will provide additional notice in the app or by other reasonable means.

Continued use of Saling after an update means you accept the revised policy.

---

## 12. Contact us

**Saling / LazyNeko**  
Email: **[akhsani27@gmail.com](mailto:akhsani27@gmail.com)**  
GitHub: [github.com/Akhsani/Saling](https://github.com/Akhsani/Saling)

For App Store privacy nutrition labels, we align our disclosures with the data practices described in this policy. If you notice a discrepancy, please let us know so we can correct it.
