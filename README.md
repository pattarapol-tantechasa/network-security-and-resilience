# Network Security & Resilience - Academic Reports

This repository contains academic reports submitted for **TNE30009 Network Security and Resilience** at Swinburne University of Technology (2025). The unit covers core security principles - from practical network hardening and cryptographic implementation to formal risk assessment and emerging post-quantum threats. Reports span both hands-on lab exercises and independent research. All practical work was carried out on virtual machines running Ubuntu, hosted via VMware.

---

## Table of Contents

- [Network Security \& Resilience - Academic Reports](#network-security--resilience---academic-reports)
  - [Table of Contents](#table-of-contents)
  - [Skills Demonstrated](#skills-demonstrated)
  - [Lab 3 - VPNs \& OpenVPN](#lab-3---vpns--openvpn)
  - [Lab 5 - Public Key Cryptography \& RSA](#lab-5---public-key-cryptography--rsa)
  - [Case Study - Risk Analysis for a LoRa Underground Mine Network](#case-study---risk-analysis-for-a-lora-underground-mine-network)
  - [Research Report - Quantum Computing \& Cryptography](#research-report---quantum-computing--cryptography)

---

## Skills Demonstrated

- Network security fundamentals - VPNs, encryption, tunnelling
- Hands-on Linux networking - OpenVPN, Wireshark, `ifconfig`, `scp`
- Cryptographic principles - RSA, AES, public/private key infrastructure
- Risk assessment - Delphi method, likelihood/impact scoring, policy design
- Research and technical writing on emerging security threats

---

## Lab 3 - VPNs & OpenVPN

Theoretical overview of VPN architecture followed by hands-on configuration of an encrypted tunnel between two Ubuntu VMs using OpenVPN. Traffic was captured and compared across the tunnel (`tun1`) and ethernet (`ens33`) interfaces using Wireshark to verify encryption in transit.

**Key concepts:** Tunnelling, IPSec, TLS, OpenVPN, Wireshark packet analysis

---

## Lab 5 - Public Key Cryptography & RSA

Mathematical introduction to RSA, covering key generation, modular arithmetic, and the role of prime factorisation in security. Practical exercise involved recovering a private key from a known public key and decrypting ciphertext using MATLAB.

**Key concepts:** RSA key generation, modular exponentiation, prime factorisation, MATLAB decryption

---

## Case Study - Risk Analysis for a LoRa Underground Mine Network

Structured risk assessment of a LoRa-based emergency communication system deployed in an underground mining environment. Threats were identified and prioritised using the Delphi method (likelihood × impact scoring), with security policies and implementation plans proposed for each risk.

**Key concepts:** Delphi method, risk scoring, AES-128, message authentication, rate limiting, security policy design

---

## Research Report - Quantum Computing & Cryptography

Research report examining the threat quantum computing poses to classical cryptography (RSA, ECC) and the pathway to post-quantum cryptography (PQC). Covers Shor's and Grover's algorithms, the NIST PQC standardisation process, lattice-based schemes, and hybrid migration strategies.

**Key concepts:** Shor's algorithm, Grover's algorithm, CRYSTALS-KYBER, CRYSTALS-Dilithium, HNDL attacks, NIST PQC standards





