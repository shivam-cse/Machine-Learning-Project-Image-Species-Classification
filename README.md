## Machine Learning Project - Image Species Classification (17 Category Flower Dataset)

This project explores image classification using a 17-category flower dataset obtained from the University of Oxford's Department of Engineering Science. 

**Dataset:** You can download the dataset from the following link: [https://www.robots.ox.ac.uk/~vgg/data/flowers/17/](https://www.robots.ox.ac.uk/~vgg/data/flowers/17/)

**Project Analysis:**

For more details and information about the experiments conducted during this project, you can refer to the accompanying PowerPoint presentation located in the `./Project_Analysis/Flower_Species_Classification.ppt` directory. This folder also includes the PDF version of the presentation and an Excel sheet containing the results.

## Feature Extraction from Images

Features are numerical representations of the information extracted from an image. In the context of classifying plants and flowers, some primary features to consider include color, texture, and shape.

This project utilizes three built-in libraries for feature extraction:

* **Color Histogram:** Quantifies the color distribution of the flower.
* **Hu Moments:** Quantifies the shape of the flower.
* **Haralick Texture:** Quantifies the texture of the flower.

## Algorithm Comparison

This section compares the accuracy achieved by various algorithms implemented in the project.

### Logistic Regression (Scikit-learn)

* Achieved 64.5% accuracy with MinMaxScaler normalization.
* Achieved 72% accuracy with StandardScaler normalization.
* **Outperformed all other evaluated algorithms.**

### Perceptron Learning Algorithm (PLA) (Scikit-learn)

* Training Accuracy: 88.83%
* Test Accuracy: 60.41%

### Single Layer Perceptron (Custom Implementation)

* Achieved 57% accuracy with 5-fold cross-validation.
* Achieved 95% training accuracy and 45% test accuracy without k-fold cross-validation.

### Multi-Layer Perceptron (Custom Implementation)

* Achieved 63.23% accuracy with 5-fold cross-validation, 1 hidden layer of 20 neurons, and 500 max iterations.
* As the number of hidden neurons increases, the model tends towards higher training accuracy (potentially due to overfitting) as described by the Universal Approximation Theorem.

**Accuracy Ranking:** Logistic Regression > MLP > PLA > SLP
