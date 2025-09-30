Bitcoin Web Traffic, Trends, and Price Fluctuations

📜 Project Overview
This project provides a comprehensive analysis of a public dataset centered on Bitcoin-related web traffic and user discussions. The primary objective is to demonstrate a complete, end-to-end data wrangling and analysis workflow. The notebook takes raw, unstructured data and transforms it into a clean, insightful report that visualizes user engagement patterns, content trends, and the geographic distribution of the user base.

A core component of this analysis is the integration and wrangling of an external dataset of historical Bitcoin prices. By merging this financial data with the platform's user activity, the project explores the compelling relationship between online discussion volume and real-world market volatility. This multi-dimensional approach provides a richer context for understanding the factors that drive user engagement.

🛠️ Techniques and Analysis
The notebook employs a robust set of data science techniques to process, analyze, and visualize the data:

Data Wrangling & Cleaning: The initial and most critical phase involves intensive data cleaning. This includes handling missing values, correcting data types (especially converting strings to datetime objects for time-series analysis), and using regular expressions (regex) to sanitize user-submitted text fields from noise and HTML tags.

Text Analysis & NLP: The Natural Language Toolkit (NLTK) is utilized for text processing. This includes tokenizing post titles, removing common English stop words, and performing frequency analysis to identify the most prominent topics of discussion.

Advanced Visualization: The Plotly library is heavily used to create dynamic and interactive visualizations. Key outputs include interactive candlestick charts for displaying market prices and a choropleth map to effectively illustrate the global distribution of users with a logarithmic scale.

💡 Key Findings
The analysis successfully identifies key discussion topics, maps the platform's global user hotspots, and visually correlates spikes in user activity with significant Bitcoin price movements, demonstrating a strong workflow for turning raw data into a compelling, data-driven narrative.
