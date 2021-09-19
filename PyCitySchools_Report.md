# PyCity Schools Analysis Report
Prepared by Robert Gallagher

## Overview

The purpose of this report is to analyize the impact of removing altered data for the Thomas High School ninth grade students from the PyCity Schools student reading and writing scores to the following views.
- District level summary
- School summary
- Top 5 schools
- Bottom 5 schools
- Average reading and math scores by grade level
- Scores by per student spending
- Scores by school size
- Scores by school type

The work for this is done by the following script:
[PyCitySchools_Challenge.ipynb](PyCitySchools_Challenge.ipynb)

## Results

- District summary dataframes
    - Original
    ![](Resources/Original_District_Summary.PNG)
    - Corrected
    ![](Resources/Updated_District_Summary.PNG)

- School summary dataframes: The only updated line in this dataframe was the Thomas High School row so that is all that is shown below.
    - Original

    ![](Resources/Original_School_Summary_Thomas_High_School.png)
    - Corrected

    ![](Resources/Updated_School_Summary_Thomas_High_School.png)

- Top 5 schools
    - Original

    ![](Resources/Original_Top_Five_Schools.png)

    - Corrected

    ![](Resources/Updated_Top_Five_Schools.png)

- Bottom 5 schools
    - Original

    ![](Resources/Original_Bottom_Five_Schools.png)

    - Corrected

    ![](Resources/Updated_Bottom_Five_Schools.png)

- Average reading scores by grade
    - Original

    ![](Resources/Original_average_reading_scores_by_grade.png)
    - Corrected

    ![](Resources/Updated_average_reading_scores_by_grade.png)

- Average math scores by grade
    - Original

    ![](Resources/Original_average_math_scores_by_grade.png)
    - Corrected

    ![](Resources/Updated_average_math_scores_by_grade.png)

- Scores by per student spending
    - Original

    ![](Resources/Original_by_spending.png)
    - Corrected

    ![](Resources/Updated_by_spending.png)

- Scores by school size
    - Original

    ![](Resources/Original_by_size.png)
    - Corrected

    ![](Resources/Updated_by_size.png)

- Scores by school type
    - Original

    ![](Resources/Original_by_type.png)
    - Corrected
    
    ![](Resources/Updated_by_type.png)
    
## Summary

- School district impact:  As you can see from above replacing the Thomas High School 9th grade scores with null values only slightly decreased our metrics.  See a summary of the movements in the list below.  Overall at the district level this did not significantly change results.
    - Average Math Score decrease by .1 point
    - % Passing Math decreased by .2 percent
    - % Passing Reading decreased by .1%
    - % Overall Passing decreased by .3%
    
- School summary impact:  The only row impacted in this dataframe was the row for Thomas High School.  See the list below for a summary of the changes.
    - Average Math Score decreased by .06 points
    - Average Reading Score increased by .05 points
    - % Passing Math decreased by 26.4%
    - % Passing Reading deceased by 27.6%
    - % Overall Passing decreased by 25.9%
    
- Top 5 schools did not change order

- Bottom 5 schools did not change order