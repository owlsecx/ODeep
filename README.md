# 🧠 ODeep

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OForensics%20%2F%20Advanced%20Forensics-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-Optional%20(python-magic%2C%20Pillow)-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **ODeep** is an advanced digital forensics toolkit. It combines file carving, hex inspection, entropy mapping, regex searching, timeline analysis, steganography detection, and basic memory forensics in one powerful interface.

---

## 📌 Overview

ODeepForensics provides deep analysis capabilities for suspicious files, disk images, memory dumps, and raw binary data. It helps investigators uncover hidden content, detect steganography, map entropy anomalies, and build evidence timelines.

**Optional dependencies**: `pip install python-magic Pillow`

---

## 🖥️ Modules

| # | Module                     | Description |
|---|----------------------------|-------------|
| **[1]** | **File Carving**           | Recover embedded files (JPEG, PNG, PDF, ZIP…) |
| **[2]** | **Hex Dump Viewer**        | Interactive hex/ASCII dump with offset support |
| **[3]** | **Entropy Map**            | Visualize file entropy to detect encrypted/hidden regions |
| **[4]** | **Regex Search**           | Advanced pattern search in binary data |
| **[5]** | **Timeline Analysis**      | Extract file system timestamps |
| **[6]** | **Steganography Detect**   | LSB analysis on images |
| **[7]** | **Vol-like Memory**        | Basic strings + IOC extraction (IP, URL, Email…) |
| **[8]** | **Auto Deep Analyze**      | Run all advanced modules automatically |

---

## 📊 Key Features

- **Signature-based File Carving** — JPEG, PNG, PDF, ZIP and more
- **Hex Dump & Search** — Navigate binary data with offset control
- **Entropy Visualization** — Identify high-entropy (encrypted/packed) sections
- **Powerful Regex Search** — Find patterns, IPs, emails, credit cards, etc.
- **Steganography Detection** — LSB analysis on images using Pillow
- **Unified Timeline** — File creation/modification/access timestamps
- **Memory Forensics Style** — String extraction and IOC hunting
- **Full Reporting** — JSON and TXT export for every operation

---

## ⚙️ Requirements

- **Linux or Windows**
- **Optional**:
  - `pip install python-magic` (file type identification)
  - `pip install Pillow` (EXIF + Steganography detection)

---

## 🚀 Usage

```bash
./ODeep

📁 Output

Carved Files — Recovered files saved to carved/ directory
Entropy Maps — Visual entropy sections with high/low indicators
Hex Dumps — Detailed hex + ASCII output
JSON/TXT Reports — Complete results with timestamps and hashes
Steg Detection — LSB analysis results


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED FORENSIC ANALYSIS USE ONLY
