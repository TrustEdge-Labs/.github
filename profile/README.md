<!--
Copyright (c) 2025 TRUSTEDGE LABS LLC
MPL-2.0: https://mozilla.org/MPL/2.0/
Project: trustedge — Privacy and trust at the edge.
GitHub: https://github.com/TrustEdge-Labs/trustedge
-->

## Mission Statement
"Building trustable edge AI and cryptographic infrastructure for secure data processing at the edge. Providing comprehensive solutions for data-agnostic encryption, digital receipts, and hardware-backed security."

## About Us

### Key Details
- **Location**: United States of America
- **Website**: https://trustedgelabs.com
- **Focus**: Trustable edge AI, cryptographic infrastructure, and privacy-preserving edge computing

### Technology Stack
- **Language**: Rust (stable) for memory safety and performance
- **Cryptography**: AES-256-GCM, Ed25519, PBKDF2, BLAKE3 with algorithm agility
- **Hardware**: YubiKey PIV operations, TPM support (planned)
- **Audio**: Cross-platform live capture (Linux/ALSA, Windows/WASAPI, macOS/CoreAudio)
- **Network**: Ed25519-based mutual authentication with session management
- **Web**: WebAssembly bindings for browser integration
- **Decentralized**: Pubky network adapter for decentralized key discovery

## Featured Project: trustedge

TrustEdge is a production-ready privacy-preserving edge computing platform that provides trustable edge AI with secure, data-agnostic encryption. Built as a comprehensive Rust workspace, TrustEdge enables secure processing of sensitive data at the edge while maintaining cryptographic guarantees.

### Core Capabilities

- **🔐 Data-Agnostic Encryption**: Envelope encryption for files, live audio, sensor data, or any binary stream
- **🧾 Digital Receipt System**: Cryptographically secure transferable receipts with ownership chains
- **🏗️ Universal Backend System**: Pluggable crypto operations (Software HSM, Keyring, YubiKey, TPM planned)
- **🎵 Live Audio Capture**: Real-time microphone input with configurable quality and cross-platform support
- **🌐 Network Operations**: Secure client-server communication with Ed25519 mutual authentication
- **🔑 Hardware Integration**: Full YubiKey PKCS#11 support with real hardware signing
- **⚡ Algorithm Agility**: Configurable cryptographic algorithms with forward compatibility
- **🌍 WebAssembly Support**: Browser integration for client-side cryptographic operations
- **🔗 Decentralized Integration**: Pubky network adapter for decentralized key discovery
- **🛡️ Memory Safety**: Proper key material cleanup with zeroization

### Project Architecture

TrustEdge is organized as a Cargo workspace with specialized crates:

**Core Infrastructure:**
- **trustedge-core**: Core cryptographic library and CLI tools with envelope encryption
- **trustedge-attestation**: Software attestation and provenance system with cryptographic "birth certificates"

**Specialized Systems:**
- **trustedge-receipts**: Digital receipt system with cryptographic ownership transfer
- **trustedge-wasm**: WebAssembly bindings for browser/Node.js integration
- **trustedge-pubky**: Clean Pubky network adapter for decentralized key discovery
- **trustedge-pubky-advanced**: Advanced Pubky integration with hybrid encryption

### Production Readiness

- **Version**: 0.2.0 with production-ready core features
- **Testing**: 109 comprehensive automated tests including security attack scenarios
- **Quality**: Comprehensive CI/CD with clippy, formatting, and security checks
- **Security**: Attack resistance testing for tampering, replay, and forgery scenarios
- **Performance**: <50MB RAM usage regardless of file size, >10MB/s encryption throughput
- **Compliance**: Memory safety with proper key zeroization and constant-time operations

### Commercial Positioning

**Open-Core Model:**
- MPL-2.0 licensed for open source use
- Commercial licenses available for enterprise customers
- Professional services and custom integrations
- Legal indemnification and warranty protection

**Enterprise Features:**
- Priority support with SLAs
- Advanced monitoring and compliance reporting
- TPM integration (planned)
- Custom backend implementations

## Vision Statement

TrustEdge Labs is developing a comprehensive "Trust-as-a-Service" platform that provides:

- **Verifiable Edge AI**: Cryptographically guaranteed AI processing at the edge
- **Secure Data Archiving**: Immutable audit trails with hardware-backed security
- **Universal Cryptographic Operations**: Cross-platform, cross-hardware crypto backends
- **Privacy-Preserving Computing**: Zero-knowledge operations with memory safety
- **Decentralized Trust**: Integration with decentralized key discovery networks

### Target Industries

- **Edge AI & IoT**: Secure sensor data processing and AI inference
- **Healthcare**: Privacy-preserving medical data processing
- **Financial Services**: Secure transaction processing and audit trails
- **Government & Defense**: High-assurance cryptographic operations
- **Media & Entertainment**: Secure content distribution and digital rights management

## Technology Approach

**Open-Core Philosophy:**
- Transparency through open source core components
- Enterprise features for commercial customers
- Community-driven development with professional support
- Standards-based cryptography with algorithm agility
- Cross-platform compatibility (Linux, Windows, macOS, Web)

## Call-to-Action

"Join TrustEdge Labs in building trustable edge AI and secure cryptographic infrastructure for the next generation of privacy-preserving applications."

## Repository Updates

### Primary Repository: `trustedge`
**Description**: Privacy and trust at the edge - Production-ready cryptographic platform for trustable edge AI with data-agnostic encryption, digital receipts, and hardware-backed security.

**Topics**: `rust`, `cryptography`, `privacy`, `edge-computing`, `yubikey`, `webassembly`, `edge-ai`, `digital-receipts`, `hardware-security`, `decentralized`

### Additional Repositories
- **`.github`**: Organization configuration and community health files

## Contact Information

- **Enterprise Inquiries**: enterprise@trustedgelabs.com
- **Security Issues**: security@trustedgelabs.com
- **General Development**: dev@trustedgelabs.com
- **Website**: https://trustedgelabs.com
- **Documentation**: https://docs.rs/trustedge-core

