# Anonymizer (Working Title)

Anonymizer is a privacy-first mobile application for local text and document anonymization.  
All processing is performed locally on the user's device. No external servers, no tracking, no analytics.

This repository contains public documentation related to the application, including legal material and user account procedures.

---

## Privacy and Data Handling

- The application does not upload or transmit documents or text to external servers.
- Sensitive data is processed locally and remains on the device.
- Authentication uses Firebase (Email/Password and Google Sign-In).
- User data (email and preferences) may be stored to support application functionality.

For full details, see:  
`PRIVACY_POLICY.md`

---

## Account Deletion Procedure

Users can delete their account at any time.

To delete an account from the application:

1. Open the app
2. Navigate to: Settings → Account → Delete Account
3. Confirm the deletion request

Alternatively, users may request deletion via the contact email listed in the Privacy Policy.

Deletion is permanent and removes all associated account data from our systems.

For full instructions, see:  
`ACCOUNT_DELETION.md`

---

## Technical Notes

- Platform: Android
- Language: Kotlin + Jetpack Compose
- Processing: 100% on-device
- No third-party analytics
- Email verification required for account access

---

## Roadmap (Public Summary)

Planned improvements (non-exhaustive):

- Extended file anonymization support (PDF, DOCX, XLSX, PPTX)
- Multi-language interface
- Local history and export options
- Additional documentation for developers

More information will be added when available.

---

## Contact

For privacy-related inquiries or account deletion requests, please refer to the contact information in `PRIVACY_POLICY.md`.
