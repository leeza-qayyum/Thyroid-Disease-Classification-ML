# Thyroid Disease Classification
Machine learning project for thyroid disease classification using KNN, Naïve Bayes, K-Means, and Random Forest.
# Dataset
- **Source:** UCI Machine Learning Repository (Garavan Institute, 1987)
- **Records:** 9,172 patients
- **Features:** 29 attributes
- **Classes:** 20 thyroid categories
# Algorithms Implemented
- K-Nearest Neighbors (KNN)
- Naïve Bayes
- Random Forest
- K-Means Clustering
# Results
| Algorithm | Accuracy | F1 Score |
|-----------|----------|----------|
| Random Forest | **69.59%** | 68.47% |
| KNN | 68.99% | 68.07% |
| Naïve Bayes | 16.62% | 17.27% |
**Best Model:** Random Forest with hyperparameter tuning
# How to Run
# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
# Open notebook
jupyter notebook "Thyroid Disease Classification.ipynb"
