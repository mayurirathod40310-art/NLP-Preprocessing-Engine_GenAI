# NLP Preprocessing Engine (Advanced)

##  Overview

This project is part of the Data Science Internship (February 2026).
The main goal is to build a robust NLP preprocessing pipeline that can handle messy real-world text data and convert it into clean and meaningful tokens.

---

##  Features

* Convert text to lowercase
* Remove numbers
* Remove URLs and email patterns
* Handle repeated characters (e.g., "soooo" → "soo")
* Remove special characters and emojis
* Remove extra spaces
* Remove very short words (≤ 2) except "no" and "not"

---

##  Tasks Covered

* Task 1: Conceptual Understanding
* Task 2: Preprocessing Function
* Task 3: Stress Testing
* Task 4: Token Analytics
* Task 5: Frequency Analysis
* Task 6: Full Pipeline
* Task 7: Error Handling

---

##  Sample Input

```
"I absolutely looooved this product 😍😍"
```

##  Sample Output

```
Tokens: ['absolutely', 'looved', 'this', 'product']  
Cleaned Sentence: absolutely looved this product
```

---

##  Key Learnings

* Importance of text preprocessing in NLP
* Handling noisy real-world data
* Tokenization and normalization techniques
* Writing clean and modular Python code

---

## Tech Stack

* Python
* Jupyter Notebook
* Libraries: re, numpy, collections

---

##  How to Run

1. Open the notebook file
2. Run all cells step by step
3. View outputs for each task

---

##  Author

Mayuri Rathod
