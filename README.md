
# 🎯 YouTube Comment Sentiment Analysis

A machine learning project that performs **sentiment analysis** on YouTube video comments. Users can input the URL of a YouTube video, and the model analyzes the comments to determine the percentage of **positive** and **negative** sentiments.

---

## 📝 Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Project Workflow](#project-workflow)
4. [Tools & Libraries](#tools--libraries)
5. [Implementation](#implementation)
6. [Results](#results)
7. [Future Improvements](#future-improvements)
8. [Getting Started](#getting-started)

---

## 📖 Overview

This project uses **Natural Language Processing (NLP)** to analyze user comments fetched from YouTube. The goal is to classify the comments into positive or negative sentiment and provide a percentage summary of the sentiment distribution.

---

## ✨ Features

- Fetches comments from YouTube using **YouTube Data API v3**.
- Analyzes sentiments using a pre-trained **transformer-based model** (`Hugging Face` pipeline).
- Returns the percentage of **positive** and **negative** comments.
- Provides a foundational ML project for sentiment analysis.

---

## 🛠 Project Workflow

1. Input a YouTube video URL.
2. Extract comments using **YouTube Data API v3**.
3. Preprocess comments (removal of special characters, lowering text, etc.).
4. Perform sentiment analysis using a **pre-trained NLP model**.
5. Display the percentage of positive and negative sentiments.

---

## 🧰 Tools & Libraries

- **Programming Language:** Python
- **ML Model:** [Hugging Face Transformers](https://huggingface.co/transformers)
- **Libraries:**
  - `transformers` for sentiment analysis.
  - `google-api-python-client` to interact with YouTube Data API.
  - `numpy` and `pandas` for data manipulation.
  - `matplotlib` for visualization (optional).
- **Environment:** Jupyter Notebook/Google Colab.

---

## ⚙️ Implementation

### 1. Fetching Comments
- Utilize the **YouTube Data API v3** to fetch the top 50 comments for a given video.
- Requires an API key for authentication.

### 2. Preprocessing
- Clean comments by removing special characters and converting to lowercase.

### 3. Sentiment Analysis
- Use a **pre-trained transformer model** from Hugging Face, such as `distilbert-base-uncased`.
- Classify comments into positive and negative sentiments.

### 4. Results
- Calculate the percentage of positive and negative comments.
- Visualize the results using a pie chart or bar graph.

---

## 📊 Results

Here’s an example output for a test video:

| Metric         | Value       |
|-----------------|-------------|
| **Positive**    | 72%         |
| **Negative**    | 28%         |

### Visualization
A pie chart displaying the sentiment distribution:
- **Positive**: Green
- **Negative**: Red

---

## 🚀 Future Improvements

- **Increase Comment Limit:** Fetch more comments for better accuracy.
- **Custom Training:** Train the sentiment model on domain-specific data for improved performance.
- **Frontend Integration:** Build a user-friendly web app using Flask, FastAPI, or React.
- **Enhanced Metrics:** Add neutral sentiment analysis for a three-way classification.
- **Batch Processing:** Allow analysis of multiple videos simultaneously.

---

## 🛠 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/YouTube-Sentiment-Analysis.git
cd YouTube-Sentiment-Analysis
```

### 2. Install Dependencies
```bash
pip install transformers google-api-python-client numpy pandas
```

### 3. Add Your YouTube API Key
Replace `YOUR_API_KEY` in the code with your API key.

### 4. Run the Model
Run the Jupyter Notebook or Python script:
```bash
python sentiment_analysis.py
```

---


## 🏗 Built With

- **Python**
- **Hugging Face Transformers**
- **YouTube Data API v3**

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

- LinkedIn: (https://www.linkedin.com/in/devanshi-sonara-b7bb171b9/)

```
