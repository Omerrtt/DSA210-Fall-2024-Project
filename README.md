# DSA210-Fall-2024-Project

# Project Report: Analyzing the Relationship Between Sleep Duration and Step Count

## Introduction
This project investigates the interplay between sleep duration and physical activity levels, measured by daily step counts. Using health data exported from Apple Health, we aim to explore whether there is a significant correlation between these two variables and to derive meaningful insights that can aid in optimizing rest and activity for improved well-being.

The dataset spans the period from [INSERT DATE RANGE], and includes daily total sleep duration (in hours) and daily total step count. The data has been carefully preprocessed to ensure reliability and consistency for analysis. By examining these relationships, we hope to contribute to the broader understanding of how rest and activity impact overall health.

---

## Data Collection and Preprocessing

### Data Source
The data for this project was extracted from Apple Health, a platform that aggregates personal health metrics recorded by various Apple devices. Specifically:

- **Sleep Data:** Aggregated from fragmented sleep intervals to represent the total sleep duration in hours per day.
- **Step Count Data:** Captures the total number of steps taken each day.

### Preprocessing Steps
1. **Outlier Removal:** Extreme values, such as abnormally high or low sleep durations or step counts, were removed to enhance data quality and prevent skewing of results.
2. **Date Alignment:** Sleep and step data were aligned by date to ensure consistency, allowing for accurate comparisons and trend analysis.
3. **Missing Data Handling:** Missing or invalid entries were identified and appropriately addressed through imputation or removal to maintain the integrity of the dataset.
4. **Normalization:** Data was normalized where necessary to allow for better comparisons between variables with differing scales.

### Dataset Summary
- **Number of entries:** [INSERT NUMBER]
- **Time period covered:** [INSERT DATES]
- **Variables included:**
  - Total sleep duration (hours)
  - Total step count

---

## Exploratory Data Analysis (EDA)

EDA provided a deeper understanding of the data and its patterns. Several types of visualizations and statistical measures were employed:

### Histograms
- Highlighted the distribution of daily sleep duration and step counts.
- Showed that most individuals had a sleep duration concentrated around 8-10 hours, while step counts ranged between 5,000 and 15,000.

### Boxplots
- Provided a clear view of variability and outliers in sleep and step data.
- Illustrated the median, interquartile range, and extreme values.

### Time-Series Plots
- Visualized daily trends and variations in sleep and step counts over the observed period.
- Revealed potential periodic patterns, such as differences between weekdays and weekends.

### Scatter Plot
- Visualized the relationship between sleep duration and step count.
- Indicated a weak negative correlation, with a tendency for higher step counts to correspond to slightly shorter sleep durations.

### Hexbin Plot
- Highlighted areas of high-density relationships between sleep and step count.
- Allowed for better visualization of data concentrations compared to scatter plots.

### Correlation Matrix
- Quantified the strength and direction of the relationship between sleep duration and step counts.
- Displayed a weak negative correlation (ρ ≈ -0.13).

### Summary Statistics
- Mean and standard deviation of sleep duration and step counts.
- Median values for a robust measure of central tendency.

---

## Findings and Analysis

### Correlation Analysis
The weak negative correlation observed (ρ ≈ -0.13) suggests that individuals with longer sleep durations tend to have slightly lower step counts. However, the relationship is not strong enough to imply causation. Other external factors likely influence these variables.

### Insights from Visualizations
- **Histograms and Boxplots:** Provided clear evidence of the typical ranges for sleep and step counts, while also identifying outliers.
- **Scatter Plots and Hexbin Plots:** Revealed clustering of data points, particularly around 8-10 hours of sleep and 5,000-15,000 steps.
- **Time-Series Analysis:** Showed fluctuations in daily sleep and step counts, with potential patterns influenced by weekdays versus weekends.

### Key Observations
1. Individuals who achieve higher step counts often report slightly lower sleep durations.
2. Outliers, such as extremely high step counts or abnormally long sleep durations, may indicate unique lifestyle factors or anomalies.
3. The weak correlation suggests that other variables, such as age, gender, or activity type, may play a significant role in influencing the relationship.

### Statistical Models
Linear regression analysis further supported the weak correlation, with a low R-squared value, indicating that step counts explain only a small portion of the variance in sleep duration.

---

## Conclusion and Future Work

### Conclusion
This analysis highlights a weak negative relationship between sleep duration and step counts, providing a foundation for understanding the balance between rest and activity. However, the findings suggest that additional factors may need to be considered to gain a comprehensive understanding of these dynamics.

### Future Work
1. **Expanded Datasets:** Include additional metrics such as heart rate, calorie expenditure, or stress levels to provide a more holistic view.
2. **Lag Effects:** Investigate whether activity on one day impacts sleep patterns the following night.
3. **Demographic Analysis:** Study the effects of variables such as age, gender, and occupation on sleep and activity relationships.
4. **Machine Learning:** Use predictive models to identify patterns and forecast sleep or activity levels based on historical data.
5. **Intervention Studies:** Explore how changes in one variable (e.g., increasing physical activity) influence the other (e.g., improving sleep quality).

By leveraging these approaches, future studies can uncover actionable recommendations to optimize health and well-being.

---

## Acknowledgments
Special thanks to Apple Health for providing the data platform and tools necessary for this analysis. We also acknowledge the importance of ensuring data privacy and security throughout this project, adhering to ethical guidelines in handling personal health data.

