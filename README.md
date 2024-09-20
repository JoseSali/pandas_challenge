# PyCitySchools Analysis

## Project Overview

This project analyzes data from multiple schools in a district to gather insights on student performance and school budgets. The analysis is done using Python and Pandas, focusing on metrics like the number of schools, total students, district budget, and average test scores. By merging school and student data, this project helps identify trends and key statistics to better understand the district's education performance.

## Files in the Repository

- **PyCitySchools_starter.ipynb**: Jupyter notebook where the analysis is performed.
- **Resources/**:
  - `schools_complete.csv`: Contains data on school names, budgets, and other relevant information.
  - `students_complete.csv`: Contains student-level data, including their math and reading scores.

## Key Analysis Steps

1. **Load and Merge Data**:
   - Load school data and student data from CSV files into Pandas DataFrames.
   - Merge the two datasets to create a complete dataset for further analysis.

2. **Summary Metrics**:
   - **Number of Schools**: Count the unique schools in the dataset.
   - **Total Number of Students**: Sum the number of unique students while accounting for potential duplicates.
   - **District Budget**: Calculate the total budget by summing individual school budgets.
   - **Average Math and Reading Scores**: Compute the average math and reading scores across all students.

3. **School-wise and Grade-wise Breakdown**:
   - Calculate school-level performance metrics, including passing rates for math and reading.
   - Break down average scores by grade level to identify any patterns.

## Dependencies

To run this analysis, the following Python libraries are required:

- `pandas`
- `pathlib`

## How to Use

1. Clone this repository to your local machine.
2. Ensure the `Resources` folder contains the CSV files (`schools_complete.csv` and `students_complete.csv`).
3. Open the Jupyter Notebook (`PyCitySchools_starter.ipynb`) in Jupyter or JupyterLab.
4. Run the cells in sequence to load the data, perform the analysis, and view the results.

## Results

- Total number of schools and students.
- Total district budget.
- Average math and reading scores across the district.
- Performance summaries by school and grade level.

## Acknowledgments

- Data provided by UC Irvine's Data Analytics Bootcamp.
- Tools and techniques taught during the bootcamp were instrumental in completing this project.
