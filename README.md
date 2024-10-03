# Crime Data Analysis in Toronto

## **Overview**

This project involves analyzing crime data from Toronto between the years 2018 and 2023. The dataset consists of various categories of crime, including Homicide, Assault, Robbery, and Auto Theft. Using Python and SQL, I processed and visualized the data to explore trends, patterns, and geographical distribution of crimes across different neighborhoods in Toronto.

**Tools and Technologies**
  - **Python:** Used for data processing, cleaning, and visualizations.
  - **Pandas:** For efficient handling and analysis of large datasets.
  - **Folium:** To generate interactive maps and crime heatmaps across Toronto.
  - **SQL:** Data filtering and extraction.
  - **Seaborn & Matplotlib:** For creating insightful visualizations and trends analysis.

**Key Visualizations**

  1. **Heatmaps of Crime Categories:**
  Visual representations of different crime categories like Homicide, Assault, Robbery, and Auto Theft are plotted using Folium. Heatmaps depict high-density crime areas across Toronto.

  ![image](https://github.com/user-attachments/assets/72159127-b57b-48fd-85c1-6bf449eff943)  ![image](https://github.com/user-attachments/assets/54e2a2d2-d709-4db1-9ce9-2287099870dc)

  2. **Distribution of MCI Categories:**
  A pie chart representing the distribution of Major Crime Indicators (MCI). This visual helps in understanding the prevalence of various crime categories (Homicide, Assault, Robbery, Auto Theft, etc.) in the dataset.

  ![image](https://github.com/user-attachments/assets/bf8e05f0-abc4-483a-bbb8-325249090494)


  3. **Crime Distribution by Day of the Week:**
  A count plot showing the number of crimes that occurred on different days of the week, giving insights into weekly crime patterns.

  ![image](https://github.com/user-attachments/assets/9b205f31-2878-4f53-97e9-66a9ff45d840)

  4. **Trends in Crime Over the Years:**
  A line plot depicting trends in crime across years, illustrating how the occurrence of various crimes has changed over time.

  ![image](https://github.com/user-attachments/assets/839c4e91-0dd9-4088-a20a-40bf07adf0ea)

  5. **Crimes by Neighborhood:**
  A bar plot highlighting the top 10 neighborhoods with the highest crime counts, providing a clear understanding of which areas experience more criminal activities.

  ![image](https://github.com/user-attachments/assets/ac3e7006-6485-46bf-afaa-117deaab0aa5)


**Data Preprocessing and Imputation**

The dataset had missing values, particularly in the OCC_HOUR field for Homicide records. I implemented imputation by filling in the missing values based on the mode of the crime hour for each month. Additionally, the OCC_TIME_RANGE column was derived by categorizing crime hours into different time periods like Morning, Afternoon, Evening, and Night.

**SQL Querying for Data Extraction**

SQL was used to query large volumes of data and extract relevant crime information based on categories, years, and geographical areas. This helped in filtering data for deeper analysis and visualization.

**Conclusion**

This project provides a comprehensive analysis of Toronto's crime data, revealing significant trends and spatial patterns. The combination of heatmaps and visual plots helps in better understanding crime dynamics across various neighborhoods and categories.

