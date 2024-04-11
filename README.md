---
# Algonquin SAR Wetland Classification Project - GEOG 6550

## Description:
This project aims to classify wetlands within the Algonquin Provincial Park using Synthetic Aperture Radar (SAR) imagery. The classification is
performed using machine learning techniques, particularly Random Forest classifiers, to identify different types of wetlands within the study area.
The project includes various notebooks for data processing, image stacking, model training, and evaluation.

## Notebooks:

### 1. Algonquin SAR Random Forest Modeller.ipynb
- **Description:** This notebook contains the implementation of the Random Forest model for wetland classification using SAR data.
- **Usage:** Follow the instructions within the notebook to train and evaluate the model.

### 2. Covariate Image Stacker.ipynb
- **Description:** This notebook stacks the covariate images extracted from SAR and DEM datasets for model input.
- **Usage:** Execute the notebook to generate stacked covariate images.

### 3. DEM Processing.ipynb
- **Description:** This notebook processes the Digital Elevation Model (DEM) data for elevation, slope, and aspect extraction.
- **Usage:** Run the notebook to preprocess the DEM data.

### 4. RCM Image Mosaicing and Pre-Processing.ipynb
- **Description:** This notebook performs mosaicing and preprocessing of SAR imagery from the RCM platform.
- **Usage:** Execute the notebook to mosaic and preprocess RCM SAR images.

## Usage:
1. Clone the repository to your local machine.
2. Open the desired notebook using Jupyter Notebook or JupyterLab.
3. Follow the instructions within each notebook to execute the necessary data processing and model training steps.
4. Most of these scripts will probably require some minor tweaking to get running on your machine

## Contributors:
- Maciej Lizak

---
