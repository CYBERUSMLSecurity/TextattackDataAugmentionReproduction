# TextattackDataAugmentionReproduction
##Data Augnementation feature of textattack




This notebook focuses on reproducing the **data augmentation feature** of the TextAttack framework. Our goal was to demonstrate how TextAttack can create diverse and meaningful variations of text to enrich datasets for training NLP models.

---

## **What We Did**

1. **Installed TextAttack**:
   - We ensured the latest version of TextAttack was installed 
    

2. **Used Positive Sentiment Examples**:
   - We started with a small set of positive sentiment sentences


3. **Applied TextAttack's Augmentation Tools**:
   - We used the **EmbeddingAugmenter**, which generates augmented text by replacing words with their similar counterparts from word embeddings.
   - To make the augmentations more meaningful:
     - We used the **WordSwapEmbedding** transformation for swapping words.
     - We applied the **StopwordModification** constraint to ensure stopwords were not altered.

4. **Generated Augmented Data**:
   - We created diverse text variations while maintaining the original meaning and sentiment.


