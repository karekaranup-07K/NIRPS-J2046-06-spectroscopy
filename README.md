# NIRPS High-Resolution Spectroscopy of EBLM J2046+06

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![ESO Data Product](https://img.shields.io/badge/ESO%20Archive-ADP.2025--07--31T08_21_26.491.fits-blue)](https://archive.eso.org/)

**Single-epoch near-infrared echelle spectrum (NIRPS/ESO 3.6m) of the eclipsing binary system EBLM J2046+06**, analyzed for radial velocity, chromospheric activity indicators, and companion constraints.

## Overview

This repository contains the complete analysis pipeline and derived results for the NIRPS science-grade spectrum of **EBLM J2046+06** (J2000: RA = 20h 46m 44.36s, Dec = +06° 18′ 14.2″), observed on 2025 July 30 (MJD 60886.246).

### Key scientific results

- **Confirmed identity**: Nearby eclipsing binary system (late-F/early-G primary + very low-mass M-dwarf companion) at ~200–400 pc (Gaia DR3).
- **Radial velocity** (barycentric, single epoch): **−204.5 km/s** (H-band cross-correlation function, highest S/N region 1500–1750 nm).
- **Chromospheric activity**: Mild and selective — weak emission in a metal line at ~1080.0 nm (local EW = −0.069 nm); normal photospheric absorption in Paschen γ (1094.0 nm, EW = +0.158 nm) and Paschen β (1282.0 nm, EW = +0.259 nm).
- **Companion detection**: No direct evidence of TiO/VO molecular bands in H-band; flux ratio upper limit < ~3–5%.
- **Data quality**: Median SNR = 11.7; H-band peaks > 100 per pixel after telluric masking and quality filtering.
- **High-redshift confusion**: Initial CCF peaks at z ≈ 0.1267–0.1394 were artifacts (sparse quasar template + telluric/stellar residuals) — definitively ruled out.

The analysis demonstrates the utility of NIR high-resolution spectroscopy for characterizing activity and kinematics in short-period low-mass binaries.

## Scientific background

**EBLM J2046+06** is part of the Eclipsing Binary Low-Mass (EBLM) survey, which targets detached eclipsing binaries with very low-mass companions initially misclassified as transiting planets. The system provides a benchmark for testing stellar evolution models of fully convective M-dwarfs and tidal interaction effects in short-period binaries.

Key published parameters (from EBLM series papers):
- Primary: T_eff ≈ 6300 K, log g ≈ 4.3, [Fe/H] ≈ 0.0, M ≈ 1.20 M_⊙
- Companion: M ≈ 0.20 M_⊙, R ≈ 0.22 R_⊙, T_eff ≈ 3200 K
- Orbital period: ~few days (precise value in ephemeris papers)
- Distance: ~200–400 pc (Gaia DR3 parallax)

## Citation

If you use data, code, plots, or derived values (RV, EWs) from this repository in a publication, please cite:

```bibtex
@misc{anup-nirps-eblm-j2046,
  author = {Anup},
  title = {NIRPS High-Resolution Spectroscopy of EBLM J2046+06},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/YOURUSERNAME/NIRPS-EBLM-J2046-analysis}},
}
```

Additionally acknowledge:
- ESO NIRPS data product: ADP.2025-07-31T08_21_26.491.fits (programme 115.27V0.001)
- Relevant EBLM publications (Swayne et al. 2021, MNRAS; Freckelton et al. 2024, A&A; etc.)

## License

MIT License — see the [LICENSE](LICENSE) file for details.

You are free to use, modify, and distribute this code and derived results, provided the original source is acknowledged.

## Contact

- **Author**: Anup
- **Location**: Kolhapur, India
- **Email**: karekaranup8@gmail.com

Last updated: February 16, 2026
