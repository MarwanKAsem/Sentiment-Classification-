# Sentiment-Classification
from scratch Sentiment classification model  a good start for beginning  natural language processing (NLP) 

## What is Natural Language processing (NLP)?

• Technology that enables computers to process, generate, and
interact with language (e.g., text). Some key aspects:

• Learn useful representations: capture meaning in a structured way that can be used for downstream tasks (e.g., embeddings used to classify a document)

• Generate language: create language (e.g., text, code) for tasks like dialogue, translation, or question answering.

• Bridge language and action: Use language to perform tasks, solve problems, interact with environments (e.g., a code IDE)

**okay now we understood what is NLP, So...** 
## what is the requirements for building an NLP System?
• Rules/prompting based on intuition:  
No data needed, but also no performance guarantees

• Rules/prompting based on spot-checks:
A small amount of data with input X only

• Rules/prompting with rigorous evaluation:
Development set with input X and output Y (e.g. 200-2000
examples). Additional held-out test set also preferable.

• Fine-tuning:
Additional train set. More is often better — constant
accuracy increase when data size doubles

for better illustrating our idea , let's just say we have a review (food ,football, hotels , books,........) any reviews from the internet 
we can call it (X) now our task is to predict it's label (y)  which will be positive (+1) Negative (-1) or Neutral (0)


![image](https://github.com/user-attachments/assets/22316828-a9d4-4195-840e-672ae717c19e)


