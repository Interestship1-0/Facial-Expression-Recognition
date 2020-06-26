# Facial-Expression-Recognition
#Branch for Gurinder

File- create_data.py: This script reads csv file and convert it to image data such that images are placed in their respective labeled folder

File- augment_data.py: This script applies some augmentation techniques like rotation, zoom in, zoom out, flip, crop etc to the images so that model can generalize better and to avoid overfitting.

File- train.ipynb: Model is trained using mini_xception architecture. Because of limited computation resources model is trained only with 60 epochs.

Accuracy: 0.62

File- epochs_056-val_accuracy_0.625.hdf5: This file stores weights of the trained model which is further used in real-time implementation of this project

