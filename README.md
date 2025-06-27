# 🎥 YouTube Video Summarizer and Analyzer Using NLP

This project is a Jupyter Notebook (`main.ipynb`) powered by **Streamlit**, allowing users to summarize and analyze the transcript of any YouTube video using various Natural Language Processing (NLP) techniques.

---

## 📌 Features

- 🔍 **Transcript Extraction**  
  Automatically fetches the transcript of a YouTube video using the `youtube-transcript-api`.

- ✂️ **Summarization**  
  Uses Hugging Face's `transformers` pipeline to summarize the entire transcript text into a readable paragraph.

- 🔑 **Keyword Extraction**  
  Applies tokenization, lemmatization, and filtering to identify the most important words from the transcript.

- 🧠 **Topic Modeling**  
  Implements Latent Dirichlet Allocation (LDA) from `scikit-learn` to detect major topics in the transcript.

- 😊 **Sentiment Analysis**  
  Uses `TextBlob` to extract sentiment polarity and subjectivity scores.

---

## 🚀 How to Run the Project

### 1. Clone or Download the Repository

git clone [https://github.com/Indranil1105/YouTube-Video-Summarizer-and-Analyzer-Using-NLP.git](https://github.com/Indranil1105/YouTube-Video-Summarizer-and-Analyzer-Using-NLP.git)
cd your-repo-name

### 2. Install Dependencies
Create a virtual environment (optional but recommended), then install the packages listed in requirements.txt:


pip install -r requirements.txt

This will install the following major packages:

 streamlit

youtube-transcript-api

nltk

scikit-learn

transformers

textblob

numpy

tensorflow

tf-keras


### 3. Download NLTK Data
   
Inside the notebook, make sure these are downloaded:

import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')

### 4. Run the App
If you're using Streamlit inside a Jupyter Notebook file, either:

Convert to .py and run with:


streamlit run main.py
(You can convert with jupyter nbconvert --to script main.ipynb)

Or copy the code from main.ipynb into a Python script like app.py.

# 🧪 Example Use Cases
Auto-generate summaries of educational, news, or interview videos

Extract keywords and sentiments for market or audience analysis

Use for content moderation, archiving, or indexing

# 📄 File Overview
main.ipynb – The core Streamlit app with summarization, keyword extraction, and sentiment analysis

requirements.txt – All required Python libraries

README.md – This documentation file

