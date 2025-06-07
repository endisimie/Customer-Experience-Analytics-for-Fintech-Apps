# Task 1: Data Collection and Preprocessing

## 📌 Objective

The goal of Task  is to collect raw mobile app reviews from the Google Play Store and perform basic preprocessing to prepare the data for sentiment and thematic analysis.

---

## 📥 Data Collection

- Source: Google Play Store
- Apps: [CBE,BOA,Dashn]
- Number of Reviews Collected: [e.g., 5,000]
- Format: CSV (`raw_reviews.csv`)
- Tools Used:
  - `google-play-scraper` for data extraction
  - `pandas` for data handling

---

## 🧹 Data Preprocessing

### Steps Performed:
1. **Lowercasing** – Converted all text to lowercase.
2. **Tokenization** – Split review text into individual words.
3. **Stopword Removal** – Removed common English stopwords.
4. **Lemmatization** – Reduced words to their base (lemma) form.
5. **Alphanumeric Filtering** – Removed non-alphanumeric tokens.

### Tools & Libraries:
- `nltk` for text preprocessing
- `pandas` for data manipulation




