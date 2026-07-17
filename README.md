# Extreme Precipitation Analysis in Belgium

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)

This repository contains the data analysis pipeline for evaluating extreme precipitation in Belgium. It compares high-resolution CORDEX.be II climate models against historical observations.

The primary goal is to assess the performance of these models. This is achieved by analysing historical biases, spatial trends in precipitation, and modelling extreme events using Extreme Value Theory (EVT).

---

# Project Overview

## 1. Initial Setup

* Loading and preprocessing data

## 2. Exploratory Analysis

### Part 1: Missing Data

* Removing missing values and non-modelled years

### Part 2: Rainfall Analysis

* **Figure 1:** Monthly precipitation climatology
* **Figure 2:** Seasonal precipitation climatology
* **Figure 3:** Spatial Spearman correlation
* **Figure 4 & 5:** Number of wet days per year
* **Figure 6 & 7:** Simple Daily Intensity Index (SDII) time-series plot (Raw Values and Relative Bias)
* **Figure 8 & 9:** Simple Daily Intensity Index (SDII) seasonal time-series plot (Raw Values and Relative Bias)
* **Figure 10 & 11:** Simple Daily Intensity Index (SDII) pixel-wise map (Raw Values and Relative Bias)
* **Figure 12:** Probability Density Function (PDF) of wet-day rainfall

## 3. Extreme Rainfall Analysis

### Part 1: Plotting Extreme Values

* **Figure 13:** Monthly occurrence frequency of annual maxima
* **Figure 14:** Monthly mean intensity of annual maxima

### Part 2: Plotting Bias and Extreme Values

* **Figure 15 & 16:** Spatial maps of time-mean annual maxima (Raw Values and Relative Bias)
* **Figure 17 & 18:** Time-series of spatially averaged annual maxima areal precipitation (Raw Values and Relative Bias)
* **Table 1 & 2:** Overall aggregated annual maxima and annual maxima areal precipitation (Raw Values and Relative Bias)

### Part 3: Trends and Changes in Extreme Biases

* **Figure 19:** Pixel-wise annual maxima bias trends and change detection over time using a two-sample KS test
* **Figure 20:** Pixel-wise annual maxima bias trends and change detection over time using linear regression

### Part 4: Extreme Value Theory and Return Period Mapping

* **Figure 21 & 22:** Pixel-wise parametrization of Generalized Extreme Value (GEV) distributions for observations and models, alongside spatial mapping of return levels and return periods (2, 5, 10, 20, 30, 50, 100, and 200 years)

---

# Data

All data will be made publicly available on ... by ... .

---

# Contributing & Contact

A special thanks to Bert Van Schaeybroeck, Inne Vanderkelen (@Ivanderkelen), Hans Van de Vyver, and Kobe Vandelanotte (@kobebryant432) for the supervision and help throughout this project.

I maintain and take full responsibility for the code logic and implementation within this repository. Feel free to adapt, modify, or build upon any part of this repository with proper attribution.
