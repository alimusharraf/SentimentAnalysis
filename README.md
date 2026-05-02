# 📊 Sentiment Analysis on Product Reviews

## 📌 Project Overview

This project focuses on building a **Sentiment Analysis system** to automatically classify customer reviews as **Positive, Negative, or Neutral**.

With thousands of reviews generated daily on e-commerce platforms, manual analysis becomes inefficient. This project leverages Natural Language Processing (NLP) techniques to extract meaningful insights from customer feedback.

---

## 🎯 Problem Statement

E-commerce platforms receive massive volumes of customer reviews. The goal is to:

* Automatically analyze review text
* Classify sentiment (Positive / Negative / Neutral)
* Generate insights to support business decisions

---

## 📂 Dataset

* Dataset used: **Amazon Fine Food Reviews**
* Source: Kaggle
* Link: [https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
* Used only **first 5000 rows** for analysis

---

## 🛠️ Tools & Technologies

* **Python 3.11**
* **Jupyter Notebook**
* **Pandas** → Data loading & preprocessing
* **TextBlob** → Sentiment analysis
* **Matplotlib / Seaborn** → Visualization

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading & Exploration

* Loaded dataset using Pandas
* Checked dataset shape and structure
* Identified review text column

### 2️⃣ Data Cleaning

* Removed null/empty reviews
* Removed duplicate entries
* Selected relevant columns

### 3️⃣ Sentiment Analysis

* Used TextBlob to compute polarity
* Classified sentiments:

  * Positive → polarity > 0
  * Negative → polarity < 0
  * Neutral → polarity = 0

### 4️⃣ Data Visualization

Created multiple charts:

* 📊 Bar Chart → Sentiment distribution
* 🥧 Pie Chart → Percentage of sentiments
* 📈 Custom Chart → (e.g., rating vs sentiment / polarity distribution)

### 5️⃣ Insights & Findings

* Majority of reviews were **positive**
* Negative reviews highlighted issues like:

  * Product quality
  * Packaging problems
  * Taste dissatisfaction
* Key takeaway: Customer satisfaction is high, but specific issues need attention

---

## 📈 Sample Output

* Sentiment classification of reviews
* Visual insights using charts
* Summary report of findings

---

## 📁 Project Structure

```
SentimentAnalysis/
│── analysis.ipynb        # Main notebook
│── Reviews.csv           # Dataset (first 5000 rows)
│── summary.pdf           # Project summary
│── charts/               # Saved visualizations
│    ├── chart1.png
│    ├── chart2.png
│    └── chart3.png
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/alimusharraf/SentimentAnalysis.git
```

2. Navigate to the folder:

```bash
cd SentimentAnalysis
```

3. Install dependencies:

```bash
pip install pandas textblob matplotlib seaborn
```

4. Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 💡 Key Learnings

* Practical use of NLP for real-world data
* Data cleaning and preprocessing techniques
* Sentiment classification using TextBlob
* Data visualization and storytelling

---

## 📌 Future Improvements

* Use advanced models (e.g., VADER, BERT)
* Deploy as a web app using Streamlit
* Add real-time review analysis

---

## 👤 Author

**Musharraf Ali**
