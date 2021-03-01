# School_District_Analysis
## Project Overview
Maria who works for the PyCity School district was notified by the school board that the scores for Thomas High School ninth graders appears to be skewed and altered in the analysis that was performed earlier. Maria requested that the math and reading scores for Thomas High School 9th graders (461) are replaced with NaNs (Not a Number) and keep the rest of the data intact. Once the math and reading scores are placed a new school district analysis was performed. The analysis will address the following questions:
1.	How is the district summary affected?
2.	How is the school summary affected?
3.	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
4.	How does replacing the ninth-grade scores affect the following:
     -	Math and reading scores by grade
     -	Scores by school spending
     -	Scores by school size
     -	Scores by school type. 

## Resources
-	Data Sources: schools_complete.csv, students_complete.csv
-	Software: Python 3.7, Jupyter Notebook 6.1.4

## Results
1.	How is the district summary affected?
     -	The Average Math Score went down from 79.0 to 78.9
     -	The % Passing Math went down from 75 to 74.8
     -	The % Passing Reading decreased from 86 to 85.7
     -	The % Overall Passing decreased from 65 to 64.9
     -	Below are the District Summaries:

Results from PyCitySchools:
![District_Analysis from original analysis](https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/District_Analysis%20from%20original%20analysis.png)

Results from PyCitySchools_challenge:
![District_Analysis from updated analysis](https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/District_Analysis%20from%20updated%20analysis.png)


2.	How is the school summary affected?
     -	The Average Math Score went down from 83.42 to 83.35
     -	The Average Reading Score went up from 83.85 to 83.90
     -	The % Passing Math went down from 93.27 to 93.19
     -	The % Passing Reading decreased from 97.31 to 97.02
     -	The % Overall Passing decreased from 90.95 to 90.63
     -	Below are the summaries:

Results from PyCitySchools:
![School Summary from original analysis]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/School%20Summary%20from%20original%20analysis.png)

Results from PyCitySchools_challenge:
![School Summary from updated analysis]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/School%20Summary%20from%20updated%20analysis.png)

3.	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the ninth graders’ math and reading scores affect Thomas High School’s performance not very much as Thomas High School is still #2 on the Top 5 schools list. There are a few changes but not enough to knock them off of the Top 5.
-	The Average Math Score went down from 83.42 to 83.35
-	The Average Reading Score went up from 83.85 to 83.90
-	The % Passing Math went down from 93.27 to 93.19
-	The % Passing Reading decreased from 97.31 to 97.02
-	The % Overall Passing decreased from 90.95 to 90.63
-	Below are the summaries:

Results from PyCitySchools:
![Top 5 schools Original]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/Top%205%20schools%20Original.png)

Results from PyCitySchools_challenge:
![Top 5 schools updated]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/Top%205%20schools%20updated.png)

4.	How does replacing the ninth-grade scores affect the following:
-	Math and reading scores by grade: For the 9th grade for Thomas High School on the original analysis for math scores the score was (83.6), where on the updated analysis there is a (nan). For the 9th grade for Thomas High School on the original analysis for reading scores 
the score was (83.7), where on the updated analysis there is a (nan).
-	Scores by school spending: Removing the 9th grade students only affected the % Overall Passing. According to the summary below, the % Overall Passing for <$584 went down from 97 to 90, for the $585-629 the Overall Passing decreased from 93 to 81, the $630-644 Overall Passing decreased by 18 points, while for the $645-675 category the decrease was from 1 to 54.
     
Results from PyCitySchools:
![School Spend Original]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/School%20Spend%20Original.png)

Results from PyCitySchools_challenge:
![School Spend Updated]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/School%20Spend%20Updated.png)

-	Scores by school size: After removing the 9th grade scores from the scores by school size there appeared to be no affect to the data.

Results from PyCitySchools:
![School Size Original]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/School%20Size%20Original.png)

Results from PyCitySchools_challenge:
![School Size Updated]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/School%20Size%20Updated.png)
-	Scores by school type:  After removing the 9th grade scores from the scores by school size there appeared to be no affect to the data.

Results from PyCitySchools:
![School Type Original]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/School%20Type%20Original.png)

Results from PyCitySchools_challenge:
![School Type Updated]( https://github.com/fletchrk/School_District_Analysis/blob/main/analysis/School%20Type%20Updated.png)


