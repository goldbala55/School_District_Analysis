# School_District_Analysis

## Project Overview
A complete analysis of the City School district standardized testing scores results was completed and sent to the school board.  After reviewing the detailed results, the school board suspects the ninth-grade scores at Thomas High School have been altered. While the full extent of the issue is not known, the board has requested a follow up analysis that effectively removes the questionable grades. 

## Resources
  * Two Input csv files were provided by the school board: 
    * schools_complete.csv - details on each school including type, size, and budget.
    * students_compete.csv - details on each student including name, gender, school, and test scores.
  * Software: Python 3.7.9, Jupyter Notebook 6.1.4, pandas 1.1.3, numpy 1.17.0, Git Bash 4.4.23

## Results
After recreating the analysis below are the observations on changes observed in each report:

    * The district summary
      * There were subtle but clear drops in average math scores, and the percentage of students passing the standard exams. 
      * This is not unexpected given the impacted data has 461 students out of a population of 39,170 students (1.1%) 
    * The school summary
      * Math scores were down, reading was flat, and none of the variances were substantial.  
    * The top 5 and bottom 5 performing schools, based on the overall passing rate.
      * There were no variances in the top or bottom 5 schools
    * The average math score for each grade level from each school
      * The average math scores for Thomas High 9th grade were not reported; all others remained unchanged.
    * The average reading score for each grade level from each school
      * The average reading scores for Thomas High 9th grade were not reported; all others remained unchanged.
    * The scores by school spending per student, by school size, and by school type
      * There were no variances in scores based on spending, size, or school type.

## Summary
In reviewing the detailed results, I have the obvious conclusions:
1. Removing the 9th grade data has minimal impact on the school district performance in any of the standardized testing.
2. This is likely the result of:
   1. My analysis is flawed, and I have not accounted for the differences correctly (likely)
   2. The alterations to the grades was subtle and not widespread so little variance is seen.
   3. The allegations of grade alterations were false, and the student grades fell within the distributions of the Thomas High School and the district.
