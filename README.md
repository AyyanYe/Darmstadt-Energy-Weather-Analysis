# Darmstadt Weather & Energy Consumption Analysis

This project explores the relationship between weather conditions and energy consumption in Darmstadt, Germany. Using historical weather data from the Open-Meteo API and simulated energy usage, the analysis includes exploratory data analysis (EDA), hypothesis testing, and predictive modeling with robust evaluation through cross-validation.

---

## Project Overview

The objective is to demonstrate data science skills by:

- Collecting and preprocessing weather data for Darmstadt in 2023.
- Simulating daily energy consumption based on temperature and heating degree days.
- Adding calendar features such as weekends and holidays.
- Conducting exploratory data analysis to identify patterns and correlations.
- Performing hypothesis testing to confirm if colder days significantly increase energy use.
- Building and evaluating regression models (Linear Regression and Random Forest) to predict energy consumption.
- Applying 5-fold cross-validation for robust model performance assessment.

---

## Data Sources

- **Weather Data:** Fetched via [Open-Meteo API](https://open-meteo.com/) — free, no API key required.
- **Calendar Features:** Derived using Python’s `holidays` package for public holidays in Hesse (HE), Germany.
- **Energy Consumption:** Simulated based on temperature and randomness, due to lack of publicly available actual data.

---

## Getting Started

### Prerequisites

- Python 3.7+
- Packages: `requests`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `holidays`

Install packages with:

```bash
pip install -r requirements.txt
```
### Clone the repository:

``` bash
git clone https://github.com/your-username/darmstadt-weather-energy-analysis.git
cd darmstadt-weather-energy-analysis
```
### Run the notebook:

Open Darmstadt_Weather_Energy_Analysis.ipynb in Google Colab or your preferred Jupyter environment.

Run the cells sequentially to fetch data, simulate energy, perform EDA, hypothesis testing, and modeling.

### Project Structure
``` bash
.
├── darmstadt_weather_2023.csv       # Raw weather data (saved CSV)
├── Darmstadt_Weather_Energy_Analysis.ipynb  # Main Colab notebook with all steps
├── requirements.txt                 # Required Python packages
└── README.md                       # Project documentation
```

## Key Highlights
- Uses Open-Meteo API to get accurate, historical weather data.

- Simulates realistic energy consumption patterns based on temperature.
 
- Applies statistical hypothesis testing to validate assumptions.

- Compares Linear Regression and Random Forest models.

- Employs cross-validation to evaluate model robustness.

- Clear and detailed documentation suitable for academic and practical use.

## Potential Future Improvements
- Integrate actual energy consumption datasets for Darmstadt or Germany.

- Explore additional weather variables such as solar radiation or humidity.

- Apply time series forecasting models like ARIMA or LSTM.

- Extend hypothesis testing to compare multiple models statistically.

- Build an interactive dashboard to visualize results dynamically.

## References
- Open-Meteo API

- Python holidays Library

- Hastie, Tibshirani, Friedman. The Elements of Statistical Learning.

- Scikit-learn documentation: https://scikit-learn.org/

## License
This project is licensed under the MIT License.

## Author
**Ayyan Ahmed**
[GitHub Profile](https://github.com/AyyanYe)
[Email](ayyanahmed@outlook.com)
