# 🎭 Author Attribution for Poems using Decision Tree Classifier

## 🧠 Project Overview
This project focuses on identifying the **author of a poem** using **Machine Learning** techniques.  
By analyzing poetic text through **Natural Language Processing (NLP)** and statistical analysis,  
the model learns unique writing patterns of poets and predicts the author of new poems.


## ⚙️ Key Features
- 🧹 **Data Preprocessing:** Text cleaning using stopword removal. 
- 📊 **Exploratory Data Analysis:** Statistical summaries (mean, median, mode) and box plots for insights.  
- 🌳 **Machine Learning Model:** Trained a Decision Tree Classifier for author prediction.  
- 🎨 **Visualization:** Tree structure plot for interpretability and box plots for word count analysis.  
- 📈 **Evaluation:** Accuracy score, confusion matrix, and classification report for model performance.


## 🗂️ Dataset
- Source: [Poetry Foundation Dataset]
- Columns:  
  - **Poet:** Name of the author  
  - **Poem:** Text of the poem  
  - **word_count:** Number of words per poem  


## 🧩 Tech Stack
- **Libraries Used:**
  - `pandas`, `numpy` – data handling  
  - `nltk` – text preprocessing (stopwords, lemmatization)  
  - `matplotlib`, `seaborn` – visualization  
  - `scikit-learn` – model training, evaluation, decision tree visualization  


## 🚀 Workflow
1. **Load Dataset** → PoetryFoundationData.csv  
2. **Clean Text** → remove punctuation, lowercase. 
3. **Feature Extraction** → word count  
4. **Train-Test Split** → 80-20 ratio  
5. **Model Training** → Decision Tree Classifier 
6. **Evaluation** → Accuracy, Confusion Matrix, Classification Report  
7. **Visualization** → Box Plot & Decision Tree Diagram  


## 📊 Results
- Model predicts poem authors based on stylistic features.  
- Provides clear visualization of word distribution and author style differences.  
- Easy-to-understand decision tree structure enhances model interpretability.



