# Automatic Cleaning and Processing of X-Ray Diffraction Patterns

##Description

This project provides a Jupyter Notebook (automatic.ipynb) designed to automatically process, filter, and analyze X-ray diffraction (XRD) data. It reads raw diffraction data, applies a smoothing filter to reduce high-frequency noise, identifies the principal diffraction peak, and calculates both the experimental interplanar distance and the lattice deformation (strain) of the sample

##Features
1 Data Loading: Automatically imports two-column files
2 Data Smoothing: Applies a Savitzky-Golay filter to clean the signal
3 Peak Detection: Uses scipy.signal.find_peaks to identify the principal peak
4 Crystallographic Analysis:
    1 Calculates the experimental interplanar distance using Bragg's Law
    2 Computes the percentage of lattice deformation (Strain) compared to a theoretical reference, classifying it as Traction or Compression

