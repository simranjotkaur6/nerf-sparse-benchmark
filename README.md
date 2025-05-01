# Benchmarking NeRF Variants on Sparse-View Reconstruction

This project benchmarks four NeRF variants under sparse-view (1–9 input views) conditions:

- **PixelNeRF** – CNN-based scene prior
- **SparseNeRF** – Depth ranking & smoothness constraints
- **S3-NeRF** – Reflectance fields from shading & shadow (single view)
- **ZeroRF** – Factorized NeRF with Deep Image Prior (no pretraining)

## 📊 Datasets & Metrics

- **Datasets**: NeRF Synthetic, DTU, NVS-RGBD
- **Metrics**: PSNR, SSIM, LPIPS, MAE

## 🔍 Highlights

- Side-by-side visual comparisons
- Quantitative results on standard benchmarks
- Proposed hybrid NeRF combining best components of all models

## 🌐 Visual Results

👉 View the full results and visualizations here:  
**[https://simranjotkaur6.github.io/nerf-sparse-benchmark/](https://simranjotkaur6.github.io/nerf-sparse-benchmark/)**

## 📚 References

1. [PixelNeRF](https://arxiv.org/abs/2012.02190)
2. [SparseNeRF](https://arxiv.org/abs/2311.10902)
3. [S3-NeRF](https://arxiv.org/abs/2305.07085)
4. [ZeroRF](https://arxiv.org/abs/2312.09249)

---
