# Extreme Precipitation Analysis in Belgium

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)

This repository contains the data analysis pipeline for evaluating extreme precipitation in Belgium. It compares high-resolution CORDEX.be II climate models against historical observations.

The primary goal is to assess the performance of these models. This is achieved by analysing historical biases, spatial trends in precipitation, and modelling extreme events using Extreme Value Theory (EVT).

---

# Project Overview

## 1. Initial Setup

* Loading + preprocessing data

## 2. Exploratory Analysis
### Part 1: Missing data

* Removing missing values and non-modelled years

### part 2: Rainfall

* **Figure 1:** Monthly precipitation climatology

* **Figure 2:** Seasonally precipitation climatology

* **Figure 3:** Spatial Spearman correlation

* **Figure 4 & 5:** Number of wet days per year

* **Figure 6 & 7:** Simple Daily Intensity Index (SDII) timeseries plot (Raw Values and Relative Bias)

* **Figure 8 & 9:** Simple Daily Intensity Index (SDII) seasonal timeseries plot (Raw Values and Relative Bias)

* **Figure 10 & 11:** Simple Daily Intensity Index (SDII) pixelwise map (Raw Values and Relative Bias)

* **Figure 12:** Probability Density Function of wet-day rainfall

## 3. Extreme Rainfall Analysis

### Part 1:  Plotting values extremes

* **Figure 13:** Monthly occurrence frequency of annual maxima
* **Figure 14:** Monthly mean intensity of annual maxima

### Part 2: Plotting bias + values extremes

* **Figure 15 & 16:** Spatial maps of time-mean annual maxima (Raw Values and Relative Bias)
* **Figure 17 & 18:** Timeseries of spatially-averaged annual maxima areal precipitation (Raw Values and Relative Bias)
* **Table 1 & 2:** Overall aggregated annual maxima and annual maxima areal precipitation (Raw Values and Relative Bias)

### Part 3: Plotting change bias extremes

* **Figure 19:** Pixelwise annual maxima bias trends and changes over time detection using two-Sample KS test
* **Figure 20:** Pixelwise annual maxima bias trends and changes over time detection using linear regression

### Part 4: Extreme Value Theory and Return Period Mapping

* **GEV Fitting:** Pixelwise parametrization of Generalized Extreme Value distributions for observations and models
* **Return Period Maps:** Spatial mapping of return levels and return periods (e.g., 10-year, 50-year, or 100-year events)

---

# Data

All data will be publicly available by ... on ... .

---

# Contributing & Contact
