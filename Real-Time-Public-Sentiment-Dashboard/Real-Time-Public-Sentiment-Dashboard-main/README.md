
# 📄 Real-Time Public Sentiment Dashboard

## 📌 Project Overview
The **Real-Time Public Sentiment Dashboard** is a Python-based NLP project that processes and analyzes sentiment from app reviews using TextBlob. The insights are visualized in an interactive dashboard to understand public opinion in real-time. This project is particularly useful for tracking sentiment trends for Android applications.

---

## 🔧 Tools & Technologies Used
- **Python**
- **TextBlob (NLP)**
- **Pandas**
- **Matplotlib / Seaborn**
- **Power BI** (for Dashboard visualization)
- **Jupyter Notebook**

---

## 🧠 Features
- Preprocessing of app review data (cleaning, null handling)
- Sentiment polarity and subjectivity scoring using TextBlob
- Classification into Positive, Neutral, and Negative categories
- Exportable results for Power BI dashboard generation
- Visuals including:
  - Sentiment distribution pie chart
  - Sentiment over time line chart
  - App-wise average sentiment bar chart
  - Review count per sentiment category

---

## 🗂️ Dataset
- Input: A CSV file containing Android app reviews with at least the column `Translated_Review`
- Sample structure:
  ```
  App, Translated_Review, Sentiment, Sentiment_Polarity
  XYZ App, "Very useful and fast", Positive, 0.8
  ```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/real-time-sentiment-dashboard.git
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook "Real-Time Public Sentiment Dashboard.ipynb"
   ```
3. Run all cells to process the data and generate outputs.
4. Export the results (e.g., to CSV) and import into Power BI for dashboard visuals.

---

## 📊 Dashboard Visuals (Power BI)
- **Pie Chart**: Sentiment categories (Positive/Neutral/Negative)
- **Bar Graph**: App vs Average Sentiment Polarity
- **Line Chart**: Sentiment trend over time
- **Card KPIs**: Total Reviews, Positive %, Negative %

---

## 📌 Future Enhancements
- Live streaming review analysis via APIs
- Integration with social media or Play Store API
- Real-time web dashboard using Flask/Dash

---

## 📬 Contact
For queries or collaborations, contact:
**Ramya Sree Tundulam**  
📧 tundalamramyasree@gmail.com  
