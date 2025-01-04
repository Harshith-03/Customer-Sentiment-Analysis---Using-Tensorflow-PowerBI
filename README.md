# **Customer Sentiment Analysis**
Analyzing customer reviews for Apple iPhones to determine sentiments using NLP and TensorFlow. The project integrates predictive analytics with Power BI for visualization.

---

## **Project Overview**
This project aims to classify customer reviews into Positive, Neutral, and Negative sentiments. It leverages:
- **Natural Language Processing (NLP)** for text preprocessing.
- **TensorFlow** for training a sentiment classification model.
- **Power BI** for creating interactive visualizations.

### **Key Features**
1. Preprocessing customer review data to clean and tokenize text.
2. Building a classification model using TensorFlow.
3. Exporting results and creating visual insights with Power BI.

---

## **Technologies Used**
- **Python**: Text preprocessing, sentiment classification.
  - Key libraries: `pandas`, `nltk`, `TensorFlow`.
- **Power BI**: Interactive data visualization.
- **Jupyter Notebook**: For model training and experimentation.
- **Kaggle Dataset**: [Apple iPhone Customer Reviews](https://www.kaggle.com/datasets/mrmars1010/iphone-customer-reviews-nlp).

---

## **Dataset**
The columns used in this dataset include:
- **Review Description**: The textual feedback provided by customers.
- **Ratings**: Numerical rating for the product.
- **Sentiment**: Derived from the rating (0 = Negative, 1 = Neutral, 2 = Positive).

---

## **How to Use**

### **1. Clone Repository**
```bash
git clone https://github.com/your_username/customer-sentiment-analysis.git
cd customer-sentiment-analysis
```

### **2. Set Up Environment**
1. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Required libraries include:
   - `TensorFlow`
   - `pandas`
   - `nltk`
   - `matplotlib`
   - `scikit-learn`

### **3. Run the Project**
- Train the sentiment analysis model:
  ```bash
  python train_model.py
  ```
- Generate CSV of predicted sentiments:
  ```bash
  python predict_sentiment.py
  ```

### **4. Visualize in Power BI**
1. Open `PowerBI_Report.pbix` in Power BI Desktop.
2. Refresh data to load the latest predictions from the `sentiment_results.csv` file.
3. Explore interactive dashboards.

---

## **Results**
- Model Training:
  - Final Accuracy: **93.7%**
  - Validation Accuracy: **78.5%**
- Key Insights:
  - Positive sentiments dominate with 65% of total reviews.
  - Negative reviews highlight concerns about battery life and pricing.
- Power BI Dashboard:
  - Pie chart for sentiment distribution.
  - Heatmap for sentiment trends by country.
  - Bar chart for total numbers of reviews by country
  - Line chart for average sentiment over time
  - Gauge to display average ratings

---

## **Future Work**
1. Use pre-trained embeddings like GloVe or BERT for improved performance.
2. Integrate Tableau for additional visualization options.
3. Experiment with advanced models like transformers.

---

## **License**
This project is licensed under the MIT License. See `LICENSE` for details.
