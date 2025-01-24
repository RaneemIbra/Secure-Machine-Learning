# Privacy-Preserving Biometric Identification with FHE

![FHE Illustration](https://miro.medium.com/v2/resize:fit:1400/1*K0qOBdS76QH3q4sV-fJqEg.png)

This project implements a privacy-preserving biometric identification system using Fully Homomorphic Encryption (FHE). It consists of three interconnected parts:

1. **Part A**: Precision impact analysis on biometric identification
2. **Part B**: Homomorphic similarity metric computation
3. **Part C**: End-to-end encrypted biometric identification

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8+ with pip
- CUDA-enabled GPU (Recommended)
- 8GB+ VRAM for full dataset processing
- LFW dataset directory in project root

### Installation
```bash
# Create and activate conda environment
conda create -n ppml python=3.8 -y
conda activate ppml

# Install core dependencies
pip install torch==1.10.2+cu113 torchvision==0.11.3+cu113 --extra-index-url https://download.pytorch.org/whl/cu113
pip install insightface==0.7.3 tenseal==0.3.15 pandas matplotlib scikit-learn opencv-python albumentations


# Install the dataset
https://www.kaggle.com/datasets/jessicali9530/lfw-dataset
### Root Directory
###  |
###  |-- Project_in_secure_ML.ipynb
###  |
###  |-- dataset/
###        |
###        |-- lfw-deepfunneled/
###             |
###             |-- ...people/


## After making all the installations, in order to run the code, just click on the run button near each cell, start from cell 1 to generate the embeddings and then move forward.