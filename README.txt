# Health Data Science – Drug Mismatch Analysis

This project analyzes a synthetic dataset comparing disease prevalence with the number of approved drugs for each disease. It aims to identify mismatches in pharmaceutical resource allocation.

## Dataset

A synthetic CSV file with ~50 diseases, including:
- `disease`: Name of the disease
- `prevalence_rate`: Estimated prevalence in the population
- `number_of_drugs`: Number of approved drugs for the disease

## Workflow

- Loaded and explored the dataset
- Visualised disease prevalence vs. drug count in a scatter plot
- Calculated correlation between prevalence and drug count
- Flagged diseases with high prevalence but below-median drug counts
- Identified under-served disease areas

## Key Visualizations

- Scatter plot: Disease prevalence vs. number of approved drugs (with disease labels)

## Example Insights

Identified diseases like Alzheimer's and Parkinson's as moderately prevalent but with relatively low drug availability.

## Tools Used

- Python
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

## Next Steps

- Expand dataset with real-world data
- Include additional variables (e.g., number of clinical trials, R&D pipeline)
- Explore geographic variations in drug availability
