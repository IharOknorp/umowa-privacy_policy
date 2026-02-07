# Umowa AI Privacy Policy

**Updated:** 7 February 2026

Umowa AI (the “App”) is published by Pronka Ihar, operating from Warsaw, Poland (“we”, “us”, “our”).
We process personal data in accordance with Regulation (EU) 2016/679 (GDPR), the Polish Personal Data Protection Act, and other applicable privacy laws.

## 1. Data Controller & Contact
Controller: Pronka Ihar (individual developer), Warsaw, Poland
E-mail: oknorpCorp@gmail.com
DPO/Privacy Contact: Not appointed; contact via the e-mail above.
Please include “Privacy” in the subject line.

## 2. Scope
This policy describes how data is handled when you:

- use the mobile application,
- upload or scan contracts for analysis,
- use built-in redaction/analysis/rewarded features,
- contact support.

## 3. Data We Process
| Category | Details | Source |
| --- | --- | --- |
| Usage/Device Data | Device/OS info, crash/error diagnostics, analytics events | Collected automatically |
| Document Content | Text extracted from uploaded PDFs; may contain personal data | Provided by you |
| Redaction Metadata | Detected PII categories, placeholders, summaries, timestamps | Generated on device |
| Reward/Token Data | Token balance and rewarded-ad outcomes | Generated in app |
| Support Information | E-mail, screenshots, logs you voluntarily share | Provided by you |

We do not require full account registration. Firebase Authentication may create an anonymous technical user ID for secure function access.

## 4. How We Process Documents & PII
- On-device processing: OCR, PII detection, and redaction are performed locally on your device.
- Cloud analysis: Redacted text is sent to backend endpoints (Firebase Cloud Functions), which call OpenAI for summarization.
- Key security: OpenAI API key is stored server-side as a secret (not in mobile app code).
- Manual edits: If you manually edit/redact text, your edited content is what gets analyzed.
- Local data: Settings and token state are stored locally on device.

## 5. Legal Disclaimer
- Umowa AI is not a law firm or attorney and does not provide legal advice.
- AI output is generated with GPT and may be inaccurate or incomplete.
- You should verify results and consult a qualified attorney for legal decisions.

## 6. Purposes & Legal Bases (GDPR)
| Purpose | Legal Basis |
| --- | --- |
| Provide redaction and AI summary features | Art. 6(1)(b) GDPR (performance of a contract/service) |
| Store minimal app settings and technical preferences | Art. 6(1)(b) and Art. 6(1)(f) GDPR |
| Security, abuse prevention, and service reliability | Art. 6(1)(f) GDPR |
| Support communication | Art. 6(1)(b) GDPR |
| Compliance obligations | Art. 6(1)(c) GDPR |

Where required by law, consent mechanisms are used.

## 7. Data Retention
- Document content: processed for requested analysis; not intended for long-term storage by us.
- Local app data: stored on your device until you clear it (or app uninstall).
- Support requests: retained as needed to resolve your request and legal obligations.
- Analytics/ads/provider logs: retained per provider policies and configured retention settings.

## 8. Sharing & International Transfers
We share data only with service providers necessary to operate the App:

- Google Firebase (Authentication, Cloud Functions, Analytics)
- OpenAI (contract analysis through our backend)
- Google AdMob (rewarded advertising)

We do not sell personal data.
International transfers, where applicable, rely on lawful safeguards (including contractual safeguards such as SCCs where relevant).

## 9. Advertising & Analytics
The App may use:

- Firebase Analytics for product and stability metrics,
- AdMob rewarded ads for token rewards.

On Android, advertising identifiers may be used according to Google Play and AdMob policies and your device/privacy settings.

## 10. Security
- TLS encryption for network communication.
- On-device redaction prior to analysis requests.
- Server-side secret management for API keys.
- Access controls and least-privilege approach for backend systems.

## 11. Children
The App is not intended for children under 16.
If you believe children’s data was processed without proper legal basis, contact us for deletion.

## 12. Your Rights
Depending on jurisdiction, you may have rights to:

- access,
- rectification,
- erasure,
- restriction/object,
- portability,
- withdrawal of consent (where consent is the basis),
- complaint to a supervisory authority (Poland: UODO).

## 13. Changes to This Policy
We may update this policy due to legal, technical, or product changes.
The date at the top shows the latest version.

<a id="data-deletion-requests"></a>
## 14. Data Deletion Requests (Anchor)
You can request deletion of data associated with your use of Umowa AI by emailing:

oknorpCorp@gmail.com
Subject: Data Deletion Request – Umowa AI

Please include:

- your device platform (Android/iOS),
- approximate date/time of use,
- any support thread reference (if applicable).

We will review and respond within legally required timelines.
You can also immediately remove local app data by using in-app “Clear All Data” and/or uninstalling the app.

## 15. Complaints
EU users may complain to UODO (Poland).
UK users may complain to the ICO.
Users in other regions may contact their local data protection authority.

By using Umowa AI, you acknowledge that you have read this Privacy Policy.
