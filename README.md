# School_District_Analysis
# Overview of the school district analysis: 
## Explain the purpose of this analysis.
A school board has hired a consulting firm to analyze student data for suspected academic dishonesty. Students_complete.csv shows that the reading and math scores of the ninth-grade students of Thomas High School have changed. The school board does not know the full extent of academic dishonesty, and to meet state testing standards, they have hired this company to help.

The conducted analysis compares this firm's analysis to previous analyzes of school districts to determine how academic dishonesty affects academic performance.
The school board has requested the following deliverables:
- A high-level overview of key district indicators, presented in tabular form
- Overview of key indicators of each school presented in tabular form
- Tables showing each of the following metrics:
  - Top 5 and 5 worst-performing schools by overall pass rate
  - Average math scores obtained by students at each grade level in each school
  - Average reading scores obtained by students at each grade level in each school
  - School performance on a per-student budget basis
  - School performance by school size
  - School performance by type of school

# Tools
- Jupyter Notebook
- Python v3.7.x
- Dependencies
- Python Pandas library
- Python Numpy library

# Resources
- schools_complete.csv
- students_complete.csv

# Results

## School Summary
![Screen Shot 2022-05-04 at 6 13 08 PM](https://user-images.githubusercontent.com/94031446/166834238-b6716d0e-1657-4e12-92fc-2de19277b4e5.png)

## District Summary
![Screen Shot 2022-05-04 at 6 13 19 PM](https://user-images.githubusercontent.com/94031446/166834321-2c23dbcb-5741-4a14-8b27-3ae48bc06f6c.png)


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
By replacing the grades with NaN the score was not calculated, if it were to replace with positive or negative score it would impact the average for the School and the District

# Summary:
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

The removal of grades from grade 9 students at Thomas High School affected the school district in the following ways:
  - Average math scores dropped slightly (<1%)
  - Mean reading scores are not affected
  - The percentage of students passing Mathematics has decreased slightly (-1%)
  - The percentage of students who succeeded in reading decreased slightly (-1%)
  - The overall success rate has decreased (-1%)
 
Only Thomas High School's scores were affected:
  - The percentage of students who passed Mathematics increased from 93.2% to 66.9%
  - The percentage of students who succeeded in reading increased from 97.3% to 69.7%
  - Overall pass percentage reduced from 90.9% to 65.1%

Thomas High School has influenced the school rankings as follows:
  - Thomas High School Dropped Out of the Top 5 High Schools in the District
  - Wright High School ranked among the top 5 high schools in the district
  - The last 5 high schools were not affected

The removal of grade 9 student scores from Thomas High School affected other reports:
  - Class wise math and reading scores remained the same for all other schools
  - Thomas High School had no data to report 9th-grade math and reading scores
  - Scores changed in the range of $601-$650 based on school expenses:
    - Math pass rate increased from 73% to 67%
    - Reading percentage increased from 84 percent to 77 percent
    - Overall pass percentage increased from 63 percent to 56 percent
  - Scores have changed by school size for medium-sized schools (1000-2000):
    - Mathematics pass percentage increased from 94 percent to 85 percent
    - Reading pass percentage increased from 97% to 91%
    - Overall pass percentage increased from 91% to 85%
  - Scores were affected by the type of school as follows: 
    - Math pass rate increased from 94% to 90%
    - Reading success percentage increased from 97% to 93%
    - Overall pass percentage increased from 90% to 87%



