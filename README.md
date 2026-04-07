# Findelengletscher Geodetic Audit (2021–2024)

**Author:** Avinash Parla, M.Tech (IIT Bombay)  
**Affiliation:** Independent Researcher

## Abstract
This repository hosts the data and computational methodology for the geodetic assessment of Findelengletscher's volumetric collapse between 2021/22 and 2024. By utilizing sub-meter LiDAR DSMs and a pixel-wise PDD seasonality correction, this study identifies a state of terminal disequilibrium and a significant monitoring bias in traditional glaciological records.

## Key Technical Specifications
- **Geodetic Interval:** 2021/22 – Sept 2024
- **Spatial Resolution:** 0.5 m (TIN-interpolated LiDAR)
- **Specific Mass Balance:** -2.155 ± 0.440 m w.e. yr⁻¹
- **Geodetic ELA:** 3916 m a.s.l.
- **Methodological Discovery:** -1.036 m w.e. yr⁻¹ bias relative to glaciological stakes.

## Repository Contents
- `/data`: Hypsometric area distribution and specific mass balance tables.
- `/scripts`: PDD linear melt model ($Melt(z) = -0.000676z + 2.8227$) and Monte Carlo propagation scripts.
- `/figures`: Spatiotemporal thinning maps and SMB-Hypsometry plots.
- `/manuscript`: LaTeX source code and final compiled PDF.

## Citation
Parla, A. (2026). The Vanishing Accumulation Zone: Geodetic Evidence of Terminal Disequilibrium at Findelengletscher. *In preparation*.
