# **U.S. Housing Market Analysis**

Team Members:
Jasmine Cofield, Cassidy Cruz, Daniel Pineda, Edward Tabijie, and Widchy Joachim
---

## **Project Overview**
This project aims to analyze the U.S. housing market from January 2012 to June 2024 to identify national trends, regional differences, and unique marketplace behaviors. The analysis focuses on various aspects such as median sale prices, sales volume, days on market, inventory levels, and the impact of significant events like the COVID-19 pandemic on housing prices.

## **Datasets Used**
- **Source**: Redfin Housing Market Data (https://www.redfin.com/news/data-center/)
- **File**: `data.csv`

## **Research Questions**
1. How have housing prices on the national and state level (before, during, and after the COVID-19 pandemic (2019 - 2024))?
2. Which areas experienced the largest change in sales price and which experienced a decline?
3. Which markets could be ‘affordable’ and which are increasingly out of reach?
4. Which areas could be considered real estate ‘hotspots’ that people are looking to call home?


## **Methodology**
1. **Data Preparation**
   - The data was cleaned by handling missing values and converting date formats.
   - The dataset was transformed to focus on quarterly data for trend analysis.

2. **Analysis**
   - **Statistical Analysis**: Used descriptive statistics to summarize trends.
   - **Correlation Analysis**: Examined the relationship between median sale prices and homes sold.
   - **Trend Analysis**: Analyzed trends in new listings and sales volume over time.

3. **Visualization**
   - Data was visualized using `matplotlib` and `scipy.stats` to create line plots, scatter plots, and other charts that represent the findings.

## **Findings**
- **Consistent Growth**: Median sale prices have consistently increased since 2012, driven by demand, supply constraints, and favorable economic conditions.
- **Metro Area Growth**: Certain metro areas have seen rapid growth in sales volume and prices, influenced by population growth and economic development.
- **Market Motivation**: Regions with high days on market and new listings suggest outmigration, possibly due to economic decline or other factors.
- **COVID-19 Impact**: Housing prices surged during and after the COVID-19 pandemic due to low interest rates and changing housing preferences.
- **High and low YoY Growth**: A clear visualization of the Top 10 and Bottom 10 Regions by YoY Growth in Median Sale Prices (2024) and explanation based on researches.
- **Correlation**: A weak correlation between median sale prices and homes sold indicates that higher prices do not necessarily result in more sales.
- **% Changes in Home Sales**: in Home Sales volume continue to be dominated by larger counties but % change/growth provides a different perspective. Unsurprisingly, the counties with the largest change in home sales occurs in smaller non-urban counties


## **Code Usage**
1. **Imported Libraries**
   - The required Python libraries are : (`pandas`, `matplotlib`, `scipy`).
   
2. **Running the Analysis**
   - The code is organized into cells for each research question. Execute the cells in sequence to reproduce the analysis.

3. **Visualization**
   - The code includes various plotting functions to visualize trends and correlations.

## **Conclusion**
Our group hypothesized that Covid-19 had drastically impacted the housing market by reshaping general market behavior towards home ownership in major metropolitan cities. Despite the numerous factors that may impact this market, we  narrowed down our parameters to analyze trends purely based on market changes. Based on our analysis, we saw the median price for homes in the US sharply rise between this period and saw a major uptick in sales volumes for counties outside of major metropolitan areas (though we do see states like Florida, California, and Texas experience rapid growth based on annual sales volume). We also noticed that several of the fastest growing markets post-covid are in counties outside of major cities such as Los Angeles, New York, Atlanta, etc. and are instead growing in less densely populated counties like Cleveland County, NC or Beckham County, OK. We concluded that Covid-19 did create a major impact to the US housing market and the change in behavior between buyers and regional markets are clearly marked with a shift towards non-urban areas post-Covid. Of course, we acknowledge that there are still several factors outside of our analysis that does not capture the entire picture of general population behavior in the wake of Covid-19, the new market developments seen in our data do show a indication of a paradigm shift in housing desirability and costs.
