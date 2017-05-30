# Dublin Openstreetmap Data Wrangling

This project is assessing the quality of the data for validity, accuracy, completeness, consistency and uniformity, to clean the OpenStreetMap data for a part of Dublin using MongoDB.

## Installation

### Installing Anaconda

Anaconda is available for Windows, Mac OS X, and Linux. You can find the installers and installation instructions at https://www.continuum.io/downloads. 

To avoid errors later, it's best to update all the packages in the default environment. Open the Anaconda Prompt application. In the prompt, run the following commands:

conda upgrade conda  
conda upgrade --all  
conda create -n py2 python=2  

### Installing Jupyter Notebook

By far the easiest way to install Jupyter is with Anaconda. Jupyter notebooks automatically come with the distribution. You'll be able to use notebooks from the default environment.

To install Jupyter notebooks in a conda environment, use 

conda install jupyter notebook