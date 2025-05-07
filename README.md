# 🎮 Ice Online Store: Video Game Sales Analysis

## 📝 Context
Ice Online Store is a global video game sales platform operating across different regions: North America (NA), Europe (EU), and Japan (JP). The goal of this project is to analyze historical sales data, user and expert ratings, game genres, and platforms, to identify patterns that predict the success of video games and help plan more effective advertising campaigns for 2017. Using data from 2016, the aim is to optimize marketing strategies and select the most promising titles.

## 🛠️ Tools Used
- **Python**: Data analysis and statistical modeling.
- **Pandas**: Data cleaning, transformation, and analysis.
- **Matplotlib** and **Seaborn**: Visualization of patterns and trends in game sales and characteristics.
- **SciPy**: Statistical tests to validate hypotheses about differences in ratings and sales.
- **Jupyter Notebook**: Interactive and detailed documentation of the analysis workflow.

## 📈 Results Analysis
The project was structured in several phases:

1. **Data Preprocessing**:
   - Cleaning columns and handling missing values, such as replacing "TBD" in ESRB ratings.
   - Conversion of sales data from different regions into a unified format.
   - Calculation of total sales per game.

2. **Descriptive Analysis**:
   - Analysis of video game sales over the years, observing the most profitable platforms.
   - Comparison of sales by platforms, identifying those that have disappeared and those that have emerged successfully.

3. **Hypothesis Testing**:
   - Evaluation of the differences in average ratings between platforms and genres.
   - Confirmation of significant differences in ratings for platforms such as Xbox One and PC, as well as between Action and Sports genres.

4. **Regional Analysis**:
   - Identification of the leading platforms and genres in different regions, and how ESRB ratings affect sales.

## 📋 Conclusions
- The most profitable genres, such as **Action** and **Sports**, had a larger audience, with consistent sales across multiple platforms.
- The most popular platforms, like **PlayStation** and **Xbox**, performed better in North America, while sales in Japan were dominated by more local platforms.
- Reviews from both users and critics influence sales, but the impact varies by region and platform, highlighting the importance of tailoring marketing strategies to local preferences.
- The ESRB rating showed that games with an **“E”** (Everyone) rating and those without ratings were the best-sellers across all regions, especially in North America and Japan, suggesting that consumers prefer games accessible to a broader audience.

This analysis provides a comprehensive view of the video game market, helping Ice Online Store make data-driven decisions to improve its advertising campaigns and maximize profitability in 2017.
