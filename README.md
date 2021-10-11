* School District Analysis by Ben Altshuler

** Overview

The purpose of this pandas scripting is to clean, analyze, and display formatted data frames for a School District looking at variables like spending and size vs outcomes for students. Grade data for 9th graders at one high school was either faulty or tampered with, so we scrubbed these values from the data set without removing the rows. Our analysis depends on Pandas and Nympy to neatly parse through this large data set and glean insights for the district. 

![Summary](Resources/Summary.png?raw=true "School District Summary")

** Results

- District Summary Effects of Removing 9th Grade THS Scores
  - Average math scores dropped
  - Overall passing rate dropped

- THS Summary Effects
  - Percentage of students passing math dropped 
  - Percentage of students passing reading dropped
  - Overall percentage of students passing dropped 
  - School's Ranking in District dropped

- THS Relative Performance
  - Because the scores had to be dropped, THS performance suffers compared to the other schools in the district
  - School rankings in THS spending and size range are negatively skewed 

* Summary

By removing the THS 9th Graders' scores, we've seen several changes in our findings. 
  - THS has no data for 9th grade math and reading
  - Scores by school spending sees a drop in Percentage passing both Math and Reading 
  - Scores by school size sees a drop for those in the same bin as THS
  - Overall Passing Percentage drops
