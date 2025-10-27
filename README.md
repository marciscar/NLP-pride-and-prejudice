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
├─ models/      # Saved checkpoints     
├─ README.md    
└─ .gitignore    


---

##  Model
   - Two-layer LSTM trained on one-hot encoded characters.
   - Parameter configuration:
     ```yaml
     hidden_dim: 256
     num_layers: 2
     dropout: 0.3
     seq_len: 200
     batch_size: 128
     lr: 0.002
     epochs: 80
     ```
   - Training uses *teacher forcing*: the correct previous character is fed at each step.


---

##  Example (seed: 'Mr')

Mr. Bennet's comparions on the parsicality as
him,” said Miss Bingley with a so much of
his feelings, to
his friends always cheer of his acturity, and all she had been a such a feel his
attention of her to be
a most ot to be an intriect of the present of the subject of
the
sase, a most
being only and asking at all and almost the composions, when he choose to be the subject of the provided, to his friends, with her at this mornibes to his side to the subject will answer, and had never all him that s






