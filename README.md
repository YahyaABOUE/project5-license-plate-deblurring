# Project 5 — License Plate Deblurring

Blind motion deblurring pipeline for license plates using 
Wiener filter and CNN-based PSF estimation.

## Results
| Method | PSNR | SSIM |
|---|---|---|
| Blurred + Noisy | 17.77 dB | 0.402 |
| Wiener CNN blind | 21.67 dB | 0.641 |
| Wiener True PSF | 23.31 dB | 0.727 |

## Setup
```bash
pip install numpy opencv-python matplotlib scikit-image scipy scikit-learn torch torchvision ipywidgets
```

## Run
Open `code/notebook.ipynb` and run all cells top to bottom.

## Dataset
Download from Kaggle (see data/README.txt) and extract into `data/archive/`.
