# 🍲 ML Sentiment Analysis — Culinary Insights from User Reviews

## 👩‍💻 Project Summary
This project explores how **sentiment analysis** and **text mining** can extract actionable insights from user feedback on recipes. By analyzing review texts and associated star ratings, we uncover patterns in user satisfaction that can guide recipe enhancements, customer engagement strategies, and data-driven culinary decisions.

---

## 🧠 Objectives
- Use **natural language processing (NLP)** to analyze user-generated content.
- Understand how star ratings correlate with written feedback.
- Identify key positive and negative terms influencing recipe perception.
- Build machine learning models to predict sentiment based on review text.
- Provide business recommendations based on data insights.

---

## 📁 Dataset
- **Source**: [Kaggle - Recipe Reviews and Feedback](https://www.kaggle.com/datasets/joebeachcapital/recipe-reviews-and-user-feedback-dataset)
- Includes:
  - Recipe names
  - User reviews
  - Star ratings
  - Metadata

---

## 🧪 Methods and Techniques

### 1. Data Preparation
- Cleaned missing and duplicate records
- Renamed columns for clarity
- Tokenization, Lemmatization, Stopword Removal

### 2. Exploratory Data Analysis
- Summary statistics
- Most and least reviewed recipes
- Distribution of star ratings

---

![Top 10 recipes](/Images/Sentiment_1.png)
Figure 1: The code above was used to visualise top 10 recipes that customer had either rated or reviewed.

---

### 3. Sentiment Analysis
- **VADER** for compound, positive, neutral, and negative scores
- Visualized review polarity across recipes
- Identified sentiment-heavy recipes

### 4. Machine Learning Modeling
- Feature Extraction via CountVectorizer
- Addressed class imbalance using **SMOTE**
- Trained **Multinomial Naive Bayes** classifier
- Evaluated with Accuracy, Precision, Recall, F1-score

---

![Star ratings](/Images/star_ratings.png)
Figure 2: Above is the visual of the distribution of star ratings using count plot.

---

![SMOTE](/Images/SMOTE_Star_rating.png)
Figure 3: Visualising the smote class distribution using count plot.

---

![Accuracy](/Images/Accuracy.png)
Figure 4: Above is the result of 0.62 accuracy

---

## 📊 Visualizations
- Count plots of star ratings
- Word clouds for positive and negative reviews
- Top frequent terms in each sentiment category
- Recipe-level sentiment breakdowns

---

![negative reviewers](/Images/negative_reviews.png)
Figure 5: Above are common words used by the negative reviewers with the larger words most frequent

---

![positive reviewers](/Images/positive_reviews.png)
Figure 6: Above are common words used by the positive reviewers with the larger words most frequent

---

## 📌 Key Findings
- Majority of reviews express **positive sentiment** (compound median ≈ 0.78)
- Recipes with high negative feedback often contain specific recurring issues
- Most frequent negative terms: *bland, undercooked, soggy*
- Most frequent positive terms: *delicious, easy, perfect*

---

## 🛠 Tools & Libraries
- Python, Pandas, Matplotlib, Seaborn
- Scikit-learn, NLTK (VADER), WordCloud
- SMOTE for balancing class distribution

---

## 🚀 How to Run
1. Clone the repo
2. Install dependencies from `requirements.txt`
3. Run the notebook/script to analyze the data
4. View results and plots in output cells

---

## 📚 References
- Hutto & Gilbert (2014) - VADER: Valence Aware Dictionary
- Bird et al. (2009) - Natural Language Processing with Python
- Geron (2019) - Hands-on Machine Learning with Scikit-learn
- [Full Reference List](#)

---

## 🔗 See Also
🔍 Explore full project details and visuals in the [Jekyll Portfolio](https://github.com/Clemobrain/Clem_Portfolio/blob/main/Big%20Data%20And%20Machine%20learning%20Project)

📁 [Back-Up Files](https://github.com/Clemobrain/Clem_Portfolio/blob/main/Big%20Data%20And%20Machine%20learning%20Project)

---

## 🙋 About Me
**Clement** — Data Engineer & AI Specialist passionate about real-world NLP applications and data-driven impact.

🔗 **LinkedIn**: [linkedin.com/in/yourprofile](https://www.linkedin.com/in/clement-airiohuodion-268279220)  
🔗 **GitHub**: [github.com/Clemobrain](https://github.com/Clemobrain)

---
