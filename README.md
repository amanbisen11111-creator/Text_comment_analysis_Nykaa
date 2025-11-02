# 🧠 Nykaa Text Analysis Project

## 📘 Overview
This project performs **text analysis on customer reviews** from the **Nykaa app** to understand user opinions, identify key sentiments, and discover common keywords that influence customer satisfaction.

Using **Natural Language Processing (NLP)** and **Python**, the notebook cleans, processes, and analyzes review text data to generate meaningful insights that can help businesses make data-driven decisions.

---

## 🎯 Objectives
- Perform text preprocessing (tokenization, stopword removal, etc.)
- Identify and visualize the most frequent words used in reviews
- Conduct **sentiment analysis** to understand customer emotions
- Generate useful insights from customer feedback

---

## 🧩 Technologies Used
- **Python 3**
- **Jupyter Notebook**
- **Libraries:**
  - `pandas` – for data manipulation  
  - `nltk` – for natural language processing  
  - `re` – for text cleaning using regular expressions  
  - `matplotlib` / `wordcloud` – for visualization  

---

## ⚙️ How It Works
1. **Import Dataset** – Load the review dataset (Nykaa app reviews).
2. **Preprocess Text** – Clean text by removing punctuation, numbers, and stopwords.
3. **Tokenize Words** – Break sentences into individual words.
4. **Generate Word Frequency** – Find and visualize most common words.
5. **Sentiment Analysis (Optional)** – Detect positive, neutral, and negative sentiments.
6. **Output Results** – Save processed data into a new file (`preprocessed_caption.xlsx` or similar).

---

## 📊 Example Insights
- Most common positive keywords: *“love”, “amazing”, “great”, “product”*  
- Most common negative keywords: *“worst”, “bad”, “delayed”, “broken”*  
- Sentiment Distribution: **65% Positive**, **25% Neutral**, **10% Negative**

*(These are example results — actual values depend on dataset.)*

---

## 🪜 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Nykaa-Text-Analysis.git
   cd Nykaa-Text-Analysis
