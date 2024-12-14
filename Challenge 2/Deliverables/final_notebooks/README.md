# ANNDL Second Homework
This file describes the structure of the notebooks submitted via the .zip file.

###  Preprocessing.ipynb
This notebook cleans and the original training set and produces as output a new dataset called `cleaned_dataset.npz`
### DoubleU-Net.ipynb
This notebook takes the `cleaned_dataset.npz`, splits the dataset into training and validation set and applies oversampling of the big rock class. It implements a Double U-Net with residual paths, SE blocks and ASPP. It is the best scoring model.
### DoubleU-Net with attention.ipynb
This notebook takes the `cleaned_dataset.npz`, splits the dataset into training and validation set and applies oversampling of the big rock class. It implements a Double U-Net with residual paths, SE blocks, ASPP and attention gates.
