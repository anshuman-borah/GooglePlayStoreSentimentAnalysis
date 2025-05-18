# 📱 Google Play Store Sentiment Analysis

This project performs **sentiment analysis** on user reviews from the **Google Play Store**, classifying them into _Positive_, _Negative_, or _Neutral_ categories using a simple yet effective keyword-based approach. 📊

---

## 🔧 Tools & Technologies Used

- **Programming Language:** Python  
- **IDE:** Jupyter Notebook / VS Code  
- **Libraries:**  
  - `pandas` – for data manipulation  
  - `numpy` – for numerical operations  
  - `matplotlib`, `seaborn` – for multiple visualizations  
  - (Optional) `wordcloud` – for generating word cloud visuals  

---

## 🧠 How It Works

1. **Data Loading:** Load Google Play Store reviews dataset (usually in CSV format).
2. **Preprocessing:**  
   - Convert text to lowercase  
   - Remove punctuation, special characters, etc.  
3. **Keyword-Based Sentiment Classification:**  
   - Define sets of keywords for _positive_, _negative_, and _neutral_ sentiment.  
   - Check each review for presence of those keywords.  
   - Assign a sentiment label based on keyword matches.
4. **Visualization:**  
   - **Bar Charts:** Sentiment distribution  
   - **Pie Charts:** Percentage of each sentiment  
   - **Word Clouds:** Frequently used words in each sentiment class  
   - **Line/Time Series (if timestamped):** Trend of sentiments over time  

---

## 📈 Output & Results

Here’s what the project outputs:
- Overall sentiment distribution using bar & pie charts  
- Top frequent words in positive, negative, and neutral reviews  
- Optional: Trend analysis of sentiments (if data contains timestamps)

---

## 🚀 How to Run the Project

### 1. Clone this repository

```bash
git clone https://github.com/your-username/playstore-sentiment-analysis.git
cd playstore-sentiment-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is not available, install libraries manually:
```bash
pip install pandas numpy matplotlib seaborn wordcloud
```

### 3. Run the Notebook or Script

- Jupyter Notebook:
```bash
jupyter notebook sentiment_analysis.ipynb
```

- Python script:
```bash
python sentiment_analysis.py
```
---

## ✅ Future Improvements

- Use **Natural Language Processing (NLP)** libraries like `TextBlob` or `VADER` for more accurate classification.
- Integrate **Machine Learning models** (e.g., Logistic Regression or SVM).
- Deploy as a **web app** using Flask or Streamlit.

---

## 🙌 Acknowledgements

- Google Play Store dataset source  
- Open-source Python community
