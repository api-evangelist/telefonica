# Telefónica (telefonica)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Telefónica is one of the world's leading telecommunications companies, operating in Europe and Latin America. Through its Open Gateway initiative, Telefónica exposes standardized network capabilities as APIs following the CAMARA (Cloud and Edge for Mobile Access and Real-time Execution) open standards developed by the GSMA. The Open Gateway APIs enable developers and enterprises to build applications leveraging Telefónica's network infrastructure for authentication, fraud prevention, location services, quality of service, and device management. APIs are available in Spain, Germany, Brazil, and the United Kingdom through the Telefónica Open Gateway sandbox and partner program.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Telecommunications
- Mobile Network
- CAMARA
- Open Gateway
- Authentication
- Fraud Prevention
- Location Services

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Telefónica Number Verification API

The Number Verification API enables automatic verification that users are interacting via devices with SIM cards associated with their phone numbers, eliminating the need for credential entry or one-time passwords. Uses carrier network data to verify the mobile number associated with the device's active data connection. Available in Spain, Germany, and Brazil.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/number-verification](https://opengateway.telefonica.com/en/apis/number-verification)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Authentication
- Number Verification
- Fraud Prevention
- Mobile Identity
- SIM

#### Properties

- [Documentation](https://developers.opengateway.telefonica.com/docs/numberverification)
- [OpenAPI](openapi/telefonica-number-verification-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonica-number-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-number-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/telefonica-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Git Hub](https://github.com/Telefonica/opengateway-developers-website)

### Telefónica SIM Swap API

The SIM Swap API enables applications to detect recent SIM card swaps on a mobile number, a common indicator of account takeover fraud. Returns whether a SIM swap occurred on the mobile line and when the last swap happened. Based on CAMARA open standards. Available in Spain, Germany, Brazil, and the United Kingdom.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/sim-swap](https://opengateway.telefonica.com/en/apis/sim-swap)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Authentication
- Fraud Prevention
- SIM Swap
- Mobile Security

#### Properties

- [Documentation](https://developers.opengateway.telefonica.com/docs/simswap)
- [OpenAPI](openapi/telefonica-sim-swap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonica-sim-swap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-sim-swap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/telefonica-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Git Hub](https://github.com/Telefonica/opengateway-samples-simswap)

### Telefónica Know Your Customer Match API

The KYC Match API validates a user's contact information (name, address, phone number, email) against reliable mobile carrier data, enabling quick identity verification without sharing personal data. Used for e-commerce, financial services, and insurance KYC compliance. Available in Spain, Germany, Brazil, and the United Kingdom.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/kyc-match](https://opengateway.telefonica.com/en/apis/kyc-match)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Authentication
- Fraud Prevention
- KYC
- Identity Verification
- Financial Services

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/kyc-match)
- [OpenAPI](openapi/telefonica-kyc-match-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonica-kyc-match.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-kyc-match.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Telefónica Location Verification API

The Location Verification API verifies the geographical location of a SIM-based device, confirming whether the device is present within a requested geographic area. Uses network data rather than GPS to verify location without privacy risks. Available in Spain, Germany, and Brazil.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/location-verification](https://opengateway.telefonica.com/en/apis/location-verification)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Location Services
- Device Location
- Fraud Prevention
- Mobile Network

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/location-verification)
- [OpenAPI](openapi/telefonica-location-verification-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonica-location-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-location-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Telefónica Quality on Demand API

The Quality on Demand (QoD) API provides applications with precise control over mobile network connectivity quality, enabling guaranteed bandwidth and low latency for specific application flows. Used for real-time communications, streaming, industrial IoT, and gaming. Available in Spain, Germany, and Brazil.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/quality-on-demand](https://opengateway.telefonica.com/en/apis/quality-on-demand)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Quality of Service
- Mobile Network
- IoT
- Network Slicing
- Communication Quality

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/quality-on-demand)
- [OpenAPI](openapi/telefonica-quality-on-demand-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonica-quality-on-demand.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-quality-on-demand.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/telefonica-qod-session-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Telefónica Device Roaming Status API

The Device Roaming Status API verifies the roaming status of a SIM-based device securely using carrier network data, without relying on GPS or identity theft risks. Enables fraud detection, access control, and compliance for applications requiring location awareness. Available in Spain and Brazil.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/device-roaming-status](https://opengateway.telefonica.com/en/apis/device-roaming-status)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Roaming
- Device Status
- Fraud Prevention
- Mobile Network

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/device-roaming-status)
- [OpenAPI](openapi/telefonica-device-roaming-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonica-device-roaming.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-device-roaming.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Telefónica Scam Signal API

The Scam Signal API enables companies to protect their customers from phishing scams and voice fraud by detecting active scam calls in real time using Telefónica's network intelligence. Available in Spain.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/scam-signal](https://opengateway.telefonica.com/en/apis/scam-signal)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Fraud Prevention
- Scam Detection
- Phishing
- Voice Fraud
- Security

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/scam-signal)
- [Postman Collection](collections/telefonica-device-roaming.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-device-roaming.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-kyc-match.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-kyc-match.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-location-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-location-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-number-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-number-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-quality-on-demand.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-quality-on-demand.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-sim-swap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-sim-swap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Telefónica Age Verification API

The Age Verification API allows companies to confirm in real time whether a mobile user meets a specified age threshold, using carrier data for privacy-preserving age checks without sharing personal data. Available in the United Kingdom.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/age-verification](https://opengateway.telefonica.com/en/apis/age-verification)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Age Verification
- Compliance
- E-Commerce
- Media
- Privacy

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/age-verification)
- [Postman Collection](collections/telefonica-device-roaming.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-device-roaming.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-kyc-match.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-kyc-match.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-location-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-location-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-number-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-number-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-quality-on-demand.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-quality-on-demand.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-sim-swap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-sim-swap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Telefónica Line Tenure API

The Line Tenure API indicates how long a mobile number has belonged to its current user, providing a fraud risk signal for identity validation and account security workflows. Available in Spain, Brazil, and the United Kingdom.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/line-tenure](https://opengateway.telefonica.com/en/apis/line-tenure)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Fraud Prevention
- Identity Verification
- Financial Services
- Mobile Security

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/line-tenure)
- [Postman Collection](collections/telefonica-device-roaming.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-device-roaming.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-kyc-match.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-kyc-match.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-location-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-location-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-number-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-number-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-quality-on-demand.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-quality-on-demand.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-sim-swap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-sim-swap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Telefónica Population Density Data API

The Population Density Data API provides dynamic real-time data on population density in a specific geographic area and time window, derived from anonymized and aggregated mobile network data. Used for transport planning, event management, and retail analytics. Available in Spain.

- **Human URL:** [https://opengateway.telefonica.com/en/apis/population-density-data](https://opengateway.telefonica.com/en/apis/population-density-data)
- **Base URL:** `https://opengateway.telefonica.com`

#### Tags

- Location Services
- Population Data
- Analytics
- Transport
- Smart City

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/population-density-data)
- [Postman Collection](collections/telefonica-device-roaming.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-device-roaming.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-kyc-match.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-kyc-match.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-location-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-location-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-number-verification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-number-verification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-quality-on-demand.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-quality-on-demand.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/telefonica-sim-swap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonica-sim-swap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://opengateway.telefonica.com/en)
- [Developer Portal](https://opengateway.telefonica.com/en/developer-hub)
- [Documentation](https://developers.opengateway.telefonica.com/docs/initiative)
- [Git Hub](https://github.com/Telefonica)
- [Git Hub](https://github.com/camaraproject)
- [A P Is](https://opengateway.telefonica.com/en/apis)
- [Sign Up](https://opengateway.telefonica.com/en/developer-hub/join)
- [LinkedIn](https://www.linkedin.com/company/telefonica)
- [X (Twitter)](https://x.com/Telefonica)
- [L L Ms Txt](https://developers.opengateway.telefonica.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
