# 📘 English-to-French Word Frequency Translator

This project processes a list of English words, translates them into French using a local dictionary, and calculates the frequency of each word. It is designed to be fast, offline, and memory-efficient—ideal for language analysis, NLP preprocessing, or educational tools.

---

## 📂 Project Structure

- `find_words.txt` — Input file containing English words (one per line)
- `french_dictionary.csv` — English to French dictionary (CSV with 2 columns)
- `Translator.ipynb` — Jupyter Notebook with the full pipeline
- `Frequency.csv` — Output file with English word, French translation, and frequency
- `performance.txt` — Time and memory performance summary

---

## 🚀 Features

- ✅ Fast local translation using dictionary lookup (no API delay)
- ✅ Word frequency computation
- ✅ Saves final results to CSV for easy analysis
- ✅ Tracks runtime and memory usage
- ✅ Works completely offline

---

## 🔧 How It Works

1. Reads English words from `find_words.txt`
2. Loads translations from `french_dictionary.csv`
3. Translates each word using a Python dictionary
4. Counts frequency of each word
5. Outputs results as `Frequency.csv`

---

## 📊 Output Example

| English_word | French_word | Frequency |
|--------------|-------------|-----------|
| love         | amour       | 2         |
| truth        | vérité      | 1         |
| war          | guerre      | 2         |

---

## 🛠️ Technologies Used

- Python (Pandas, I/O, Dictionary operations)
- Jupyter Notebook
- psutil (for memory tracking)

---

## 🧠 Use Cases

- Language learning tools
- Natural Language Processing (NLP) preprocessing
- Word usage analysis in literature
- Educational text mining projects

---

## 📈 Performance

- Fast execution (under a second on sample data)
- Low memory usage (under 20MB for sample runs)

---

## 🧹 To Run the Project

1. Clone or download the repo
2. Place `find_words.txt` and `french_dictionary.csv` in the same folder
3. Open `Translator.ipynb` in Jupyter and run all cells
