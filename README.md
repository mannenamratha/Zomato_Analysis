# Zomato_Analysis


---

# 🍽️ Zomato Bangalore Restaurant Analysis & Recommendation

This project focuses on exploring, analyzing, and building a **restaurant recommendation system** using Zomato's Bangalore restaurant data. It includes data cleaning, visualization, and the development of a content-based filtering model to recommend restaurants based on user preferences.

---

## 📌 Project Highlights

* Cleaned and preprocessed real-world restaurant data from Zomato.
* Performed **exploratory data analysis (EDA)** to uncover insights about cuisines, locations, and ratings.
* Built a **content-based recommendation system** using restaurant metadata (name, location, cuisines, etc.).
* Utilized **TF-IDF** vectorization and **cosine similarity** for restaurant recommendations.
* Created rich visualizations using `matplotlib`, `seaborn`, and `plotly`.

---

## 🔍 Dataset

* **Source**: [Zomato Restaurant Data for Bangalore (via Kaggle)](https://www.kaggle.com/shrutimehta/zomato-restaurants-data)
* **Key Features**:

  * `name`, `location`, `cuisines`, `rate`, `votes`, `cost`, `dish_liked`, `reviews_list`, etc.

---

## 🧪 Technologies Used

* **Python**: Pandas, NumPy, Scikit-learn
* **NLP**: TF-IDF, NLTK (for text cleaning)
* **Visualization**: Matplotlib, Seaborn, Plotly
* **Recommendation Engine**: Cosine Similarity (content-based filtering)

---

## ⚙️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/mannenamratha/Zomato_Analysis.git
   cd Zomato_Analysis
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook "Zomato Recommendation System.ipynb"
   ```

---

## 📈 Sample Outputs

* Insights on most popular cuisines, locations with highest-rated restaurants, and customer preferences.
* Given a restaurant or cuisine, the model recommends similar places with ratings and cuisine information.

---

## 🚀 Future Enhancements

* Add **collaborative filtering** for more personalized recommendations.
* Integrate **FastText or Word2Vec** embeddings for better text understanding.
* Build an interactive **web app using Streamlit or Flask**.
* Include **geolocation** and **price filtering** in recommendations.

---


