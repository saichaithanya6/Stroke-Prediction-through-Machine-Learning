### Experiment Setup
This part presents an introduction to the dataset, a block diagram, a flow diagram, and evaluation criteria. Additionally, it describes the approach and methods utilized in 
the project.
The data can only be used to create a model once it has been processed. To build the model, a preprocessed dataset and machine learning techniques are required. The methods 
used in this project include Logistic Regression, Random Forest classification, Gradient Boosting, XGBoost, Support Vector Machine, and K-Nearest Neighbors. After creating 
eight different models, their performance is compared using metrics such as accuracy score, precision score, recall score, and F1 score. 

![image](https://github.com/saichaithanya6/Stroke-Prediction-through-Machine-Learning/assets/111531760/c5e587c8-02a3-441d-af62-b3fbc74ad216)


The missing values in the 'BMI' column are filled using the mean of the column's data.

![image](https://github.com/saichaithanya6/Stroke-Prediction-through-Machine-Learning/assets/111531760/040fbe91-f98a-41d7-98a5-27624e68f356)

The data exhibits a significant imbalance in the number of stroke cases (1) compared to non-stroke cases (0), with a mere 249 rows containing the former while the latter
comprises 4,861 rows. This disproportionality can potentially impact model accuracy, thereby requiring preprocessing of the data to balance the dataset. Figure 2 provides 
a visual representation of the total count of stroke and non-stroke records in the target column before preprocessing.

![image](https://github.com/saichaithanya6/Stroke-Prediction-through-Machine-Learning/assets/111531760/df06d83f-6436-4535-b81f-88feb19a2784)

The above figure indicates that the dataset suffers from an imbalance. To mitigate this problem, the Synthetic Minority Over-sampling Technique (SMOTE) has been utilized to 
balance the dataset.

### Data Pre-Processing 
Data preprocessing is a crucial step before model development to remove any unwanted noise and outliers from the dataset that could hinder the model's intended training. 
This step involves identifying and addressing any factors that could potentially affect the model's efficiency. Once the relevant dataset is obtained, it is cleaned and 
prepared for model development. The dataset contains twelve features, with the 'id' column being excluded as it does not contribute to model construction. Any missing values
in the dataset are filled, and in this case, missing values in the 'BMI' column are filled using the mean of the column's data.
