# 🦉 ODeep

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **ODeep** — Deep forensic analysis: carving, entropy, steg, overlay/polyglot and reporting

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

ODeep (ODeepForensics) is a digital forensics suite for deep file inspection. It combines carving, entropy mapping, string extraction, steganography hints, signature scanning, and reporting so investigators can triage unknown binaries and artefacts quickly. CLI quick modes support hashes, strings, entropy, and JSON output.

---

## ✨ Features

- File carving, hex viewing, and entropy mapping for unknown artefacts
- String extraction, regex search, and signature scanning
- Steganography detection hints and overlay/polyglot oriented checks
- EXIF/metadata, archive inspection, and timeline-oriented analysis
- Hash verification and auto deep-analyse of a target file
- Report generation with JSON/TXT/HTML export paths

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ODeep suspicious.bin
./ODeep suspicious.bin --hashes
./ODeep suspicious.bin --strings --entropy --json
./ODeep --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
