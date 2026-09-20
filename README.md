# Awesome Identity Verification [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of identity verification, KYC, AML, and biometric authentication resources — APIs, open-source tools, standards, datasets, and regulations.

Identity verification (IDV) is how online businesses confirm that a user is a real person and who they claim to be. It underpins **KYC** (Know Your Customer) in fintech, **age verification** in restricted commerce, **KYB** (Know Your Business) in B2B onboarding, and **AML** (Anti-Money Laundering) compliance everywhere money moves.

Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Identity Verification Platforms](#identity-verification-platforms)
- [Open-Source Tools](#open-source-tools)
- [Sanctions & AML Data](#sanctions--aml-data)
- [Standards & Testing](#standards--testing)
- [Regulations & Guidance](#regulations--guidance)
- [Learning Resources](#learning-resources)

## Identity Verification Platforms

Hosted APIs and SDKs for document verification, biometrics, and compliance screening.

- [FinAuth](https://finauth.io) — Developer-first KYC API with a free tier: ID document verification, passive liveness + selfie-to-ID face match, age estimation, AML/PEP/sanctions screening, KYB with UBO checks, transaction (KYT) and crypto wallet screening, hosted verification sessions (shareable link or QR code), and signed webhooks. [Docs](https://docs.finauth.io).
- [Sumsub](https://sumsub.com) — Full-cycle verification platform covering KYC, KYB, transaction monitoring, and travel-rule support.
- [Veriff](https://www.veriff.com) — Video-first identity verification with broad document coverage.
- [Onfido](https://onfido.com) — Document and biometric verification, now part of Entrust.
- [Persona](https://withpersona.com) — Configurable identity workflows and case review tooling.
- [Jumio](https://www.jumio.com) — Long-established IDV vendor for regulated enterprises.
- [Ondato](https://ondato.com) — KYC/KYB suite popular with European financial institutions.
- [Stripe Identity](https://stripe.com/identity) — Lightweight IDV for businesses already on Stripe.

## Open-Source Tools

- [Open Source Face Recognition (InsightFace)](https://github.com/deepinsight/insightface) — Widely used face analysis toolkit (research/self-hosted use).
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) — General-purpose OCR engine often used as a baseline for document text extraction.
- [OpenSanctions yente](https://github.com/opensanctions/yente) — Self-hostable sanctions & PEP screening API over the OpenSanctions dataset.
- [MRZ parsers](https://github.com/topics/mrz) — Libraries for reading the machine-readable zone on passports and ID cards.
- [Tessio.Verifier](https://github.com/tripledownab/tessio-verifier) — Self-hostable .NET verifier for the EU Digital Identity Wallet: OpenID4VP 1.0 with DCQL, SD-JWT VC and ISO 18013-5 mdoc, Apache-2.0, on NuGet.

## Sanctions & AML Data

- [OpenSanctions](https://www.opensanctions.org) — Consolidated open database of sanctions targets, PEPs, and persons of interest.
- [OFAC Sanctions Lists](https://ofac.treasury.gov/sanctions-programs-and-country-information) — U.S. Treasury designated-persons lists (SDN and consolidated).
- [EU Sanctions Map](https://www.sanctionsmap.eu) — Official overview of EU restrictive measures.
- [UN Security Council Consolidated List](https://main.un.org/securitycouncil/en/content/un-sc-consolidated-list) — UN sanctions designations.
- [FATF](https://www.fatf-gafi.org) — Intergovernmental standard-setter for AML/CFT; publishes the 40 Recommendations and high-risk jurisdiction lists.

## Standards & Testing

- [ISO/IEC 30107-3](https://www.iso.org/standard/67381.html) — Presentation attack detection (liveness) testing methodology.
- [iBeta PAD Testing](https://www.ibeta.com/biometric-testing/) — Accredited lab conducting ISO 30107-3 liveness evaluations.
- [NIST FRTE / FRVT](https://pages.nist.gov/frvt/html/frvt11.html) — Independent benchmark of face recognition algorithm accuracy.
- [NIST SP 800-63](https://pages.nist.gov/800-63-3/) — U.S. digital identity guidelines (identity proofing and authentication assurance levels).
- [eIDAS](https://digital-strategy.ec.europa.eu/en/policies/eidas-regulation) — EU regulation on electronic identification and trust services.
- [ICAO Doc 9303](https://www.icao.int/publications/pages/publication.aspx?docnum=9303) — The specification behind machine-readable travel documents and passport NFC chips.

## Regulations & Guidance

- [EU AML Directives (AMLD)](https://finance.ec.europa.eu/financial-crime/anti-money-laundering-and-countering-financing-terrorism-eu-level_en) — The EU's AML framework.
- [FinCEN](https://www.fincen.gov) — U.S. financial crimes enforcement; CDD Rule and BSA guidance.
- [GDPR](https://gdpr.eu) — EU data protection law; governs biometric and identity data handling.
- [FATF Travel Rule Guidance](https://www.fatf-gafi.org/en/publications/Fatfrecommendations/Guidance-rba-virtual-assets-2021.html) — Requirements for virtual asset service providers.

## Learning Resources

- [KYC Compliance Handbook](https://github.com/FinAuth-SDK/kyc-compliance-handbook) — Practical guide to KYC, KYB, AML screening, and transaction monitoring.
- [Identity Verification API Guide](https://github.com/FinAuth-SDK/identity-verification-api-guide) — Developer patterns: hosted sessions, webhooks, QR hand-off, key security.
- [FinAuth Use Cases](https://github.com/FinAuth-SDK/finauth-use-cases) — Real-world IDV scenarios from fintech onboarding to crypto compliance.
- [Digital Onboarding Best Practices](https://github.com/FinAuth-SDK/digital-onboarding-best-practices) — Designing verification flows that convert.

---

Maintained by [FinAuth](https://finauth.io) — the developer-first identity verification API. Start free at [finauth.io](https://finauth.io) · [Documentation](https://docs.finauth.io)
