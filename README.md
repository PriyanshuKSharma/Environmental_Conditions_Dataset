# Environmental_Conditions_Dataset
### Summary of the Dataset

This dataset is a synthetic collection of environmental and weather-related data for 39 cities across India. The data is generated for a period starting from January 1, 2013, with 100 data points per city. The dataset includes various parameters that affect air quality and general weather conditions.

---

#### Key Attributes:

1. **City**:
   - **Description**: The name of the city in India where the data is recorded.
   - **Type**: Categorical
   - **Values**: 39 unique cities, including Delhi, Mumbai, Kolkata, Chennai, Bangalore, Hyderabad, etc.

2. **Date**:
   - **Description**: The date for each data point.
   - **Type**: DateTime
   - **Range**: Starts from January 1, 2013, and progresses daily for each city over 100 data points.

3. **PM2.5**:
   - **Description**: Particulate Matter with a diameter of less than 2.5 micrometers.
   - **Type**: Continuous
   - **Range**: 10 to 300 (units could be micrograms per cubic meter, µg/m³)

4. **PM10**:
   - **Description**: Particulate Matter with a diameter of less than 10 micrometers.
   - **Type**: Continuous
   - **Range**: 20 to 400 (µg/m³)

5. **NO2**:
   - **Description**: Nitrogen Dioxide concentration in the air.
   - **Type**: Continuous
   - **Range**: 10 to 150 (ppb or µg/m³)

6. **SO2**:
   - **Description**: Sulfur Dioxide concentration in the air.
   - **Type**: Continuous
   - **Range**: 5 to 100 (ppb or µg/m³)

7. **CO**:
   - **Description**: Carbon Monoxide concentration in the air.
   - **Type**: Continuous
   - **Range**: 0.1 to 10 (ppm)

8. **O3**:
   - **Description**: Ozone concentration in the air.
   - **Type**: Continuous
   - **Range**: 10 to 100 (ppb or µg/m³)

9. **Temperature**:
   - **Description**: Ambient temperature recorded in the city.
   - **Type**: Continuous
   - **Range**: 10 to 45 (°C)

10. **Humidity**:
    - **Description**: Relative humidity percentage.
    - **Type**: Continuous
    - **Range**: 20% to 100%

### Dataset Dimensions

- **Number of Rows**: 3900 (100 data points for each of the 39 cities)
- **Number of Columns**: 10 (City, Date, PM2.5, PM10, NO2, SO2, CO, O3, Temperature, Humidity)

### Potential Analysis and Findings

1. **Air Quality Index (AQI) Analysis**:
   - **Objective**: Calculate and analyze the Air Quality Index (AQI) for each city using PM2.5, PM10, NO2, SO2, CO, and O3 levels.
   - **Findings**: Identify cities with the highest and lowest AQI, trends over time, and correlations with temperature and humidity.

2. **Temporal Analysis**:
   - **Objective**: Investigate seasonal variations in air pollution levels and weather conditions.
   - **Findings**: Discover patterns such as increased pollution during winter months due to temperature inversion or higher ozone levels in the summer.

3. **City-Wise Comparisons**:
   - **Objective**: Compare the environmental data between different cities.
   - **Findings**: Identify cities with consistently poor air quality, such as high PM2.5 or NO2 levels, and those with better conditions.

4. **Correlation Analysis**:
   - **Objective**: Explore correlations between different pollutants and weather conditions.
   - **Findings**: Determine whether higher temperatures lead to higher ozone levels, or how humidity affects particulate matter.

5. **Trend Analysis**:
   - **Objective**: Analyze trends over time for individual cities or pollutants.
   - **Findings**: Identify any improving or worsening trends in air quality or temperature changes over the years.

6. **Health Impact Assessment**:
   - **Objective**: Estimate the potential health impacts of different pollutants based on WHO standards.
   - **Findings**: Identify cities where air quality could have significant health implications for residents.

7. **Extreme Events Analysis**:
   - **Objective**: Detect and analyze extreme events such as pollution spikes or temperature anomalies.
   - **Findings**: Understand the frequency and impact of such events, possibly relating them to external factors like festivals, industrial activity, or weather patterns.

### Limitations

- **Synthetic Data**: The dataset is artificially generated and may not represent real-world scenarios accurately.
- **Lack of Granularity**: The data is daily and city-wide; it doesn't account for intra-city variations or more granular time scales.
- **Uniform Distribution**: The use of uniform distributions in generating data may oversimplify real-world variability and complexity.

This dataset provides a comprehensive platform for practicing data analysis, statistical modeling, and environmental studies. However, conclusions drawn from this synthetic dataset should be interpreted with caution and validated against real-world data where possible.
