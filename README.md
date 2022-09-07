# School_District_Analysis

## Project Overview
A school district employee has tasked me to remove data from their test scores that was dishonest and then recalculate and analyze the new results for changes.

1. Remove dishonest test scores from data
2. Recalculate reading and math scores for Thomas High School
3. Analyze the new results by school type, school size, grade level, and spending per student
4. Determine the top 5 and bottom 5 performing schools

## Challenge Overview

### Overview of School District Analysis
The purpose of this analysis is to determine whether and how the academically dishonest data from Thomas High School affected the math and reading scores for the school district.

## Resources
-Data Source:students_complete.csv, schools_complete.csv
-Software: Python 3.7.13, Jupyter Notebook 6.4.12, Anaconda 2.2.0

## Results
The analysis of the changes to the test scores shows that:
- At the district level:
    - The average math score decreased from 79.0 to 78.9
    - The average reading score did not change
    - The percent of students passing math lowered from 75.0% to 74.8%
    - The percent of students passing reading lowered from 86.0% to 85.7%
    - The percent of students passing both math and reading lowered from 65.0% to 64.9%
    
   Old data:
   
   ![Old School Data](https://user-images.githubusercontent.com/109701875/188981519-ea373654-fae0-43ae-b391-93946678c6ae.PNG)
  

   New Data:
   
   ![New District Data](https://user-images.githubusercontent.com/109701875/188981670-8c6f8e7f-2fcf-4a7d-a030-50baa490982e.PNG)
    
- Thomas High School:
    - Had its average math score decrease from 83.41 to 83.35
    - Had its average reading score increase from 83.84 to 83.89 
    - Had its math passing rate lower from 93.3% to 93.2%
    - Had its reading passing rate lower from 97.3% to 97.1%
    - Had its overall passing rate lower from 90.9% to 90.6%
    
- Compared to other schools, Thomas High School:
    - Remained the second best performing school
    
    Old data:
    
    ![Old Top 5](https://user-images.githubusercontent.com/109701875/188982646-9cb3657e-b39f-4532-9a45-e6089a268c10.PNG)

    New Data:
    
    ![New Top 5](https://user-images.githubusercontent.com/109701875/188982682-d37bfce3-fde2-44e6-a31e-f2b10c751ffc.PNG)

- Looking at scores by grade:
    - 9th Grade math scores went from an average of 80.35 to 80.12
    - 9th Grade reading scores went from an average of 82.51 to 82.42
    
Old Math Score Stats:

![Old math scores](https://user-images.githubusercontent.com/109701875/188985155-6f014313-0fe1-48ed-a95f-f959b13830bf.PNG)

New Math Score Stats:

![New math scores](https://user-images.githubusercontent.com/109701875/188985226-4f8c096d-b414-4787-8993-762645d3bc82.PNG)

Old Reading Score Stats:

![Old reading scores](https://user-images.githubusercontent.com/109701875/188985730-5ce4022a-e6e0-4203-9f05-b8520c50a30f.PNG)

New Reading Score Stats:

![New reading scores](https://user-images.githubusercontent.com/109701875/188985718-e95363fd-f360-4e8b-bb71-f0b77850feea.PNG)

- By School Spending:
    - Did not change at the level of precision used
    
Old Data:

![Old Spending](https://user-images.githubusercontent.com/109701875/188986601-1cee3610-0a7b-4a33-b434-7aebfb9fac64.PNG)

New Data:

![New Spending](https://user-images.githubusercontent.com/109701875/188986607-6a28f539-f82b-4ebd-89c6-27652e378ba4.PNG)


- By School Size:
  - Did not change at the level of precision used
Old Data:

![Old Size](https://user-images.githubusercontent.com/109701875/188987695-2eaa3094-82a4-4943-b2cc-44c5f822d3df.PNG)

New Data:

![New Size](https://user-images.githubusercontent.com/109701875/188987297-6d51d73b-098e-49c9-9a3d-9bff8b428a9b.PNG)


- By School Type: 
  - Did not change at the level of precision used
  
Old Data: 

![Old Type](https://user-images.githubusercontent.com/109701875/188987935-d8a1a9b1-5934-40c1-b778-02c16e741146.PNG)

New Data:

![New Type](https://user-images.githubusercontent.com/109701875/188987978-bef6e654-3a9c-4caa-840f-84a3dc816983.PNG)


## Summary

There are several major changes in the district test scores after this analysis. First, Thomas High School's overall passing dropped from 90.9% to 90.6%. Second, in the district, 9th Grade math scores went from an average of 80.35 to 80.12 and 9th Grade reading scores went from an average of 82.51 to 82.42. Third, the percent of students passing both math and reading in the district lowered from 65.0% to 64.9%. Finally, the percent of students passing math in the district lowered from 75.0% to 74.8% and the percent of students passing reading in the district lowered from 86.0% to 85.7%.
