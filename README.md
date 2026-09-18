# The Data Portfolio — Big Mac Index Analysis

## Objective

This project examines global purchasing power parity (PPP) deviations using The Economist's Big Mac Index, quantifying currency over- and under-valuation across 57 countries from 2000 to 2026.

## Methodology

- Sourced the Big Mac Index dataset directly from The Economist's public GitHub repository, covering 45 time periods (2000-04 through 2026-07) and up to 57 countries, with 54 countries represented in the July 2024 cross-section
- Computed implied PPP exchange rates and derived valuation percentages relative to actual market exchange rates
- Classified the dataset's structural dimensions, distinguishing cross-sectional, time-series, and panel data components to guide appropriate analytical methods
- Conducted a missing data diagnosis, identifying Russia's exit from the dataset as Missing Not At Random (MNAR) given its association with sanctions-driven market withdrawal rather than random data loss
- Built visualizations to communicate findings: a bar chart ranking countries by valuation percentage, and a time series comparing currency valuation trends across the full sample period

## Key Findings

- **Switzerland** emerged as the most persistently overvalued currency in the dataset, trading at **+41.8%** above PPP-implied value in the July 2024 cross-section
- **Japan** showed sustained undervaluation, registering below PPP-implied value in every decade covered by the series — a pattern consistent with long-run structural currency dynamics rather than short-term volatility
