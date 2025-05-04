# Life Expectancy and GDP Analysis

## Overview
This project analyzes the relationship between GDP and life expectancy for six countries (Chile, China, Germany, Mexico, United States, Zimbabwe) from 2000 to 2015. The goal is to answer:
- Has life expectancy increased over time?
- Has GDP increased over time?
- Is there a correlation between GDP and life expectancy?
- What is the average life expectancy?
- What is the distribution of life expectancy?

## Dataset
- **Source**: World Health Organization and World Bank, provided by Codecademy.
- **Columns**:
  - `Country`: Chile, China, Germany, Mexico, United States, Zimbabwe
  - `Year`: 2000–2015
  - `Life_Expectancy`: Life expectancy at birth (years)
  - `GDP`: Gross Domestic Product (USD)
- **Rows**: 96 (16 years × 6 countries)

## Tools Used
- **Python**: pandas, matplotlib, seaborn
- **Jupyter Notebook**: For analysis and visualizations
- **Git/GitHub**: For version control and sharing

## Key Findings
- **Life Expectancy Trends**: Most countries show increases; Zimbabwe rose from 44 to 60 years.
- **GDP Trends**: China and USA showed significant growth; Zimbabwe remained low.
- **Correlation**: Moderate positive correlation overall (0.343); Zimbabwe has a strong correlation (0.96).
- **Average Life Expectancy**: Germany (80 years) highest, Zimbabwe (55 years) lowest.
- **Distribution**: Ranges from 44 to 80 years, left-skewed due to Zimbabwe’s lower values.

## Repository Structure
- `all_data.csv`: Dataset
- `Life_Expectancy_GDP.ipynb`: Jupyter Notebook with analysis
- `.gitignore`: Excludes unnecessary files
- `README.md`: This file

## How to Run
1. Clone the repository: `git clone https://github.com/GoudyMT/GDP-and-Life-Expectancy.git`
2. Install dependencies: `pip install pandas matplotlib seaborn`
3. Open `Life_Expectancy_GDP.ipynb` in Jupyter Notebook and run all cells.

## Acknowledgments
- Codecademy for the project framework and dataset.
- World Health Organization and World Bank for the data.
