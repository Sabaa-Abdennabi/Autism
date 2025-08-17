# Autism Classification Project  

Machine learning project to classify **Autism Spectrum Disorder (ASD)** using survey and demographic data.  

## Features  
- Preprocessing & visualization  
- Feature engineering & encoding  
- Models: Logistic Regression, SVM, XGBoost  
- Handle imbalance with RandomOverSampler  
- Hyperparameter tuning (GridSearchCV)  
- Evaluation: accuracy, confusion matrix, classification report  

##  Usage  
```sh
# Create venv & install deps
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt
````
Run the notebook: **Autism.ipynb**

## Output

* Best model → `best_model.pkl`
* Metrics shown in notebook

## Requirements

Python 3.8+, scikit-learn, xgboost, imbalanced-learn, pandas, numpy, matplotlib, seaborn, joblib
