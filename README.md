# Global_Happiness_index_analysis
a simple data science project to analyse the  Global Happiness Index
This project explores the factors that contribute to national happiness levels across the globe using the World Happiness Report dataset. After cleaning the data and renaming features for better accessibility, I conducted a distribution analysis which revealed that happiness scores are not perfectly normal, often skewed by a "tail" of countries facing extreme hardship. Consequently, I utilized Spearman Rank Correlation to accurately measure the relationships between socio-economic factors and the overall happiness score, ensuring the analysis remained robust against outliers and non-linear trends.
The analysis identifies Social Support (0.80) and GDP per Capita (0.79) as the two strongest predictors of a nation's happiness. These "Heavy Hitters" suggest that while economic prosperity is vital, the strength of a country's social safety net and community reliability is equally, if not more, important for life satisfaction. Furthermore, Healthy Life Expectancy (0.78) showed a nearly identical correlation, confirming a "package deal" relationship where wealth, health, and community support move together to lift a nation’s ranking.
Interestingly, the data revealed that Generosity (0.08) had a negligible correlation with the overall happiness score, suggesting that a country's philanthropic habits are not a primary driver of its citizens' reported satisfaction. My comparative analysis of the Top 10 vs. Bottom 10 countries highlighted a massive "Happiness Gap," with Nordic countries consistently leading due to high scores in Freedom and low Perception of Corruption. Conversely, the bottom-ranked nations shared commonalities in low economic output and systemic instability, emphasizing that the absence of basic security and social support creates a ceiling on national well-being.
Data Cleaning: Handled missing values and renamed columns.

Statistical Testing: Ran Shapiro-Wilk and chose Spearman Correlation.

Visualizations: Created a Distribution Plot, Heatmap, and Top/Bottom Bar Chart.

Interactive Element: Built a Plotly Choropleth map.

The above project uses the dataset publicly available on Kaggle
