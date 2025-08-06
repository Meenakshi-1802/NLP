# 🧠 Regex Stemming with NLTK

This demonstrates how to use **NLTK's RegexpStemmer** to perform custom stemming using regular expressions.

---

## 💡 What is Stemming?

**Stemming** is the process of reducing a word to its root or base form.

Examples:
- "playing" → "play"
- "running" → "run"
- "swimming" → "swim"

---

## 🔍 What is RegexpStemmer?

`RegexpStemmer` allows us to create **custom rules** for stemming using **regular expressions** (regex).

---

## 🧪 What Does This Code Do?

- Uses the regex `'ing$'` to remove `"ing"` at the **end** of any word.
- Only applies to words with **minimum 4 characters**.
- Leaves other words untouched.

---

