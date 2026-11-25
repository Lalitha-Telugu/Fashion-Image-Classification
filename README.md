# Fashion Image Classification Using Machine Learning

## Project Overview
This project focuses on classifying clothing images into 10 different categories using Machine Learning algorithms. The Fashion-MNIST dataset is used to train and evaluate the classification models.

## Dataset
- Dataset: Fashion-MNIST
- Total Images: 70,000
- Image Size: 28 × 28 pixels
- Number of Classes: 10
- Training Images: 60,000
- Testing Images: 10,000

Dataset Source: https://github.com/zalandoresearch/fashion-mnist

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithms
1. K-Nearest Neighbors (KNN)
2. Decision Tree Classifier

## Project Workflow
1. Dataset loading
2. Data visualization
3. Image flattening
4. Pixel normalization
5. Model training
6. Prediction
7. Model evaluation
8. Classification report
9. Confusion matrix
10. Model comparison

## Model Performance

| Algorithm | Accuracy |
|---|---:|
| KNN | 81.51% |
| Decision Tree | 78.90% |

Note: KNN was trained using a stratified sample of 10,000 images, whereas Decision Tree was trained using the full 60,000-image training set. Both were evaluated on the same 10,000 test images.

## Conclusion
KNN achieved 81.51% accuracy, while Decision Tree achieved 78.90% accuracy. KNN performed better in this experiment. Both models classified certain categories effectively but struggled with visually similar clothing items.

## Author
Lalitha
