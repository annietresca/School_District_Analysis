# School_District_Analysis

## Project Overview
The purpose of this report is to provide a new school district analysis that takes into account reports of academic dishonesty. This report first replaces all the reading and math scores from the ninth grade at Thomas High School with NaNs in order to ensure inaccurate scores are not included in the analysis. It then repeats the school district analysis and updates the following metrics in the PyCitySchools_Challenge file:
- The district summary impacts
- The school summary impacts
- The reading and math scores at Thomas High School relative to other schools
- As well as:
1. Math and reading scores by grade
2. Scores by school spending
3. Scores by school size
4. Scores by school type 

## Resources
Data Source: schools_complete.csv , students_complete.csv

Software: Python 3.6.1, Pandas

## Results:
- District Summary:

![District Summary](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/District%20Analysis.png)


Compared to the original analysis shown here:
![Original Analysis](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Original%20PyCitySchools%20District.png)



- Thomas High School's performance relative to other schools in this analysis:
1. Top five schools in the district
![Top five](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Top%20five%20schools.png)

2. Bottom five schools in the district
![2. Bottom five schools in the district](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Bottom%20five%20schools.png)



As compared to in the original analysis shown here:
1. Top five schools in the district
![1. Top five schools in the district](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Top%20five%20schools%20from%20PyCitySchools%20Original.png)

2. Bottom five schools in the district
![2. Bottom five schools in the district](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Bottom%20five%20schools%20in%20Original%20PyCitySchools.png)






- Updated average math scores by grade:

![math scores by grade:](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Math%20scores%20by%20grade.png)


- Updated average reading scores by grade:

![reading by grade:](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Reading%20scores%20by%20grade.png)


- Scores by schools spending:

![spending](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Scores%20by%20school%20spending.png)


- Scores by school size:

![size](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Scores%20by%20school%20size.png)


- Scores by school type:

![type](https://github.com/annietresca/School_District_Analysis/blob/main/Resources/Scores%20by%20school%20type.png)


## Summary
- As a result of omitting the ninth grade reading and math scores from Thomas High School, the following changes occurred:
1. The average Math score at Thomas High School went from 83.42 to 83.35
2. The average Reading score at Thomas High School increased from 83.85 to 83.90
3. We can conclusively say omitting this data has had no impacts on overall standings in the district. 
4. Additionally, omitting this data has had no impacts on average school spend per student.
