# 🌧️ Explore Annual Rainfall Patterns in Southern Israel

[![IMS Logo](https://ims.gov.il/themes/imst/ims/images/logo.jpg)](https://ims.gov.il/en)<br>
# [slideshows](https://nisanman.github.io/NegevRainAnnual/#/)
This is a data presentation project based on rainfall analysis using Python and Jupyter Notebook.

## 🔍 Overview
This project explores the annual rainfall patterns across twenty-six meteorological stations in Southern Israel, utilizing data from the [Israel Meteorological Service (IMS)](https://ims.gov.il/he/data_gov). The data was analyzed using Python and various libraries for statistical analysis and data visualization.

## 📊 Data and Web API
The project leverages rainfall data which can be explored through the provided Jupyter Notebook. You can also access the data and findings via the [Web API](https://ims.gov.il/he/ObservationDataAPI), but you will need a valid token to access it.

## 💬 Discussion
Analyzing rainfall data proves challenging when relying on a single trendline due to substantial correlation within the dataset. The data does not fit neatly into a linear trend, and different subsets of years lead to varying slopes in trendlines. This is visually demonstrated, as selecting different ranges of years can show either a positive or negative slope.

This study challenges the assumption that rainfall patterns are solely influenced by the time period chosen for measurements. By calculating all possible trendlines, the project captures the respective slopes over different time periods, allowing for a more comprehensive analysis. The heatmaps presented in the project visually represent these fluctuating slopes, revealing that rainfall amounts in southern Israel have generally declined over time.

While examining a 70-year span, the slope of the trendline varies significantly, but by focusing on periods of at least 10 years, a consistent downward trend emerges, marked by a predominant red hue, particularly in the upper corner. This suggests a clear and ongoing decrease in rainfall over time.

## 📈 Tableau 📉
[Click here to view the Tableau visualization](https://public.tableau.com/shared/GN7J29MRK?:display_count=n&:origin=viz_share_link)
