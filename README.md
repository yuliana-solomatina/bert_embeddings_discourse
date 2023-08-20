# bert_embeddings_discourse
Testing the BERT embeddings' ability to encode discourse properties of the natural language for Russian

Current repository contains code with the experiments design and results for the task of testing the BERT embeddings' ability on the basis of the Russian discourse dataset RSTreebank. The research was inspired by (Huber et al., 2020).

# Dataset

The dataset used in the current research is Russian discourse corpus _Ru-RSTreebank_, which consists of 333 texts, annotated with rhethoric relations. For the purposes of this research, only news articles were extracted from the corpus.

# Experiments 
## Experiment 1. Swapped Sentence Units 
Changing the ordering of adjacent clauses in the sentence to detect incoherence. 

## Experiment 2. Scrambled Sentence Detection
Replacing a randomly chosen discourse unit by a randomly chosen discourse unit from another text.

## Experiment 3. Relation Semantics Detection 
Testing model's ability to differentiate 17 types of rhethoric relations.
