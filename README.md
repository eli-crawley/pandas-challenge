# School District Analysis

This project analyzes school and student data to uncover insights into student performance and spending. The analysis involves merging datasets, calculating key metrics, and presenting results in a structured and visual manner.

## Project Overview

The goal of this project is to:
1. Combine school and student datasets.
2. Compute high-level metrics for the district.
3. Analyze performance by individual schools.
4. Segment data by spending, size, and grade level.
5. Present findings in a well-organized format.

## Key Features

- **District-Level Summary**: Includes total schools, students, budget, average test scores, and passing rates.
- **School-Level Analysis**: Provides a breakdown of performance by school, with metrics such as budget, per-student spending, and test scores.
- **Performance by Spending, Size and Grade Level**: Groups data by spending ranges, school size, and grade level to identify trends.
- **Performance Metrics**:
  - Average Math and Reading Scores
  - Percentage of Students Passing Math and Reading
  - Overall Passing Rate

## Data Sources

- `schools_complete.csv`: Contains school-level data including fields: name, type, size, and budget.
- `students_complete.csv`: Contains student-level data including fields: name, grade, school, and test scores.

## Key Steps in the Analysis

1. **Data Preparation**:
   - Import libraries and load CSV files.
   - Merge datasets into a comprehensive dataframe.

2. **District Summary**:
   - Calculate total schools, students, and budget.
   - Compute average test scores and passing percentages.

3. **School Summary**:
   - Analyze metrics at the school level.
   - Include spending per student, average scores, and passing rates.

4. **Performance by Spending and Size**:
   - Group schools by spending ranges and size.
   - Compare performance metrics across categories.

5. **Grade-Level Analysis**:
   - Group data by grade and calculate average scores.

## Requirements

- Python 3.x
- `pandas`: For data manipulation and analysis.
- `pathlib`: To manage file paths.

## How to Run the Code

1. Ensure you have Python installed on your machine.
2. Install the required libraries using:
   ```bash
   pip install pandas
   ```
3. Clone or download the repository
- You can either clone this repository (if hosted on a platform like GitHub) or download the script file directly. 
4. Replace the `schools_complete.csv` and `students_complete.csv` files in a `Resources` folder with your csv's. Ensure the data is structured as shown in the Data Sources section.
5. Run the script to generate the analysis and view the results.


