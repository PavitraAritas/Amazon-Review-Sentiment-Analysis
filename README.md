# 📦 Amazon-Review-Sentiment-Analysis

<img width="603" height="182" alt="image" src="https://github.com/user-attachments/assets/2f60afe6-8e49-4527-a71d-80b6dbfcc40d" />


## Project Overview

Customer reviews are crucial in making purchasing decisions. This research analyzes Amazon customer sentiment over time to uncover evolving patterns. This research focuses on understanding the patterns in Amazon customer sentiment over time, aiming to uncover what factors like product categories, seasons, or events, affect these shifts. By doing so, businesses can better align their strategies with customer needs and improve satisfaction

### It focuses on two main goals:

Sentiment Classification – categorizing reviews as positive or negative.

Topic Modeling Over Time – identifying key themes that emerge in reviews year by year using BERTopic, a state-of-the-art topic modeling library.


##  Methodology
- **Dataset**: [Kaggle – Amazon Reviews](https://www.kaggle.com/datasets/tarkkaanko/amazon)
- **Preprocessing**: Tokenization, lemmatization (spaCy), stopword removal (NLTK), contraction expansion
- **Sentiment Labeling**: Ratings ≥ 4 = Positive, ≤ 2 = Negative
- **Topic Modeling**: Applied BERTopic year-wise (2012–2014)

---

## Results
- **Frequent Topics**: Battery life, screen quality, packaging, speaker issues
- **Visuals**: Word clouds, bar plots, topic frequency over time
- **Insight**: Customer concerns shifted from hardware to service/software by 2014

---

##  Installation
```bash
pip install pandas nltk spacy contractions tqdm bertopic matplotlib seaborn
python -m nltk.downloader stopwords
python -m spacy download en_core_web_sm
```

---

## ▶️ Run
Launch `Report.ipynb` in Jupyter Notebook and run cells sequentially.

---

## 👤 Author
**Pavitra Aritas Raghunath Sharma**
