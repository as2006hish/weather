# 🌦️ Weather Data Analysis
This project involves comprehensive analysis of weather data to understand trends, anomalies, and patterns in atmospheric conditions over time.

## 📁 Dataset Overview
The dataset contains hourly weather data with the following key features:
- **Date/Time**: Timestamp of the observation
- **Temp (°C)**: Temperature in Celsius
- **Dew Point Temp (°C)**: Dew point temperature
- **Rel Hum (%)**: Relative humidity
- **Wind Speed (km/h)**: Wind speed
- **Visibility (km)**: Visibility distance
- **Press (kPa)**: Atmospheric pressure
- **Weather**: General weather condition (e.g., Snow, Rain, Clear)

## 🧹 Data Preprocessing
- Removed or imputed missing values
- Converted timestamp to datetime format
- Filtered relevant features for analysis
- Normalized and formatted data for consistency
## 🛠️ Feature Engineering
- Extracted `day`, `month`, and `hour` from the datetime
- Created binary features such as `Is_Rainy`, `Is_Snowy` based on weather descriptions
- Grouped data by time intervals for temporal pattern analysis
## 📊 Exploratory Data Analysis (EDA)
- Temperature trends over time
- Distribution of weather conditions
## 📈 Key Visualizations
- Line plots showing temperature fluctuations across days and months
- Bar plots of weather condition frequencies
- Scatter plots and histograms to assess distributions and relationships
## 💡 Insights
- High humidity is often associated with foggy or rainy conditions
- Temperature follows a daily cycle and varies seasonally
- Visibility significantly drops during snowfall and fog events
## ✅ Conclusion
This analysis provided insights into how various weather attributes interact and evolve over time. The processed dataset and engineered features can serve as input for predictive modeling or further climatological research.
