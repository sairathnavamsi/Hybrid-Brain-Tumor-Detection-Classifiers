# Hybrid Brain Tumor Detection Classifiers
A project on brain tumor detection using hybrid neural network classifiers. CNN is used along with one of random forest, logistic regression, KNN, naive bayes, support vector machine or gradient boost classifier to determine if an MRI scan contains tumor. The generated classifiers are compared using their accuracies, f1 scores and confusion matrices. 

The dataset images are preprocessed with median filter and canny edge detection. A CNN is trained on the preprocessed dataset and output from the penultimate layer of this CNN is gives as the input features to different ML algorithms for training. 

### Requirements
- Python 3.7
- OpenCV
- Tensorflow
- Pandas
- Scikit Learn

### Notes
- The dataset is collected from [this](https://www.kaggle.com/datasets/simeondee/brain-tumor-images-dataset), [this](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection) and [this](https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection) sources.
- CNN model is saved and loaded using tensorflow.