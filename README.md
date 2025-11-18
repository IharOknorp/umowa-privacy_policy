# Umowa AI Privacy Policy

_Updated: 18 November 2024_

Umowa AI (the “App”) is published by Pronka Ihar, operating from Warsaw, Poland (“we”, “us”, “our”).  
We process personal data in accordance with Regulation (EU) 2016/679 (GDPR), the Polish Personal Data Protection Act, and comparable international privacy regulations, including the UK GDPR, the California Consumer Privacy Act (CCPA/CPRA), Brazil’s LGPD, and other applicable laws.

## 1. Data Controller & Contact
- **Controller:** Pronka Ihar (individual developer), Warsaw, Poland  
- **E‑mail:** oknorpCorp@gmail.com  
- **DPO/Privacy Contact:** Not appointed; the controller can be reached at the e‑mail above.  
Please include “Privacy” in the subject line when contacting us.

## 2. Scope
This policy describes how the App handles personal data when you:
- use the mobile application or web preview,
- upload or scan contracts for analysis,
- interact with built-in translation/UI features, and
- contact our support team.

## 3. Data We Process
| Category | Details | Source |
| --- | --- | --- |
| **Usage/Device Data** | Device model, OS version, crash/error diagnostics, anonymized analytics events. | Collected automatically. |
| **Document Content** | Text extracted from uploaded PDFs; may contain personal data such as names, PESEL, NIP, IBAN, addresses. | Provided by you. |
| **Redaction Metadata** | The list of detected PII types, placeholders, summaries, timestamps. | Generated on device. |
| **Support Information** | E-mail address, screenshots, debugging logs that you voluntarily share. | Provided by you. |

We do **not** require account registration and we do **not** intentionally collect biometric data, special category data, or precise location data.

## 4. How We Process Documents & PII
- **On-device processing:** OCR, PII detection, and redaction run locally on your device.  
- **Cloud requests:** Only the redacted text (without detected PII) is sent to OpenAI’s API for contract summarisation. We sign a Data Processing Agreement with OpenAI and use EU-hosted endpoints when available.  
- **Temporary caching:** Extracted text is held in volatile memory. If you opt in to “Auto-save last session”, the encrypted cache is deleted after 24 hours.  
- **Manual edits:** Any manual redactions you enter replace the cloud-bound payload. Logs are not uploaded unless you expressly share them via support.

## 5. Purposes & Legal Bases
| Purpose | Legal Basis |
| --- | --- |
| Provide contract redaction & summary features | Art. 6(1)(b) GDPR (performance of a contract: delivering the requested service). |
| Store minimal settings (language, consent flags) | Art. 6(1)(b) and Art. 6(1)(f) GDPR (legitimate interest in ensuring functionality). |
| Debugging, security monitoring | Art. 6(1)(f) GDPR (maintaining app integrity). |
| Support communications | Art. 6(1)(b) GDPR (responding to your inquiries). |
| Compliance with legal obligations | Art. 6(1)(c) GDPR. |

Where local laws require consent (e.g., certain analytics or transmissions), we request opt-in in advance.

## 6. Data Retention
- Document content: retained only in volatile memory; optional encrypted cache deleted after 24 hours or when the user taps “Clear Data”.  
- Support tickets: kept for up to 24 months, unless law requires longer.  
- Diagnostic logs: anonymized and rotated every 30 days.  
When retention periods expire, data is securely deleted or anonymized.

## 7. Sharing & International Transfers
We share data only with:
1. **OpenAI, L.L.C.** – receives redacted text for AI summarisation. Processing is covered by Standard Contractual Clauses.  
2. **Expo/EAS & Google Play** – receive build metadata and crash diagnostics.  
3. **Infrastructure & security vendors** (e.g., AWS, Sentry) strictly as processors under GDPR Art. 28.  
We do not sell personal data. Cross-border transfers rely on SCCs or other lawful safeguards.

## 8. Data Subject Rights
Depending on your jurisdiction, you may have the right to:
- access, rectify, or erase your data;  
- restrict or object to processing;  
- portability of data you provided;  
- withdraw consent at any time;  
- lodge a complaint with a supervisory authority (in Poland: Urząd Ochrony Danych Osobowych).  
Because most processing happens on your device, exercising rights usually involves deleting data locally or contacting us for support.

## 9. Security
- All communications use TLS 1.2+.  
- Redaction and OCR run offline; only sanitized text leaves the device.  
- Optional caches and keys are stored via secure OS storage (SecureStore/Keychain/Keystore).  
- Access to production systems is role-based and audited.

## 10. Children
The App is not intended for persons under 16. If we learn that we processed minors’ data without proper consent, we will delete it promptly.

## 11. Changes
We may update this policy to reflect new features or legal requirements. Material changes will be announced in-app and via release notes. The revision date at the top indicates the latest version.

## 12. Contact & Complaints
For privacy inquiries or to exercise your rights, contact **oknorpCorp@gmail.com**.  
EU users may lodge complaints with UODO; UK users with the ICO; US users with their state privacy regulator.

---

By using Umowa AI you acknowledge that you have read this Privacy Policy. If you do not agree, please uninstall the App and contact us with any concerns.
