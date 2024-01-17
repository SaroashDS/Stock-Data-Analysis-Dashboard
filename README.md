# Stock-Data-Analysis-Dashboard

![Screenshot 2024-01-16 010644](https://github.com/Aliihadi8114/Stock-Data-Dashboard-BI/assets/144004248/186929d7-e99a-4dea-bd99-9fba88b8a451)
## Dashboard Link: https://app.powerbi.com/groups/me/reports/804d76a1-15f9-4d46-b72d-88252006f6b7/ReportSection?experience=power-bi

## Problem Statement
This dashboard aims to provide comprehensive insights into stock data, enabling users to analyze the performance of different companies. Users can select a specific company, explore stock prices over multiple years, and understand key financial metrics. The dynamic time selection and interactive buttons enhance the user experience, allowing for quick analysis.

## Features:
### 1. Company Selection:
- Users can choose a specific company from a list of 10 different companies.
### 2. Stock Price Overview:
- Display of stock prices over multiple years.
- User-friendly interface for easy navigation through different years.
- Visualization through an area chart showcasing stock prices over time.
### 3. Financial Metrics:
- Total Return: Represents the total return on investment over the selected period.
- Total Percentage Gained: Indicates the overall percentage gain during the chosen time frame.
- Compound Annual Growth Rate (CAGR): Represents the annual growth rate of an investment over a specified period.
### 4. Dynamic Time Selection:
- Users can dynamically select the time period (1 year, 3 years, 5 years, or all years) to view relevant data.
### 5. Interactive Buttons:
- Buttons for 1 year, 3 years, 5 years, and all years for quick switching between different time frames.
### 6. Bookmarks:
- Efficient use of bookmarks for seamless navigation between selected time frames.
- Bookmarks are organized logically for a smooth user experience.
### 7. Customized Buttons:
- Buttons with clear labeling and dynamic coloring based on the selected time frame.
- Up and down arrows indicate positive or negative trends in financial metrics.

## DAX Measures:
### 1. Total Return:
- Purpose:
Quantifies the overall change in stock value over a selected period.

- Calculation:
Identify the maximum and minimum dates within the selected timeframe.
Determine the maximum and minimum stock prices corresponding to these dates.
Calculate the difference between the maximum and minimum stock prices.

### 2. Total Percentage Gained:
- Purpose:
Expresses the percentage change in the stock value over a chosen period.

- Calculation:
Utilize the same date and price calculations as in Total Return.
Divide the price difference by the minimum stock price to obtain a percentage.
Normalize the percentage change over the number of years in the selected period.

### 3. Compound Annual Growth Rate (CAGR):
- Purpose:
Provides a smoothed annualized rate of return, considering the effect of compounding over time.

- Calculation:
Determine the starting and ending values of the stock.
Calculate the total number of years between these two points.
Apply the CAGR formula: (Ending Value / Starting Value)^(1 / Number of Years) - 1.

### 4. Placeholder Measure for Color Coding:
- Purpose:
Used for dynamic color coding of the Total Return subtitle based on the trend.

- Calculation:
Check if the Total Return contains an indicator of a positive or negative trend.
Assign a green color for positive trends and red for negative trends.


![Screenshot 2024-01-16 011538](https://github.com/Aliihadi8114/Stock-Data-Dashboard-BI/assets/144004248/dcef36d7-1749-4c9d-9a1c-5d9ad85a8d48)



## Insights:
The Stock Data Dashboard offers valuable insights into the performance of selected companies. Users can analyze stock prices, track financial metrics, and identify trends over different time frames. The interactive and user-friendly design enhances the overall user experience, making it a powerful tool for financial analysis.

<div align="center">
  <img src="https://github.com/Aliihadi8114/Stock-Data-Dashboard-BI/assets/144004248/0524bba6-3e66-4fef-af01-5b44701cb9f2" alt="Description of the image">
</div>



## Employees Data:
The dashboard also provides total number of employees and Sales/Employee for five years.


![Screenshot 2024-01-16 012311](https://github.com/Aliihadi8114/Stock-Data-Dashboard-BI/assets/144004248/510bd789-0ec3-4c1f-a2a6-7e238450d065)
