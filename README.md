# Pride and Prejudice — Character-Level Text Generation with LSTM (PyTorch)

This project trains a **character-level LSTM** to generate text in the literary style of *Pride and Prejudice* by Jane Austen.

The model learns to predict the next character in the sequence, allowing it to produce new passages that mimic the author’s tone and syntax.  
It demonstrates how recurrent neural networks can capture language structure from raw text without any word-level preprocessing.

---

## Dataset

 Source: *Pride and Prejudice*

---

## Project Goals

The main objective of this project is to explore how recurrent neural networks can learn linguistic patterns from raw text and generate coherent, stylistically consistent language.
Using Pride and Prejudice as a training corpus allows the model to capture the distinctive syntax, rhythm, and vocabulary of Jane Austen’s writing.

---

## Repository Structure

NLP-pride-and-prejudice/
├─ data/
│  └─ pride_and_prejudice.txt        # original text    
├─ notebook/    
│  └─ pride_and_prejudice_generator.ipynb   
├─ README.md    
└─ .gitignore    