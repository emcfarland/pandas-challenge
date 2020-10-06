# pandas-challenge

This repository takes data from a school district--both individual schools' budgets, size, and type, and individual students' test scores and grade level--and uses pandas to compare schools' math and reading performance.

After reading and merging the two CSVs by school name, this code adds three helper columns with Boolean values based on whether each student passed math, reading, and both. A summary table combines all data for the district--showing district size, budget, and testing outcomes. Then the same data are grouped by school, and sorted by perentage of students passing both math and reading to determine the top and bottom five schools. While grouped by school, series are created by grade level to display student performance across grade levels at each school.

The last three analyses group students based on school type. Bins are created for per-student spending ranges and school size ranges, and testing averages of students in the schools within each of these ranges are taken. Finally, schools are grouped by their "district" and "charter" designations and testing averages are taken for those groups.
