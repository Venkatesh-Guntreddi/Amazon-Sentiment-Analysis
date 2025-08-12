# Amazon Product Reviews Sentiment Analysis

This project performs **sentiment analysis** on Amazon product reviews using Python. It classifies reviews as positive or negative based on their text content using machine learning techniques.

---

## Project Description

Sentiment analysis is a natural language processing (NLP) technique used to determine the emotional tone behind text. This project processes Amazon product reviews to classify their sentiment into positive or negative categories.

### How the project works:

1. **Data Preparation:**  
   The dataset contains reviews and star ratings (1 to 5). Ratings 1, 2, and 3 are labeled as negative (0), and ratings 4 and 5 as positive (1). Missing values are removed.

2. **Text Cleaning:**  
   Common stopwords (e.g., "the", "and") are removed to focus on meaningful words.

3. **Feature Extraction:**  
   Reviews are transformed into numerical data using TF-IDF vectorization, which captures important words relative to their frequency.

4. **Model Training:**  
   A Logistic Regression model is trained on the processed data to learn sentiment classification.

5. **Evaluation and Visualization:**  
   The model’s accuracy is measured, and confusion matrix and word clouds for positive and negative reviews are plotted.

### Why Logistic Regression?

Logistic Regression is a simple yet effective algorithm for binary classification problems like this. It estimates the probability of a review belonging to each sentiment class based on the input features.

---

## Files

- `Sentiment_Analysis_of_Amazon_Product_Reviews_in_Python.ipynb` — Jupyter notebook with code and analysis.  
- `AmazonReview.csv` — Dataset of Amazon product reviews with ratings and sentiments.

---

## Requirements

- Python 3.x  
- Libraries: pandas, scikit-learn, matplotlib, wordcloud, nltk

Install dependencies with:

```bash
pip install pandas scikit-learn matplotlib wordcloud nltk

How to Run
Clone or download this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/your-repo.git
cd your-repo
Open the Jupyter notebook:

bash
Copy
Edit
jupyter notebook Sentiment_Analysis_of_Amazon_Product_Reviews_in_Python.ipynb
Run all cells sequentially to perform data cleaning, feature extraction, model training, evaluation, and visualization.

License
This project is licensed under the MIT License.


