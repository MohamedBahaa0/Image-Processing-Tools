# Image Processing Tools

A desktop GUI (Python + PyQt5) that implements classic image-processing and medical-imaging algorithms from scratch with NumPy, built during my Systems & Biomedical Engineering studies at Cairo University.

![Python](https://img.shields.io/badge/Python-3-blue) ![PyQt5](https://img.shields.io/badge/GUI-PyQt5-green) ![License](https://img.shields.io/badge/license-MIT-lightgrey)

## Features

| Area | Implemented |
|---|---|
| Geometry | Nearest-neighbour and bilinear interpolation (zoom), rotation, shearing |
| Intensity | Histogram and histogram equalization |
| Spatial filtering | Smoothing and sharpening filters, noise generation and median filtering |
| Frequency domain | Fourier transform, FFT filtering, notch-reject filter for periodic noise |
| ROI analysis | Select a region and inspect its noise statistics and histogram |
| Medical imaging | Shepp-Logan phantom, sinogram (Radon transform), laminogram / back-projection |
| Morphology | Erosion, dilation, opening, closing |
| Input | Standard images and DICOM files (pydicom) |

## Run

```bash
pip install pyqt5 numpy matplotlib pillow pydicom scikit-image phantominator
python Task9.py
```

## Tech stack

Python · PyQt5 · NumPy · Matplotlib · scikit-image · pydicom
