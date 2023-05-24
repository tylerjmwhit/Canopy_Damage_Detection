# Canopy_Damage_Detection
This codebase is used to predict fire damage in sonoma county based on Naip Imagery

 - The segmented_dataset_classification contains all the code to train the models and use them to predict labels
 - The helpfer functions file contain all of the models and helper functions used to generate the models
and display the results
 - The two PDF's are tutorials on how to generate the data chips in ARCgis and how to upload your predicitions back into ARCgis
 - The google drive link contains two datasets that we can use
  - This first link is to the raw dataset before being split and exported as chips: https://drive.google.com/file/d/1JbsVUnGHv28yEldEwbH83Q4JJQ8qz7Sk/view?usp=share_link
  - This second link is the Naip imagery used to create our chips in comboination with the first link:
  https://drive.google.com/file/d/1XH2bZz0rY52VWy2C5h-NJ-MQ31W7tLdQ/view?usp=share_link
  -  the the dataset after it has already been seperated and transformed into chips:

The steps to set up this codebase are as follows:

1. Download the codebase
2. Set up your conda environment using the environment.yml file
3. Download the datasets by following the google drive link provied above
4. Optional - (Create your dataset referenceing the PDF "Creating fire datasets in ARCGIS")
5. After setting up your enviroment launch the segmented_dataset_classification.ipynb
6. Follow the intructions in this ipynb tutorial in order to perfrom the sgementation
7. Follow the instructions in the "Visualing predicitions in ARCgis" pdf in order export your predictions back into ARCgis
