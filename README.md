# Distribution-Status-Prediction-of-Animals-Plants-and-Natural-Communities-.
Starting from data collection and preprocessing to insightful visualizations, model creation, and developing a user-friendly Streamlit apps. Witness the power of Random Forest, enhanced with hyperparameter tuning, all backed by compelling visualizations showcasing the intricate patterns in animal, plant, and natural community distributions.
Steps:

🌿 Data Collection: Gathered a dataset from Data.gov.

📊 Data Loading: Imported the dataset into a Data Frame to start the analysis.

🔍 Data Exploration: Explored the dataset to understand its structure, features, data types and identifying any missing values.

🧹 Data Cleaning: Handled missing values by dropping rows with missing data, removed duplicates if any, and dropped irrelevant columns that wouldn't contribute to the prediction model.

🗑️ Dropping Columns: After exploring the data, selected relevant columns for the prediction model based on their importance and contribution to the target variable.

🎨 Encoding Categorical Variables: Encoded categorical variables using techniques like get dummies encoding or label encoding to convert them into numerical format, which is necessary for the machine learning algorithms to process.

🎯 Feature Selection with Pearson and SelectKBest with Chi-Squared: Utilized statistical methods like Pearson correlation and SelectKBest with chi-squared to select the most significant features for

predicting biodiversity distribution status. This step ensured that only the most relevant features were used in the model.

📊 Outlier Removal: Employed outlier removal techniques, such as the Interquartile Range (IQR) method, to deal with outliers in the dataset, ensuring the model's robustness and accuracy.

🔍 SMOTE Oversampling: Managed class imbalance in the target variable using Synthetic Minority Over-sampling Technique (SMOTE), which generates synthetic samples to balance the distribution of classes, thus improving the model's performance.

🧩 Model Creation with KNN, Decision Tree, SVM, Naive Bayes, Random Forest Algorithms and compare the performance of multiple classification models.  Random Forest classifier excels with an accuracy

score of 90.61% in classification tasks, demonstrating superior predictive power compared to other models.

🌟 Hyper Parameter Tuning: Tuned hyperparameters using GridSearchCV to achieve better outcomes, ensuring the model's accuracy and reliability in predicting biodiversity distribution status.

🚀 Streamlit App Development: Designed a user-friendly interface using Streamlit, to get predictions on biodiversity distribution status.
