# Image Processing from Scratch

Jupyter notebooks that implement basic digital image-processing operations directly in NumPy, so you can see what built-in functions in MATLAB / OpenCV actually do. The code is written for clarity, not speed. Use library implementations for real work.

## Contents

| Notebook | Topics |
|---|---|
| [`basics/image_processing.ipynb`](basics/image_processing.ipynb) | Loading images, RGB channels, grayscale conversion (mean vs. luminance-weighted), histograms, thresholding, bit-depth reduction, channel swapping, cropping and binning, line profiles, edge padding, 1D box filter, 2D convolution and Gaussian blur |
| [`correlation/understanding_correlation.ipynb`](correlation/understanding_correlation.ipynb) | Template matching with normalised cross-correlation, in 1D and 2D (locating a Gaussian spot in a noisy image) |

Each notebook is split into numbered sections with a short explanation before every step.

## Running

Python 3 with `numpy` and `matplotlib`:

```bash
pip install numpy matplotlib jupyter
jupyter notebook
```

Open the notebooks from their own folders; the example image `basics/Sunflower-field-Fargo-North-Dakota.jpg` is loaded with a relative path. The 2D convolution cells in `basics/` loop over every pixel in pure Python and take a long time on the full image. Crop the image first if you want to experiment.

## Further reading

David Jacobs' notes on [filters and convolution](https://www.cs.umd.edu/~djacobs/CMSC426/Convolution.pdf) are an excellent companion to these notebooks.

---

Indranil Roy · PhD Candidate, SSCU, Indian Institute of Science · [Homepage](https://sites.google.com/iisc.ac.in/indranilroy)
