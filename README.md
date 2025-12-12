## Malicious URL Detection - CS549 Final Project

Team Members: Jianna Gapuz, Abigail Dupaya, James Duong, Bahnam Bahnam

This project provides scripts for preprocessing and feature engineering a dataset of malicious and legitimate URLs, which is then used to train and evaluate four machine learning classification models: SVM, Random Forest, CNN, and AdaBoost.

### Data Preprocessing Instructions

To generate the annotated URL dataset, go to the ```/data preprocessing``` folder and run all cells in the ```preprocessing.ipynb``` file. 

This generates the feature engineered and cleaned dataset named ```processed_urls.csv```, which saves directly into the root folder of the project for ease of access for the other models. 

### Training and Testing the Individual Models

All four models, SVM, Random Forest, CNN, and AdaBoost, are in the root folder of the project.

To run each model, simply go to the individual .ipynb files and run all cells. This trains and tests the models as well as provides evaluation metrics at the end.

*Note: some of the models may take >10 minutes to train*

### Testing Environment

The experiments were run on a 64-bit Windows machine with an Intel N100 CPU, 16 GB of RAM, using Python 3.10