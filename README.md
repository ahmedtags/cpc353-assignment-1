# CPC353 - Natural Language Processing (Assignment 1)

This repository contains the Jupyter Notebook implementation and PDF report for **CPC353: Natural Language Processing - Assignment 1** (Semester 1, Academic Session 2025/2026) at Universiti Sains Malaysia (USM).

## Course Details
- **Course Code:** CPC353
- **Course Name:** Natural Language Processing
- **Semester:** Semester 1, Year 3 (2025/2026)
- **Project Title:** Exploring Game Reviews using N-gram and Part-of-Speech Analysis

---

## Assignment Overview

The goal of this assignment is to perform natural language processing on a corpus of video game reviews. The project implements:
1. **Data Pre-processing:** Tokenization, lowercasing, punctuation removal, and stopword filtering.
2. **N-gram Analysis:** Extraction and frequency analysis of unigrams, bigrams, and trigrams to discover common themes and patterns in game reviews.
3. **Part-of-Speech (POS) Tagging:** Categorizing tokens (e.g., nouns, verbs, adjectives) and identifying the most common descriptive words used by players.
4. **Sentiment / Semantic Context:** Using R/Python NLTK libraries to draw insights into player sentiment and review descriptions.

---

## What I Did
- Wrote the Python/Jupyter notebook implementation [`CPC353 Text Analysis.ipynb`](CPC353%20Text%20Analysis.ipynb) using NLTK, pandas, and matplotlib.
- Compiled the methodology, charts, N-gram tables, and linguistic interpretations in the final group report: [`Report_Assignment_CPC353_GROUP27.pdf`](Report_Assignment_CPC353_GROUP27.pdf).
- Included the original assignment guidelines: [`251 CPC353 Assignment 1 Guideline.pdf`](251%20CPC353%20Assignment%201%20Guideline.pdf).

---

## Tools & Tech Stack
- **Language:** Python (Jupyter Notebook)
- **Libraries:** NLTK, pandas, matplotlib, WordCloud
- **Environment:** Google Colab / Jupyter

---

## How to Run

1. Install Jupyter notebook or upload [`CPC353 Text Analysis.ipynb`](CPC353%20Text%20Analysis.ipynb) to Google Colab.
2. Install dependencies:
   ```bash
   pip install nltk pandas matplotlib wordcloud
   ```
3. Run the cells sequentially to load the review corpus, perform tokenization, extract N-grams, run POS tagging, and view the word distributions.

---

## 📸 Sample Output

Here are the text analysis results extracted from running [`CPC353 Text Analysis.ipynb`](CPC353%20Text%20Analysis.ipynb):

### 1. N-Gram Analysis (Top Words & Phrases)

- **Top Positive Bigrams:**
  - `best game`: 2
  - `not think`: 1
  - `think would`: 1
  - `would ever`: 1
  - `ever experience`: 1
  - `experience overwhelming`: 1

- **Top Negative Bigrams:**
  - `game extremely`: 1
  - `extremely good`: 1
  - `good however`: 1
  - `however wait`: 1
  - `wait awhile`: 1

- **Top Positive Trigrams:**
  - `not think would`: 1
  - `think would ever`: 1
  - `would ever experience`: 1
  - `ever experience overwhelming`: 1

- **Top Negative Trigrams:**
  - `game extremely good`: 1
  - `extremely good however`: 1
  - `good however wait`: 1
  - `however wait awhile`: 1
  - `wait awhile planning`: 1

---

### 2. Part-of-Speech (POS) Tagging Distributions

- **Top Part-of-Speech Counts (Positive Reviews):**
  - **NN** (Noun, singular): 39
  - **JJ** (Adjective): 18
  - **RB** (Adverb): 10
  - **NNS** (Noun, plural): 10
  - **VBG** (Verb, gerund/present participle): 7

- **Top Part-of-Speech Counts (Negative Reviews):**
  - **NN** (Noun, singular): 23
  - **JJ** (Adjective): 18
  - **RB** (Adverb): 14
  - **NNS** (Noun, plural): 7
  - **VBD** (Verb, past tense): 6

---

### 3. Descriptive Words (Top Adjectives)
- **Positive Reviews:** `immersive`, `favorite`, `creative`, `overall`, `long`, `pixel`.
- **Negative Reviews:** `good`, `major`, `super`, `repetitive`, `boring`, `empty`, `dull`.

