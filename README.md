# MUSA650_LandUseClassification
## Homework 3 - Land Use and Land Cover Classification

### Overview
In this individual project, I tackled the challenge of classifying satellite images into various land use and cover categories using the EuroSAT dataset. This benchmark dataset is pivotal for satellite imaging within the remote sensing field.

### Objective
The goal was to effectively classify images into categories such as urban areas, forests, and rivers, utilizing different modeling techniques ranging from traditional machine learning to advanced deep learning methods.

### Models Used
Support Vector Machine (SVM)

Random Forest

Deep Learning Models including basic and advanced CNN architectures.

VGG16, a pre-trained model, demonstrating the efficacy of transfer learning.

### Data Source
The EuroSAT dataset consists of 27,000 labeled images from Sentinel-2 satellites covering 13 spectral bands.
https://github.com/phelber/eurosat

### Implementation and Results
Data Preprocessing: Standardization and augmentation techniques were employed to enhance model training.
Model Training and Evaluation: Models were trained and tuned for optimal performance and evaluated based on metrics like accuracy, precision, recall, and F1-score. The VGG16 model outperformed others, showcasing the advantages of transfer learning.
Error Analysis: Misclassifications were specifically analyzed to understand model weaknesses.

### Conclusion
This project underlines the complexities and methodologies in satellite image classification, highlighting how different models perform on a standardized dataset like EuroSAT.
