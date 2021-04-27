# Using Artificial Intelligence to Automate Product Identification on Beef Boning Lines

This repository contains the models implemented in the paper "Using Artificial Intelligence to Automate Product Identification on Beef Boning Lines". The experimentation have been performed on the dataset collected by DATAS (Deductive Analytics for Tomorrows Agri Sector) and sponsored by Science Foundation Ireland.

## Dataset
The raw data can be found on [Zenodo](https://zenodo.org/record/4704391#.YH6pN-hKhPY). If you use the dataset, please cite us.

## Experiments
Download the pickle files from [here](https://drive.google.com/drive/folders/1mUXsuGZeMkACrbWEE_vcVECS1HlAI28y?usp=sharing) to run the experiment.

### Convolutional neural network (CNN)
#### With BW Images
For this experiment, use the pickle file X_BW.pickle and Y_BW.pickle with [CNN on BW images](https://github.com/SuzanneMcC/Vision_Detection_Meat_Cuts/blob/main/CNN_without_weights_BW.ipynb). Provide the directory of the pickle files in the code where X_BW.pickle and Y_BW.pickle have been used.
For example if the file is in the following directory: D:/User/X_BW.pickle, replace X_BW.pickle with D:\User\X_BW.pickle

#### With Colour Images
For this experiment, use the pickle file X_Color.pickle and Y_Color.pickle with [CNN on Colour images](https://github.com/SuzanneMcC/Vision_Detection_Meat_Cuts/blob/main/CNN_without_weights_color.ipynb). Provide the directory of the pickle files in the code where X_Colour.pickle and Y_Colour.pickle have been used.
For example if the file is in the following directory: D:/User/X_Colour.pickle, replace X_Colour.pickle with D:\User\X_Colour.pickle

### CNN mixed with Product Weights
#### With BW Images
For this experiment, use the pickle file X_BW.pickle, W_BW.pickle and Y_BW.pickle with [CNN Multiinputs (with weights) on BW images](https://github.com/SuzanneMcC/Vision_Detection_Meat_Cuts/blob/main/CNN_with_weights_BW.ipynb). Provide the directory of the pickle files in the code where X_BW.pickle and Y_BW.pickle have been used.
For example if the file is in the following directory: D:/User/X_BW.pickle, replace X_BW.pickle with D:\User\X_BW.pickle

#### With Colour Images
For this experiment, use the pickle file X_Colour.pickle, W_Colour.pickle and Y_Colour.pickle with [CNN Multiinputs (with weights) on Colour images](https://github.com/SuzanneMcC/Vision_Detection_Meat_Cuts/blob/main/CNN_with_weights_Color.ipynb). Provide the directory of the pickle files in the code where X_Colour.pickle , W_Colour.pickle, and Y_Colour.pickle have been used.
For example if the file is in the following directory: D:/User/X_Colour.pickle, replace X_Colour.pickle with D:\User\X_Colour.pickle

### Ensemble Approach with Product Weights
#### Multinomial Logistic Regression and Decision Tree Classifier
For this experiment, use the [CSV](https://github.com/SuzanneMcC/Vision_Detection_Meat_Cuts/blob/main/F_names.csv) file by changing the directory in 'df = pd.read_csv('/content/drive/My Drive/Practicum: Identifying meat cut using Ensemble techniques/F_names.csv')'

#### With BW Images
For this experiment, use the [CSV](https://github.com/SuzanneMcC/Vision_Detection_Meat_Cuts/blob/main/MeatCutPredictions.csv) file by changing the directory in 'E:/Meat_Excels/MeatCutPredictions.csv'

#### With Colour Images
For this experiment, use the [CSV](https://github.com/SuzanneMcC/Vision_Detection_Meat_Cuts/blob/main/MeatCutPredictions.csv) file by changing the directory in 'E:/Meat_Excels/MeatCutPredictions.csv'

### Transfer Learning (ResNet 34)
#### With BW Images
Download the data from [here](https://drive.google.com/drive/folders/13Strpxx5_SgADUR642MmzMDFZvThaFDh?usp=sharing) to be used with this experiment. Change the directory for 'data1' and 'data2' variables. 'data1' is for training and data2 is for testing purpose. (It is recommended to use this notebook in Google Colab)

#### With Colour Images
Download the data from [here](https://drive.google.com/drive/folders/1CURLQUe3oxBOD_J5x2uuXLwwj9SoDhZZ?usp=sharing) to be used with this experiment. Change the directory for 'data1' and 'data2' variables. 'data1' is for training and data2 is for testing purpose. (It is recommended to use this notebook in Google Colab)
