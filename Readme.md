# IPL Data Analysis (2008–2017)

This project analyzes Indian Premier League (IPL) data for the seasons 2008–2017 using PySpark and Spark SQL.

## Data Pipeline

- **Source:** IPL datasets fetched from an open data API
- **Storage:** Data stored on AWS S3 in CSV format
- **Processing:** Data pulled from S3 using Spark, transformed with PySpark, and analyzed with PySpark and SQL

## Main Data Files

- `Ball_By_Ball.csv` — ball-by-ball delivery data
- `Match.csv` — match information
- `Player.csv` — player details
- `Player_match.csv` — player performance per match
- `Team.csv` — team information

## Workflow Steps

1. **Load Data:** Data files loaded from S3 with PySpark using custom schemas
2. **Transform:** Cleaned, filtered, and engineered new columns for advanced analysis
3. **Analyze:** Insights generated using Spark SQL and DataFrame API

## Example Insights

- Top run-scorers and wicket-takers by season
- Most successful teams and venues
- Toss and match outcome relationships
- Player performance trends

## Getting Started

- Requires Python and Apache Spark (PySpark)
- AWS credentials setup for S3 access is required

**Note:**  
See project scripts or notebooks for code and detailed analysis steps.

## Acknowledgements

- Data sourced from [data.world IPL dataset](https://data.world/raghu543/ipl-data-till-2017)

---
