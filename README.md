# olist-business-analytics
End-to-end business analytics and visualization project using the Olist Brazilian E-Commerce dataset. Includes data cleaning, EDA, feature engineering, ML/DL model training, and visual insights to support data-driven decision making.

---

## 📦 Dataset

We use the [Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) which contains:
- Customer orders
- Products and sellers
- Payments, reviews, shipping info
- Geolocation data

All 9 sub-datasets were merged to build a **master dataset** used for further analysis.

---

## 🧹 Data Preprocessing

- Merged all sub-datasets into a master dataset.
- Handled missing values (e.g., review comments, product categories).
- Converted categorical data and engineered new features (delivery time, review scores, etc.).
- Standardized numerical fields for modeling.

---

## 📊 Exploratory Data Analysis (EDA)

We used visual tools like:
- **Boxplots** for distribution checks
- **Heatmaps** to detect correlations
- **Bar charts** for product category trends
- **Pie charts** to show payment types

Example insight: Late deliveries are strongly correlated with negative review scores.

---

## 🤖 Model Training & Evaluation

We trained the following models:
| Model                    | Validation Accuracy | Test Accuracy |
|--------------------------|---------------------|---------------|
| Logistic Regression      | 0.5710              | 0.5688        |
| Random Forest            | 0.8161              | 0.8159        |
| K-Nearest Neighbors      | 0.7545              | 0.7537        |
| MLP Classifier (Sklearn) | 0.7775              | 0.7761        |
| Keras Deep Neural Network| 0.7904              | 0.7902        |

Additional evaluation tools:
- Confusion matrices
- Classification reports
- ROC curves

---

## 📈 Data Visualization Techniques

We incorporated:
- **Seaborn** and **Matplotlib** for static plots
- **Plotly** for interactive dashboards
- **Correlation heatmaps**, **distribution plots**, and **feature importance charts**

---

## 💼 Business Impact

- Predicts customer satisfaction based on delivery metrics.
- Identifies top-performing product categories and delivery bottlenecks.
- Helps marketing teams with customer segmentation based on location, spending, and review behavior.

---

## 🚀 Deployment Strategy

- Streamlit-based dashboard (optional extension).
- Hosted on a cloud platform (e.g., Heroku, AWS, or local Flask API).
- REST API endpoint for prediction input from new order features.

---

## ⚠️ Challenges & Limitations

- Some features had high missingness (e.g., review comments).
- Review scores can be subjective.
- Limited by dataset’s timeframe and Brazilian market specificity.

---

## 📚 References

- Olist Dataset: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
- Scikit-learn: https://scikit-learn.org/
- Keras/TensorFlow: https://keras.io/
- Plotly/Seaborn/Matplotlib: Python Visualization Libraries

---

## ✍️ Author

**Sai Saran Tottempudi**  
Postgraduate Student – MSc Artificial Intelligence & Data Analytics  
Loughborough University London

---

## 🧾 License

This project is licensed under the MIT License.
