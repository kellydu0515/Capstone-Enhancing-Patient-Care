# Capstone-Enhancing-Patient-Care
Capstone Project Name: Vagelos - Enhancing Patient Care: Artificial Intelligence for Hepatocellular Carcinoma Diagnosis and Management 

### Group members Name UNI 
- Nathaniel Ho njh2135 (Team captain)
- Kelly Du xd2286
- Yunchen Jiang yj2733

Emails  &lt;UNI&gt; @ columbia.edu

**Accenture mentor & co-mentors:** Dr. Laurent

**Instructor/CA:** Prof. Sining Chen, Vivian Zhang, Peter Chao

Expoloration of various machine learning models for classifying liver nodules as HCC vs. non-HCC based on radiomics features and additional biological variables (e.g., AFP), while addressing dataset imbalance and reducing dimensionality.

The capstone project aims to develop a machine-learning model using radiomics features to classify liver nodules as HCC or non-HCC in cirrhotic patients with indeterminate liver nodules. We establish baseline performance for our models using the Random Forest, K-Nearest Neighbors (KNN), and Logistic Regression algorithm, measured by classification metrics such as precision, recall, and F1-Score. We initially train the models on the originial training dataset when the time point is at the portal venous phase and subsequently evaluate their classification accuracy on integrated dataset with both HCC and non-HCC. The Random Forest Classifier initially shows promise in accuracy, precision, and recall metrics. Feature set refinement incorporates data from Advanced HCC and phenotype datasets, but using SMOTE leads to overfitting, prompting a reconsideration of sampling strategies. KNN and Logistic Regression models, while exhibiting varying success, benefit from additional techniques like stratified K-Folds and GridSearchCV. The Logistic Regression model, however, remains relatively weaker compared to others.


**Directory tree**
```
│   README.md
│   FinalReport.pdf
├───EDA_and_Random_Forest.zip
│       PCA+RFC.ipynb
│       Training_set.csv
│       AllPhenotypes.csv
│       AdvancedHCC.csv
│   KNNcapstone_knn_version (1).ipynb
│   capstone_logistic_regression.ipynb
