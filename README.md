# Market Risk Analysis Project (2025-2026)

Applied quantitative finance models to analyze market risk across multiple financial datasets and time scales.


## Academic Context
**Program:** ESILV  
**Course:** Market Risk  
**School:** ESILV  
**Year:** 2025-2026  
**Coordinator:** Matthieu Garcin  
**Professor:** Nicolas Pesci  


## Authors
- Matthieu HANNA GERGUIS  
- Renaud DE L'EPINE  

---

## Project Overview
This repository contains our work for the **Market Risk** module at ESILV.  
The goal is to implement and compare several market-risk and microstructure tools, ranging from **distribution-based risk measures** to **tail modeling**, **price impact**, and **multi-scale analysis**.

**Keywords:** VaR, Expected Shortfall, EVT, Pickands estimator, Bouchaud model, price impact, wavelets, Hurst exponent.

Main objectives:
- estimate and interpret risk measures (VaR / ES)
- characterize tail behavior with EVT
- quantify intraday price impact from trade information
- analyze correlation/volatility across scales (wavelets, Hurst)

---

## Models & Parts
The project is divided into four main parts:

1. Historical VaR & Expected Shortfall (ES)
- Estimated Value-at-Risk for Natixis stock using a **non-parametric biweight kernel** approach
- Computed **Expected Shortfall** to evaluate average losses in extreme scenarios

2. Extreme Value Theory (EVT)
- Studied extreme gains/losses and tail behavior
- Used the **Pickands estimator** to characterize tail heaviness

3. Bouchaud Price Impact Model
- Used intraday variables such as **trade signs** and **volume**
- Estimated how trades move prices through an impact framework

4. Wavelets & Hurst Exponent
- Applied **Haar wavelets** to study FX rate correlations across multiple time scales
- Computed the **Hurst exponent** to analyze volatility scaling / persistence

---

## Data
The repository includes multiple raw datasets used across the different parts.

Data files (examples):
- `Natixis_stock.txt`
- `Dataset_TD4.xlsx`
- `Dataset_TD5.xlsx`

Notes:
- Raw files are kept in `data/`
- All transformations and computations are performed in the notebook(s)

---

## Repository Structure
```bash
.
├── data/              # Raw source files (Natixis_stock.txt, Dataset_TD4.xlsx, Dataset_TD5.xlsx)
├── notebook/          # Jupyter Notebook(s): code + calculations + figures
├── report/            # Final PDF report (methodology + results)
└── screen_report/     # Visuals and charts used for project documentation
