# 🏙️ NYC Airbnb Market Data Analysis

This project performs detailed Exploratory Data Analysis (EDA) on the **New York City Airbnb Open Data** to uncover trends, patterns, and insights about the short-term rental market in NYC. The analysis is performed using Python in Google Colab.

---

## 📁 Dataset

The dataset used is from [Inside Airbnb](http://insideairbnb.com/get-the-data.html):

- **File name**: `AB_NYC_2019.csv`
- **Data includes**:
  - Listings information (ID, host, name)
  - Location (borough, neighborhood, latitude, longitude)
  - Price, minimum nights
  - Number of reviews and availability

---

## 🔧 Tools & Libraries

- Python (Google Colab)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Folium (for interactive map visualization)

---

## 🔍 Project Structure


---

## 📊 Exploratory Data Analysis (EDA)

The EDA includes:

### 🧼 Data Cleaning:
- Handling missing values in `reviews_per_month`
- Filtering listings with price = 0 or very high prices (outliers)
- Removing irrelevant or redundant columns if any

### 📈 Visualizations:
- Distribution of listing prices
- Room type distribution
- Listings per borough
- Average price per neighborhood group
- Correlation heatmaps of numerical features
- Reviews and availability trends
- Top hosts and neighborhoods

### 🗺️ Geospatial Visualization:
- Interactive map of listings using **Folium**
- Price vs Location scatter plots
- Clustering potential insights based on latitude and longitude

---

## 📌 Key Insights

- Most listings are concentrated in **Manhattan** and **Brooklyn**
- **Entire home/apartment** listings are more expensive than **private/shared rooms**
- Some neighborhoods like **Williamsburg** and **Harlem** have very high listing counts
- Price does not always correlate strongly with number of reviews
- A large number of listings are available all year

---

## 📦 How to Run

1. Open the Google Colab notebook: [`NYC_Airbnb_EDA.ipynb`](NYC_Airbnb_EDA.ipynb)
2. Upload the dataset `AB_NYC_2019.csv` when prompted.
3. Run all cells sequentially to see the analysis and visualizations.

---

## 📈 Future Enhancements

- Predict price based on listing features using machine learning
- Build an interactive dashboard with Plotly or Streamlit
- Perform clustering analysis of location and price
- NLP on listing names or descriptions (if available)
