# Premier-League-Club-Investment-Analysis

## Context:
Company ABC is strategically investing in top-tier sports teams to diversify its portfolio. They possess a comprehensive dataset detailing the performance metrics of all teams that have participated in the Premier League to date. This dataset includes crucial information such as goals scored and conceded, top finishes, and other relevant details, providing a robust foundation for investment decisions.

## Data Overview:
Dataset: Premier League Final Data.csv
The dataset encompasses performance data of all football clubs that have ever participated in Premier League tournaments.

## Data Dictionary:
- Club: Name of the football club
- Matches: Total number of Premier League matches played by the club
- Wins: Number of matches won in the Premier League
- Loss: Number of matches lost in the Premier League
- Draws: Number of matches drawn in the Premier League
- Clean Sheets: Number of matches in which the club prevented the opposing team from scoring
- Team Launch: Year the club was founded
- Winners: Number of times the club has won the Premier League
- Runners-up: Number of times the club has finished as runners-up in the Premier League
- Lastplayed: Last year the club participated in the Premier League

## Primary Objective:
Company ABC aims to identify and invest in high-performing Premier League clubs that are not currently owned by competitors. The goal is to ensure that investments are directed towards clubs that promise profitability and long-term success. The analytics team has been tasked with generating a detailed report on club performance to guide these investment decisions.

## Methodology:
### 1. Data Collection and Preparation:

- Loading the Dataset: The dataset, Premier_League_Final_Data.csv, was loaded and inspected for any inconsistencies or missing values.
- Data Cleaning: Steps were taken to handle missing values, correct any inaccuracies, and ensure the dataset was ready for analysis. This included:
  - Removing duplicates.
  - Imputing or dropping missing values based on domain knowledge.
  - Ensuring data types were correctly assigned.

### 2. Exploratory Data Analysis (EDA):
- Descriptive Statistics: Calculated basic statistics (mean, median, standard deviation) for each numeric column to understand the distribution of data.
- Visualizations: Created various plots to visualize the data:
  - Histograms for the distribution of goals scored, goals conceded, and matches played.
  - Box plots to identify outliers in performance metrics.
  - Scatter plots to explore relationships between variables such as matches played and wins.
- Key Findings: Noted significant trends, such as:
  - Clubs with consistently high win rates.
  - The relationship between the number of clean sheets and overall club performance.

### 3. Performance Metrics Analysis
- Win-Loss Ratios: Calculated win-loss ratios to rank clubs based on their historical performance.
- Top Performers: Identified clubs with the highest number of wins and clean sheets.
- Recent Performance: Analyzed recent performance trends to highlight clubs showing improvement or decline.

### 4. Investment Potential Assessment
- Competitor Analysis: Filtered out clubs already owned by competitors.
- Performance Benchmarking: Compared potential investment clubs against top-performing clubs to assess their relative strengths.
- Financial Projections: Estimated potential returns based on historical performance data and market conditions.

## Key Findings:
1. Top Performing Clubs: Manchester City, Liverpool, and Chelsea consistently ranked among the top performers based on winning percentage, total points, and goal difference.
2. Market Value Drivers: While winning percentage is a significant predictor of market value, the analysis reveals that it's not the sole factor. Goal difference and spending also play crucial roles in determining a club's market value.
3. Clean Sheet Impact: A strong positive correlation was observed between clean sheet percentage and winning percentage, reinforcing the importance of defensive solidity for overall success.
4. Relegation and Promotion Impact: Clubs like Blackburn Rovers, despite past successes, may not be ideal investments due to relegation and inconsistent performance.
5. Investment Recommendation: Leicester City emerges as the most promising investment opportunity due to their consistent top 10 finishes, past championship win, and potential for further growth with financial backing

## Conclusion:
This data analysis project not only demonstrates the power of statistical techniques in evaluating investment opportunities in the Premier League but also provides a clear, data-driven recommendation. The identification of Leicester City as a prime investment target showcases the ability to translate complex data analysis into actionable insights for potential investors.
Leicester City's consistent top 10 finishes in recent years, coupled with their remarkable Premier League championship in 2016, demonstrates their capability for high performance. While they may not currently be at the absolute top of the league table, their consistent presence in the top half and potential for further growth with sufficient investment make them a promising prospect.
This analysis underscores the importance of considering a club's historical performance, recent trajectory, and future potential when making investment decisions. By looking beyond current standings and delving into the underlying data, we can identify opportunities that may not be immediately apparent.

## Acknowledgments
I would like to express my sincere gratitude to Data Analyst Duo for generously providing the dataset used in this analysis. 
