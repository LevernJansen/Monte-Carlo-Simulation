# Monte-Carlo-Simulation
Group assignment applying advanced econometric techniques in EViews/Stata: Koyck distributed-lag models, simultaneous-equation identification (Order Condition), 2SLS estimation of a beef-market system, and nonlinear least-squares via the Marquardt algorithm. Includes full derivations, regression output, and economic interpretation.
Full README Description
# AEM702S — Applied Econometric Modeling Portfolio

Coursework portfolio for **AEM702S: Applied Econometric Modeling** (BSc Applied Mathematics and Statistics, NUST). Contains applied econometrics projects using Python (pandas, statsmodels, matplotlib).

## Projects

### 1. Rainfall and Agricultural Output — Distributed Lag (Koyck)
Estimated a Koyck geometric distributed-lag model on 149 years of Namibian rainfall and agricultural output data. Derived short-run (0.050) and long-run (0.156) multipliers, decay rate (λ̂ = 0.683), and mean/median lags (2.15 / 1.82 years). Validated with autocorrelation tests, an IV estimate and a trend-augmented specification.

### 2. Namibian Beef Market — Simultaneous Equations
Specified a structural demand-and-supply model, checked identification via the order condition (demand overidentified, supply exactly identified), estimated reduced-form equations by OLS, and recovered structural parameters using ILS (supply) and 2SLS (demand).

### 3. Determinants of Livestock Income — OLS & Monte Carlo
Analysed drivers of smallholder livestock income using OLS grounded in economic theory, with a Monte Carlo simulation to examine estimator properties.

## Methods

OLS · IV · 2SLS · ILS · distributed-lag models · Koyck transformation · identification · time-series diagnostics · Monte Carlo simulation

## Structure

## Authors — Group 5

Jansen Levern (221093877) · Kuiri Kandorozu (221104461) · Victoria Nakaleke (222101180) · Martin Shaanika (223032425) · Adriaan Haraseb (223045691)

## Requirements & Usage

```bash
pip install pandas numpy statsmodels matplotlib scipy
python Q1_distributed_lag/koyck_model.py
python Q3_beef_market/structural_estimation.py

