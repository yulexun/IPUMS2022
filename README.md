# IPUMS2022

## Overview

This paper analyses the 2022 ACS data from IPUMS to answer the following questions:
1. How many respondents were there in each state (STATEICP) that had a doctoral degree as their highest educational attainment (EDUC)?
2. Given there were 391,171 Californian respondents, we use the ratio estimators approach of Laplace to estimate the total number of respondents in each state.

Then we compare the estimated values to the actual number of respondents in each state, and try to justify why they differ.

## File Structure

The repo is structured as:

- `paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper.
- `renv` contains the code for setting up the R environment

## Statement on LLM usage

No aspects of the code were written using any LLMs.
