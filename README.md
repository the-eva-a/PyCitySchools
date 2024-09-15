#Pandas Challenge
## Overview

This Python project analyzes data from the PyCity School District to understand trends in academic performance and budget distribution across 15 schools. The analysis includes metrics such as average math and reading scores, passing rates, and the relationship between per-student spending and performance.

The project uses pandas to manipulate and analyze the data, generating key insights and summary statistics.
## Features
- **District Summary**: An overview of the number of schools, total students, total budget, and average scores.
- **School Summary**: Detailed analysis of each school, including total students, budget, scores, and pass rates.
- **Top and Bottom Performing Schools**: Identification of the highest- and lowest-performing schools based on overall pass rates.
- **Analysis by Spending, Size, and Type**: Comparison of academic performance based on school spending ranges, size, and type (charter vs. district).

## Data

The analysis uses two CSV files:
- `schools_complete.csv`: Includes school data such as `School ID`, `school_name`, `type` (charter/district), 
`size` (student population), and `budget`.
- `students_complete.csv`: Contains student data including `Student ID`, `student_name`, 
`gender`, `grade`, `school_name`, r`eading_score`, and `math_score`.

These datasets are merged and analyzed to generate insights on student performance and budget allocation.

## Installation

To run this project locally, follow these steps:
1. **Clone the repository**
``` bash
git clone https://github.com/the-eva-a/PyCitySchools.git
```

2. Install required libraries: The project uses pandas, numpy, and matplotlib. Install them using pip:
``` bash
pip install pandas numpy matplotlib
```

3. Run the analysis: The main script that performs the analysis is school_analysis.py. Run it using:

``` bash
    python school_analysis.py
```
## Usage

Once you run the script, the following outputs will be generated:
- **District Summary**: A table showing the total number of schools, students, budget, and average scores.
- **School Summary**: A breakdown of scores and pass rates for each school.


## Results

-  Charter schools tend to outperform district schools significantly in both math and reading scores.
- Schools with lower per-student spending show higher overall passing rates.
-  Medium-sized schools perform better compared to larger schools.


## Acknowledgements
This project is part of the curriculum in the edX Data Analytics Bootcamp. Special thanks to my instructors and peers for their support and guidance.