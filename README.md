# Telefónica (telefonica)

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
