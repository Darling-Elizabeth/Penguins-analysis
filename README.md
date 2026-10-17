# Penguins Analysis

Data cleaning, visualization, and a Random Forest model to predict penguin species from body measurements.

## Dataset
- Palmer Penguins dataset, loaded from the `seaborn-data` repository on GitHub
- Species (Adelie, Chinstrap, Gentoo), island, bill length and depth, flipper length, body mass, and sex

## What I did
1. Loaded and inspected the data (shape, columns, data types, missing values)
2. Cleaned the data by dropping the rows with missing values
3. Explored it with `groupby` and `value_counts`
4. Visualized it with histograms, scatter plots, boxplots, a pairplot, and a correlation heatmap
5. Built a Random Forest classifier to predict species from the four body measurements

## Key findings
- The model reached 100% accuracy on the test set (1.0)
- [Add: your cross-validation average, if you ran it]
- [Add: which species is heaviest, or one finding from your charts]

## Tools
Python, pandas, matplotlib, seaborn, scikit-learn

## Files
- `your_notebook_name.ipynb`: the full notebook with code, charts, and explanations
