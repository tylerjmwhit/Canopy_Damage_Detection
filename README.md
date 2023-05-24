# Canopy_Damage_Detection
This codebase is used to predict fire damage in sonoma county based on Naip Imagery

 - The segmented_dataset_classification contains all the code to run the segmentation side of the project
 - The helpfer functions file contain all of the models and helper functions used to generate the models
and display the results
 - The two PDF's are tutorials on how to generate the data chips in ARCgis and how to upload your predicitions back into ARCgis

The steps to set up this codebase are as follows:

1. Download the codebase
2. Set up your conda environment using the environment.yml file
3. Download the datasets by following the google drive link provied below
4. Optional - (Create your dataset referenceing the PDF "Creating fire datasets in ARCGIS")
5. After setting up your enviroment launch the segmented_dataset_classification.ipynb
6. Follow the intructions in this ipynb tutorial in order to perfrom the sgementation
7. Follow the instructions in the "Visualing predicitions in ARCgis" pdf in order export your predictions back into ARCgis
