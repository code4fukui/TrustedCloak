# TrustedCloak

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A secure cloak management system with QR code-based verification.

## Demo
https://code4fukui.github.io/TrustedCloak/

## Features
- Generate unique QR codes for each cloak deposit
- Verify the authenticity of cloak deposits using digital signatures
- Reset public/private key pair for the system
- Store cloak deposit history in the browser's local storage

## Usage
1. Enter a cloak deposit number and click "Issue Deposit Certificate" to generate a QR code.
2. Scan the QR code using the built-in QR code reader to verify the deposit information.
3. The public key for the system is displayed and can be reset if needed.

## License
MIT License — see [LICENSE](LICENSE).