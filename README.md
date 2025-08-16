# 🔤 Auto-Correct Tool

This project implements an **Auto-Correct system** using Natural Language Processing techniques. It identifies misspelled words and suggests the most probable corrections based on frequency and similarity to known words.

## 🚀 Features

* Detects misspelled words in user input
* Suggests the most likely correction
* Uses **edit distance** (Levenshtein distance) for similarity
* Considers **word frequency** to rank suggestions
* Lightweight and efficient – can be extended to chatbots or writing assistants

## 🛠️ Tech Stack

* **Python 3.x**
* **NLTK** – for tokenization, corpus-based word frequency
* **Regex** – for text cleaning
* **Pandas / NumPy** – data handling and analysis

## 📂 Workflow

1. **Load Corpus** – prepare a dataset of valid words and their frequencies
2. **Preprocessing** – tokenize and normalize text
3. **Error Detection** – find words not in the dictionary
4. **Correction Algorithm** – generate candidate corrections based on:

   * Deletion
   * Insertion
   * Substitution
   * Transposition
5. **Ranking** – choose the most likely word based on frequency

## ▶️ How to Run

1. Clone this repository

   ```bash
   git clone https://github.com/prakashsaialla/auto-correct-tool.git
   cd auto-correct-tool
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook

   ```bash
   jupyter notebook Auto-Correct-Tool.ipynb
   ```

4. Try correcting a sentence:

   ```python
   correct_sentence("I lvoe progrmming in Pythn")
   # Output: "I love programming in Python"
   ```

## 📌 Future Improvements

* Integrate with a **chatbot or writing app**
* Extend dictionary with domain-specific vocabulary
* Use **deep learning models** for contextual spelling correction

## 📜 License

This project is licensed under the MIT License – feel free to use and modify.

---
