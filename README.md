# publication-scraper
# 🔍 Publication Search Engine (Web Crawling + NLP + Text Classification)

A custom-built search engine that crawls academic publications, preprocesses content using NLP, builds an inverted index for fast search, and includes sentiment/text classification utilities.

---

##  Features

- Crawl publication titles, authors, and links from university websites
- Build inverted index using NLTK (tokenizing, stemming, stopwords removal)
- Search engine with relevance ranking (based on term match frequency)
- Optional classification features (sentiment / topic categorization)
- Interactive CLI loop for search experience
---

## Tech Stack

- Python  
- BeautifulSoup (for scraping)  
- NLTK (for NLP & IR)  
- Requests  
- Optional: Scikit-learn (for future text classification)

---

## How It Works

1. `crawl_and_parse()` – Fetches publication data from multiple pages  
2. `build_inverted_index()` – Constructs a term-to-document map  
3. `search_publications(query)` – Accepts user query and ranks documents  
4. (Optional) Add `classify_text()` – For binary/multi-class sentiment analysis

---

## Future Enhancements

- Add web UI or Streamlit frontend  
- Integrate with ElasticSearch  
- Add cosine similarity or TF-IDF scoring  
- Expand to other academic databases (arXiv, Springer)

---

## Note

- This tool is for educational/demo purposes.  
- Dataset scraped from a public university website.



