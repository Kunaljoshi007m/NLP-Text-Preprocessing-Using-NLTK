# NLP Text Preprocessing Using NLTK

A Python-based **Natural Language Processing (NLP)** project demonstrating fundamental text preprocessing and text analysis techniques using **NLTK**.

The project uses **The Hungry Mouse** as the sample text and demonstrates sentence tokenization, word tokenization, punctuation removal, stopword removal, frequency analysis, word cloud generation, stemming, and lemmatization.

---

## 📌 Project Overview

This project demonstrates the basic workflow of processing and analyzing natural language text.

The project covers:

- Reading text from a `.txt` file
- Identifying the datatype of the loaded text
- Sentence tokenization
- Word tokenization
- Word frequency analysis
- Frequency distribution visualization
- Punctuation removal
- Lowercase conversion
- Stopword identification
- Stopword removal
- Frequency analysis after preprocessing
- Word Cloud generation
- Custom-shaped Word Cloud generation
- Stemming
- Lemmatization
- Comparison of stemming and lemmatization

---

## 📄 Input Text

The primary input for the project is:

**`The hungry mouse.txt`**

The **`The hungry mouse.txt`** file is included in this repository and is used as the primary text source for the NLP analysis.

---

## 🔤 Text Loading

The project begins by reading the contents of the text file and storing the complete text as a Python string.

The loaded text is then used as input for the different NLP preprocessing and analysis techniques.

---

## 🔢 Sentence Tokenization

Sentence tokenization divides the complete text into individual sentences.

The project uses NLTK's sentence tokenization functionality to identify separate sentences within the text.

The provided text contains:

**21 sentences**

---

## 🔠 Word Tokenization

Word tokenization divides the text into individual words and punctuation tokens.

The project uses NLTK word tokenization to convert the text into a list of tokens.

The original text contains:

**285 tokens**

These tokens include both words and punctuation marks.

---

## 📊 Word Frequency Analysis

The project calculates the frequency of individual tokens using a frequency distribution.

This helps identify which words or tokens occur most frequently in the text.

The frequency distribution is also represented graphically to provide a visual understanding of the most common tokens.

---

## 🧹 Punctuation Removal

Punctuation is removed from the tokenized text.

The words are also converted to lowercase so that uppercase and lowercase versions of the same word are treated consistently.

After punctuation removal:

**244 words**

remain in the processed text.

---

## 📈 Frequency Analysis After Punctuation Removal

After removing punctuation, a new frequency distribution is generated.

The most frequently occurring words include:

- `the`
- `she`
- `mouse`
- `a`
- `to`
- `her`
- `basket`
- `of`
- `come`
- `out`

The frequency distribution is also visualized using a graph.

---

## 🛑 Stopword Removal

The project uses the English stopword list provided by NLTK.

Stopwords are commonly occurring words that may provide limited value for certain text analysis tasks.

Examples include:

- `the`
- `is`
- `was`
- `and`
- `to`
- `of`
- `for`
- `with`

The project removes stopwords from the cleaned word list.

After stopword removal:

**130 words**

remain.

---

## 📊 Frequency Analysis After Stopword Removal

A new frequency distribution is created after removing stopwords.

The most frequently occurring meaningful words include:

| Word | Frequency |
|---|---:|
| mouse | 9 |
| basket | 5 |
| come | 5 |
| food | 4 |
| days | 4 |
| hole | 4 |
| corns | 3 |
| ate | 3 |
| fat | 3 |
| rat | 3 |

This provides a clearer view of the important words in the text after preprocessing.

---

## ☁️ Word Cloud

The project generates a **Word Cloud** to visually represent word frequencies.

Words that occur more frequently appear more prominently in the generated Word Cloud.

The project includes:

- Standard Word Cloud
- Custom-shaped Word Cloud

A mask image is used to create the custom-shaped Word Cloud.

---

## 🌱 Stemming

Stemming reduces words to their root or stem form by removing or modifying word endings.

The project uses the **Porter Stemmer** from NLTK.

The project demonstrates stemming using different word forms and shows how they can be reduced to a common stem.

Stemming may sometimes produce a result that is not a complete dictionary word.

---

## 🌿 Lemmatization

Lemmatization converts words into their meaningful dictionary base form.

The project uses the **WordNet Lemmatizer** from NLTK.

Examples demonstrated in the project include:

- `leaves` → `leaf`
- `mouse` → `mouse`
- `dead` → `dead`

The output of lemmatization can also depend on the part-of-speech information provided to the lemmatizer.

---

## 🔄 Stemming vs Lemmatization

| Feature | Stemming | Lemmatization |
|---|---|---|
| Method | Rule-based word reduction | Dictionary-based normalization |
| Output | Stem/root-like form | Meaningful base form |
| Dictionary word | Not always | Generally |
| Example | `leaves` → `leav` | `leaves` → `leaf` |
| Processing | Generally simpler | More linguistically informed |

The project demonstrates both techniques to show their differences in NLP preprocessing.

---

## 🧩 NLP Workflow

