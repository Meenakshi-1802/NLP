# ⚙️ NLP Package Installation 

Before running any NLP programs, make sure to install the required Python packages.

---

## 📌 Step 1: Install `nltk`

Install the Natural Language Toolkit using pip:


---

## 📌 Step 2: Import and Download Required NLTK Resources

Once `nltk` is installed, open your Python file or notebook and download the required resources:

```python
import nltk

# Download tokenizers, stopwords, and taggers
nltk.download('punkt')                         # For tokenization
nltk.download('stopwords')                     # For stopword removal
nltk.download('averaged_perceptron_tagger')    # For POS tagging
nltk.download('wordnet')                       # For lemmatization



