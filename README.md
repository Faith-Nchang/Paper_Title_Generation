# Paper_Title_Generation
 filter out which paper titles from research papers could be playful, funny, etc.


# Project Overview

This project focuses on **adding filters to research paper titles**. The goal is to classify, clean, or enhance titles based on keywords, sentiment, or other custom rules to make them more readable, accurate, or playful.

# Features

- **Title Filtering:** Remove or flag inappropriate, irrelevant, or overly complex words.
- **Keyword-based Classification:** Detect themes or categories in titles.
- **Sentiment Analysis:** Optional sentiment-based filtering or scoring.
- **Dataset-ready:** Works with datasets containing `title` and `abstract` columns.

# Project Status

**Completed**
- Utilized regex keyword filters to add filter tags to article title
- Used Gemini model for some sentiment analysis of the title
  

**In Progress**
- Fine-tuning a Hugging Face model to generate paper titles from abstracts

# Setup

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

# Dataset 
- Download the data set from : https://arxiv.org/abs/2502.20582
  

