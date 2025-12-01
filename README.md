# PAMIS-ZT-WAN-PulseTrust
# PAMIS + ZT-WAN + PulseTrust

## Overview
This repository contains a defensive cybersecurity framework designed to prevent rogue Wi-Fi access, MITM attacks, and device impersonation in high-security environments.

- **PAMIS**: PHY-Assisted Multi-Identity Safeguard. Multi-layer attestation including environmental, cryptographic, RF, and anomaly checks.
- **ZT-WAN**: Zero-Trust WAN stack for routers, enforcing strong mTLS, signed policies, and live integrity checks.
- **PulseTrust**: Optional device biometrics/temperature/RF sensor to generate cryptographic keys for device identity validation.

## Purpose
- Preserve intellectual priority
- Provide a reference implementation and simulation environment
- Allow academic and professional collaboration without exposing production secrets

## Structure
- `src/`: Source code for each module
- `docs/`: Whitepapers, design documents, and ASCII diagrams
- `examples/`: Sample configuration and simulation data
- `package/`: OpenWrt overlay for building firmware
- `tests/`: Unit tests and simulation harnesses

## Contribution
Pull requests, issues, and forks are welcome for improving simulations, test harnesses, and documentation.

## License
MIT License (or whatever you choose)
All rights reserved. For review/educational purposes only.
