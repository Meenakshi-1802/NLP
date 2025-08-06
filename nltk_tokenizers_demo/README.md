# 🧠 NLP Tokenization using NLTK Tokenizers

This demonstrates the use of different **tokenizers** provided by the **NLTK (Natural Language Toolkit)** library in Python to break down a sample sentence into tokens using various approaches.

---

## 📌 What is Tokenization?

Tokenization is the process of splitting a sentence into smaller parts called **tokens**, which could be:
- Words
- Punctuation marks
- Hashtags
- Mentions
- Emojis, etc.

---

## 🧰 Tokenizers Used in This Project

### 1. 🐦 TweetTokenizer
- Designed for social media text (especially tweets)
- Keeps emojis, hashtags, mentions (`@user`), etc.
- Handles common tweet structures like smileys and abbreviations

---

### 2. 🔗 MWETokenizer (Multi-Word Expression Tokenizer)
- Treats multi-word expressions like `Republic Day` or `Indian Army` as single tokens.
- Very useful when working with named entities or phrases.

---

### 3. 🔍 RegexpTokenizer (Regular Expression Tokenizer)
- Uses a regular expression (pattern) to define how to split tokens.
- Allows for full control over what counts as a "word".
- Example: `\w+|\$[\d\.]+|\S+` splits words, numbers, and punctuations properly.

---

### 4. ␣ WhitespaceTokenizer
- Splits text **only on whitespace**.
- Doesn't handle punctuation separately.
- Good for simple pre-tokenized inputs.

---

### 5. 🧩 WordPunctTokenizer
- Splits text into **words and punctuation separately**.
- Very granular. Good for tasks needing punctuation awareness.

---



