# myanalysis

A small Python package for capturing SDR data and computing voltage and power spectra using Fourier transforms.

## Description

This package provides simple helper functions to:
- Capture data from an SDR using `ugradio`
- Compute the voltage spectrum via FFT
- Compute the power spectrum from the voltage spectrum

The code is a direct refactor of analysis scripts developed for an astronomy/SDR lab.

## Installation

From the project directory:
```bash
pip install git+https://github.com/Stormchasers10/analysistools.git