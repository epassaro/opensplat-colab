# opensplat-colab
Run OpenSplat on Google Colaboratory

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1USqQsIBcqdOP6Fy0aVAyoXzTdpaEoTL_)

## Usage
Paste and execute the following code at the begginning of your notebook:
```bash
# Install COLMAP and OpenSplat (~3min)
!curl -fsSL https://epassaro.github.io/opensplat-colab/install.sh | bash
```

## Runtime
This project continuously integrates the latest upstream changes from OpenSplat, ensuring compatibility with the latest version of Google Colaboratory.

| Component        | Version       |
|------------------|---------------|
| Ubuntu           | 22.04         |
| Python           | 3.11          |
| CUDA Toolkit     | 12.5          |
| GPUs             | T4, A100, L4  |
