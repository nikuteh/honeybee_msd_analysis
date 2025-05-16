# Analyzing movements of honeybees in tracked data
Project focusing on the mean squared displacement of honeybee movement, made in collaboration with mentor Danielle Chase for the 2024-25 STEM Routes Uplift Program at the University of Colorado Boulder.
***
This project uses data found in the paper "Markerless tracking of an entire honey bee colony" (Bozek et al, 2021). This data can be found at https://zenodo.org/records/4507648. Download the files titled "S1-S5.tgz". Extract the contents from these folders, and ensure that the folder is on the same directory level as the "code" folder in this repository. 

## Python Packages Setup:
### Using Anaconda: 
conda env create -f environment.yml

conda activate peleglab_msd_analysis

### Using pip:
1. Create a virtual environment:

python -m venv venv  # or python3 -m venv venv

cd venv

source bin/activate  # On macOS and Linux. Use `venv\Scripts\activate` on Windows

2. Install the packages:

pip install -r requirements.txt

***

## Notes:
- There are many different image folders; all the mean squared displacement images that are up-to-date can be found in "/msd_images." Any other mean square displacement images are from previous code tests and are not as relevant as the ones found in /msd_images. All images found from "honeybee_analysis.ipynb" are found in the folder "/plotted_images."  
- Inside of "msd_code.ipynb", there is code to load a .pkl file titles "all_msd_curves.pkl" from the folder "/modified_data." If this is the first time running, all the code and calculations for the mean squared displacement must be ran for the first time. More details in msd_code.ipynb.
