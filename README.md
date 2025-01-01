## **Automatic Questions Tags using NLP and Machine Learning**

This repository contains the implementation of a project focused on processing textual data from platforms like Stack Overflow. It uses natural language processing (NLP) techniques and machine learning models to analyze sentiment polarity and classify question tags effectively.

## **Project Overview**

The project integrates diverse datasets (questions, answers, and tags) and employs machine learning techniques to achieve two main goals:
1. **Sentiment Analysis**: Analyzing the sentiment polarity of textual data.
2. **Tag Classification**: Classifying questions into appropriate tags.

---

## **Features**
- **Data Integration & Cleaning**: 
  - Merged multiple datasets into a unified structure.
  - Preprocessed textual data by removing HTML tags, punctuation, and stop-words, and performing lemmatization.
- **Sentiment Analysis**:
  - Used TextBlob to compute sentiment polarity scores.
- **Feature Engineering**:
  - Applied TF-IDF for extracting textual features.
- **Model Training & Evaluation**:
  - Experimented with models such as:
    - Support Vector Machines (SVM)
    - Random Forest
    - Gradient Boosting
    - Logistic Regression

---

## **Key Results**
- **SVM**: Achieved high accuracy with a linear kernel.  
- **Random Forest**: Demonstrated robustness, especially with large trees.  
- **Gradient Boosting**: Delivered competitive accuracy with moderate complexity.  

These models effectively classified tags while addressing challenges such as overfitting and irrelevant data.

---

## **Challenges**
1. Cleaning datasets with irrelevant content like HTML tags and special characters.  
2. Mitigating overfitting in models like Decision Trees and Random Forests for high-dimensional data.  
3. Handling the limitations of TextBlob in analyzing domain-specific technical text.


---

## **Getting Started**

### Prerequisites
- Python 3.8 or higher
- Required Python libraries:
  - `scikit-learn`
  - `TextBlob`
  - `pandas`
  - `numpy`
  - `matplotlib`

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/musmankkh/Auto-Questions-Tags.git
   cd your-repository-name
   
   ```
3. Explore Jupyter notebooks or run scripts in the `/src` directory.

---

## **Usage**
1. **Preprocess Data**:
   Run scripts in `/src` for data cleaning and feature engineering.
2. **Train Models**:
   Use the training scripts or notebooks to train and evaluate classifiers.
3. **Analyze Results**:
   Check model performance metrics and output visualizations.

---

## **Acknowledgments**
Special thanks to **Prof. Dr. Usman Ghani** for his guidance and mentorship throughout this project.

---

## **Future Work**
This project sets the foundation for further exploration into:
- Advanced NLP techniques (e.g., transformer models like BERT).
- Deep learning approaches for improved scalability and accuracy.

---

Feel free to explore, contribute, or provide feedback!

---

**Contact**: For questions or collaborations, reach out at [42khan0@gmail.com].

```
