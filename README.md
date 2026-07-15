# XPS Analysis of Boronic Polymer-Modified Surfaces using Python

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dframosbal/xps-boronic-polymer-analysis/blob/main/notebooks/XPS_boro_analysis.ipynb)

This repository presents a Python-based workflow for the analysis of X-ray Photoelectron Spectroscopy (XPS) data obtained from a boronic polymer-modified surface.

The project demonstrates how to process, calibrate, fit and visualize experimental XPS spectra using Python.

## Project overview

The workflow includes:

- Importing `.xy` files exported from XPS software.
- Parsing survey and high-resolution XPS regions.
- Binding energy calibration using the C 1s signal at 284.8 eV.
- Shirley background correction.
- Peak deconvolution using Pseudo-Voigt functions.
- Extraction of binding energy, FWHM, relative area and goodness-of-fit parameters.
- Generation of publication-quality figures.

## Analyzed XPS regions

- Survey spectrum
- B 1s
- C 1s
- O 1s
- N 1s

## Tools and libraries

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- lmfit
- Google Colab

## Repository structure

```text
xps-boronic-polymer-analysis/
├── notebooks/
│   └── XPS_boro_analysis.ipynb
├── data/
│   └── example/
│       └── xps_boronic_polymer_example.xy
├── figures/
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

## Data availability

The XPS dataset included in this repository corresponds to an experimental replicate used for demonstration purposes. These data were not included in the author's thesis, publications or formal research outputs.

The dataset is provided only to illustrate a reproducible Python workflow for XPS preprocessing, calibration, background correction, peak fitting and visualization.

## How to run

Clone this repository and install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook notebooks/XPS_boro_analysis.ipynb
```

Alternatively, the notebook can be opened and executed in Google Colab.

## License

The source code in this repository is released under the MIT License.

The experimental XPS dataset is provided only for educational and demonstration purposes.

## Use of AI assistance

This repository was prepared with the assistance of ChatGPT for repository organization, README drafting and documentation improvement.

The experimental XPS data, scientific interpretation and Python analysis workflow were developed and reviewed by the author.

## Author

Danilo Ramos Balbontín
