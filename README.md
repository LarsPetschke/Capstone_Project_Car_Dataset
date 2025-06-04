# Google Data Analytics Capstone Project: Car Dataset

## Overview
This project is the final capstone of the [Google Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-data-analytics). It demonstrates the complete data analysis process using a real-world automotive dataset. The goal is to uncover trends in car pricing, performance, fuel efficiency, and market segmentation.

---

## Business Task
**"What factors influence the price and popularity of cars, and how are engine performance and fuel efficiency related to these factors?"**

This analysis aims to identify actionable patterns in pricing (MSRP), fuel efficiency (MPG), and engine specs (HP, Cylinders) to support product positioning and marketing strategies.

---

## Tools Used
- **Python**: pandas, seaborn, matplotlib  
- **R (via Colab)**: ggplot2, dplyr, reshape2, gridExtra  
- **Google Colab**: for interactive notebook execution  
- **GitHub**: for project versioning and publication

---

## Project Steps (Google DA Framework)

### 1. Ask
- Defined a clear business question around car value, efficiency, and popularity.

### 2. Prepare
- Imported dataset containing 11,000+ entries from 1995 onward.
- Cleaned and unified text data.
- Filled missing values via research and logical imputation.

### 3. Process
- Verified data types and standardized formats.
- Filtered records, removed duplicates.
- Created new variables:
  - `Total MPG` = average of city and highway MPG  
  - `Price per HP` = MSRP divided by engine horsepower

### 4. Analyze
- Descriptive statistics: mean, median, std dev for key metrics.
- Grouped analysis by drivetrain, size, and engine type.
- Visualizations:
  - Histogram (MPG)
  - Bar plot (Vehicle Size vs MSRP)
  - Scatter plot (HP vs MSRP)
  - Box plot (MSRP by Driven Wheels)
  - MPG by Transmission Type (Grouped Bar)
  - Correlation Heatmap

### 5. Share
- Key insights presented with clean visualizations.
- Positive correlation between horsepower and MSRP.
- Direct Drive vehicles outperform in MPG.
- AWD & RWD vehicles dominate luxury segment.
- Popularity metric showed little correlation with price or efficiency.

### 6. Act
**Recommendations:**
1. Promote fuel-efficient compact/midsize cars to cost-sensitive consumers.
2. Position AWD and high-horsepower cars as premium offerings.
3. Use transmission type (Direct Drive) to target eco-conscious drivers.
4. Deprioritize generic popularity metrics in favor of measurable specs.

---

## Repository Structure

```
📦car-dataset-capstone/
┣ Capstone_Project_Car_Dataset.ipynb
┣ car_dataset.csv
┣ README.md
┣ visualizations/
┃ ┣ city_mpg_histogram.png
┃ ┣ engine_hp_vs_msrp.png
┃ ┣ correlation_matrix.png
┗ presentation/
┗ Car_Data_Capstone_Presentation.pdf
```

---

## Outcome
This project demonstrates proficiency in:
- Cleaning and transforming messy real-world data
- Combining Python and R for enhanced analytics
- Applying business thinking to technical results
- Communicating insights through visual storytelling

---

## License & Credits
- Created by **Lars Petschke** as part of the Google Data Analytics Certificate


