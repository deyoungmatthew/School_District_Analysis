# School_District_Analysis
## **Overview**

The purpose of the project was to update the cleaned student data by changing the reading and math scores for Thomas High School 9th graders to NaN as there appears to have been an alteration of grades due to academic dishonesty.  The school district analysis summary had to be updated, this included the average math and reading scores as well as performance metrics in relation to budgets.  The loc() method was used to make the changes in the student data.

## **Results**

* **District Summary**
There was a slight decrease in both Average Math and Average Scores for the District.  Average math scores dropped from 79.0 to 78.9; however, the average reading score remained the same at 81.9. The percentage passing for Math dropped from 75% to 74.8% and the passing percentage for Reading also slightly dropped from 85.8% to 85.7%.  Overall passing percentage for both dropped slightly more from 65.2% to 64.9%.

* **School Summary**
The only numbers affected here were Thomas High School's scores and passing percentages.  Here are the results:

### Thomas High School before replacing 9th grade reading and math scores with Nan:
![Thomas Summary Before](https://user-images.githubusercontent.com/78942457/111912802-aaeb8080-8a41-11eb-86e7-66e802db6917.PNG)

### Thomas High School after replacing 9th grade reading and math scores with Nan:
![Thomas Summary After](https://user-images.githubusercontent.com/78942457/111912863-e7b77780-8a41-11eb-8bd1-f0282a8532e8.PNG)

### The variances are as follows: * Average Math Score: Decrease of .067
                              * Average Reading Score: Increase of .047
                              * % Passing Math: Decrease of .086
                              * % Passing Reading: Decrease of .290
                              * % Passing Overall: Decrease of .318

* **Thomas High School's performance relative to other schools in district**
Thomas High School's standing in relative performance to other schools in the district did not change.  Using the % of Overall Passing, Thomas High School was second highest in performance before and after the 9th grade score replacement.

### **Effects of replacement**

* **Math and reading scores by grade**
The only scores that changed were the 9th grade scores for Tomas High School.  Before the Math and Reading scores for the 9th grade at Thomas High School were 83.6 and 83.7 respectively and now they read NaN.

* **Scores by school spending**
Thomas High School fell in the $630 - $644 per student bin, but no average scores or percentages changes are a result of the removal of 9th grade scores.

* **Scores by school size**
Thomas High School is in the medium sized bin, but no average scores or percentages changes are a result of the removal of 9th grade scores.

* **Scores by school type**
Thomas High School is in the charter bin, but no average scores or percentages changes are a result of the removal of 9th grade scores.

## **Summary**
The four major changes in the District summary were the drops in Average math score, % Passing Math, % Pass Reading, and a larger drop in % Overall Passing.
