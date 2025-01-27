# Bengaluru Housing Price Prediction 🏡

This project predicts housing prices in Bengaluru based on features such as location, square feet, bedrooms, and bathrooms. It includes an interactive web application built with **Streamlit**, enabling users to input details and get real-time predictions. The project also features data analysis, preprocessing, and visualizations to provide insights into housing trends.

---

## 🚀 Technologies Used

### **Frontend**
- **Streamlit**: For creating an interactive web application to display and interact with data.

### **Data Processing**
- **Pandas**: Used for data manipulation, preprocessing, handling missing values, feature engineering, and analysis.
- **NumPy**: Handles numerical operations such as processing arrays and applying mathematical functions.

### **Visualizations**
- **Matplotlib**: For basic visualizations like histograms and scatter plots to understand data distribution.
- **Plotly Express**: For advanced, interactive visualizations integrated into the Streamlit app, including bar charts, line plots, and scatter plots.

### **Machine Learning**
- **Scikit-learn**: For building and training the machine learning model (Linear Regression), as well as splitting data into training and testing sets.
- **Pickle**: To serialize and save the trained model for reuse without retraining.

---

## 📊 Features

- **Data Analysis and Preprocessing**:
  - Cleaned and analyzed housing data to ensure reliable predictions.
  - Handled missing values and applied feature engineering for better performance.

- **Interactive Web App**:
  - Users can input location, square feet, bedrooms, and bathrooms to predict housing prices.
  - Visualizes housing trends using interactive plots.

- **Machine Learning**:
  - Trained a **Linear Regression** model to predict prices based on input features.
  - Model is serialized with **Pickle** for efficient reuse.

---

## 🔧 Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/bengaluru-housing-prediction.git
   cd bengaluru-housing-prediction
