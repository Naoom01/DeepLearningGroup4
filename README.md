This Github repository consists of the data, models and the code used for the project of the Deep Learning course. 
The raw data can be found in the part3_adjusted folder. The images in this folder were split into 3 classes. The split dataset with adjused filenames can be found in the Classes folder. 
Data augmentation was applied using the already seperated images. Therefore, the augmented images can be found in the folder Classes_augmented2. 
The trained models are stored as .p files and can be found in its according folder. This allows for immediatley loading in the already trained model without
having to go through the entire model training proces again. 
Finally, the code can be found in DL_Models.ipynb. Note that before running this notebook, the paths should be changed according to your personal path structure. Furthermore, 
this particular notebook was used in Google Collab for the benefits of a free GPU. Therefore the file mounted to a drive path. If running the code locally, you can ignore the cell where
the path is mounted to your drive and replace base_dir with a regular path. 
