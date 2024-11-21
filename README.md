# Entity Role Classification in News Articles

This repository hosts the project "Entity Role Classification in News Articles," aimed at analyzing how named entities (NEs) are framed within multilingual news articles. The project focuses on classifying entities into roles like protagonists, antagonists, and innocents using a fine-grained taxonomy. It leverages state-of-the-art natural language processing techniques to understand and uncover narrative biases in media.

---

## Motivation

News articles often influence public opinion by portraying entities in specific roles such as heroes, villains, or neutral parties. Understanding these portrayals can:

- Identify patterns of bias in journalism.
- Support better decision-making in policy and media analysis.
- Enable automated tools for social media monitoring and reporting.

This project seeks to build a system capable of automatically classifying NEs in news articles to facilitate these goals.

---

## Dataset

The dataset comprises multilingual news articles (Bulgarian, English, Hindi, Portuguese, and Russian) published between 2022 and mid-2024. It covers globally significant topics such as:

1. **The Ukraine-Russia War**
2. **Climate Change**

### Key Features
- Articles annotated with named entities and their roles (protagonist, antagonist, innocent).
- Fine-grained sub-roles such as guardian, instigator, and victim.
- Training and development sets to evaluate the model's ability to generalize.

---

## Methodology

The project employs advanced natural language processing techniques and machine learning models:

1. **Data Preprocessing**:
   - Tokenization, cleaning, and NE extraction.

2. **Model Training**:
   - Transformer-based models like XLM-RoBERTa or mBERT fine-tuned for multilingual, multi-label classification.
   - Attention mechanisms to capture contextual information.

3. **Linguistic Enhancements**:
   - Dependency parsing and part-of-speech tagging for syntactic and semantic insights.

4. **Evaluation Metrics**:
   - Precision, Recall, F1 Score, Hamming Loss, Subset Accuracy.

---

## Expected Results

- Accurate classification of named entities into predefined roles across multiple languages.
- Robust performance in low-resource languages through cross-lingual training.
- Enhanced interpretability by integrating linguistic features.

---

## Challenges

- **Linguistic Diversity**: Variations in syntax and semantics across languages.
- **Class Imbalance**: Overrepresentation of frequent roles like protagonists.
- **Context Dependence**: Requires understanding both sentence-level and article-level contexts.

---

## Lisense

- This project is licensed under the MIT License. You are free to use, modify, and distribute this software, provided that proper credit is given to the original authors.


