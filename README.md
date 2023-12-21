
Advertising Sales Prediction


This project explores the relationship between advertising spending and product sales using machine learning techniques. A linear regression model is employed to predict sales based on different advertising channels, such as TV, radio, and newspaper.

Contents
data/: Folder containing the dataset (ads.csv).
notebooks/: Jupyter notebooks with the analysis and modeling process.
01_data_exploration.ipynb: Initial exploration of the dataset.
02_feature_selection.ipynb: Feature selection using correlation.
03_multifeature_selection.ipynb: Multifeature selection and model comparison.
04_lasso_regression.ipynb: Lasso regression implementation.
README.md: Documentation for the project.
requirements.txt: List of dependencies for reproducing the project environment.
Getting Started
Clone the repository: git clone https://github.com/your-username/your-repo.git
Install dependencies: pip install -r requirements.txt
Explore the notebooks in the notebooks/ directory for a step-by-step walkthrough.
Results
The linear regression model achieved an R-squared value of 0.46 on the test data.
Multifeature selection and Lasso regression significantly improved the model, achieving an R-squared value of 0.90.
Usage
Run the Jupyter notebooks in the specified order for a comprehensive understanding.
Modify parameters and experiment with your dataset for different results.
Feel free to contribute or raise issues!
Dependencies
pandas
matplotlib
seaborn
scikit-learn
