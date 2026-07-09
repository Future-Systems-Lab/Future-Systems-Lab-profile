<!-- Rights Reserved, Unlicensed -->

# Future Systems Lab

**SOVEREIGN by Design**

Decentralized infrastructure for sovereign data governance, with behavioral health as the proving ground.

**[evidence.futuresystemslab.io](https://evidence.futuresystemslab.io)** — public evidence portfolio documenting deployed contracts, system architecture, and independent verification.

---

## What FSL Is

A deployed multi-platform Web3 ecosystem built on wallet-signed consent:

- **EncryptHealth** — unified participant platform: therapeutic games, session attestation, encrypted journaling, consent-gated records
- **HypnoNeuro** — wellness-engagement platform organized around neurotransmitter systems
- **SovereignLedger** — on-chain governance and session attestation
- **AlchemistForge** — permissionless behavioral health engagement recording
- **NeuroBalance** — biosensor integration layer (scaffolded)

Four platforms deployed, one scaffolded. Nine smart contracts deployed and verified on Ethereum Sepolia testnet.

## Architecture

EIP-191 wallet-signed consent unifies authentication, informed consent, session authorization, and data attribution into a single cryptographic signature event. The system holds no protected health information written on-chain; it operates outside HIPAA regulatory scope by architectural design, not by compliance claim. Hybrid on-chain/off-chain data model. AlchemistForge entries are encrypted client-side (AES-256-GCM) under a wallet-signature-derived key before the on-chain call — the infrastructure operator holds no key and cannot read the stored ciphertext. Bilateral session encryption, in which keys derive via HKDF from both parties' signatures so neither can decrypt alone, is the Phase 5 doctoral contribution and is not deployed.

## Research

*EIP-191 Consent Architecture for Sovereign Behavioral Health Data Governance: A Hybrid On-Chain/Off-Chain Implementation* — manuscript prepared for Blockchain in Healthcare Today (BHTY), double-blind submission. Central research question: can wallet-signed bilateral consent serve as a defensible governance primitive for sovereign behavioral health data?

Proposed Doctor of Engineering applied project at Arizona State University.

## Intellectual Property

- **U.S. Provisional Patent No. 64/063,037** — filed May 2026, covering the single-signer EIP-191 wallet-signed consent architecture, zero-PHI constraint, and Sovereign Guide attestation model
- **U.S. Provisional Patent No. 64/106,748** — filed July 2026, covering the bilateral dual-signature consent protocol (EIP-191 + EIP-712) with HKDF session-key derivation
- **USPTO Trademark Serial No. 99533250** — "Future Systems Lab," Class 42, filed December 2025
- **USPTO Trademark Serial No. 99821948** — "Future Systems Lab," Class 35, filed May 2026

## Open-Source Contributions

| Repository | PR | Description | Status |
|---|---|---|---|
| [bcgov/aries-vcr](https://github.com/bcgov/aries-vcr/pull/811) | #811 | Healthcare verifiable-credential schema examples + validation | Merged |
| [openmrs/openmrs-module-fhir2](https://github.com/openmrs/openmrs-module-fhir2/pull/577) | #577 | FHIR CodeableConcept normalization utility + tests (Java) | Open |
| [openmrs/openmrs-contrib-fhir2-ig](https://github.com/openmrs/openmrs-contrib-fhir2-ig/pull/63) | #63 | macOS build documentation for FHIR2 IG | Open |

## Founder

**Margarita Montañez Davenport**, D.N.Psy., BCHN, CBHP

Weekly contributing author at [America Out Loud](https://www.americaoutloud.news/author/meg-montanez-davenport/)

future.systems.lab@proton.me · [futuresystemslab.io](https://futuresystemslab.io) · [LinkedIn](https://linkedin.com/in/margarita-montanez-davenport-680652226) · ORCID: [0009-0001-4536-3070](https://orcid.org/0009-0001-4536-3070)

[View Full CV](https://evidence.futuresystemslab.io/cv)
