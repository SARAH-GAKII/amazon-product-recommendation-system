# Amazon Product Recommendation System

This project builds and evaluates recommendation models using the Amazon product reviews dataset. The objective is to learn user–item interaction patterns and generate personalized product recommendations.

The analysis explores several recommendation approaches, including popularity-based methods, collaborative filtering, and matrix factorization, and compares their performance using standard recommendation metrics.

---

## Objectives

- Explore and clean the Amazon review dataset
- Build baseline recommendation models
- Implement matrix factorization using Singular Value Decomposition (SVD)
- Evaluate models using recommendation system metrics
- Generate predictions for unseen user–item pairs

---

## Dataset

The dataset contains Amazon product reviews with the following key fields:

- **UserID** – reviewer identifier
- **ItemID** – product identifier
- **Rating** – rating given by the user

For computational purposes and to reduce sparsity and ensure meaningful recommendations, the dataset is filtered to include:

- users with at least 50 ratings
- items with at least 5 ratings

This filtering step improves model stability and reduces noise in the recommendation process.

---

## Methods Used

- Exploratory Data Analysis (EDA)
- Popularity/Ranked-based Recommendation
- Collaborative Filtering
- Matrix Factorization using SVD
- Model Evaluation (Precision@k, Recall@k, F1-score@k, RMSE)

---

## Tools

- Python
- Pandas
- Scikit-learn
- Surprise (Recommendation system library)
- Matplotlib
- Seaborn

---

## Repository Content
- **[Amazon Product Recommendation System Notbook(pdf)](Amazon_Product_Recommendation_System.pdf)**
- **[Amazon Product Recommendation System Notebook (python nb)](Amazon_Product_Recommendation_System.ipynb)**

---

## Future Work

Future work could extend this system by implementing a hybrid recommendation approach that combines collaborative filtering with content-based features. This would allow the system to leverage both user interaction patterns and product attributes, improving recommendations and addressing cold-start scenarios in production environments.
