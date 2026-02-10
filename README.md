# Digital Image Formation and Enhancement

This Jupyter notebook explores core concepts and practical applications of **digital image processing** using Python. It presents a structured workflow for manipulating digital imagery, enhancing visual quality, and analyzing image components through both mathematical and visual techniques.

---

## Features

### Image Formation and Enhancement
Demonstrates fundamental techniques for manipulating and improving digital images, including intensity transformations and contrast adjustments.

### White Balancing
Implements a `percentile_whitebalance` function to correct color imbalance by rescaling pixel intensities based on percentile thresholds of RGB channel histograms.

### Color Analysis
Provides tools for generating and interpreting color histograms, allowing visualization of the distribution of pixel intensities across Red, Green, and Blue channels.

### Visualization
Uses the `matplotlib` library to:
- Plot RGB color histograms  
- Display side-by-side comparisons of original and processed images  

---

## Prerequisites

This notebook is designed to run in a Python environment with the following libraries installed:

- `numpy`
- `matplotlib`
- `scikit-image` (`skimage`)
- `Pillow` (`PIL`) — optional, depending on image loading methods

### Installation

You can install the required dependencies using `pip`:

```bash
pip install numpy matplotlib scikit-image pillow
