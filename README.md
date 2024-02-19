# Data-analysis-Project-Glassdoor-job-Data
Data Cleaning, Visualization &amp; Pandas: Improved dataset clarity with pandas for cleaning. Seaborn &amp; Matplotlib used for insightful visualizations. Explore for a clear understanding!
## Table of Contents

- [Data Cleaning](#data-cleaning)
- [Visualization](#visualization)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Data Cleaning

The dataset is loaded using pandas, and various cleaning steps are performed:
- Handling missing values
- Transforming salary data
- Creating new features (e.g., 'same_state', 'age', 'python_yn', 'R_yn', 'spark', 'aws', 'excel')
- Removing unnecessary columns

## Visualization

Insightful visualizations are created using Seaborn and Matplotlib:
- Histograms for 'age', 'Rating', and 'desc_len'
- Bar charts for job states, Python usage, R usage, Spark usage, AWS usage, and Excel usage
- Heatmap for correlation analysis
- Pie chart for the distribution of 'Type of ownership'
- Count plots for 'Size' and 'same_state'
- Regression plots for 'Rating' vs 'min_salary', 'max_salary', and 'avg_salary'

## Usage

1. Clone the repository
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the data cleaning script: `python data_cleaning_script.py`
4. Run the visualization script: `python visualization_script.py`

## Dependencies

- pandas
- matplotlib
- seaborn
