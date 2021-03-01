# Tracking the Evolution of the SARS-CoV-2 N Gene using Unsupervised Learning

---

### Intro

---



---

### Table of Contents

---

1. **fasta_processing.ipynb:** 
    - Convert sequence data in the fasta file format to csv format
    - Filter out all sequences except N gene sequences
    - convert raw sequences into hexamer 'words' (sliding windows containing 6 base pairs)
2. **dataset_assmbly.ipynb**
    - Balance the amount of sequence data from each country
3. **NLP_cluster.ipynb**
    - sequence pre-processing using NLP methods
    - clustering (kmeans, heirarchical)
4. **viz.ipynb**
    - visualizations of clustered results
