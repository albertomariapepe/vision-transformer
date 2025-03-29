# 🌦️ Vision Transformer for Weather Forecasting on 2D Grids

This is a sandbox notebook intended for experimentation, and demonstrates how to implement a **Vision Transformer (ViT)** architecture for **weather forecasting** using 2D grid-based meteorological data. Inspired by the spatial structure of satellite or reanalysis datasets (e.g., temperature, pressure, wind fields), we treat each grid as an image and leverage transformer-based architectures to learn temporal-spatial patterns.

## 🔍 Overview

- **Objective**: Predict future weather variables (e.g., temperature, precipitation) on a 2D spatial grid using historical sequences.
- **Data Format**: 2D arrays over time — can be synthetic, reanalysis (e.g., ERA5), or gridded satellite observations.
- **Model**: Vision Transformer (ViT) adapted for spatiotemporal forecasting.
- **Tasks**:
  - Visualizing sample weather snapshots
  - Splitting into train/test sequences
  - Implementing a simple ViT model
  - Study of failure cases

