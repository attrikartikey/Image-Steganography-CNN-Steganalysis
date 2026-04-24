# 🕵️ Image Steganography & CNN Steganalysis

> **Hiding data. Detecting deception. End-to-end pipeline.**

A complete implementation of spatial-domain image steganography and deep learning-based steganalysis — from embedding secret payloads into pixels to training a CNN that catches them.

---

## 📌 Overview

This project implements the full steganography lifecycle across three phases:

| Phase | Description |
|-------|-------------|
| **1 — Steganography** | Embed secret ASCII text into grayscale images using sequential LSB substitution |
| **2 — Steganalysis** | Train a CNN binary classifier to detect hidden payloads from statistical image properties |
| **3 — Visualisation** | Forensic-grade 9-plot diagnostic suite to quantify and interpret embedding footprints |


---

## 🎯 Results at a Glance

| Metric | Value |
|--------|-------|
| PSNR (embedding quality) | **> 50 dB** — imperceptible to the human eye |
| MSE per pixel | **< 0.5** — near-zero distortion |
| Extraction fidelity | **100%** — perfect round-trip recovery |
| CNN detection accuracy | **~97%** — clean vs. stego classification |
| Training duration | 5 epochs on Google Colab |

---

## 🛠️ Tech Stack

- **Language:** Python 3.10
- **Deep Learning:** TensorFlow 2.x / Keras
- **Image Processing:** OpenCV
- **Data & Math:** NumPy, Pandas
- **Visualisation:** Matplotlib
- **Runtime:** Google Colab
- **Storage:** Google Drive

---

