# Astronomy course Python SU - lecturer Petya Yanchulova

This project utilizes astronomical data from FITS files to analyze and visualize stellar properties.
It includes generating color-magnitude diagrams (CMDs), spatial distribution plots, and histograms of stellar parameters such as age, mass, and distance.
The visualizations help in studying the characteristics and evolution of stars in a given dataset.

---

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Usage](#usage)
- [Testing](#testing)
- [Notes](#notes)

---

## Requirements

Make sure you have the following installed on your system:
- Python 3.8 or higher
- `pip` (Python package manager)
- The following Python libraries:
  - `numpy`
  - `matplotlib`
  - `astropy`
  - `notebook`
  - `jupyterlab`

You can install all the required dependencies using the provided `requirements.txt` file.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Leny73/astronomy-course.git

## Running the project

1.The project has a venv installed and main packages added to the astrocourse folder
2.cd python_su
3. Ensure you have the required FITS files in the project directory.
4.Launch Jupyter Notebook or JupyterLab

## Usage 
- The project generates plots and saves them as .png files in the project directory.
- Example outputs include:
- Color-magnitude diagrams
- Distance histograms
- Spatial distribution plots

## Testing
TBD

## Notes

- Ensure that the FITS files used in the project are correctly formatted and located in the project directory.
- If you encounter issues with missing dependencies, ensure you have installed all required libraries listed in requirements.txt.
