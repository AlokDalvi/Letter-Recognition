# Handwritten Character Recognition README

## Introduction
This project focuses on recognizing handwritten Hindi characters using logistic regression and principal component analysis (PCA). The code provided in this repository loads a dataset of handwritten Hindi characters, preprocesses the images, applies PCA for dimensionality reduction, trains a logistic regression model, and evaluates its performance.

## Libraries and Packages
The following libraries and packages are used in the code:
- NumPy: Numerical computing
- Pandas: Data manipulation and analysis
- Matplotlib: Data visualization
- Plotly: Interactive visualizations
- scikit-learn: Machine learning library
- OpenCV: Image processing

Please make sure to install the required packages using the appropriate package manager.

## Code Explanation
1. Dataset creation: The code reads the handwritten Hindi character images from the provided dataset folder and creates a dataset by loading the images and their corresponding class labels.

2. Data exploration: Basic statistics of the dataset are provided, including the count of samples for each class and the shape of the input images.

3. Data splitting: The dataset is split into training and testing sets using the `train_test_split()` function from scikit-learn.

4. Data normalization: The pixel values of the input images are normalized by dividing them by 255 to bring them into the range [0, 1].

5. Dimensionality reduction: PCA is applied to reduce the dimensionality of the input images. The explained variance ratio threshold of 0.96 is used to determine the number of principal components to retain.

6. Data visualization: Scatter plots are generated to visualize the transformed data using PCA components. Each point in the scatter plot represents an image, and the color represents the corresponding class label.

7. Model training and evaluation: A logistic regression model is trained on the transformed training set and evaluated on both the training and testing sets. The accuracy scores are calculated and displayed.

8. Model performance visualization: A bar chart is generated to visualize the training and testing accuracy of the logistic regression model.

Please refer to the code for more detailed explanations and implementation details.

## Results
The logistic regression model achieved a training accuracy of XX% and a testing accuracy of XX%. The scatter plot visualizations provide insights into the distribution of the transformed data using PCA components.

Please note that the provided code may require further adjustments and improvements depending on the specific requirements of your project.

