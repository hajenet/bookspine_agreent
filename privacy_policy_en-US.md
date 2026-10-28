# BookSpine Privacy Policy

> **Draft; not published or effective.** This policy is based on the currently inspected app, Supabase migrations, and Edge Functions. Confirm the legal operator, production configuration, providers, processing countries, public URLs, and effective date before publication. This is a general global draft, not a substitute for jurisdiction-specific legal review.

- Version: `1.0-draft`
- Draft date: 2026-10-26
- Contact: `hajenet@gmail.com` (privacy inquiries; legal operator identity is not yet confirmed)

## 1. Scope and your local rights

This policy describes BookSpine's common privacy practices for users worldwide. Local privacy laws may provide additional rights or notices; those requirements continue to apply, and we will provide regional supplements where needed. We do not treat one country's rules as replacing protections required in another.

## 2. Information, purposes, and retention

| Information | Why we use it | Retention |
|---|---|---|
| Account identifier, email address, authentication provider identifiers, and session data | Sign-in, account security, recovery, and requested account changes | While the account is active; session data until sign-out or expiration, subject to provider retention |
| Required consent document/version, locale, and timestamp | Record and demonstrate consent | Until account deletion, unless a limited record must be retained for legal compliance or a dispute |
| Optional profile, handle, biography, visibility choices, and user-submitted public posts, comments, reviews, and shelves | Provide profile and community features chosen by you | Until you delete the item, make it private, or delete the account; limited security or dispute records may remain as legally permitted |
| ISBN or search terms you submit | Retrieve book catalog information | For the request and short-lived service processing; provider logs are governed by that provider's policy |
| Book-spine photos you submit for One Stop recognition, derived crops, and OCR/analysis results | Perform the recognition request you initiate | Target: automatic deletion 30 days after the job completes, fails, or is cancelled; deleted sooner with account deletion where the production cleanup is active |
| Device-only library entries, shelf positions, reading status, and private notes/reviews | Provide your personal library | Stored on your device until you remove the data or clear/uninstall app data; server account deletion does not remove device-only data |
| Diagnostic, security, and service-operation records | Protect and operate the service, investigate abuse, and resolve failures | For the period set by the production configuration and applicable law; the exact production log and backup periods must be confirmed before publication |

The 30-day One Stop period is a selected operational target. The cleanup code is present in the repository, but the production schedule and deletion run have not been verified as active. Do not represent this target as an active deletion guarantee until the scheduled cleanup is deployed and observed.

## 3. Choices and sharing

BookSpine does not make device-only personal library data public by default. Optional profile, shelf, post, review, or other community data is visible according to the choices presented in the feature. We do not sell personal information or use it for advertising in the inspected implementation. When you request third-party sign-in, book lookup, or image recognition, the information needed for that request is sent to the relevant provider. Provider name, exact data fields, purpose, legal basis, country, and retention must be confirmed from production settings and provider agreements before this draft can be activated.

## 4. Service providers and international processing

The inspected project uses Supabase for authentication, database, file storage, and server functions; Google for sign-in and book lookup; Gemini (`gemini-3-flash-preview`) for the active recognition configuration; and Open Library for ISBN lookup. The Supabase database and Storage project region is Seoul, South Korea (`ap-northeast-2`). Whether Google OAuth/Books and Gemini API requests are processed outside South Korea, and their receiving countries, transfer basis, and retention, must be confirmed from production settings and provider terms before publication. Where local law requires, we will provide the applicable transfer notice and legal basis or obtain consent.

## 5. Your choices and rights

Depending on where you live, you may have rights to access, correct, delete, restrict, object to, or obtain a copy of personal information, withdraw consent where processing relies on consent, and complain to a regulator. You may also use the app's profile/privacy controls or contact us. We may ask for reasonable identity verification and will respond within applicable legal deadlines. We will not deny a request solely because you exercise a privacy right.

## 6. Account and data deletion

You can start deletion in the app under **Account > Delete account**, or use the [BookSpine account and data deletion page](account_deletion_request_en-US.html) without reinstalling the app. We normally complete the request or provide a status update within 30 days. Server profile, public content, authentication data, consent history, and One Stop files are removed as described there, subject to legally required retention. Device-only library data must be removed separately from the device. Copies in backups or provider logs may persist for a limited period under the applicable backup or provider schedule; exact production periods must be confirmed before publication.

## 7. Security

We use measures in the application and hosting configuration intended to limit access and protect data in transit and at rest. No internet transmission or storage method can be guaranteed completely secure. Production access controls, backup protections, incident procedures, and retention settings must be confirmed before publication.

## 8. Children

BookSpine is not currently represented as a service designed for children. The minimum age and any parental-consent process must be confirmed for each market before launch. Do not submit another person's personal information, particularly a child's, without appropriate authority.

## 9. Changes

We will update this policy when processing changes. For material changes, we will publish the revised text and effective date and provide notice or obtain renewed consent when required. Prior versions will remain available as required by law.

## 10. Privacy contact and operator identity

- Privacy contact: [hajenet@gmail.com](mailto:hajenet@gmail.com)
- Legal operator name and postal address: **must be confirmed and added before publication**
- Production-specific complaint contact and regulator details: add where required for each market
