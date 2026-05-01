# Iran-Israel-War-Macro-Analysis

### Overview
This paper examines how macroeconomic regimes shape asset behavior, using the February 2026 Iran–Israel energy shock as a case study.

A regime detection framework is constructed using inflation, growth, interest rates, and volatility (VIX). These indicators are standardized to classify macro environments such as expansion, stagflation, and crisis. The analysis then evaluates how key asset classes—equities, bonds, commodities, and volatility—respond under stress conditions.

The study extends to sector-level dynamics and global equity markets, highlighting how shocks propagate unevenly across assets and geographies. The core insight is that market reactions are regime-dependent, leading to significant cross-asset and sectoral divergence during periods of stress.

### Research Document
The full white-paper version of this research is published on the research portfolio:
https://carpal-collarbone-066.notion.site/From-Shock-to-Dispersion-Macro-Regime-Response-to-the-2026-Iran-Israel-Energy-Shock-3272f2f4ff37805b8f1aca53ac85fc07 

The narrative version for a general audience is on Medium:


### Repository Structure
01_regime_detection      — macro data processing and regime classification  
02_cross_asset_analysis — asset normalization and shock response  
03_sector_analysis      — sector divergence and relative performance  
04_event_study          — event-centered analysis and zoomed windows  

### Data

#### Sources:

FRED (CPI, Industrial Production, 10Y Yields)
Yahoo Finance (SPY, GLD, TLT, USO, VIX, sector ETFs, global indices)

#### Coverage:

Macro regime data: 2005 – 2026
Asset-level analysis: 2021 – 2026
Event study window: February 2026 shock

Raw data is stored in /data/raw/ and remains unmodified.

### Dependencies

Python 3.10+
pandas · numpy · matplotlib · seaborn · yfinance · pandas-datareader · scipy
