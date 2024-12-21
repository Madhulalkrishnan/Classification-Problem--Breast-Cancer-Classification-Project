# Classification-Problem--Breast-Cancer-Classification-Project
The Breast Cancer Classification Project uses the sklearn dataset to classify tumors as malignant or benign. It implements Logistic Regression, Decision Tree, Random Forest, SVM, and k-NN. Preprocessing includes scaling and handling missing values. Insights reveal Random Forest as the best model, achieving 97% accuracy.
# Breast Cancer Classification Project

## Description
This project classifies breast cancer tumors as malignant or benign using the sklearn dataset. It implements five supervised learning models: Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), and k-Nearest Neighbors (k-NN). Preprocessing includes handling missing values and feature scaling to improve model accuracy and performance. 

## Project Overview
1. **Dataset**: The breast cancer dataset from the sklearn library was used for this project.  
2. **Preprocessing**:
   - Handled missing values to ensure data consistency.
   - Applied feature scaling to normalize the data for algorithms sensitive to feature magnitudes.  
3. **Algorithms Implemented**:
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  
   - Support Vector Machine (SVM)  
   - k-Nearest Neighbors (k-NN)  
4. **Model Comparison**:
   - Models were evaluated based on accuracy and confusion matrices.
   - Random Forest outperformed others with 97% accuracy, while Logistic Regression showed the lowest performance.

## Insights
- **Random Forest**: Achieved the highest accuracy, demonstrating its robustness for this dataset.
- **k-NN**: Performed well due to its ability to handle non-linear relationships.
- **SVM**: Delivered strong performance with high precision but required more computation.
- **Logistic Regression**: Showed the lowest accuracy, indicating limited suitability for this dataset.  
- **Decision Tree**: Provided interpretable results with moderate accuracy.

## Conclusion
This project demonstrates the application of supervised learning algorithms to a real-world dataset, highlighting the importance of preprocessing and model selection for effective classification. Random Forest proved to be the best choice for this task, achieving reliable predictions.  

## Requirements
- Python 3.x  
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`  

## Instructions
1. Clone this repository.  
2. Open the Jupyter Notebook file.  
3. Run the cells sequentially to explore the data, preprocess, and implement classification models.  

## Acknowledgments
- Dataset: sklearn library's breast cancer dataset.  
- Tools: Python and Jupyter Notebook.  
