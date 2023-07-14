# Data-Viz-Pymaceuticals-Challenge

In this challenge, I was tasked to take on the role of the newest senior data analyst for Pymaceuticals, Inc., a company that specializes in anti-cancer medications, and analyze a study of 249 mice who were identified with SCC tumors and who recieved a range of drug regimens. 

You can find my analysis in the Pymaceuticals folder under pymaceuticals_analysis.ipynb. 

Executive Summary of Findings

- Our analysis removed mouse ID 'g989' as there were duplicate entries in the data. That left 248 total mice observed in our study.
- Ramicane produced the lowest mean (40.2 mm3) and median tumor volume (40.7 mm3), closely followed by Capomulin (40.7 mm3 and 41.6 mm3, respectively). Ramicane and Capomulin also had the lowest variance, standard deviation, and standard error, meaning most results fell most close to their respecitve mean tumor volume so results were fairly consistent.
- Capomulin and Ramicane were tested on the most number of mice, 230 and 228 respectively.
- Our sample of mice was fairly balanced between sex, with 51% of mice being male and 49% female.
- When looking at the bloxplot of our four most promising treatments, Capomulin, Ramicane, Infubinol, and Ceftamin, it's clear that Ramicane and Capomulin have the consistently lowest tumor volume at the end of treatment.
- Looking at a single mouse treated with Capomulin, 'i557', we see the tumor initially shrink but then steadily rises through the end of treatment.
- The correlation between weight and tumor size for mice treated with Capomulin is 0.84, meaning that the two dimensions are correlated and that the greater the mouse weight, the greater the tumor size.
