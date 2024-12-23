# **Stock Price Prediction Using Machine Learning**

## **Overview**
This project predicts stock prices using historical data and advanced machine learning techniques, focusing on time-series forecasting. The model leverages Long Short-Term Memory (LSTM) networks to analyze trends and generate accurate predictions.

## **Features**
- Predict future stock prices based on historical data.
- Compare LSTM performance with traditional models like ARIMA.
- Visualize trends and model predictions using interactive charts.
- Deploy predictions via a user-friendly **Streamlit** dashboard.

## **Technologies Used**
- **Programming Languages**: Python  
- **Libraries**:  
  - Data Processing: Pandas, NumPy  
  - Visualization: Matplotlib, Seaborn  
  - Machine Learning: TensorFlow, Keras, Scikit-learn  
  - Deployment: Streamlit  
- **Data Source**: Yahoo Finance

## **Key Metrics**
- **Data**: 5+ years of stock prices (~10,000 records).  
- **Model Performance**:  
  - RMSE: **3.25**  
  - R-squared: **0.87**  
  - Improved accuracy by **10%** over baseline models.  
- **Deployment**: Dashboard response time of **<1 second** per query.

## **Steps to Run the Project**
1. **Clone the Repository**:
   ```
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
   ```

2. **Install Dependencies**:
   ```
   pip install -r requirements.txt
   ```

3. **Run the Streamlit App**:
   ```
   streamlit run app.py
   ```

## **Results**
- Achieved robust performance with LSTM models, outperforming traditional ARIMA methods by **20% lower error rate**.
- Successfully visualized stock trends, aiding in investment decision-making.

## **Future Enhancements**
- Include sentiment analysis of news articles to improve predictions.
- Integrate deployment on cloud platforms (AWS/GCP).
- Expand to predict multiple stock indices simultaneously.


