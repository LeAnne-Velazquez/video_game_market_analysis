# Video Game Sales Analysis
This project explores global video game sales during the emerging 3D gaming era (1995–2015), using Python for data preprocessing and Power BI for interactive visualization. The analysis focuses on trends across home gaming platforms, genres, and regional markets.
The goal of this project is to translate raw sales data into identifiable patterns within the global video game market, leading to actionable insights. 

## Tools & Technologies
Python (pandas) – data cleaning, transformation, and preprocessing
Power BI – interactive dashboard development, data modeling, and visualization
DAX (Data Analysis Expressions) – creating calculated measures, KPIs, and supporting data modeling within Power BI

## Data Source
Video Game Sales. – Kaggle
https://www.kaggle.com/datasets/anandshaw2001/video-game-sales?resource=download

## Key Insights
The PlayStation 2 (PS2) emerges as the top-selling platform across the dataset.
The Action genre ranks as the highest-performing genre across platforms and regions.
North America led global game sales, while Japan remained the smallest market.
Japan diverged from global trends, not experiencing the 2006–2009 sales peak seen in other regions

## Data Preparation & Methodology
Data was cleaned and preprocessed using Python (Pandas) to ensure consistency and support reliable time-series and comparative analysis in Power BI.
Key steps included:
  Handling missing and inconsistent values, including converting missing publisher values to null to prevent misleading aggregations in regional and genre
  analysis
  Retaining records with missing year values where appropriate, while converting the Year field to numeric format to support time-series analysis
  Filtering the dataset to include home gaming systems only
  Focusing on 3D-capable and selected console categories to support consistent cross-platform comparisons
  Excluding newer-generation consoles (e.g., PS4, Xbox One) due to limited representation within the 1995–2015 timeframe
  Aggregating sales data across regions and platforms for analysis in Power BI
  Structuring the dataset for efficient modeling and dashboard development
Included Platforms: GC, N64, PC, PS, PS2, PS3, SAT, Wii, WiiU, X360, XB
 
## View the Dashboard
👉 https://app.powerbi.com/view?r=eyJrIjoiODBmZTIwN2MtMTJiNC00MzkzLTg3M2YtNmJjMjI2YmFlMjc4IiwidCI6ImMyZjEyZmQwLWY5MGMtNDlmMy05ODcxLTAwMmYwODY4MzljMSIsImMiOjZ9
Features:
  Interactive filters by year, platform, genre, and region
  Regional breakdowns of sales trends

## Future Directions
Incorporate recent gaming data (post-2015 trends)
Add predictive analysis or forecasting models
Enhance interactivity with additional drill-through features
