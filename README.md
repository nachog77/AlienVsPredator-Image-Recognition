# Visual Classification of Alien/Predator images using Keras

Contains the next subdirectories:

/data/: where the file alien_vs_predator_thumbnails.zip must be unzip. This file is obtained from Kaggle in https://www.kaggle.com/pmigdal/alien-vs-predator-images#alien_vs_predator_thumbnails.zip
/Notebook/: which stores iPython notebooks for data preprocessing, Model training and model evaluation.
/subdatasets/: where training,test, and validation folders are created for training and evaluation
/models/: Where trained models are stored

   
## Steps to follow:

1) download https://www.kaggle.com/pmigdal/alien-vs-predator-images#alien_vs_predator_thumbnails.zip and unzip it in /data
2) Execute Create_sets.ipynb notebook. This will create the trainig, test and validation subsets in /models
3) Execute the Training_*.ipynb notebooks to train models
4) Execute make_predictions.ipynb to evaluate models

## Requirements:

- Keras
- Numpy
- shutil
- Pandas
