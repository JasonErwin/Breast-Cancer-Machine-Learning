# Machine Learning for Disease Treatment Response Prediction

This coursework's task was to apply advanced machine learning method to predict  pathological complete response [PCR] (classification) and relapse-free survival [RFS] (regression) using both clinically measured features and features derived from magnetic resonance images (MRI) prior to chemotherapy treatment. 

## Getting Started

Please ensure that the following Python Packages are installed before running the Jupyter Notebook.

No | Packages      |
-- | ------------- |
1  | Numpy         |
2  | Matplotlib    |
3  | Pandas        |
4  | Seaborn       |
5  | Scikit-learn  |
6  | Pickle        |



## Evaluation

For PCR, a confusion matrix was plot which represents the actual postive, actual negative, false positive and false negative predictions. In addition, an receiver opearting characteristic curve (ROC) curve was generated. 

K-fold Cross Validation Classification Accuracy  :
       Model         | Classification Accuracy |
-------------------  | ---------------------   |
Random Forest        |     0.71                |
SVC                  |     0.74                |
Logistic Regression  |     0.52                |

For RFS, mean absolute error was calculated.

Mean absolute error cross-validation score :
       Model         | Mean Absolute Error  |
-------------------  | ---------------      |
Random Forest        |  19.16               |
SVM                  |  19.36               |
Lasso Regression     |  19.88               |


## Testing Results on Independent Test Set

PCR classification accuracy = 65.41%

RFS = 19.01
