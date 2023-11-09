## Multiclass classification of dry beans using machine learning
<p align="center">
  <img src="images/pie graph data distribution.png" alt="Features Distribution" width="60%" height="auto"/>
</p>

This report focuses on the development of two multiclass classification models using computer vision and machine learning techniques to classify dry beans. The study aims to provide a method for obtaining uniform seed varieties from crop production, which is in the form of population, so the seeds are not certified as a sole variety. The primary objective is to distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification.

<a href="https://archive.ics.uci.edu/dataset/602/dry+bean+dataset">The dataset</a>  used in this study consists of images of 13,611 grains of seven different registered dry beans, which were subjected to segmentation and feature extraction stages, resulting in a total of 16 features. The outliers were removed for each class from the dataset using the Z-score method and the total size of the dataset was reduced to 12,909. The PCA dimension reduction technique was applied, reducing the total columns of the dataset to 10.

XGBoost and Support Vector Machine (SVM) classification models were created with nested cross-validation methods, and performance metrics were compared. Overall correct classification rates were determined as 94.00\% and 94.39\% for XGBoost and SVM respectively.
