# Multi-Band Photometric Reduction of Messier 82 (M82)

Quantitative analysis of ionized gas outflows and minor-axis surface brightness profiles in the starburst galaxy M82 using archival Hubble Space Telescope (HST) imaging.

---

## 🔬 Scientific Context & Objectives
Messier 82 drives a powerful galactic superwind fueled by intense starburst activity in its core. This repository houses the photometric reduction pipeline designed to:
- Isolate minor-axis outflow filaments from underlying starlight continua.
- Extract calibrated surface brightness profiles across optical bands.
- Quantify radial flux decay rates to evaluate outflow expansion models.

---

## 🛠️ Methodology & Pipeline Workflow
1. **Data Ingestion:** Fetching calibrated archival FITS files from the Mikulski Archive for Space Telescopes (MAST).
2. **Astrometry & Bounding:** Aligning coordinates and defining polygonal apertures in [SAOImage DS9](https://github.com/).
3. **Photometric Reduction:** Executing background subtraction, flat-field correction, and flux calibration via custom Python scripts using `Astropy` and `NumPy`.

---

## 📊 Key Results & Visualizations
*Minor-axis flux profile and photometric reduction parameters.*
---

## 🚀 Getting Started / Reproduction
To run the analysis scripts locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/Kavya-Phy/m82-galactic-outflow.git](https://github.com/Kavya-Phy/m82-galactic-outflow.git)
   cd m82-galactic-outflow
