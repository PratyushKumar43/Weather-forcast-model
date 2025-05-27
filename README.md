# Weather Forecasting with Machine Learning

A comprehensive machine learning project that analyzes historical temperature data and builds predictive models to forecast future weather patterns.

## 📊 Project Overview

This project demonstrates the application of machine learning techniques for weather forecasting using historical temperature data. The analysis includes exploratory data analysis, clustering, seasonal pattern identification, and predictive modeling to forecast future temperatures.

## 🎯 Features

- **Data Preprocessing**: Transforms raw weather data into time-series format
- **Exploratory Data Analysis**: Comprehensive visualization of temperature patterns
- **Clustering Analysis**: K-means clustering to identify temperature patterns
- **Seasonal Analysis**: Analysis of weather patterns across different seasons
- **Machine Learning Model**: Decision Tree Regressor for temperature forecasting
- **Interactive Visualizations**: Dynamic charts and animations using Plotly

## 📈 Key Analysis Components

### 1. Time Series Analysis
- Temperature trends over time
- Monthly temperature patterns
- Yearly average temperature analysis

### 2. Clustering Analysis
- K-means clustering to identify temperature groups
- Optimal cluster determination using elbow method
- Temperature pattern classification

### 3. Seasonal Weather Analysis
- Winter, Summer, Monsoon, and Autumn temperature patterns
- Seasonal temperature trends over years
- Climate cycle understanding

### 4. Machine Learning Forecasting
- Decision Tree Regressor model
- Temperature prediction for future periods
- Model performance evaluation

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Plotly** - Interactive visualizations
- **Scikit-learn** - Machine learning algorithms
- **Datetime** - Time series handling

## 📋 Prerequisites

Make sure you have the following libraries installed:

```bash
pip install pandas numpy plotly scikit-learn
```

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/PratyushKumar43/Weather-forcast-model.git
   cd Weather-forcast-model
   ```

2. **Prepare your data:**
   - Ensure you have a `Weather.csv` file in the project directory
   - The CSV should contain yearly temperature data with months as columns

3. **Run the notebook:**
   - Open `weather_forecasting.ipynb` in Jupyter Notebook or JupyterLab
   - Execute all cells to see the complete analysis

## 📁 Project Structure

```
Weather-forcast-model/
│
├── weather_forecasting.ipynb    # Main Jupyter notebook with analysis
├── Weather.csv                  # Weather dataset (not included)
└── README.md                   # Project documentation
```

## 📊 Data Format

The expected data format for `Weather.csv`:

| YEAR | JAN | FEB | MAR | APR | MAY | JUN | JUL | AUG | SEP | OCT | NOV | DEC |
|------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| 2010 | 15.2| 18.1| 25.3| 30.2| 35.1| 28.9| 26.8| 25.5| 23.2| 20.1| 17.8| 14.9|
| ...  | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... |

## 🎨 Visualizations

The project includes various interactive visualizations:

- **Timeline Charts**: Temperature evolution over time
- **Box Plots**: Monthly temperature distributions
- **Scatter Plots**: Temperature clusters and patterns
- **Histograms**: Temperature frequency distributions
- **Seasonal Charts**: Temperature patterns by season
- **Animated Plots**: Dynamic temperature changes over years

## 🤖 Machine Learning Model

### Model Details
- **Algorithm**: Decision Tree Regressor
- **Features**: Year and Month (one-hot encoded)
- **Target**: Temperature values
- **Performance**: High R² score indicating good predictive accuracy

### Model Training Process
1. Data preprocessing and feature encoding
2. Train-test split (80-20)
3. Model training with Decision Tree Regressor
4. Performance evaluation using R² score
5. Temperature forecasting for future periods

## 📈 Results

The model successfully:
- Identifies seasonal temperature patterns
- Clusters temperature data into meaningful groups
- Achieves high accuracy in temperature prediction
- Provides reliable forecasts for future periods

## 🔮 Future Enhancements

- [ ] Integration of additional weather parameters (humidity, pressure, etc.)
- [ ] Implementation of more advanced ML models (LSTM, ARIMA)
- [ ] Real-time weather data integration
- [ ] Extended forecasting periods
- [ ] Weather alerts and notifications
- [ ] Web application deployment

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Pratyush Kumar**
- GitHub: [@PratyushKumar43](https://github.com/PratyushKumar43)

## 🙏 Acknowledgments

- Thanks to the open-source community for the amazing libraries
- Weather data providers for making historical data available
- Contributors to the scientific Python ecosystem

---

⭐ If you found this project helpful, please give it a star!
