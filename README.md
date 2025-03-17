# Project-1
High-End Consumer Preferences and Behavioral Analysis in the Hospitality Industry (Europe)

📊 A Data-Driven Supervised Modelling Approach
(A Case Study on Hotel Reviews Data)
Project Overview
This project explores consumer behavior and satisfaction within the European luxury hospitality sector by analyzing 515,000 hotel reviews from Booking.com. The focus is on deriving actionable insights using supervised machine learning techniques to identify key drivers of customer satisfaction and predict reviewer ratings.

🎯 Key Objectives
Identify top and low-performing hotel brands.
Analyze key factors affecting hotel ratings.
Investigate rating variations based on nationality and trip types.
Predict review scores using machine learning models.
Explore seasonal patterns in reviews.
Examine how demographic factors impact consumer behavior.
🧰 Technologies & Tools Used
Programming Language: Python
Libraries & Frameworks:
Pandas, NumPy, Scikit-learn, NLTK
Matplotlib, Seaborn, WordCloud
XGBoost, Random Forest
Visualization: Tableau, Matplotlib, Seaborn
ML Techniques: Classification & Regression (Random Forest, XGBoost)
NLP Techniques: Sentiment analysis, Tokenization, Stopword Removal, TF-IDF, CountVectorizer

🧩 Dataset
Source: Booking.com hotel reviews dataset
Size: 515,000+ reviews (reduced to 10,000 entries for analysis)
Features:
Hotel details, reviewer nationality, review scores, review text (positive & negative), tags (trip types), date, etc.
🛠️ Main Work Done
1. Data Preprocessing
Missing value treatment (median imputation & forward fill).
Text preprocessing (tokenization, stopword removal, TF-IDF/CountVectorizer).
Feature Engineering:
Review_Length, Sentiment Flags, Weighted Scores, City Extraction, One-Hot Encoding.
2. Exploratory Data Analysis (EDA)
Visualizations of:
Hotel ratings over time
Nationality-based patterns
Seasonal trends
Sentiment distribution (word clouds)
Correlation heatmaps & boxplots
3. Modelling
Models built:
Random Forest Classifier & Regressor
XGBoost Classifier & Regressor
Hybrid model (Random Forest + XGBoost ensemble)
Techniques used:
SMOTE for class imbalance
Hyperparameter tuning (GridSearchCV)
Threshold moving for optimizing recall/precision
4. Evaluation Metrics
Precision, Recall, F1-Score, AUC-ROC, Confusion Matrices, Macro & Weighted averages.
Addressed class imbalance issues across models.

🔑 Key Insights
Room quality is a major factor influencing satisfaction.
Nationality affects review length and sentiment intensity.
Seasonality plays a role: higher satisfaction scores in summer months (e.g., June).

Luxury hotels like St. James' Court, A Taj Hotel London, performed the best, while others showed inconsistent service quality.
📌 Conclusion
This project showcases how machine learning and NLP techniques can provide critical insights into consumer preferences in the European hospitality sector.
The models and findings can guide hotel managers in improving services and tailoring offerings based on customer behavior and demographic patterns.

✨ Acknowledgements
Special thanks to my supervisor Philip Worrall for his invaluable guidance and support.

📚 Keywords
consumer behaviour, hotel reviews, supervised learning, NLP, classification, hospitality analytics
