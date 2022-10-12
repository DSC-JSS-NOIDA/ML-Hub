## White Wine Quality Predictor 

### Dataset
https://www.kaggle.com/datasets/athu1105/book-genre-prediction
### Models
	1. Logistic Regression
	2. LinearSVC
	3. Random Forest Classifier

### Libraries used :
		Preprocessing :
                	pandas
                	numpy
                	seaborn 
                	matplotlib
                    sentence_transformers


        Model Training & Evaluation :
            import pandas as pd
            from sklearn.model_selection import train_test_split
            from sklearn.ensemble import RandomForestClassifier
            from sklearn.linear_model import LogisticRegression 
            from sklearn.svm import LinearSVC
            from sklearn.naive_bayes import MultinomialNB
            from sklearn.model_selection import cross_val_score
            from sentence_transformers import SentenceTransformer
            from sklearn.feature_extraction.text import TfidfVectorizer
            from sklearn.metrics import classification_report, confusion_matrix
            import matplotlib.pyplot as plt
            import seaborn as sns
