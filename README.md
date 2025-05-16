# Analyzing movements of honeybees in tracked data
Project focusing on the mean squared displacement of honeybee movement, made in collaboration with mentor Danielle Chase for the 2024-25 STEM Routes Uplift Program at the University of Colorado Boulder.
***
This project uses data found in the paper "Markerless tracking of an entire honey bee colony" (Bozek et al, 2021). This data can be found at https://zenodo.org/records/4507648, with this code using the files titled S1-S5.tgz. The data folder must be on the same directory level as the "/code" folder. 

#### Notes:
- There are many different image folders; all the mean squared displacement images that are up-to-date can be found in "/msd_images." Any other mean square displacement images are from previous code tests and are not as relevant as the ones found in /msd_images. 
- Inside of "msd_code.ipynb", there is code to load a .pkl file titles "all_msd_curves.pkl" from the folder "/modified_data." If this is the first time running, all the code and calculations for the mean squared displacement must be ran for the first time. More details in msd_code.ipynb.
