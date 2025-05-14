# 🎓 Online Education Analysis at University

## 📌 Project Overview

This project explores student behavior and engagement in online education at a university using data analysis and machine learning techniques. The goal is to uncover patterns, segment students, and evaluate the effectiveness of different learning formats.

Both **supervised** and **unsupervised learning** approaches are used, alongside extensive preprocessing and visualization.

---


## 🧾 Data Collection

This research was conducted among third-year students of the Business School at Suleyman Demirel University. These participants were specifically selected because they had direct experience with online education during the pandemic and could provide informed insights.

A **stratified sampling technique** was used to ensure representative data. Data was collected using a structured survey based on a **5-point Likert scale** for most questions.

### 📋 Survey Questions

- **Agreement of participation** — Yes / No  
- **Gender** — Female / Male / Prefer not to say  
- **Major of study** — Accounting and Audit / Finance / Management / Economics / Digital Marketing  
- **Impact on Business School** — 1 (Very low) to 5 (Very high)  
- **Disruption** — 1 (Not at all) to 5 (To a great extent)  
- **Crisis management** — 1 (Inadequate) to 5 (Very good)  
- **Communication efficiency (students & staff)** — 1 (Not at all) to 5 (To a great extent)  
- **Strategic change at SDU** — 1 (Not at all) to 5 (To a great extent)  
- **Stressfulness** — True / False  
- **Stress level rating** — 1 (Not at all stressful) to 5 (Extremely stressful)  
- **Course evaluation** — 1 (Very poor) to 5 (Very good)  
- **Expectations impact** — 1 (Not at all) to 5 (To a great extent)  
- **Connection dynamics among groupmates** — 1 (Very poor) to 5 (Very good)  
- **Academic freedom affected** — 1 (Much worse) to 5 (Much better)  
- **Platform rating** (e.g. Moodle, Zoom, Teams) — 1 (Very low) to 5 (Very high)  
- **OER (Open Educational Resources)** — 1 (Totally useless) to 5 (Very useful)  
- **Support from SDU** — 1 (Never) to 5 (A great deal)  
- **Total** — Sum of all numerical answers per participant (used for composite score analysis)

This structured data was used as input for further statistical analysis and machine learning models.

---

## 🗂️ Project Structure

### 1. 📊 Data Preprocessing
- Handling missing values and duplicates
- Normalizing numerical features using `MinMaxScaler`
- Exploratory data analysis (EDA): distributions, correlations, feature profiling

### 2. 🤖 Supervised Learning

#### 2.1 Random Forest
- Train-test split
- Parameter tuning
- Underfitting and overfitting detection
- Evaluation metrics: accuracy, confusion matrix, etc.

#### 2.2 Decision Tree
- Feature and target selection
- Model training and visualization
- Hyperparameter tuning
- Performance evaluation

#### 2.3 K-Nearest Neighbors (KNN)
- Selecting optimal number of neighbors
- Model performance analysis

#### 2.4 Support Vector Machine (SVM)
- Model training
- Comparison with other classifiers
- Visualization of classification boundaries

---

### 3. 🔍 Unsupervised Learning – K-Means Clustering
- Feature selection
- Optimal number of clusters using the Elbow method
- Clustering analysis
- Dimensionality reduction with PCA for visualization
- Cluster interpretation

---

### 4. 📈 Model Evaluation & Optimization
- Hyperparameter tuning
- Learning curves to detect overfitting/underfitting
- Metric-based model comparison
- Insights and interpretation of results

---

## 🛠️ Technologies Used

- **Python 3.8+**
- **NumPy** – numerical computations
- **Pandas** – data manipulation
- **Matplotlib** & **Seaborn** – data visualization
- **Scikit-learn** – machine learning models and tools
  - Classifiers: RandomForest, DecisionTree, KNN, SVM
  - Unsupervised Learning: KMeans, PCA
  - Preprocessing: LabelEncoder, MinMaxScaler
  - Model selection: Train-test split, GridSearchCV
  - Evaluation: Accuracy, F1-score, Confusion Matrix, Silhouette Score, R2 Score, etc.
- **Warnings** – suppress unnecessary warnings for cleaner output

---

## 📌 Key Takeaways
- Practical application of both supervised and unsupervised ML algorithms
- Complete data science pipeline from preprocessing to evaluation
- Insights into student behavior and potential ways to personalize the learning experience

---

## 📁 How to Run
1. Clone the repository
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt


