# Using Artificial Intelligence to Automate Product Identification on Beef Boning Lines

This repository contains the models implemented in the paper "Using Artificial Intelligence to Automate Product Identification on Beef Boning Lines". The experimentation have been performed on the dataset collected by DATAS (Deductive Analytics for Tomorrows Agri Sector) and sponsored by Science Foundation Ireland.

## Dataset
The data can be found on [Zenodo](https://zenodo.org/record/4704391#.YH6pN-hKhPY)
If you use the dataset, please cite us.

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
For this experiment, use the pickle file X_Colour.pickle, W_Colour.pickle and Y_Colour.pickle with [CNN Multiinputs (with weights) on Colour images](https://github.com/SuzanneMcC/Vision_Detection_Meat_Cuts/blob/main/CNN_with_weights_Color.ipynb). Provide the directory of the pickle files in the code where X_BW.pickle and Y_BW.pickle have been used.
For example if the file is in the following directory: D:/User/X_BW.pickle, replace X_BW.pickle with D:\User\X_BW.pickle
### Ensemble Approach with Product Weights
#### Multinomial Logistic Regression and Decision Tree Classifier

#### With BW Images

#### With Colour Images

### Transfer Learning (ResNet 34)
#### With BW Images

#### With Colour Images
