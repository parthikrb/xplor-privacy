# Privacy Policy for Xplor

**Effective date:** 2026-05-07
**App:** Xplor (`app.xplor.travel`)
**Contact:** parthi.krb@gmail.com

This Privacy Policy explains what information Xplor ("we", "us", "the app") collects, how we use it, and the choices you have. By using Xplor, you agree to this policy.

## 1. Information We Collect

### 1.1 Account information (via Clerk)
We use [Clerk](https://clerk.com) to handle sign-up and sign-in. Clerk processes:
- Email address
- Name (if provided)
- Profile image (if provided)
- Authentication identifiers (e.g. OAuth provider IDs, hashed credentials)

We do not see or store your password. See [Clerk's Privacy Policy](https://clerk.com/legal/privacy).

### 1.2 App content you create
Data you enter into Xplor — trips, expenses, notes, attached receipt photos — is stored in our database (hosted on [Neon](https://neon.tech), a serverless Postgres provider) and linked to your account.

### 1.3 Photos
If you attach a receipt or image, the app reads the selected photo from your device's photo library (Android permission `READ_MEDIA_IMAGES`). Only photos you explicitly pick are uploaded. The app does not scan or read your library in the background.

### 1.4 Information we do NOT collect
- Location (location permissions are explicitly disabled)
- Microphone / audio (explicitly disabled)
- Contacts, calendar, SMS, call logs
- Advertising identifiers
- Background activity or device sensors

## 2. How We Use Your Information

- To create and authenticate your account
- To store and sync your trips, expenses, and attachments across your devices
- To respond to support requests
- To keep the service secure and prevent abuse

We do not sell your personal data. We do not show advertising in the app.

## 3. Third-Party Services (Sub-processors)

| Provider | Purpose | Data |
|---|---|---|
| Clerk | Authentication | Email, name, profile image, auth metadata |
| Neon (Postgres) | Database hosting | All app content tied to your account |
| Expo / EAS | App build & delivery | App binaries; no user data |

Each provider has its own privacy policy and security controls.

## 4. Data Retention

Account and app content remain stored as long as your account is active. If you delete your account (see Section 6), associated data is removed within 30 days, except where retention is required by law.

## 5. Data Security

- Data in transit is encrypted using TLS.
- Authentication tokens are stored on-device using `expo-secure-store` (iOS Keychain / Android Keystore).
- Database access is restricted and credentials are not embedded in the app.

No method of transmission or storage is 100% secure; we make reasonable efforts to protect your data but cannot guarantee absolute security.

## 6. Your Rights and Choices

You may:
- Access or update your profile information from inside the app
- Request deletion of your account and associated data by emailing **parthi.krb@gmail.com**
- Revoke photo permission at any time in your device's system settings

Depending on your jurisdiction (e.g. EU/UK GDPR, California CCPA), you may have additional rights including data portability and the right to lodge a complaint with a supervisory authority.

## 7. Children

Xplor is not directed to children under 13 (or the equivalent minimum age in your jurisdiction). We do not knowingly collect personal information from children. If you believe a child has provided us data, contact us and we will delete it.

## 8. International Transfers

Data may be processed on servers located outside your country (including the United States and the European Union) by our sub-processors listed in Section 3.

## 9. Changes to This Policy

We may update this policy from time to time. Material changes will be reflected by updating the "Effective date" above. Continued use of the app after changes means you accept the revised policy.

## 10. Contact

Questions or requests:
**parthi.krb@gmail.com**
