# RNN for Time Series Prediction — Edge AI

RNN implementation for time series prediction using PyTorch — built as preparation for Edge AI research under supervision of Dr. Korkut Kaan Tokgöz.

## Overview

This project implements a 2-layer RNN that predicts the next value in a sine wave sequence — exploring the same temporal pattern recognition principles used in low-power Edge AI behavior monitoring systems. It serves as a foundation for resource-constrained deployment on FPGA-based edge devices.

## Results

| Metric | Value |
|--------|-------|
| Test MSE | 0.000681 |
| Training Epochs | 100 |
| Train/Test Split | 80/20 |

## Relevance to Edge AI Research

This work directly aligns with integer-only, resource-minimized RNN deployments on low-power hardware. The sine wave prediction task mirrors real-world low-frequency sensor behavior monitoring — a key challenge in FPGA-based Edge AI systems.

## Tech Stack

- Python
- PyTorch
- NumPy
- Matplotlib

## Inspired By

Tokgöz et al. (2023) — *"An Integer-Only Resource-Minimized RNN on FPGA for Low-Frequency Sensors in Edge-AI"*, IEEE Sensors Journal

## Author

**Hoor-Ain Rajput**  
Shaheed Benazir Bhutto University, Shaheed Benazirabad, Sindh, Pakistan  
24bsit124@student.sbbusba.edu.pk | hoorain.it.ai@gmail.com
