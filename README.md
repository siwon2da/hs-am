# HSOO

HSOO is a next-generation encrypted visual code system built as an alternative to traditional QR structures.

Instead of using standard QR alignment and marker layouts, HSOO uses a custom deterministic `56x56` symbol grid with encrypted packet transport, Reed-Solomon recovery, and signed payload verification.

The project is designed for secure offline transport, custom visual encoding research, experimental machine-readable symbols, and future camera-based scanning systems.

---

# Features

- Custom non-QR visual code architecture
- Fixed `56x56` HSOO symbol matrix
- AES-256-GCM encrypted payloads
- HKDF-derived session keys
- Ed25519 packet signatures
- Reed-Solomon protected transport layer
- PNG rendering
- PDF export support
- Multi-image payload sequencing
- ZIP bundle support for large payloads
- CLI-first architecture
- PySide6 desktop UI prototype
- Deterministic decode pipeline for generated scans

---

# Project Goals

HSOO is intentionally designed as:

- A fully custom visual transport format
- A cryptographically authenticated image-code protocol
- A non-QR research platform
- A future-ready visual encoding system

Current development focuses on deterministic generation and decoding before real-world camera distortion support.

---

# Current Status

## Working

- Text encode/decode
- File encode/decode
- Image encode/decode
- Multi-part payload reconstruction
- ZIP archive decode support
- PNG generation
- PDF export
- Packet signing
- Payload encryption
- Deterministic clean-image decoding

## In Progress

- Camera distortion correction
- Perspective recovery
- Webcam scanning
- Mobile scan pipeline
- Adaptive symbol recovery
- Visual optimization system
- Production UI

---

# Installation
https://github.com/siwon2da/hs-am/issues/2   (다운로드)
## Windows

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -e .[dev]
https://github.com/siwon2da/hs-am/issues/2
