# Target Trial Emulation (TTE) in Python

This repository contains Python implementations of the **Target Trial Emulation (TTE)** process, originally outlined in the [RPubs article by Alan Yang](https://rpubs.com/alanyang0924/TTE). The repository includes two Jupyter Notebooks:
1. **[TTE.ipynb](TTE.ipynb)**: A direct translation of the R-based workflow into Python.
2. **[TTE-v2.ipynb](TTE-v2.ipynb)**: An extended version that integrates a **clustering mechanism** to identify subgroups and generate insights into treatment effects.

The dataset (`data_censored.csv`) is generated using the `generateData.R` script, which utilizes the `TargetTrialEmulation` library in R.

## Overview

The **Target Trial Emulation (TTE)** process involves emulating a randomized controlled trial (RCT) using observational data. This project translates the R-based workflow into Python and extends it by integrating a **clustering mechanism** to uncover heterogeneity in treatment effects across subgroups.

## Contributors 
- Angelo J. Pumar & Philip Isidro Go
