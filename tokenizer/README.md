This repository contains the source code and documentation for implementing custom text tokenization. The project utilizes Python and NLP libraries (like Hugging Face Transformers or NLTK) to break down raw text into manageable tokens.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Customization & Theory](#customization--theory)
- [Contributing](#contributing)

## Introduction

Text tokenization is a crucial first step in almost any Natural Language Processing (NLP) pipeline. This project demonstrates how to tokenize text using different methods (e.g., word-level, subword-level) and potentially customize the tokenizer for specific domain needs.

## Installation

To run this project, you need to have Python installed on your system.

Install all dependencies using `pip`:

```bash
pip install -r requirements.txt
# If requirements.txt is not available, use:
# pip install tiktoken
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/tumstech/AI-Projects/tokenization_project.git
   cd AI-Projects/tokenization_project
   ```

2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook tokanizer.ipynb
   ```

3. Follow the steps in the notebook to test different tokenization strategies on sample text.

## Customization & Theory

The core of this project lies in understanding tokenization algorithms. The notebook demonstrates:
*   **Word Tokenization:** Simple splitting by whitespace and punctuation.
*   **Subword Tokenization (e.g., BPE):** Using model-specific tokenizers to handle Out-Of-Vocabulary (OOV) words efficiently.

Feel free to experiment with loading different pre-trained tokenizers for advanced analysis.

## Contributing

Contributions are highly appreciated! If you find any bugs, have suggestions for improving tokenization strategies, please open an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/ImprovedTokenizer`).
3. Commit your changes (`git commit -m 'feat: Improved tokenizer logic'`).
4. Push to the branch (`git push origin feature/ImprovedTokenizer`).
5. Open a pull request.