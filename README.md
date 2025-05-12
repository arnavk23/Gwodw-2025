# Gravitational Wave Open Data Workshop 2025

This repository contains my completed exercises and analysis from the **Gravitational Wave Open Data Workshop 2025**, using real and simulated data from the LIGO and Virgo observatories. The experience was not only technically enriching but also transformational in my understanding of signal processing, noise analysis, statistical inference, and the power of collaborative open science.

## Overview

Gravitational waves — ripples in spacetime caused by massive astrophysical events like binary black hole mergers — are detected by LIGO and Virgo using incredibly sensitive interferometers. This workshop focused on learning how to:
- Load and explore real gravitational wave data
- Identify gravitational-wave signals buried in noisy environments
- Use signal processing and statistical techniques to estimate merger properties
- Understand matched filtering and inference without black-box tools

## What I Learned

### Core Skills and Concepts
- **Time Series Analysis**: Visualizing and filtering strain data from LIGO detectors.
- **Spectrograms and Q-Transforms**: Locating gravitational wave signals in the time-frequency domain.
- **Matched Filtering**: Detecting known waveform templates in noisy data.
- **Power Spectral Density Estimation**: Using Welch's method to understand detector noise behavior.
- **Waveform Modeling**: Using approximants like `SEOBNRv4_opt` to simulate astrophysical events.
- **Parameter Estimation**: Estimating source masses and merger times using template matching.

### Libraries and Tools Explored

| Library         | Purpose                                                  |
|----------------|----------------------------------------------------------|
| `gwosc`        | Accessing open LIGO/Virgo datasets                       |
| `gwpy`         | Plotting, handling, and analyzing gravitational wave data|
| `pycbc`        | Core for matched filtering, PSD estimation, waveform generation |
| `numpy` / `matplotlib` | Fundamental Python stack for data analysis and plotting |
| `bilby` | Bayesian inference library (explored, not heavily used here) |

## Challenges Completed

Each challenge progressively explored real-world gravitational wave analysis:

1. **Challenge 1**: Identifying loud BBH signals in white Gaussian noise.
2. **Challenge 2**: Estimating merger times and SNR in colored Gaussian noise.
3. **Challenge 3**: Analyzing real LIGO data with embedded signals.
4. **Challenge 4**:
   - Identifying multiple events in real detector data
   - Filtering glitches and distinguishing them from real signals

## Why This Mattered to Me

Before this workshop, signal processing and gravitational physics seemed distant and abstract. But as I worked through the challenges:
- I **understood how ML pipelines for time-series data should be designed** when noise isn't IID and signals are buried deep.
- I **gained intuition for interpreting data beyond accuracy metrics** — learning to trust matched filter curves and PSDs instead.
- I learned how **Bayesian reasoning connects with physical modeling**, giving meaning to statistical outputs.
- I felt a deep appreciation for the **intersection of science and computation** — where open data, physics, and code come together.

## How This Helps

- **Noise-aware Thinking**: Not all noise is white. This changed how I approach denoising and anomaly detection in ML.
- **Bayesian Foundations**: Understanding posterior distributions gave me tools to better frame uncertainty in ML models.
- **Template Matching**: The concepts of waveform matching translate well to similarity-based learning and metric learning.
- **Scientific Rigor**: Every signal had to be statistically justified — no more "it looks good" models.
- **Real-world Constraints**: Working with real LIGO data showed me how messy, misaligned, and glitch-prone real signals can be.

## Final Thoughts

This workshop transformed my perspective. It wasn’t just about detecting gravitational waves — it was about **learning to listen through the noise**, in data and in life. I walked away with new skills, deeper curiosity, and a reinforced desire to build ML tools that are scientifically grounded, interpretable, and impactful.

Thanks to the LIGO Scientific Collaboration, Virgo Collaboration, and the amazing organizers of the Open Data Workshop 2025!

---
