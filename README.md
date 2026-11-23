# Diwali Sales Analysis

A small data analysis project where I explored Diwali sales data to understand who is buying, where the orders are coming from, and which product categories are getting more attention.

## About the Project

For this project, I used Python to explore a Diwali sales dataset. I started by cleaning the data and then used charts to look at buying patterns across different customer groups.

The main aim was to turn the raw sales data into simple observations that are easier to understand.

## Files Included

| File | What it contains |
|---|---|
| `Diwali Sales Data.csv` | The sales dataset used for the analysis. |
| `Diwali_Sales_Analysis(1).ipynb` | The Jupyter Notebook with the cleaning steps, analysis, charts, and observations. |

## Tools Used

- Python
- Jupyter Notebook
- Pandas – for working with and analysing the data
- NumPy – for numerical operations
- Matplotlib and Seaborn – for creating charts and visualising patterns

## What I Did

I first loaded the CSV file and checked its structure. The dataset has 11,251 rows and 15 columns. I then removed the two empty columns (`Status` and `unnamed1`), handled missing values, and converted the `Amount` column to an integer.

After cleaning the data, I explored the sales information in a few different ways:

- Compared purchases and sales amount by gender.
- Looked at customer age groups.
- Compared orders and sales across states.
- Explored buying patterns by marital status and occupation.
- Checked which product categories had higher sales.
- Found the products with the highest number of orders.

I used bar charts and count plots to make these comparisons easier to follow.

## A Few Observations

Here are some of the patterns I noticed in the notebook:

- Female customers account for a larger share of purchases and sales amount in this dataset.
- The 26–35 age group stands out, particularly among female buyers.
- Uttar Pradesh, Maharashtra, and Karnataka are among the leading states in the state-wise comparisons.
- The marital-status comparison shows higher sales amount for married women.
- IT, Healthcare, and Aviation appear among the prominent occupations in the analysis.
- Food, Clothing, and Electronics are among the leading product categories by sales amount.

These observations describe this dataset only. They should not be taken as fixed rules about customers in general.

## Run It on Your Machine

1. Clone this repository or download the files.
2. Install Python and Jupyter Notebook if you do not already have them.
3. Install the libraries used in the notebook:

   ```bash
   pip install pandas numpy matplotlib seaborn notebook
   ```

4. Keep the CSV file and notebook in the same folder.
5. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `Diwali_Sales_Analysis(1).ipynb` and run the cells from top to bottom.

## What I Learned

Working on this project gave me practice with data cleaning, grouping and summarising data, exploratory data analysis, and presenting findings through visualisations. It also helped me understand how a dataset can be explored from different angles to find useful patterns.

---

**Created by Aditya Mehta**
