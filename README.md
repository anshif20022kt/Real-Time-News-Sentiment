# Real-Time News Sentiment Dashboard

This project is a **real-time news sentiment classification and visualization dashboard**. It fetches the latest news headlines from **NewsAPI** (with **GNews** fallback), classifies each headline as **Positive** or **Negative**, and visualizes the results in a Streamlit dashboard.

---

## Features

- Fetch real-time news from **NewsAPI** or **GNews**.
- Classify headlines as **Positive** or **Negative** using **TextBlob**.
- Store predictions in **Parquet** files for history tracking.
- Visualize:
  - Latest headlines with sentiment.
  - Sentiment distribution (bar chart).
  - Positive sentiment trend over time (line chart).
- Fully deployable on **Streamlit Cloud**.

---

## Requirements

Python 3.9+ with the following packages:

```bash
streamlit
pandas
plotly
textblob
gnews
requests
pyarrow
