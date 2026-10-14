# Diamond Pricing Analysis

## 1. Problem / Research Question
What factors drive diamond prices? This project explores how carat weight, cut quality, and color grade relate to price, and reveals some counterintuitive patterns in the diamond market.

## 2. Dataset Source & Usage Permission
The dataset is the built-in "diamonds" dataset from the seaborn library. It contains prices and attributes of 53,940 round-cut diamonds sold in the US market. It is freely available for educational and analytical use.

## 3. Methods & Tools Used
- Python with pandas for data loading and descriptive statistics
- matplotlib and seaborn for data visualization
- Exploratory Data Analysis (EDA): scatter plots, box plots, and bar charts to examine relationships between diamond attributes and price

## 4. Key Findings & Limitation
Key findings: (1) Carat weight is the strongest predictor of price — larger diamonds cost significantly more. (2) Counterintuitively, Ideal-cut diamonds have a LOWER median price than Fair-cut diamonds. This is because buyers typically choose premium cuts for smaller stones, while large rare diamonds may have lower cut grades. (3) Similarly, better color grades (D, E) do not correlate with higher median prices once carat is not controlled for.
Limitation: This analysis does not control for carat size when comparing cut and color groups, so the apparent "better cut = cheaper" effect is confounded by the fact that smaller diamonds are more likely to have ideal cuts.

## 5. How to Run the Analysis
1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Open the notebook and run all cells in order (the data loads directly from seaborn's built-in dataset)
