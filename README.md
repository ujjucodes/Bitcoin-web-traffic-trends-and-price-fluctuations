Bitcoin Web Traffic, Trends, and Price Fluctuations: A Data Analysis Project
🎯 Project Overview
This project presents a comprehensive analysis of user engagement and content trends from a public dataset related to Bitcoin. The goal of this work is to demonstrate a full-cycle data analysis workflow, starting from raw data extraction and moving through cleaning, wrangling, analysis, and advanced visualization.

The analysis uncovers insights into user behavior, content popularity, geographic distribution, and the relationship between online discussions and market price fluctuations. The findings are presented through a series of interactive and static visualizations that tell a data-driven story about the platform's user base and the topics they engage with.

📂 Report and Dataset Basis
The analysis is based on a dataset of user posts and interactions. The primary goal was to wrangle this raw data into a clean, structured format suitable for uncovering meaningful patterns.

To enrich the analysis, an external dataset of historical Bitcoin prices was integrated. This allowed for a multi-dimensional investigation into potential correlations between online discussion trends and real-world market activity, forming a core part of the report's insights.

🛠️ Techniques and Methodologies Used
This notebook demonstrates a wide range of data wrangling and analysis techniques to process and interpret the data.

1. Data Cleaning and Preprocessing:
Handling Missing Values: Strategically identified and removed rows and columns with excessive missing data to ensure the integrity of the dataset.

Data Type Conversion: Corrected data types for critical columns (e.g., converting timestamps from strings to datetime objects) to enable accurate time-series analysis.

Text Cleaning: Utilized regular expressions (regex) to clean and standardize user-submitted text, removing irrelevant characters, HTML tags, and noise to prepare it for natural language processing.

Feature Engineering: Extracted meaningful features from existing data, such as deriving the year and month from timestamp columns to facilitate trend analysis over time.

2. Text Analysis (Natural Language Processing):
Tokenization: Broke down post titles and bodies into individual words (tokens).

Stop Word Removal: Used the NLTK (Natural Language Toolkit) library to filter out common English stop words (e.g., "the", "a", "is") to focus on the most meaningful terms.

Frequency Distribution: Calculated and visualized the frequency of the most common words to identify the key topics of discussion within the dataset.

3. Data Visualization:
Interactive Time-Series Charts: Employed the Plotly library to create dynamic visualizations, including:

Candlestick Charts to display the daily fluctuations of Bitcoin prices (Open, High, Low, Close).

Line Charts to track the volume of posts over time, revealing trends in user activity.

Geographic Mapping: Created a Choropleth Map to visualize the worldwide distribution of users. A logarithmic scale was used to effectively represent the wide range of user counts across different countries.

Bar Charts and Histograms: Used matplotlib and seaborn for static visualizations, such as plotting word frequencies and analyzing the distribution of user scores.

4. Statistical Analysis:
Descriptive Statistics: Calculated summary statistics to understand the central tendency and spread of numerical data.

Correlation Analysis: Investigated the relationship between post activity (volume of posts) and Bitcoin price movements by overlaying time-series data.

💡 Key Findings and Visualizations
The analysis culminates in several key insights, supported by powerful visualizations:

Topic Identification: By analyzing word frequencies, the project successfully identified the core topics discussed by users, confirming the dataset's relevance to Bitcoin and related technologies.

User Activity Trends: Time-series analysis revealed clear patterns in user engagement, showing peaks and troughs in post volume that can be correlated with external events.

Market Correlation: The interactive candlestick charts, when viewed alongside post volume data, provide a compelling visual tool to explore the hypothesis that surges in online discussion are linked to periods of high market volatility.

Global User Distribution: The choropleth map effectively illustrates the platform's global reach, highlighting hotspots of user activity in North America, Europe, and other regions, while also identifying areas with lower engagement.

Overall, this notebook successfully transforms raw, messy data into a clean and insightful report, showcasing a strong command of data wrangling techniques and visual storytelling.
