# ANNDL First Homework
This file describes the structure of the notebooks submitted via the .zip file.

The order in which the notebooks should be read is the following:

 1. Preprocessing.ipynb
 2. DatasetSplitAugmentations.ipynb
 3. {DenseNet121/ConvNeXtBase/MobileNet}_TL_FT.ipynb

###  Preprocessing.ipynb
This notebook cleans and rebalances the original training set and produces as output a new dataset called `balanced_dataset.npz`
### DatasetSplitAugmentations.ipynb
This notebook takes the `balanced_dataset.npz`, splits the dataset into training set and validation set and applies some augmentations over them. The result (both training and validation set) is saved on the file `last_dataset.npz`
### {DenseNet121/ConvNeXtBase/MobileNet}_TL_FT.ipynb
This notebook takes `last_dataset.npz` and applies Transfer Learning & Fine Tuning over the three different pre-trained models specified by the name. Each of them produces a `.keras` and `model.py` which are compressed together and submitted to the platform.