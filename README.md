Market Risk Analysis Project (2025-2026)
This repository contains our work for the Market Risk module at ESILV. We applied quantitative finance models to analyze risk across different financial datasets and time scales.
+2

Project Overview
The project is divided into several parts based on different financial models:


Historical VaR and Expected Shortfall: We estimated the Value-at-Risk for Natixis stock using a non-parametric biweight kernel approach. We also calculated the Expected Shortfall to analyze average losses in extreme scenarios.
+4


Extreme Value Theory (EVT): we studied the behavior of extreme gains and losses using the Pickands estimator to understand tail behavior.
+1


Bouchaud Price Impact Model: We used intraday variables like trade signs and volume to estimate how trades move market prices.
+2


Wavelets and Hurst Exponent: We applied Haar wavelets to analyze FX rate correlations across different scales and used the Hurst exponent to study volatility scaling.
+2

Project Structure
The project is organized as follows:


data/: Contains raw source files, including Natixis_stock.txt, Dataset_TD4.xlsx, and Dataset_TD5.xlsx.
+2


notebook/: Includes the Jupyter Notebook containing all the code and calculations.


report/: Contains the final PDF report with our methodology and results.
+1

screen_report/: Contains visuals and charts used for the project documentation.

Authors

Matthieu HANNA GERGUIS 


Renaud DE L'EPINE 


Coordinator: Matthieu GARCIN Professor: Nicolas PESCI
