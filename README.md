# Awesome-Device-Intelligence-Platform

## Top Device Intelligence Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Device Fingerprinting, Bot Detection & Fraud Signal Enrichment*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Device Intelligence**. These tools identify and risk-score devices interacting with web and mobile applications to detect fraud, account takeover, bot activity, and multi-accounting without relying on cookies or persistent identifiers.

**Examples** include Fingerprint, Castle, SEON, Telesign, ThreatMetrix (LexisNexis), iovation, Ekata, Prove, Incode Device Intelligence, and Socure Sigma (the category leaders).

**Open-source emphasis**: The open-source ecosystem for device intelligence is anchored by **TrustDevice** (battle-tested device fingerprinting SDKs for Android, iOS, and web), with strong coverage in browser fingerprinting libraries and behavioral analysis tools. Note that full commercial-grade device intelligence with consortium networks and real-time risk verdicts remains largely proprietary.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Fingerprint](https://fingerprint.com/)**
  Device intelligence platform providing stable visitor IDs and 60+ real-time signals for fraud prevention, personalization, and SMS pumping prevention . Provides native SDKs for Android, iOS, React Native, and Flutter . Offers no-code deployment via Cloudflare edge wizard and a low-code Rules Engine for if-this-then-that enforcement . Entry pricing at $99/month for 20K API calls with a free tier .

- **[Castle](https://castle.io/)**
  Device intelligence and fraud prevention platform with 99.5% fingerprinting accuracy and a 0.001% collision rate optimized for account security scenarios . Stealth fingerprinting technology bypasses ad blockers and privacy plugins for 100% coverage . Returns device fingerprint, user agent, IP geolocation, proxy/VPN/Tor status, carrier, and bot score (0-100) with 150ms API response time . Starting at $0 for 1,000 requests/month .

- **[SEON](https://seon.io/)**
  Full fraud prevention and AML compliance platform that wraps device intelligence in digital footprint enrichment, transaction monitoring, and KYC workflows . Detects emulators, VPNs, residential proxies, remote access tools, AI agents, and device farms by correlating behavioral patterns (typing, mouse movement) with device and network signals . Processes 15M+ fraud checks daily and has prevented $300B+ in attempted fraud . Clients include Wise, Plaid, and Revolut .

- **[Telesign](https://www.telesign.com/)**
  Phone-centric identity and fraud detection platform. The Score product receives a phone number and assigns a fraud risk score from 0 to 1000, with thresholds triggering action responses (block/allow) . PhoneID provides carrier, line type, and subscriber information for identity verification and risk assessment .

- **[ThreatMetrix (LexisNexis)](https://risk.lexisnexis.com/)**
  Enterprise device intelligence platform with SmartID (device attributes) and ExactID (persistent markers including cookies, Flash LSO, HTML5 storage) . Digital ID uses probabilistic matching with confidence scores (0-10000) to link events to identities . Personas system detects consistent attribute combinations over time windows (e.g., name+address seen 3+ times over 3 months) .

- **[iovation (TransUnion)](https://www.iovation.com/)**
  Device reputation service that exposes a computer's history of fraud and abuse without requiring personally identifiable information . Has performed 4B+ device reputation checks, manages 180M+ unique device reputations, and stops 11M+ fraudulent activities annually . Subscribers share a network of device reputations across multiple industries .

- **[Ekata](https://ekata.com/)**
  Identity verification API returning 70+ data signals from name, email, phone, address, and IP checks . Provides a Confidence Score derived from identity network patterns and machine learning . Checks include email-to-name match, address-to-name match, phone-to-name match, IP risk flag, and distance-to-address calculations .

- **[Prove](https://www.prove.com/)**
  Phone-Centric Identity™ platform that leverages mobile, telecom, and other signals for identity verification and fraud prevention . Uses phone line tenure, behavior (calls, texts, logins), change events (ports, SIM swaps), and velocity as high-depth, high-consistency signals correlated with digital trust . Provides a binary "possession" check via the mobile device as a "what you have" factor .

- **[Incode Device Intelligence](https://incode.com/)**
  Device intelligence module within Incode's identity verification platform. Fetches device info during onboarding including IP address, device type, geolocation, and a fingerprint hash generated from userAgent, webdriver, language, screen resolution, timezone, canvas, WebGL, adBlock detection, and touch support .

- **[Socure Sigma](https://www.socure.com/)**
  Identity fraud solution leveraging the Network Identity Graph connecting 2,800+ organizations to assess identity behavior across institutions, geographies, and timeframes . Entity Profiler fuses digital footprints and session intelligence with authoritative data for a persistent device ID . Captures 85% of fraud in the highest 3% of risky applications (vs. industry average 37%) and 89% in the highest 5% .

## Open-Source GitHub Projects

- **[TrustDevice-Android](https://github.com/trustdecision/trustdevice-android)**
  Leading open-source Android device fingerprinting SDK for accurate deviceID and risk identification, with 373+ stars . Kotlin-based with active maintenance . Part of the TrustDevice suite from TrustDecision .

- **[TrustDevice-JS](https://github.com/trustdecision/trustdevice-js)**
  Leading open-source browser device fingerprinting library for accurate deviceID and risk identification, with 259+ stars . JavaScript-based with 235KB size .

- **[TrustDevice-iOS](https://github.com/trustdecision/trustdevice-ios)**
  Leading open-source iOS device fingerprinting SDK for accurate deviceID and risk identification, with 216+ stars . Objective-C-based .

### Additional Strong Open-Source Options

- **Osquery** — Open-source agent for inspecting operating system internals across Windows, Linux, and macOS. Queries running processes, network sockets, logged-in users, and file system changes via SQL. Lightweight and scalable to hundreds of thousands of devices .
- **Fleet** — Open-source osquery manager providing a single source of truth for endpoint visibility at scale .

**Frameworks for building custom device intelligence solutions**: Combine **TrustDevice** SDKs for cross-platform device fingerprinting (Android, iOS, web) with **Osquery** for endpoint-level device inventory and threat hunting. Note that true commercial-grade device intelligence with consortium networks, real-time risk verdicts, and behavioral ML models remains primarily proprietary. Open-source stacks provide strong fingerprinting primitives and endpoint visibility foundations that require integration for complete fraud detection pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Device intelligence tools collect sensitive device and behavioral data. Self-hosted solutions require proper security hardening and compliance with data privacy regulations (GDPR, CCPA). Fraud prevention is recognized as a legitimate interest under GDPR Recital 47 .
- Fingerprinting accuracy varies by device type, browser privacy settings, and ad blocker usage. Commercial platforms provide consortium networks and real-time enrichment that open-source libraries cannot replicate.
- The open-source ecosystem provides strong fingerprinting primitives and endpoint visibility foundations, but consortium device reputation, behavioral ML models, and real-time risk verdicts remain primarily commercial offerings.

---

**Made for fraud prevention analysts, identity verification teams, risk engineers, and security architects.**
Let's make device intelligence more open, transparent, and privacy-respecting.
