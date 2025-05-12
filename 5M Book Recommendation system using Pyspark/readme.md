**Scalable Book Recommendation System Using Distributed Computing and Collaborative Filtering**

1. Abstract
2. Data Source
3. System Architecture
4. Machine learning Pipeline
4.1. Installing Libraries and Importing
4.2. Raw Data Storage in S3 Bucket
4.3. Data Preprocessing
4.4. Store preprocessed data for Athena Querying
4.5. Exploratory Data Analysis (EDA)
4.6. ML Recommendation Training
4.7. Model Evaluation
5. Conclusion and Future Work
6. Future System Architecture

Book recommendation systems are essential for enhancing user experience by suggesting
relevant books based on individual preferences. This project develops a recommendation model using
machine learning, specifically collaborative filtering techniques. Implemented with PySpark and utilizing
AWS distributed computing for computation and Athena for querying the staging data, the system
leverages user-item interaction data and matrix factorization to predict ratings. The model achieved a
Root Mean Squared Error (RMSE) of 0.95, demonstrating its reliability in providing accurate book
suggestions.


<img width="837" alt="Screenshot 2025-05-12 at 2 14 01 PM" src="https://github.com/user-attachments/assets/3702d172-3d64-4c78-835d-113d28fcd2ff" />
