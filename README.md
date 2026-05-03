# Telefónica (telefonica)

Telefónica is one of the world's leading telecommunications companies. Through its Open Gateway initiative, Telefónica exposes standardized network capabilities as APIs following CAMARA (Cloud and Edge for Mobile Access and Real-time Execution) open standards developed by the GSMA. Open Gateway APIs enable fraud prevention, identity verification, location services, and network quality management using carrier network data across Spain, Germany, Brazil, and the United Kingdom.

**URL:** [https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Authentication, CAMARA, Fraud Prevention, Location Services, Mobile Network, Open Gateway, Telecommunications

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-03

## APIs

### Telefónica Number Verification API

Verify phone numbers against device SIM connections using carrier data - eliminates OTPs.

**Human URL:** [https://opengateway.telefonica.com/en/apis/number-verification](https://opengateway.telefonica.com/en/apis/number-verification)

#### Tags:

 - Authentication, Fraud Prevention, Mobile Identity, Number Verification, SIM

#### Properties

- [Documentation](https://developers.opengateway.telefonica.com/docs/numberverification)
- [OpenAPI](openapi/telefonica-number-verification-openapi.yml)
- [JSONSchema](json-schema/telefonica-device-schema.json)
- [GitHub](https://github.com/Telefonica/opengateway-developers-website)

### Telefónica SIM Swap API

Detect SIM swap fraud attempts on mobile numbers using carrier network data.

**Human URL:** [https://opengateway.telefonica.com/en/apis/sim-swap](https://opengateway.telefonica.com/en/apis/sim-swap)

#### Tags:

 - Fraud Prevention, Mobile Security, SIM Swap

#### Properties

- [Documentation](https://developers.opengateway.telefonica.com/docs/simswap)
- [OpenAPI](openapi/telefonica-sim-swap-openapi.yml)
- [GitHub](https://github.com/Telefonica/opengateway-samples-simswap)

### Telefónica Know Your Customer Match API

Validate identity data against carrier records for KYC compliance without exposing personal data.

**Human URL:** [https://opengateway.telefonica.com/en/apis/kyc-match](https://opengateway.telefonica.com/en/apis/kyc-match)

#### Tags:

 - Financial Services, Fraud Prevention, Identity Verification, KYC

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/kyc-match)
- [OpenAPI](openapi/telefonica-kyc-match-openapi.yml)

### Telefónica Location Verification API

Verify device geographic location using network data (no GPS required).

**Human URL:** [https://opengateway.telefonica.com/en/apis/location-verification](https://opengateway.telefonica.com/en/apis/location-verification)

#### Tags:

 - Device Location, Fraud Prevention, Location Services, Mobile Network

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/location-verification)
- [OpenAPI](openapi/telefonica-location-verification-openapi.yml)

### Telefónica Quality on Demand API

Guarantee network quality (bandwidth/latency) for device sessions.

**Human URL:** [https://opengateway.telefonica.com/en/apis/quality-on-demand](https://opengateway.telefonica.com/en/apis/quality-on-demand)

#### Tags:

 - Communication Quality, IoT, Mobile Network, Network Slicing, Quality of Service

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/quality-on-demand)
- [OpenAPI](openapi/telefonica-quality-on-demand-openapi.yml)
- [JSONSchema](json-schema/telefonica-qod-session-schema.json)

### Telefónica Device Roaming Status API

Check whether a device is roaming and which country it's connected in.

**Human URL:** [https://opengateway.telefonica.com/en/apis/device-roaming-status](https://opengateway.telefonica.com/en/apis/device-roaming-status)

#### Tags:

 - Device Status, Fraud Prevention, Mobile Network, Roaming

#### Properties

- [Documentation](https://opengateway.telefonica.com/en/apis/device-roaming-status)
- [OpenAPI](openapi/telefonica-device-roaming-openapi.yml)

### Additional APIs

- **Scam Signal API** - Detect active scam calls to protect against phishing (Spain)
- **Age Verification API** - Confirm age threshold for mobile users (UK)
- **Line Tenure API** - How long a number has belonged to its user (Spain, Brazil, UK)
- **Population Density Data API** - Real-time population density from network data (Spain)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [telefonica-number-verification-openapi.yml](openapi/telefonica-number-verification-openapi.yml) | Number Verification - verify and retrieve phone numbers |
| [telefonica-sim-swap-openapi.yml](openapi/telefonica-sim-swap-openapi.yml) | SIM Swap - check and retrieve swap dates |
| [telefonica-kyc-match-openapi.yml](openapi/telefonica-kyc-match-openapi.yml) | KYC Match - validate identity data against carrier records |
| [telefonica-location-verification-openapi.yml](openapi/telefonica-location-verification-openapi.yml) | Location Verification - verify device geographic presence |
| [telefonica-quality-on-demand-openapi.yml](openapi/telefonica-quality-on-demand-openapi.yml) | Quality on Demand - create and manage QoS sessions |
| [telefonica-device-roaming-openapi.yml](openapi/telefonica-device-roaming-openapi.yml) | Device Roaming Status - check roaming status |

### JSON Schemas

| File | Description |
|---|---|
| [telefonica-device-schema.json](json-schema/telefonica-device-schema.json) | CAMARA Device identifier schema (used across all APIs) |
| [telefonica-qod-session-schema.json](json-schema/telefonica-qod-session-schema.json) | Quality on Demand session schema |

### JSON Structure

| File | Description |
|---|---|
| [telefonica-device-structure.json](json-structure/telefonica-device-structure.json) | Field documentation for CAMARA Device object |

### JSON-LD Context

| File | Description |
|---|---|
| [telefonica-context.jsonld](json-ld/telefonica-context.jsonld) | Linked data context mapping CAMARA terms to schema.org |

### Examples

| File | Description |
|---|---|
| [telefonica-number-verification-example.json](examples/telefonica-number-verification-example.json) | Number verification request/response |
| [telefonica-sim-swap-check-example.json](examples/telefonica-sim-swap-check-example.json) | SIM swap check request/response |
| [telefonica-location-verification-example.json](examples/telefonica-location-verification-example.json) | Location verification request/response |
| [telefonica-kyc-match-example.json](examples/telefonica-kyc-match-example.json) | KYC match request/response |

### Spectral Rules

| File | Description |
|---|---|
| [telefonica-rules.yml](rules/telefonica-rules.yml) | Spectral ruleset for Telefónica CAMARA API conventions |

### Naftiko Capabilities

| File | Description |
|---|---|
| [capabilities/fraud-prevention.yaml](capabilities/fraud-prevention.yaml) | Fraud prevention - Number Verification + SIM Swap + KYC + Location (6 MCP tools) |
| [capabilities/network-quality-management.yaml](capabilities/network-quality-management.yaml) | Network quality management - QoD sessions (4 MCP tools) |
| [capabilities/shared/number-verification.yaml](capabilities/shared/number-verification.yaml) | Shared Number Verification API definition |
| [capabilities/shared/sim-swap.yaml](capabilities/shared/sim-swap.yaml) | Shared SIM Swap API definition |
| [capabilities/shared/kyc-match.yaml](capabilities/shared/kyc-match.yaml) | Shared KYC Match API definition |
| [capabilities/shared/location-verification.yaml](capabilities/shared/location-verification.yaml) | Shared Location Verification API definition |
| [capabilities/shared/quality-on-demand.yaml](capabilities/shared/quality-on-demand.yaml) | Shared Quality on Demand API definition |

### Vocabulary

| File | Description |
|---|---|
| [telefonica-vocabulary.yml](vocabulary/telefonica-vocabulary.yml) | Domain vocabulary for Telefónica Open Gateway and CAMARA standards |

## Common Properties

- [Open Gateway Portal](https://opengateway.telefonica.com/en)
- [Developer Hub](https://opengateway.telefonica.com/en/developer-hub)
- [Technical Documentation](https://developers.opengateway.telefonica.com/docs/initiative)
- [APIs Catalog](https://opengateway.telefonica.com/en/apis)
- [GitHub](https://github.com/Telefonica)
- [CAMARA Project](https://github.com/camaraproject)
- [Developer Hub Signup](https://opengateway.telefonica.com/en/developer-hub/join)
- [LinkedIn](https://www.linkedin.com/company/telefonica)
- [X](https://x.com/Telefonica)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
