# 🧹 Clean Text with Python using Regular Expressions

This is a simple Python script to clean and preprocess raw text by removing unwanted characters such as punctuation, special symbols, hashtags, mentions, and emails. It is very useful for beginners learning **NLP (Natural Language Processing)**.

---

## ✅ What This Script Does

- Removes:
  - Punctuation marks (like `!`, `.`, `,`, etc.)
  - Special characters (`@`, `#`, `:`, etc.)
  - Underscores (`_`)
  - Email addresses (treated as normal words and broken into parts)
- Returns: A **list of clean words** from the sentence

---

## 📌 Example Sentence

sentence = 'Sunil tweeted, "Witnessing 70th Republic Day of India from Rajpath, \
New Delhi. Mesmerizing performance by Indian Army! Awesome airshow! @india_official \
@indian_army #India #70thRepublic_Day. For more photos ping me sunil@photoking.com :)"'


## ⚙️ Output

['Sunil', 'tweeted', 'Witnessing', '70th', 'Republic', 'Day', 'of', 'India',
 'from', 'Rajpath', 'New', 'Delhi', 'Mesmerizing', 'performance', 'by',
 'Indian', 'Army', 'Awesome', 'airshow', 'india', 'official', 'indian',
 'army', 'India', '70thRepublic', 'Day', 'For', 'more', 'photos', 'ping',
 'me', 'sunil', 'photoking', 'com']

---

## 🧠 Concepts Used
re.sub() – to substitute unwanted characters

Regular Expression Pattern:

r'([^\s\w]|_)+'

\s → whitespace

\w → word characters (letters, digits, underscore)

^ → not

So it matches anything except word characters and spaces

---
