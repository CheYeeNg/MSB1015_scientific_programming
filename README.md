# Scientific Programming - MSB1015 
## (academic year: 2023-2024)

This repository contains a Python notebook with the code for my project in the Scientific Programming course. 

The data used for this project can be found at Kaggle (this was originally from a Kaggle competition): https://www.kaggle.com/competitions/amp-parkinsons-disease-progression-prediction/data

The used data files were:
- train_proteins.csv
- train_clinical_data.csv

Python version 3.10.12 was used with the following libraries to run the code:
- Pandas (version 2.0.0)
- NumPy (version 1.23.5)
- Matplotlib (version 3.7.1)
- Seaborn (version 0.12.2)
- TensorFlow (version v2.14.0)
- TensorFlow Decision Forests (version 1.6.0)

The "prediction_of_Parkinsons_disease_related_proteins.ipynb" notebook contains the code used for the project.

The other 8 .npy files contain the output for the ML part. As 2 models were trained (one to predict updrs_1 and the other updrs_2) 4 .npy files correspond to updrs_1 and 4 to updrs_2 (also indicated in the name of the files). These files are included so it is possible to recreate the figures used in the presentations (and without the need to retrain models). These .npy files will be loaded in the ML part in the "prediction_of_Parkinsons_disease_related_proteins.ipynb" notebook (make sure to put these 8 files in the same map as the notebook, otherwise change the path to the files).
