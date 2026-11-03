# Image Processing from Scratch

Jupyter notebooks that implement basic digital image-processing operations directly in NumPy, so you can see what built-in functions in MATLAB / OpenCV actually do. The code is written for clarity, not speed. Use library implementations for real work.

## Contents

| Notebook | Topics |
|---|---|
| [`basics/image_processing.ipynb`](basics/image_processing.ipynb) | Loading images, grayscale conversion, thresholding / binarisation, cropping, line profiles, padding, box (mean) filters and Gaussian blur via 2D convolution |
| [`correlation/understanding_correlation.ipynb`](correlation/understanding_correlation.ipynb) | Template matching: estimating where a template occurs in an image using cross-correlation |

## Requirements

Python 3 with `numpy` and `matplotlib`:

```bash
pip install numpy matplotlib jupyter
jupyter notebook
```

## Further reading

David Jacobs' notes on [filters and convolution](https://www.cs.umd.edu/~djacobs/CMSC426/Convolution.pdf) are an excellent companion to these notebooks.

---

Indranil Roy · PhD Candidate, SSCU, Indian Institute of Science · [Homepage](https://sites.google.com/iisc.ac.in/indranilroy)
