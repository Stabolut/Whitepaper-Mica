# Stabolut Whitepaper

This repository contains the LaTeX source code for the Stabolut Whitepaper, which details our innovative dual-stablecoin strategy.

## Latest Version

The latest version of the whitepaper is [Stabolut_WP_0.7.3.pdf](./Stabolut_WP_0.7.3.pdf).

## Abstract

Stabolut is pioneering a dual-stablecoin strategy to address the diverse needs of the global digital economy. Our ecosystem features two distinct stablecoins: ESB, a Euro-pegged, MiCA-compliant Asset-Referenced Token (ART) for the European market, and USB, a US Dollar-pegged, decentralized stablecoin for international markets.

The entire Stabolut ecosystem is governed by the SBL token. SBL holders have the power to vote on key parameters for both ESB and USB, including risk management, treasury allocation, and the implementation of new features. This ensures that the Stabolut protocol remains a community-driven and decentralized project.

This whitepaper provides a comprehensive overview of the Stabolut ecosystem, detailing the architecture, mechanisms, and tokenomics of ESB, USB, and SBL.

## Compiling the PDF

To compile the whitepaper into a PDF, you will need a LaTeX distribution (such as TeX Live, MiKTeX, or MacTeX). Once installed, you can compile the `main.tex` file using the following command:

```bash
pdflatex -jobname=Stabolut_WP_0.7.3 main.tex
```

This will generate a PDF named `Stabolut_WP_0.7.3.pdf`.

## Project Structure

- `main.tex`: The main LaTeX file.
- `general.tex`: Contains package imports and general settings.
- `content/`: Contains the individual chapters of the whitepaper.
- `figure/`: Contains the figures used in the whitepaper.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
