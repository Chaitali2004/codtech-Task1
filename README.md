# codtech-Task1

Name: Chaitali Jain
Company: Codtech It Solutions
ID: CT6WDS1358
Domain: Data Analytics
Duration: July to August 2024
Mentor: Muzammil Ahmed

Google Play Store Exploratory Data Analysis (EDA) Project

Welcome to the Google Play Store EDA project repository! This project provides a comprehensive exploratory data analysis of the Google Play Store dataset, aimed at uncovering insights about app features, trends, and relationships.

Project Overview
This project involves a detailed analysis of the Google Play Store dataset, which includes various app attributes such as ratings, reviews, size, and installs. The goal is to clean and preprocess the data, perform exploratory data analysis (EDA), and visualize the findings to gain actionable insights.

Key Objectives
•	Data Cleaning: Prepare the dataset by handling missing values, correcting data types, and normalizing data.
•	Exploratory Data Analysis: Analyse and visualize the data to uncover trends, patterns, and relationships.
•	Visualization: Create various plots to represent data insights clearly.

Technologies Used 

•	Python: The primary programming language for data analysis.
•	Pandas: Used for data manipulation and analysis.
•	Matplotlib: Employed for creating static animated and interactive visualizations.
•	Seaborn: utilized for making statistical graphics that are informative and attractive. 

Data Overview:
![Screenshot 2024-07-18 114402](https://github.com/user-attachments/assets/b04e1d66-1f61-4d6b-9a2a-9b41eade85d2)

Data Cleaning and Wrangling
1.	Renaming Columns: Renamed columns for better clarity.
2.	Handling Missing Values: Removed rows with null values.
   ![Screenshot 2024-07-18 115540](https://github.com/user-attachments/assets/5157798c-151f-4604-81aa-bc1cf53d77ac)

 
4.	Data Type Conversion:
o	Converted Reviews to numeric values.
o	Cleaned Installs to numeric format.
o	Converted Price to float after removing currency symbols.
o	Converted LastUpdated to datetime format.
5.	Size Conversion: Transformed Size from string to numeric by handling size units (e.g., 'M', 'k').

   
Exploratory Data Analysis (EDA)
Summary Statistics
•	Generated summary statistics for both numerical and categorical features.

Feature Analysis
•	Content Rating:
o	Visualized the distribution of ContentRating with a pie chart and horizontal bar chart.

•	App Installs by Category:
o	Created a bar plot to show average installs per category.

Trend Analysis

•	Average Ratings Over Time:
o	Plotted a line graph showing the trend of average app ratings over the years.

Relationships and Correlations
•	Pairwise Relationships:
o	Used a pair plot to explore relationships between numerical features.
•	Correlation Analysis:
o	Displayed a heatmap of correlations among selected numerical features.


Visualizations

•	Pie Chart: Distribution of content ratings. 
![Screenshot 2024-07-18 124350](https://github.com/user-attachments/assets/941c4f8f-ce5e-4b05-aacb-9787031c545c)

•	Horizontal Bar Chart: Frequency of content ratings. 
![Screenshot 2024-07-18 124948](https://github.com/user-attachments/assets/526ad2d8-38b3-4baf-ae9a-e445125e20c7)

•	Bar Plot: Average installs per app category. 
![Screenshot 2024-07-18 124716](https://github.com/user-attachments/assets/49770e14-ed9a-495e-b3f7-43ce18415607)

•	Line Plot: Trend of average app ratings over time.
![Screenshot 2024-07-20 094838](https://github.com/user-attachments/assets/576c42ef-a27e-4148-8da1-a70764f657b9)

•	Pair Plot: Visual representation of relationships between numerical features.
![Screenshot 2024-07-20 102943](https://github.com/user-attachments/assets/1352e6cb-a59a-42f4-9649-42947d94ab31)

•	Histograms: Distribution of key numerical features including Rating, Reviews, Size, Installs, and Price
![Screenshot 2024-07-20 103354](https://github.com/user-attachments/assets/103f824d-bd58-4150-ae61-1043cc1e4211)

•	Heatmap: Correlation matrix of selected numerical features.
![Screenshot 2024-07-20 101730](https://github.com/user-attachments/assets/c443a895-43b4-4cc4-81f8-a321b9db29c3)


Conclusion:
In this exploratory data analysis (EDA) of the Google Play Store dataset, numerous notable insights and trends have emerged: 

1. Data Overview and Cleaning: - The first dataset included both categorical and numerical variables. Extensive data cleaning was carried out, including resolving missing numbers, rectifying data types, and converting sizes to a standard numeric format. 

2. Statistical Summary: - The summary statistics revealed a diverse set of software ratings, install numbers, and costs. This variation displays the wide range of apps available on the Google Play Store. 

3. Feature Analysis: - 
Category Variables: The pie chart of 'ContentRating' revealed a high prevalence of specific content ratings, indicating popular age groups for app content. The horizontal bar chart highlighted the dispersion of these ratings. 
 Numerical Variables: A bar plot of average installs by category revealed that certain categories attract more installs, which can help understand market trends. 

4. Trends Over Time: The line plot shows an upward trend in average rating, indicating that app quality has improved over time. This could indicate technological breakthroughs or improved developer practices. 

5. Correlation Analysis: - The heatmap of correlations between characteristics such as 'Rating', 'Reviews', 'Size', 'Installs', and 'Price' revealed intriguing patterns. For example, greater app ratings were associated with more installs, although app size and pricing were not strongly associated with ratings. 
6. Pairwise Relationships - The pair plot offered a thorough understanding of the interactions between numerical features. It was clear that 'Reviews' and 'Installs' have a strong positive correlation with 'Rating', emphasizing the importance of user interaction in app success. 

7. Histograms - Histograms showed the distribution of significant numerical features. Most features, such as 'Installs' and 'Reviews', had skewed distributions, indicating that a small number of apps dominate user involvement. 

Overall, the EDA provided useful insights into the Google Play Store dataset, allowing us to better understand the distribution of app features, their correlations, and trends over time. This study lays the groundwork for more sophisticated modelling and strategic decisions on app development and marketing tactics.







