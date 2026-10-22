# Global Air Pollution Dataset — Exploratory Data Analysis (EDA)

## Project Overview

This project was completed as **Task 2: Exploratory Data Analysis (EDA)** for the SWYNEX Technologies Data Analyst Internship.

Using Microsoft Excel, I explored air quality patterns, calculated descriptive statistics, compared country-level AQI averages, and created visualisations to communicate the findings.

This analysis uses the cleaned dataset prepared during Task 1. The focus here is on the exploratory analysis and insights obtained.

## Dataset and Tools

- **Dataset:** Global Air Pollution Dataset
- **Source:** [Kaggle — Global Air Pollution Dataset](https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset)
- **Tool:** Microsoft Excel
- **Records analysed:** 23,463

## Objectives

- Examine the distribution of AQI values.
- Calculate descriptive statistics for AQI and selected pollutant measures.
- Compare average AQI values across countries.
- Analyse the distribution of AQI categories.
- Create charts to communicate patterns and findings.
- Identify notable observations in the dataset.

## Analysis and Key Findings

### 1. Distribution of Overall AQI Values

I created a histogram in Excel to examine how AQI values were distributed across the dataset.

![Histogram showing the distribution of overall AQI values](images/aqi_histogram.png)

The recorded AQI values had a mean of **72.01**, a median of **55**, and a mode of **50**. Values ranged from **6 to 500**, with a skewness of **3.29**.

The mean being higher than the median, alongside the positive skewness, indicates a right-skewed distribution. Most values were concentrated towards the lower end, while a smaller number of high values extended the distribution to the right. The maximum value of 500 was noted as an extreme observation; no formal outlier test was performed to establish whether it was an error.

### 2. Descriptive Statistics for AQI and Pollutant Measures

Descriptive statistics were calculated to summarise AQI values and the average values of four pollutant measures.

| Measure | Result |
|---|---:|
| Mean AQI | 72.01 |
| Median AQI | 55 |
| Mode AQI | 50 |
| Minimum AQI | 6 |
| Maximum AQI | 500 |
| AQI skewness | 3.29 |
| Average PM2.5 | 68.52 |
| Average Ozone | 35.19 |
| Average NO2 | 3.06 |
| Average CO | 1.37 |

Among the four pollutant measures examined, PM2.5 had the highest recorded average. Pollutant averages should be interpreted with consideration of their respective measurement units and scales.

### 3. Top 10 Countries by Average AQI

I used an Excel PivotTable to compare average AQI values across countries. Records labelled `Unknown` in the Country field were excluded from this country-level comparison.

![Bar chart showing the top ten countries by average AQI](images/top_10_countries_aqi.png)

The ten highest recorded country averages were:

| Country | Average AQI |
|---|---:|
| Republic of Korea | 421.00 |
| Bahrain | 188.00 |
| Mauritania | 179.00 |
| Pakistan | 178.79 |
| United Arab Emirates | 163.67 |
| Aruba | 163.00 |
| Kuwait | 162.00 |
| Qatar | 157.50 |
| India | 152.96 |
| Senegal | 152.42 |

The comparison showed differences in the average AQI values recorded for the countries represented. The Republic of Korea had the highest average in this comparison.

These results reflect the available dataset records and should not be interpreted as definitive national air quality rankings because the amount and coverage of data may vary between countries.

### 4. AQI Category Analysis

I used a PivotTable to summarise the number of records in each AQI category. A bar chart and a pie chart were created to show the record counts and percentage distribution.

![Bar chart and pie chart showing the distribution of AQI categories](images/aqi_category_charts.png)

The category counts were:

| AQI Category | Record Count |
|---|---:|
| Good | 9,936 |
| Moderate | 9,231 |
| Unhealthy | 2,227 |
| Unhealthy for Sensitive Groups | 1,591 |
| Very Unhealthy | 287 |
| Hazardous | 191 |
| **Total** | **23,463** |

Good accounted for approximately **42.3%** of the records, while Moderate accounted for approximately **39.3%**. Together, these categories represented approximately **81.7%** of the records.

The other categories made up a smaller share of the dataset. These percentages describe the records analysed, not the proportion of the world's population exposed to each category.

## Key Insights

The exploratory analysis highlighted the following findings:

- AQI values were positively skewed, with the mean higher than the median.
- The recorded AQI values ranged from 6 to 500.
- PM2.5 had the highest average among the four pollutant measures examined.
- Good and Moderate were the most frequent categories, together accounting for approximately 81.7% of records.
- Recorded average AQI values differed considerably among the countries included in the comparison.
- Differences in data coverage may affect country-level comparisons.

## Limitations

- The findings depend on the records available in the selected dataset.
- Country averages may be affected by differences in record counts and coverage.
- The maximum AQI value was noted as an extreme observation, but no formal outlier test was performed.
- The analysis identifies patterns in the data; it does not establish the causes of air pollution.
- Pollutant averages must be interpreted with consideration of their measurement units and scales.

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Descriptive statistics
- Microsoft Excel PivotTables
- Data sorting and filtering
- Data visualisation
- AQI category analysis
- Statistical interpretation
- Communicating data-driven findings

## Conclusion

This task applied Microsoft Excel to explore air quality data, summarise AQI and pollutant measures, compare country-level averages, and visualise AQI category distributions.

The analysis highlighted a right-skewed AQI distribution, differences in recorded country averages, and the predominance of Good and Moderate categories in the dataset. It also strengthened my practical skills in exploratory data analysis, statistical interpretation, and data visualisation.

---

**Internship:** SWYNEX Technologies Data Analyst Internship  
**Task:** Task 2 — Exploratory Data Analysis (EDA)  
**Tool:** Microsoft Excel# SWYNEX-Task-2-EDA
Exploratory Data Analysis of the Global Air Pollution Dataset using Microsoft Excel.
