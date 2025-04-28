# IST 664 Natural Language Processing - Sentiment Analysis Project

## Project Overview
This project focused on performing **sentiment analysis** on Twitter data, classifying tweets into **positive, negative, and neutral** categories. It leveraged various **NLP techniques** for preprocessing, feature extraction, and classification.

- **Course:** IST-664 Natural Language Processing
- **Author:** Abhi Chakraborty

---

## Project Steps

### Step 1: Data Processing
- **Tokenization:**
  - Tweets were tokenized using NLTK's TweetTokenizer.
- **Text Cleaning:**
  - Removed URLs, Twitter handles, special characters.
- **Lowercasing:**
  - Standardized all tokens to lowercase.

**Example:**
> Original Tweet: "Love the new #iPhone! @Apple"  
> Preprocessed: ["love", "the", "new", "iphone"]

**Impact:** Clean and consistent text ensured better model training and evaluation.

---

### Step 2: Feature Extraction
- **Unigrams:**
  - Single words used as features.
- **Bigrams:**
  - Consecutive word pairs captured for context.
- **POS Tags:**
  - Part-of-speech tags included for grammatical structure analysis.

**Example:**
> Unigrams: "love", "iphone"  
> Bigram: "love the"  
> POS Tag: Noun ("iphone")

**Impact:** Diverse features captured sentiment nuances more effectively.

---

### Step 3: Classification Experiments
- **Classifier:** Naive Bayes
- **Validation:**
  - Cross-validation to avoid overfitting.
- **Evaluation Metrics:**
  - Precision, Recall, F1-score (preferred over accuracy due to class imbalance).

**Example Performance:**
> Positive tweets precision: 0.76 (76% correctly classified)

**Impact:** Best performance achieved by combining unigrams, bigrams, and POS features.

---

## Key Observations and Lessons Learned
- **Feature Diversity:**
  - Combining various features significantly improved model performance.
- **Metric Importance:**
  - Precision, recall, and F1-score offered a holistic view, crucial for imbalanced data.
- **Cross-Validation:**
  - Essential for ensuring the model's generalizability.

---

## Final Conclusion
- Feature engineering (unigrams + bigrams + POS) is critical for successful sentiment classification.
- Using precision, recall, and F1-scores alongside cross-validation enhances result reliability.
- Practical applications extend beyond academia:
  - **Brand monitoring**
  - **Customer feedback analysis**
  - **Market research**

This project demonstrated the **transformative potential of NLP** in extracting actionable insights from textual data.

---

## Tools and Technologies
- **Language:** Python
- **Libraries:** NLTK
- **Techniques:**
  - Text preprocessing
  - Feature extraction
  - Classification with evaluation

---

## Author
**Abhi Chakraborty**  
Syracuse University - Applied Data Science  
Email: abchakra@syr.edu

