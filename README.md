# Adaverse-Security-Labs

Enterprise cybersecurity infrastructure, PKI, IAM, cloud security, and security engineering labs built under the Adaverse ecosystem.

---

## Overview

This repository contains hands-on cybersecurity labs focused on building and understanding real-world security systems used in enterprise and government environments.

The goal is to move beyond theory and simulate actual security infrastructure components, including identity systems, certificate authorities, and network security controls.

---

## Focus Areas

- Public Key Infrastructure (PKI)
- Identity and Access Management (IAM)
- Certificate Authorities (Root & Intermediate)
- Secure Communications & Trust Chains
- Network Security Fundamentals
- Linux Security & Hardening (future labs)
- Cloud Security Concepts (future labs)

---

## Current Lab: PKI Certificate Hierarchy

### What was built

A fully functioning two-tier PKI system using OpenSSL:

- Root Certificate Authority (offline trust anchor)
- Intermediate Certificate Authority (issuing authority)
- End-entity/user certificate issuance
- Certificate trust chain validation

### Key Concepts Demonstrated

- RSA key generation (4096-bit Root CA)
- Self-signed Root CA creation
- Intermediate CA signing workflow
- Certificate Signing Requests (CSR)
- Certificate chain verification

---

## Architecture

```text
Adaverse Root CA (Trust Anchor)
        ↓
Adaverse Intermediate CA (Issuing Authority)
        ↓
End-Entity / User Certificates
