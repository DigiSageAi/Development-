### Development Document: DigiSageAI Project

#### **Project Overview**
- **Project Name**: DigiSageAI  
- **Objective**: Develop an AI-driven cryptocurrency trading analysis tool that leverages historical trading data to train AI models, predict market trends, and identify effective combinations of technical indicators.  
- **Development Environment**:
  - **Operating System**: Windows
  - **Programming Language**: Python  
  - **Database**: MySQL  

---

### **Feature Requirements**
1. **Data Retrieval Module**:
   - Automatically fetch historical cryptocurrency trading data (support for APIs like Binance, CoinGecko, etc.).
   - Fetch live price data and store it in the MySQL database.

2. **AI Model Module**:
   - Build AI models to analyze market trends.
   - Provide predictions for short-term, mid-term, and long-term trends.

3. **Technical Indicators Module**:
   - Provide calculations for popular trading indicators (e.g., RSI, MACD, Bollinger Bands).
   - Support dynamic parameter adjustments for optimization.

4. **Visualization Module**:
   - Display historical market data and predictions using charts (e.g., candlestick charts, trend lines).
   - Overlay technical indicators on charts.

5. **Logging and Reporting Module**:
   - Record logs for model training and predictions.
   - Generate analysis reports for trading insights.

---

### **Technology Stack**

#### **Machine Learning & Deep Learning**
- **Scikit-learn**: For feature engineering and basic model training.  
- **XGBoost**: For analyzing time-series data.  
- **TensorFlow / PyTorch**: Deep learning frameworks for models like LSTM.  
- **Prophet**: A tool for trend forecasting.  

#### **Time-Series Analysis**
- **LSTM**: Captures long-term dependencies in time-series data.  
- **ARIMA**: A classic model for time-series forecasting.  

#### **Data Retrieval and Processing**
- **pandas**: For data processing and analysis.  
- **ccxt**: For retrieving data from cryptocurrency exchange APIs.  
- **SQLAlchemy**: To interact with the MySQL database.  

---

### **Current Progress**
1. Completed the design of the project directory structure.  
2. Finalized the module architecture.  
3. Designed the database schema and table structure.  

**Note**: This project is independently developed and is not open source.

