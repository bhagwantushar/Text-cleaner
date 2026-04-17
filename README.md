# Sentiment Analysis Assignment

## About this
This was part of my Text Processing module where I worked on building a sentiment analysis system.

The goal was to understand how different approaches (machine learning vs rule-based) perform on real datasets.

---

## What I implemented

### 1. Naive Bayes Classifier
I trained a Naive Bayes model on movie reviews and tested it on:
- Film dataset
- Nokia product reviews

### Observations
- Performed well on training data (~89% accuracy)
- Dropped on test data (~77%) → shows overfitting
- Performed poorly on Nokia dataset (~61%)

This shows that models trained on one domain don’t always generalise well.

---

### 2. Rule-Based (Dictionary) Model
I also implemented a dictionary-based approach using:
- positive and negative word lists

### Observations
- Worked better on Nokia dataset
- Struggled with context and sentence structure

---

### 3. Improvements I made
To improve the rule-based model, I added:
- Negation handling (e.g., "not good")
- Intensifiers (e.g., "very", "extremely")
- Diminishers (e.g., "a bit", "slightly")

This improved performance, especially on the Nokia dataset.

---

## Key Learnings

- Machine learning models adapt better but depend on training data
- Rule-based models are simple but lack context understanding
- Handling negation and modifiers is very important in NLP
- Models can easily misinterpret sentences like:
  - "not good"
  - "hardly useful"

---

## Why models made mistakes

From error analysis:

- Naive Bayes ignores word order  
  → treats "not good" as positive  

- Rule-based model:
  - misses context
  - struggles with modifiers
  - depends heavily on word lists

---

## Files
- report.pdf → full assignment report
- text Processing.py → implementation

---

## Note
This is academic coursework and was done as part of my university module.
