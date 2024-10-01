# Global-Trends-Analysis
### Problem Statement:
In a world shaped by complex population, health, and economic changes, understanding these trends is crucial for effective policy-making. GlobalTrends, a leading analytics firm, aims to unravel these patterns, using the Gapminder dataset to analyze global trends over time. The project uses Python EDA libraries such as NumPy, Pandas, Matplotlib, Pyplot, and Seaborn to uncover relationships between demographic shifts, economic growth, and health progress.

### Key Features:
- **Data Cleaning and Manipulation:** Leveraging **Pandas** for data manipulation and analysis and **NumPy** for calculations.
- **Data Visualization:** Using **Seaborn and Matplotlib** to generate insightful visualizations of global trends.
- **Exploratory Data Analysis:** Exploring the interplay between life expectancy, GDP, and population changes over time.

### Tool and Libraries Used:
-  Python
-  NumPy
-  Pandas
-  Matplotlib
-  Seaborn
-  RegEx

### Key Insights:
The analysis uncovers crucial patterns between economic and health metrics, helping to inform policy decisions by visualizing how changes in population and wealth have impacted health outcomes.

### Files:
- `data/gapminder_full.csv`: Contains the original Gapminder dataset used for population, health, and economic trends analysis.
- `notebooks\global_trends_analysis.ipynb`: Jupyter Notebook with the complete Exploratory Data Analysis (EDA) and visualizations of the Gapminder data.
- `reports\global_trends_analysis.docx`: Document with detailed descriptions of visualizations and key findings from the EDA.

## How to use

### Prerequisites
- Jupyter Notebook (Python with the all required libraries installed).

**1. Clone this repository:**
- Open a terminal and run the following command to clone the repository.
  ```bash
  git clone https://github.com/purna-chandrasekhar/Global-Trends-Analysis.git
  ```
**2. Open the Jupyter Notebook:**
- Navigate to the `notebooks/` folder and open `global_trends_analysis.ipynb` using Jupyter Notebook or Jupyter Lab:
  ```bash
  cd Global-Trends-Analysis/notebooks/
  jupyter notebook global_trends_analysis.ipynb
  ```
**3. Load the Dataset:**
- The dataset `gapminder_full.csv` is located in the `data/` folder. The notebook should automatically load it, but if not, update the file path in the notebook to:
  ```python
  df = pd.read_csv('../data/gapminder_full.csv')
  ```
**4. View Visualizations and Analysis:**
- Open the `reports/global_trends_analysis.docx` file to review the detailed descriptions of the visualizations and the analysis conducted in the notebook.
