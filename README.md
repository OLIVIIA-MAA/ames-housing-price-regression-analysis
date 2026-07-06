# Housing Price Drivers and Regression Analysis

## Project Overview

This project analyzes housing prices using the Ames Housing dataset.

The goal was to understand which property characteristics are most strongly related to sale price and to build regression models that estimate house prices based on selected numerical features.

The analysis focuses not only on model performance, but also on understanding what drives housing prices and where the model has limitations.

---

## Dataset

The dataset contains **2,930 residential property records** and **82 variables** describing different aspects of each property.

For this project, I focused on selected numerical variables that are easy to interpret and suitable for regression modeling.

| Variable | Description |
|---|---|
| `price` | Final sale price of the property |
| `area` | Above-ground living area |
| `bedrooms` | Number of bedrooms above ground |
| `total_rooms` | Total number of rooms above ground |
| `year_built` | Original construction year |
| `overall_quality` | Overall material and finish quality rating |

The target variable is:

```text
price
