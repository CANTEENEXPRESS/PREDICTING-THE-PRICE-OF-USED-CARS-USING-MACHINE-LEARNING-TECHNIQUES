📌 PREDICTING THE PRICE OF USED CARS USING MACHINE LEARNING
📖 Overview
This project developed an automated, data-driven framework for estimating the market value of pre-owned vehicles. By moving away from subjective human appraisal, the system utilizes machine learning to provide objective and high-precision financial insights. The model analyzes over 500,000 unique records to understand complex depreciation patterns.

🎯 Objectives
Automate Valuation: Eliminate information asymmetry and pricing inconsistencies in the secondary market.


Attribute Analysis: Study the impact of features like vehicle age, mileage, fuel type, and engine displacement on resale value.


Algorithm Comparison: Benchmark models like Linear Regression and SVM against Ensemble Learning.


Real-time Deployment: Implement model serialization for instant predictions without re-training.


🛠️ Technologies Used
Language: Python 3.8+


Environment: Anaconda Navigator, Jupyter Notebook, VS Code


Libraries: Pandas (Data handling), NumPy (Matrices), Scikit-Learn (ML Models), Matplotlib/Seaborn (Visualization)


Model Persistence: Pickle


⚙️ Machine Learning Models Used
Random Forest Regressor: The primary model, selected for its superior ability to capture non-linear relationships.


Linear Regression: Used as the initial baseline model for performance comparison.


Gradient Boosting: Sequential ensemble method used to transform weak learners into strong ones.


KMeans Clustering: Applied to identify categorical linearity within dataset clusters.


🔄 Workflow
Data Ingestion: Loading 500,000+ car listings from the dataset.


Pre-processing (0_dataclean.py): Handling null values and removing outliers using the Interquartile Range (IQR) method.


Feature Engineering: Encoding categorical text (e.g., "Diesel", "Manual") into numerical formats.


Algorithm Testing (1_algorithmTest.py): Evaluating candidates using a 70-30 Train-Test split.


Model Building (2_buildModel.py): Finalizing the "brain" of the system with hyperparameter tuning.


Prediction Engine (3_mainModel.py): User-facing script that loads the serialized model for instant estimates.


📊 Key Results
Best Model: Random Forest Regressor.


Accuracy: Achieved an R-Squared ($R^{2}$) Score of 0.92 (92%).


Precision: Mean Absolute Error (MAE) of approximately ₹12,400, proving high reliability.


Scalability: Successfully processed high-volume "Big Data" scenarios.


📁 Project Structure
0_dataclean.py: Automated dataset standardization.


1_algorithmTest.py: Diagnostic environment for model evaluation.


2_buildModel.py: Logic for training and serialization.


3_mainModel.py: Real-time prediction interface for end-users.


randomforest.pickle: The serialized "wisdom" of the trained algorithm.


👨‍💻 Batch 13 Team (CSE-A)
N. Yashashwini (22TQ1A0515)


V. Vineela (22TQ1A0554)


S. Vaibhav (22TQ1A0558)


Guide: Dr. V. Sumalatha, Assistant Professor



Siddhartha Institute of Technology and Science (Autonomous)
