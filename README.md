#  NLP Assignment – Text Analysis and Topic Discovery  

##  Overview  
This project is part of my **Week 3 AI/NLP Assignment**.  
The goal is to practice different **text analysis techniques** using Python, scikit-learn, gensim, and nltk.  

We worked on a small **synthetic dataset (10–15 sentences)** about **nature, environment, technology, and data science**, and then applied the following techniques:  

1. **Text Preprocessing**  
   - Tokenization  
   - Lowercasing  
   - Stopword removal  

2. **TF-IDF Analysis**  
   - Extracted top words per document based on term frequency–inverse document frequency.  

3. **Word2Vec Embeddings**  
   - Trained a Word2Vec model on the dataset.  
   - Found similar words (e.g., to “data”).  
   - Visualized embeddings using PCA.  

4. **Topic Modeling with LDA**  
   - Created dictionary and corpus.  
   - Built an **LDA model with 3 topics**.  
   - Displayed top keywords for each topic.  
   - Visualized using **pyLDAvis**.  

---

##  Dataset  
- The dataset contains **short text documents (sentences)**.  
- Example entries:  
  - "Climate change is affecting forests and wildlife"  
  - "Machine learning and data science are transforming industries"  
  - "The ocean is full of diverse marine life"  

---

##  Tools & Libraries Used  
- **Python 3**  
- **NLTK** → Stopword removal, tokenization  
- **Scikit-learn** → TF-IDF  
- **Gensim** → Word2Vec, LDA topic modeling  
- **PyLDAvis** → Topic visualization  
- **Matplotlib** → PCA plots for embeddings  

---

##  Results  

###  TF-IDF  
- Identified **important words per document**.  
- Example:  
  - Doc 1 (Climate sentence) → {climate, change, wildlife}  
  - Doc 2 (Tech sentence) → {data, analysis, forecasting}  

###  Word2Vec  
- Most similar words to **“data”** included: `analysis, science, machine, learning`  
- PCA plot shows clustering of nature words vs tech words.  

###  LDA Topics  
- **Topic 0** → Nature/Environment (forest, rivers, ocean, wildlife)  
- **Topic 1** → Climate/Conservation (climate, biodiversity, balance)  
- **Topic 2** → Technology/Data (data, analysis, machine, learning)  

---
