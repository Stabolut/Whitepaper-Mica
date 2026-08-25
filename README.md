# Stabolut MiCA Whitepaper (ESB Token)

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](https://opensource.org/licenses/GPL-3.0)

This repository contains the LaTeX source code and regulatory compliance documentation for the **Stabolut European MiCA-Compliant Stablecoin (ESB Token)**.

---

## 📄 Read the Whitepaper

- 📥 **[Download / View Compiled PDF (main.pdf)](./main.pdf)**
- 📋 **[Read Stablecoin Regulation & Compliance Analysis (Markdown)](./StablecoinRegulation.md)**

---

## 🏛️ About ESB & Stabolut

Stabolut is a dual-stablecoin ecosystem designed to meet the diverse needs of the global digital economy:

- **ESB**: A Euro-pegged, **MiCA-compliant Asset-Referenced Token (ART)** designed specifically for European regulatory frameworks, backed by high-quality liquid reserves.
- **USB**: A US Dollar-pegged decentralized stablecoin for international markets, backed by crypto-hedging strategies.
- **SBL Token**: Governance token allowing the community to vote on risk parameters, treasury allocations, and protocol upgrades.

---

## 🛠️ Compiling from Source

To compile the LaTeX source into a PDF document:

### Prerequisites
Install a TeX distribution:
- **macOS**: MacTeX (`brew install --cask mactex`)
- **Ubuntu/Debian**: `sudo apt install texlive-full`
- **Windows**: [MiKTeX](https://miktex.org/) or TeX Live

### Compilation Command
```bash
pdflatex main.tex
```

---

## 📂 Repository Structure

- `main.tex`: Master LaTeX entrypoint.
- `general.tex`: LaTeX packages, typography, and styling configurations.
- `content/`: Individual chapters (Coverpage, Introduction, Chapters 2-6, Conclusion).
- `figure/`: Diagrams, flowcharts, and branding assets.
- `StablecoinRegulation.md`: Comprehensive regulatory reference document.

---

## 📄 License

This work is licensed under the **GNU General Public License v3.0** - see [LICENSE](LICENSE) for details.