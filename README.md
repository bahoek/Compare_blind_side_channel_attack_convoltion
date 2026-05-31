# 1D-CNN-Kyber-SCA: Unified Blind Side-Channel Analysis Framework targeting CRYSTALS-Kyber

This repository contains the official implementation and evaluation module for the paper: **"Enhancing Blind Profiled Side-Channel Analysis on CRYSTALS-Kyber via Modern 1D-CNN Architectures"**.

The framework delivers a systematic benchmarking pipeline across modern deep learning backbones under a rigorous, multi-dimensional variable isolation strategy using both public open-source profiles and locally measured synchronous high-fidelity configurations.

---

## 🛡️ Repository Structure & Intellectual Property (IP) Protection

To respect non-disclosure policies and safeguard proprietary research infrastructure (including target microcontroller firmware emulators, specific Barrett reduction models, and hardware-level fractional Montgomery multiplication pipelines), the raw data parsing layers have been decoupled. 

The dataset loaders provided herein are engineered to ingest **pre-compiled binary matrices** containing pre-synchronized traces and categorical 256-way direct coefficient mapping layers. This ensures 100% architectural reproducibility for neural network scaling and optimization metrics without exposing confidential infrastructure configurations.
