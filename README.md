# AtmosphericCorrection
# RemoteSensing
Introduction 
This README file provides instructions for completing atmospheric corrections on Landsat 9 satellite data using a Python notebook. 
The tasks involve processing data to obtain RGB images, reflectance values, radiance, and brightness temperature.

Prerequisites
Before starting, ensure you have the following installed:

1. Visual Studio Code: Install Visual Studio Code and the following extensions: Jupyter and Python.
2. Python: Install Python from python.org.
3. Required Python Packages: Install the necessary packages using pip:

$ pip install matplotlib earthpy numpy scikit-image


Data
1. Notebook: Access the provided Python notebook 'AtmosphericCorrection.ipynb' on WueCampus under Exercise 1.
2. Download Data: Download the referenced data files 'Landsat9Data.zip' from the same location on WueCampus. A password may be required.


Getting Started
1. Open 'AtmosphericCorrection.ipynb' in Visual Studio Code and familiarize yourself with the code.
2. Follow the instructions provided in the notebook for each task.

Tasks Overview

Task 1.1: RGB Image 
Plot an RGB image using appropriate bands (2: blue, 3: green, 4: red).

Task 1.2: Reflectance 
Implement the dn_to_radiance function to convert numerical data from a single band into radiance at the top of the atmosphere.
Plot histograms for bands 1-7 in radiance.


Task 1.3: Radiance 
Implement the dn_to_reflectance function to convert numerical data from a single band into reflectance at the top of the atmosphere.
Plot bands 1-7 as images and the combined RGB image. Note down two interesting observations.

Task 1.4: Brightness Temperature 
Implement the dn_to_brightness_temperature function to convert the top of atmosphere brightness temperature from spectral radiance.
Plot bands 10 and 11 in TOA brightness temperature data as images.

Additional Resources
A guide on using Landsat Level-1 data and performing atmospheric correction can be found here.Link : https://www.usgs.gov/landsat-missions/using-usgs-landsat-level-1-data-product






