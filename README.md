# Association Rules: Apriori Algorithm
Our main objective for this university project was to apply the Apriori algorithm to find association rules between the characteristics of the adult population in the USA. Using the `arules` package in R, we identified rules that link variables such as age, marital status, occupation, and income. These rules were then visualized to understand potential patterns and correlations.

The structure of the project is as follows:

1. **load_data.R**: Code to load and preprocess the "Adult" dataset from the UCI repository.
2. **apriori_algorithm.R**: Code to apply the Apriori algorithm using the `arules` package to generate association rules.
3. **filter_rules.R**: Code to filter rules based on support, confidence, and lift.
4. **visualize_rules.R**: Code to visualize the association rules with interactive charts.
5. **eclat_function.R**: Implementation of the `eclat()` function to find frequent itemsets in the dataset.
6. **answers.R**: Code containing detailed answers to the project questions based on the association rules.
7. **README.md**: Detailed explanation of the project and setup instructions.

## Data Used
This project uses the "Adult" dataset from the [UCI Repository](https://archive.ics.uci.edu/ml/datasets/adult), which contains information about the adult population in the USA, including variables such as age, occupation, marital status, and income.

### Key Variables:
- **`age`**: Age of the individual
- **`workclass`**: Employment type
- **`education`**: Educational level
- **`marital-status`**: Marital status
- **`occupation`**: Occupation
- **`sex`**: Gender
- **`hours-per-week`**: Hours worked per week
- **`income`**: Income (target variable)

## Packages Used
To run this project, ensure you have the following packages installed:

- **R** - version 4.3.2
- **arules** - version 1.7.7
- **arulesViz** - version 1.5.2
