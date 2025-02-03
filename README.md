
# Igno Project

This repository contains the **Igno Project**, which includes various datasets, analysis, and visualizations aimed at understanding customer behaviors, product profitability, and customer spending. The project includes the use of tools like **Python**, **pandas**, **seaborn**, and **matplotlib** for data analysis and visualization.

## Project Overview

This project analyzes customer transaction data and purchase behavior to:
1. Calculate the most profitable products.
2. Identify loyal customers based on their spending.
3. Understand customer characteristics such as **Lifestage** and **Premium Customer** categories.

## Files and Directories

- `transaction_data.csv`: Transaction details such as product quantity, sales, and customer IDs.
- `purchase_behaviour.csv`: Customer behavior details like lifestage and premium customer status.
- `analysis.py`: Python code for analyzing and visualizing the data.
- `visualizations`: Directory containing plots and graphs related to the analysis.

## Requirements

To run this project locally, you will need to install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

## Instructions to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/prathameshfuke/Igno.git
```

2. Navigate to the project directory:

```bash
cd Igno
```

3. Run the analysis script:

```bash
python analysis.py
```

This will load the data, perform the analysis, and display various visualizations for the most profitable products and loyal customers.

## Output

1. **Top 3 Most Profitable Products**: Displays a bar plot of the top 3 products based on revenue.
2. **Characteristics of Loyal Customers**: Displays the distribution of loyal customers based on their **Lifestage** and **Premium Customer** categories.

## Acknowledgments

- This project was developed as part of a data analysis and machine learning exercise.
- Thanks to the libraries used: pandas, numpy, seaborn, and matplotlib for making data analysis and visualization easy.
