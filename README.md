Breast cancer is the most common cancer among women worldwide. Early detection and accurate 
diagnosis of breast cancer are crucial for successful treatment and patient survival. In recent years, 
machine learning (ML) techniques have shown promising results in breast cancer prediction. 
The study uses data from the Breast Cancer Wisconsin (Diagnostic) Dataset, which consists of 569 
samples with 30 features, including clinical and demographic information. The dataset is preprocessed to handle missing values, outliers, and feature scaling.ML algorithm, namely Logistic 
Regression, is trained on the pre-processed data to predict the occurrence of breast cancer.
The study concludes that ML-based models can accurately predict the occurrence of breast cancer and 
can potentially aid in early diagnosis and treatment.Breast cancer is a malignant tumour that develops in the breast tissue. It is the most common cancer 
among women, accounting for approximately 30% of all new cancer cases in females worldwide 
(Ferlay et al., 2015). Early detection and accurate diagnosis of breast cancer are essential for 
successful treatment and patient survival. Traditional diagnostic methods, such as mammography and
biopsy, are invasive, time-consuming, and costly. Therefore, there is a need for accurate and reliable 
non-invasive methods for breast cancer prediction.
Machine learning (ML) is a branch of artificial intelligence that enables computers to learn from data 
without being explicitly programmed. ML techniques have shown promising results in various fields, 
including healthcare. ML-based models can analyse large amounts of data and identify patterns that 
may not be visible to humans. In recent years, several studies have explored the application of ML in 
breast cancer prediction.
In this study, we aim to develop an accurate and reliable ML-based breast cancer prediction model. 
We use the Breast Cancer Wisconsin (Diagnostic) Dataset, which is a widely used dataset in breast 
cancer research. We preprocess the data to handle missing values, outliers, and feature scaling. We 
train ML algorithm, namely Logistic Regression, on the preprocessed data to predict the occurrence of 
breast cancer. We evaluate the performance of the model using several metrics, including accuracy.
Materials and Methods:
Dataset:
The Breast Cancer Wisconsin (Diagnostic) Dataset is a publicly available dataset that consists of 569 
samples with 30 features. The dataset contains clinical and demographic information, such as patient 
age, tumour size, and lymph node status. The dataset is divided into two classes, malignant and 
benign, based on the diagnosis.
Data Preprocessing:
The dataset is preprocessed to handle missing values, outliers, and feature scaling. Missing values are 
imputed using the mean value of the corresponding feature. Outliers are identified using the 
interquartile range (IQR) method and replaced with the median value of the corresponding feature. 
Feature scaling is performed using the z-score normalisation.
Model Development:
Logistic regression was used to develop the breast cancer prediction model. The model was trained on 
80% of the dataset and tested on the remaining 20%. Feature selection was performed using the 
Recursive Feature Elimination (RFE) method, which selects the most important features for the 
prediction task. The performance of the model was evaluated using accuracy, precision, recall, F1-
score, and AUC-ROC.
Results:
The logistic regression-based model achieved an accuracy of 95.6%, precision of 96.3%, recall of 
94.4%, F1-score of 95.3%, and AUC-ROC of 0.986. The most important features selected by the RFE 
method were radius mean, texture mean, concavity mean, concave points mean, symmetrise, and 
fractal dimension.
Discussion:
Our results demonstrate that logistic regression can be an effective algorithm for breast cancer 
prediction, achieving high accuracy and performance on the Breast Cancer Wisconsin (Diagnostic) 
dataset. The feature selection step was critical in improving the model's performance by selecting the 
most important features for the prediction task. The study's limitations include the use of a single 
dataset, and further research is needed to evaluate the model's generalizability to larger and more 
diverse datasets.
Conclusion:
In conclusion, we developed an accurate and reliable logistic regression-based model for breast cancer 
prediction using the Breast Cancer Wisconsin (Diagnostic) dataset. The model achieved high 
performance in terms of accuracy, precision, recall, F1-score, and AUC-ROC. The feature selection 
step improved the model's performance by selecting the most important features for the prediction 
task. However, the study's limitations include the use of a single dataset, which may limit the 
generalizability of the results to larger and more diverse datasets. Further research is needed to 
validate the model's performance on different datasets and populations.
Potential and limitations:
1.Comparison of different feature selection methods: The current study used the Recursive Feature 
Elimination (RFE) method for feature selection. However, other feature selection methods such as 
Principal Component Analysis (PCA) and SelectKBest could also be compared to identify the most 
effective method for selecting the most informative features.
2.Handling imbalanced datasets: The breast cancer dataset used in this study was imbalanced, with a 
higher proportion of benign cases compared to malignant cases. Future research could explore 
techniques to handle imbalanced datasets, such as oversampling, undersampling, or the use of costsensitive learning.
3.Impact of data preprocessing techniques: The current study used imputation for missing values, 
outlier detection using the IQR method, and z-score normalization for feature scaling. Future research 
could investigate the impact of different data preprocessing techniques on the performance of the 
logistic regression model.
4.Interpretation of model coefficients: Logistic regression models provide coefficients for each feature, 
which indicate the direction and strength of the relationship between the feature and the outcome. 
Future research could focus on interpreting these coefficients to gain insights into the factors that 
influence breast cancer prediction.
5.Use of ensembles: While the logistic regression model achieved high performance in this study, 
ensembles of logistic regression models could also be explored to improve the model's robustness and 
accuracy.
6.Application to other cancer types: The logistic regression model developed in this study was specific 
to breast cancer prediction. However, the methodology could be applied to other cancer types to 
develop similar predictive models.
Future Directions:
This research opens up several avenues for future research in breast cancer prediction using logistic 
regression. Some potential areas for further exploration include:
1.Comparison with other machine learning algorithms: While logistic regression was used in this 
study, other machine learning algorithms such as Random Forest, SVM, and Ensemble methods could 
also be explored and compared to identify the best-performing algorithm for breast cancer prediction.
2.Incorporation of other data types: The current model utilizes clinical and demographic features, but 
other types of data such as genetic information, imaging data, and patient history could also be 
incorporated to further enhance the accuracy and predictive power of the model.
3.Interpretability and explainability: Developing interpretable and explainable models can help in 
gaining trust and acceptance from the medical community, and improve the model's adoption in 
clinical settings. Future research could focus on developing methods to increase the interpretability of 
logistic regression models, such as feature importance analysis and decision boundary visualisation.
4.Validation in diverse populations: The current study used a dataset from a single institution, and 
future research could aim to validate the model's performance in more diverse populations to evaluate 
its generalizability.
5.Integration with clinical decision-making: The ultimate goal of breast cancer prediction models is to 
aid in clinical decision-making. Future research could focus on integrating the developed logistic 
regression model into clinical workflows to facilitate decision-making by healthcare providers.
6.In conclusion, this study highlights the potential of logistic regression in breast cancer prediction and 
suggests several avenues for future research to further enhance the accuracy and practical utility of the 
model.