```text
The hungry mouse.txt
        ↓
Read Text
        ↓
Sentence Tokenization
        ↓
Word Tokenization
        ↓
Frequency Distribution
        ↓
Remove Punctuation
        ↓
Convert to Lowercase
        ↓
Frequency Distribution
        ↓
Remove Stopwords
        ↓
Frequency Distribution
        ↓
Word Cloud
        ↓
Stemming
        ↓
Lemmatization
```

---

## 📊 Graphs and Visualizations

The project includes graphical analysis of the processed text.

The visualizations include:

- Frequency distribution of original tokens
- Frequency distribution after punctuation removal
- Frequency distribution after stopword removal
- Standard Word Cloud
- Custom-shaped Word Cloud

These visualizations help understand the frequency and distribution of words within the text.

---

## 🛠️ Technologies Used

- Python
- NLTK
- NumPy
- Matplotlib
- WordCloud
- Pillow

---

## 📚 Libraries Used

| Library | Purpose |
|---|---|
| NLTK | Natural Language Processing and text preprocessing |
| NumPy | Numerical operations and image mask handling |
| Matplotlib | Frequency graphs and data visualization |
| WordCloud | Word Cloud generation |
| Pillow | Loading and processing the Word Cloud mask image |

---

## 📦 Installation

Install all required Python libraries using:

```bash
pip install nltk numpy matplotlib wordcloud pillow
```

---

## ⬇️ NLTK Resources

The project uses NLTK resources for:

- Tokenization
- Stopwords
- WordNet
- Lemmatization

The required NLTK resources are downloaded during the project workflow.

If the required resources are not already available, they need to be downloaded before running the NLP analysis.

---

## ▶️ How to Run

### 1. Clone the Repository

Clone the repository to your local machine.

### 2. Install Dependencies

Install the required Python libraries:

```bash
pip install nltk numpy matplotlib wordcloud pillow
```

### 3. Keep the Input Text File

Make sure the following file is present in the repository:

**`The hungry mouse.txt`**

### 4. Open the Notebook

Open the project notebook using:

- Jupyter Notebook
- JupyterLab
- Google Colab
- VS Code

### 5. Run the Notebook

Run the notebook cells sequentially to reproduce:

- Text loading
- Sentence tokenization
- Word tokenization
- Frequency analysis
- Punctuation removal
- Stopword removal
- Graphs
- Word Clouds
- Stemming
- Lemmatization

---

## 📁 Repository Structure

```text
NLP-Text-Preprocessing-Using-NLTK/
│
├── README.md
├── The hungry mouse.txt
└── NLP_Text_Preprocessing.ipynb
```

### Files

**`README.md`**

Project documentation.

**`The hungry mouse.txt`**

The primary text file used for NLP analysis.

**`NLP_Text_Preprocessing.ipynb`**

Jupyter Notebook containing the NLP preprocessing and analysis workflow.

**`square.png`**

Mask image used for generating the custom-shaped Word Cloud.

---

## 📌 Analysis Results

The provided analysis produces the following results:

| Processing Stage | Result |
|---|---:|
| Number of Sentences | 21 |
| Original Tokens | 285 |
| After Punctuation Removal | 244 |
| After Stopword Removal | 130 |

The most frequent meaningful word after stopword removal is:

**`mouse` — 9 occurrences**

Other frequently occurring words include:

- `basket`
- `come`
- `food`
- `days`
- `hole`
- `corns`
- `ate`
- `fat`
- `rat`

---

## 🎯 Learning Objectives

This project demonstrates practical understanding of:

- Natural Language Processing
- Text preprocessing
- Sentence tokenization
- Word tokenization
- Frequency distribution
- Punctuation removal
- Lowercase conversion
- Stopword removal
- Word frequency analysis
- Data visualization
- Word Cloud generation
- Custom-shaped Word Cloud
- Stemming
- Lemmatization
- NLTK

---

## ✨ Key Features

- Text file-based NLP analysis
- Sentence tokenization
- Word tokenization
- Frequency distribution
- Frequency graphs
- Punctuation removal
- Stopword removal
- Word Cloud generation
- Custom-shaped Word Cloud
- Porter Stemming
- WordNet Lemmatization
- Stemming and Lemmatization comparison
- Jupyter Notebook-based analysis

---

## 📚 Educational Purpose

This project provides a practical introduction to **Natural Language Processing using Python and NLTK**.

It demonstrates how raw text can be processed step-by-step:

```text
Raw Text
   ↓
Tokenization
   ↓
Cleaning
   ↓
Punctuation Removal
   ↓
Stopword Removal
   ↓
Frequency Analysis
   ↓
Visualization
   ↓
Stemming
   ↓
Lemmatization
```

---

## 👨‍💻 Author

**Kunal Joshi**

---

## ⭐ Conclusion

**NLP Text Preprocessing Using NLTK** demonstrates fundamental Natural Language Processing techniques using **The Hungry Mouse** as the input text.

The project covers the basic NLP preprocessing workflow, including tokenization, punctuation removal, stopword removal, frequency analysis, Word Cloud generation, stemming, and lemmatization.

It provides a practical foundation for understanding how raw text can be cleaned, processed, analyzed, and visualized using Python and NLTK.
