# MACHINE LEARNING SOUNDBAR ANALYSIS CLASSIFICATION PREDICTION 

This project focuses on building a comprehensive machine learning pipeline for analyzing soundbar products. It integrates web scraping, data cleaning, feature engineering, unsupervised learning (clustering), and supervised learning (classification) to uncover insights and automate product categorization.

---

## Objective

To develop a machine learning-driven system that:
- Extracts product data from Amazon via web scraping
- Performs feature extraction using NLP and regular expressions
- Applies unsupervised learning for clustering and market segmentation
- Builds supervised models to predict product categories
- Compares multiple classification algorithms and optimizes performance using hyperparameter tuning

---

##  Project Scope

- Web scraping of soundbar data from Amazon (filtered by brand)
- Storage of raw data in MySQL for persistence and scalability
- Data preprocessing: handling nulls, duplicates, text processing
- Feature extraction using regular expressions
- EDA with univariate, bivariate, and multivariate analysis
- Encoding and scaling for unsupervised learning
- PCA + KMeans clustering for segmentation
- Supervised classification using:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Decision Tree
  - Gaussian Naive Bayes
  - Random Forest
  - XGBoost
- Hyperparameter tuning and performance comparison

---

## Tech Stack

- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, BeautifulSoup, Requests
- **Database**: MySQL
- **Tools**: Jupyter Notebook, VS Code

---

## Key Steps

### 1. Data Collection
- Web scraped Amazon listings filtered by brand.
- Extracted raw fields: product name, brand, price, and ratings.

### 2. Data Storage
- Stored structured data in a MySQL database using SQLAlchemy.

### 3. Preprocessing
- Removed missing values and duplicates
- Extracted features like wattage, channels, wireless capability using regex
- Converted ratings from text to numeric
- Standardized data types and cleaned text

### 4. Exploratory Data Analysis (EDA)
- Brand-wise product distribution
- Histograms of price, rating
- Channel configuration and wireless capability count plots
- Bivariate & multivariate visualizations

### 5. Unsupervised Learning
- Applied Label Encoding for categorical features
- Standardized numerical features using StandardScaler
- Reduced dimensions with PCA
- Clustered data using KMeans and identified optimal K using Elbow & Silhouette methods

### 6. Supervised Learning
- Used PCA-based clusters as labels for classification
- Trained multiple models and evaluated using accuracy, precision, recall, F1-score
- Performed hyperparameter tuning for optimal performance

---

## Results

- Clustering revealed distinct market segments based on technical features.
- Random Forest and XGBoost outperformed other models with high accuracy.
- Feature importance highlighted wattage, brand, and channel configuration as strong predictors.

---

## Future Scope

- Extend to other audio devices like Bluetooth speakers and home theaters.
- Integrate NLP sentiment analysis using customer reviews.
- Deploy model via web interface for live predictions.

---

## Target Audience

- Data scientists and ML practitioners
- Consumer electronics analysts
- E-commerce businesses for competitive benchmarking

---

## License

This project is for educational and research purposes only. Data usage must comply with Amazon's terms of service.

---

## PRESENTED BY

**VEENA SRI P M**  
*Data Analytics and Data Science*

