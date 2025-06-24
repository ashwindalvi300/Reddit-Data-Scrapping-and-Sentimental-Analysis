# Reddit-Data-Scrapping-and-Sentimental-Analysis

This project performs sentiment analysis on Reddit posts related to TCL NXTPAPER mobile and tablet devices. It uses the Reddit API (via `PRAW`) to scrape relevant posts and then applies LLaMA-3-based sentiment classification and category tagging. Finally, it visualizes the results using Plotly.

---

## 🚀 Features

- ✅ Scrapes Reddit posts for multiple TCL NXTPAPER models.
- ✅ Performs text preprocessing and cleanup.
- ✅ Uses LLaMA-3 API to classify sentiment (Very Positive to Very Negative) and tag categories (Design, Performance, Features, etc.).
- ✅ Exports labeled data to CSV (`sent_demo.csv`).
- ✅ Visualizes sentiment distribution with interactive Plotly graphs.

---

## 📦 Technologies Used

- Python
- [PRAW](https://praw.readthedocs.io/) – Reddit API Wrapper
- Pandas & NumPy
- Plotly (for data visualization)
- LLaMA-3 API (for text classification via HTTP requests)
- Regex & JSON (for parsing outputs)

---
