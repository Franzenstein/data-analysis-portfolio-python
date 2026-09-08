# Exploratory Data Analysis (EDA) on the Palmer Penguins Dataset

## Analyzing species differences in body measurements

### Question
Do the three penguin species (Adélie, Chinstrap, Gentoo) differ measurably in
body characteristics? And which feature separates them best?

### Dataset
[penguins.csv](https://gist.github.com/slopp/ce3b90b9168f2f921784de84fa445651#file-penguins-csv)
– measurements of ~340 penguins from three Antarctic islands
(bill length/depth, flipper length, body mass, sex).

### Approach
1. Check data quality (missing values, duplicates, data types)
2. Univariate analysis: distributions of each measurement
3. Species comparison: boxplots & scatter plots
4. Correlation analysis
5. Summary of key findings

### Results
1. 344 → 342 rows after dropping 2 incomplete rows
