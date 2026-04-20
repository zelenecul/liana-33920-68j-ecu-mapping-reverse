# Suzuki Liana 33920-68J ECU Mapping (Reverse Engineered)

TunerPro XDF and ECU map definitions for Suzuki Liana 68J-series ECUs,
based on reverse engineering of stock firmware (base: 33920-68JC).

---

## 📌 Supported ECUs

This project targets the following ECU part numbers:

* 33920-68JA
* 33920-68JB
* 33920-68JC *(base definition)*
* 33920-68JD

> ⚠️ Note: All definitions are primarily based on analysis of the 68JC firmware.
> Other variants are assumed compatible but may require verification.

---

## 🔧 Features

* ✅ TunerPro XDF definitions
* ✅ Fuel maps (main / enrichment / corrections)
* ✅ Ignition timing maps
* ✅ Rev limiter / speed limiter
* ✅ Sensor-based corrections (IAT, coolant, etc.)
* ✅ Address mapping and table structures

---

## 🧠 Methodology

All data in this repository was obtained through reverse engineering using tools such as:

* Ghidra
* Manual disassembly analysis
* Cross-referencing ECU memory structures
* AI-assisted code analysis and interpretation

Maps and parameters were identified by:

* pattern recognition
* axis detection (RPM / load)
* correlation with engine behavior

---

## ⚠️ Disclaimer

This repository contains **only user-created content**:

* XDF definitions
* reverse engineering notes
* derived data structures

❗ **No original firmware, binaries, or proprietary code are included.**

All trademarks and copyrights belong to their respective owners, including
Suzuki and Denso.

---

## 🚗 Usage

1. Obtain your own ECU firmware dump
2. Open it in TunerPro
3. Load the provided XDF file
4. Modify maps as needed

> ⚠️ You are responsible for any modifications and their consequences.

---

## 🤝 Contributing

Contributions are welcome:

* map verification
* additional ECU variants
* bug fixes in XDF
* documentation improvements

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Notes

This project is intended for:

* educational purposes
* ECU reverse engineering research
* tuning support for legacy platforms

---
