# School Data Analysis

## Overview
---

The purpose of this analysis is to provide crucial data about the following school districts and there students given by these documents: (insert). Due to the dishonesty of the 9th grade in Thomas high school I will need to eliminate all of their test scores from the dataframe and update all of our data analysis of the schools. 

## Analysis
---

* The district summary is affected from eliminating the 9th grade test scores to now have "NaN" wherever 9th grade scores from Thomas High School appear. The data has been deleted from the dataframe and the district summary's math score went up. The percent passing both reading and math went down along with the overall passing percentage. This could be due to the ninth grade students cheating which artificially inflated the passing percentages. The revised district summary looks like this: (insert district dataframe) compared to the old one:(insert district dataframe)
*  The school summary was barely affected with Thomas High School now having relatively simliar scores. The cheating students' seem to have not affected the scores of Thomas high school overall. This was found by recalculating the scores of the tenth to twelfth graders in this code: (insert code) Revised: () Old:()
*  This therefore depicts that Thomas High schools performance compared to other schools is still top tier because even with eliminating the cheaitng students' data Thomas high school still managed to have the same high results as it had prior.
*  Replacing the ninth grade scores affected the math and reading scores by grade database by now having "NaN" appear in the ninth grade column for Thomas high schools. This is due to the data being eliminated. (insert)
*  Replacing the ninth grade scores have a slight effect on the school spending database. Thomas high school is in the 630 to 644 spending range so it only affects this row. The math score and percentage both decrease while the reading score and percentage increase. Combining this informaiton this leads to the overall percentage to decrease for this row. In this row The The data is still the same due to their simliar scores, and the fact that the number of students counted in Thomas high school has not decreased, only the data from the 9th graders' scores aren't being considered, but they are still part of the total student count. 
*  The school type dataframe does not change as well since deleting the 9th graders does not change the type of school Thomas high school is

## Summary
---
Even though deleting the ninth grade data from Thomas high school had little affect on their overall performance there were still four changes that occured because of this. In the district summary the average math score went up by .1. The percent passing math decreased as well as the percent passing reading and overall passing percentage. In the school summary, sort by grade, and sort by school spending dataframe the average math score decreased as well as it's passing percentage. The average reading score increased as well as it's passing percentage and the overall passing percent decreased in all of these dataframes. 
