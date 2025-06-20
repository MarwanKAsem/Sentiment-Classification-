# Sentiment-Classification

What Is Sentiment Analysis?
Sentiment Analysis is a Natural Language Processing (NLP) task where the goal is to determine the emotional tone behind a piece of text.

Usually, we classify text into:

🔴 Negative

🟢 Positive

⚪ Neutral

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

## A Three-step Process for Making Predictions

• Feature extraction: Extract the salient features for making the decision from text

• Score calculation: Calculate a score for one or more possibilities

• Decision function: Choose one of the several possibilities

## how can we we apply this ? 

![image](https://github.com/user-attachments/assets/5e10c2e8-1acb-4f58-8e3a-1176e622952c)

# Build a Rule-based Sentiment Classifier
It will take in a text `X` and return a `label` of "1" if the sentiment of the text is positive, "-1" if the label of the feature is negative, and "0" if the label of the feature is neutral. 

The final way the classifier decides whether to assign a positive, negative, or neutral label is by calculating the dot product `feature_weights * extract_features(X)`, and if the value is greater than zero, return 1, less than zero return -1, and if exactly zero return 0.

Let's have some fun trying to design a classifier , see the notebook and run it...!!!😁

Credits: 

[CMU CS11-711 Advanced NLP](https://cmu-l3.github.io/anlp-spring2025/)
