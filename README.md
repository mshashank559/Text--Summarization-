
# 📚 Text Summarization using Transformers

This is a Data Science project that performs **abstractive text summarization** using Hugging Face's `transformers` library. It uses pre-trained NLP models to generate concise summaries from user-provided input.

----------

## 🧠 Project Objective

To build a **text summarization tool** that can reduce long-form text into shorter, meaningful summaries using state-of-the-art transformer models like BART or T5.

----------

## 📂 Files

-   `text_summarization.ipynb`: The Jupyter Notebook containing the entire code and implementation steps.
    

----------

## 🚀 Technologies Used

-   Python 3.x
    
-   Hugging Face Transformers
    
-   PyTorch or TensorFlow (backend for models)
    

----------

## 🔧 Installation

Install the required libraries:


```bash
`pip install transformers torch` 
```
----------

## ▶️ How to Use

Run the code in a Python environment or Jupyter Notebook. The script will prompt you to enter a paragraph for summarization.

### Sample Execution

```bash

CopyEdit

`Enter the paragraph to summarize (press Enter twice to finish):
Natural language processing is a field of artificial intelligence that focuses on the interaction between computers and humans through natural language...

🔹 Summarized Text:

Natural language processing enables human-computer interaction using natural language through AI.` 

```
----------

## 📊 Model

The summarization model is loaded using:


```bash

`from transformers import pipeline
summarizer = pipeline("summarization")` 

```
It uses models like `facebook/bart-large-cnn` or `t5-small` under the hood (automatically handled by Hugging Face).

----------

## 💡 Future Enhancements

-   Enable summarizing long documents from `.txt` or `.pdf` files
    
-   Add support for batch processing of multiple texts
    
-   Compare extractive vs. abstractive summarization approaches
    
-   Add evaluation metrics like ROUGE or BLEU scores
    

----------

## 👨‍💻 Author

**Shashank Mishra**
