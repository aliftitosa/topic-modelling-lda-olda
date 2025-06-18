# Twitter Topic Modeling using LDA (Latent Dirichlet Allocation) & OLDA (Online Latent Dirichlet Allocation)

This project is part of my undergraduate thesis at Universitas Islam Negeri Syarif Hidayatullah Jakarta. It uses topic modeling with **Online Latent Dirichlet Allocation (OLDA)** to discover the most discussed topics on Twitter using specific keywords.

## 👨‍💻 Author
**Alif Tito Shiddiq ArRosyid**

---

## 📌 Project Description

This Python project collects Twitter data using the Twitter API, preprocesses the text, and performs topic modeling using the **LDA** & **OLDA** algorithm from the Gensim library.

**Case Study:**  
Topic analysis on tweets containing the keyword **"pemerintah"** (Indonesian for "government").

---

## 🧰 Tools & Libraries Used

- `Python`
- `Tweepy` — to fetch tweets from Twitter API
- `NLTK` — for tokenization
- `Sastrawi` — for Indonesian stemming
- `Gensim` — to build the LDA model
- `Matplotlib` — for plotting
- `json`, `datetime`, `slangword`, `stopword` — for processing

---

## 📁 Project Structure

```
twitter-topic-modeling/
│
├── data/                         # Input/output data
│   └── tweets.json
│
├── src/                          # Source code
│   ├── listener.py              # Collect tweets using Twitter API
│   ├── preprocessing.py        # Clean and preprocess text
│   ├── lda_model.py            # Build and visualize LDA topics
│
├── images/                      # Visualizations (optional)
│
├── main.py                      # Entry point for full pipeline
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/twitter-topic-modeling.git
cd twitter-topic-modeling
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the Pipeline

```bash
python main.py
```

---

## 📊 Output

- Top topics discussed on Twitter using a given keyword
- LDA topic distribution and coherence score
- Visualized result (optional)

---

## 📮 Notes

- To use live Twitter streaming, you must provide your own Twitter Developer credentials.
- This project is tailored for Bahasa Indonesia texts.
