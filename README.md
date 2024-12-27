
# Amazon Reviews Sentiment Analysis

This project involves analyzing Amazon product reviews to classify the sentiment (e.g., positive, negative, neutral). The analysis leverages Python and popular data science libraries to preprocess text data, build machine learning models, and evaluate their performance.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Technologies Used](#technologies-used)

---

## Project Overview
The goal of this project is to process a dataset of Amazon reviews, clean the text, and train machine learning models to predict sentiment. The project also demonstrates data preprocessing, feature extraction (e.g., TF-IDF), and model evaluation using metrics like accuracy and classification reports.

---

## Dataset
The dataset used is sourced from Kaggle:
- **Name**: Amazon Reviews Dataset
- **Link**: [Kaggle Dataset](https://www.kaggle.com/bittlingmayer/amazonreviews)

---

## Features
1. **Data Cleaning**: Removing stopwords, punctuation, and applying lemmatization.
2. **Feature Extraction**: Using Count Vectorizer and TF-IDF.
3. **Sentiment Analysis**: Training machine learning models to classify sentiment.
4. **Visualization**: Data distribution and insights using Matplotlib and Seaborn.

---

## Installation
### Prerequisites
Make sure you have Python 3.7 or higher installed. Install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

### Required Libraries
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `nltk`
- `tensorflow`
- `scikit-learn`
- `kaggle`

---

## Usage
1. **Clone the Repository**:

```bash
git clone https://github.com/your-username/amazon-reviews-analysis.git
cd amazon-reviews-analysis
```

2. **Set Up Kaggle API**:
   - Place your Kaggle API token (`kaggle.json`) in the `.kaggle` directory.
   - Download the dataset using:
     ```bash
     !kaggle datasets download bittlingmayer/amazonreviews
     ```

3. **Run the Notebook**:
   Open the Jupyter Notebook `fai_amazon.ipynb` and execute the cells sequentially to:
   - Import the dataset
   - Preprocess the data
   - Train and evaluate the model

---

## Results
- **Data Distribution**: Visualizations of word frequencies, review lengths, and sentiment categories.
- **Model Performance**: Classification reports and confusion matrices showcasing accuracy, precision, recall, and F1-score.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Data Analysis: Pandas, NumPy
  - Data Visualization: Matplotlib, Seaborn
  - Text Processing: NLTK, TF-IDF
  - Machine Learning: TensorFlow, scikit-learn
- **Environment**: Jupyter Notebook

---

Feel free to contribute or suggest improvements to this project by opening an issue or a pull request!