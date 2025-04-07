# SpecRNet Implementation for Audio Deepfake Detection

## Overview
SpecRNet is a lightweight neural network architecture designed for efficient and accurate detection of audio deepfakes. It balances computational efficiency with high detection accuracy, making it suitable for both real-time applications and resource-constrained environments. SpecRNet achieves performance comparable to leading models like LCNN while reducing processing time per audio sample by up to 40%.

This repository provides the implementation of SpecRNet, including its model architecture, training scripts, and evaluation benchmarks.

---

## Features
- **Lightweight Architecture**: Optimized for low computational requirements without sacrificing accuracy.
- **Fast Inference**: Reduces processing time by up to 40% compared to LCNN.
- **High Accuracy**: Achieves state-of-the-art results on audio deepfake detection benchmarks.
- **Accessibility**: Suitable for deployment on personal devices and online multimedia platforms.

---

### Dependencies:
- Python 3.8+
- PyTorch
- Torchaudio
- NumPy
- Pandas
- tqdm
- Librosa
- os

## Installation

Install the required dependencies manually, making sure you are using **Python 3.8 or above**:

```bash
pip install torch torchaudio librosa numpy pandas tqdm
```

## Dataset
SpecRNet is evaluated on the **ASVspoof 2019 Logical Access (LA)** dataset. You can download the dataset from [ASVspoof's official website](https://www.asvspoof.org/). This database has been used since it is a detailed deepfake classification dataset which been extensively benchmarked for various models, allowing for reliable comparsions between models.

## Environment

The entire implementation was performed through a Kaggle Notebook, using NVIDIA Tesla GPU P100 Accelerator.