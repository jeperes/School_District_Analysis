# School_District_Analysis

A school distric asked to perform a analysis in a school data and showcase trends in school performance based on key metrics. However after finish the analysis, the board asked for a new data analysis because the file shows evidence of academic dishonesty. The new performance consists in replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the both score are replaced, a new school district analysis is performed. 

# Overview 

After replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, a new school district analysis is done and some changes are noticeble. The eprcentage of overall passing changes, Thomas high school have a new position in the rank.

# Resources

1. Software: Python 3.9.1
2. Anaconda
3. Jupyter-Notebook
4 - Pandas

# Results

# How is the district summary affected?

After turn the 9th graders at Thomas High School into null data, the percentages of passing math, passing reading, and the overall passing didn't have a big change. 

![old_districtsummary.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/old_districtsummary.jpg)

![new_districtsummary.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/new_districtsummary.jpg)

# How is the school summary affected?

In the first analysis, Thomas High School started with a 91% overall passing rate. After calculating the total number of 10th - 12th grade students and removing the 9th grade, the npassing percentage droped from 91% to 65%. 

![old_schoolsummary.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/old_schoolsummary.jpg)

![new_schoolsummary.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/new_schoolsummary.jpg)

# How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High School dropped from 2nd place to the bottom of the list.

![old_ninth graders.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/old_ninth%20graders.jpg)

![new_ninth graders.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/new_ninth%20graders.jpg)

# How does replacing the ninth-grade scores affect the following:

# Math and reading scores by grade

Thomas High School math average and reading average for the 9th grade tests have been replaced with null values and shows up as NaN in the following charts.

![AdjustedAverages_mathscore.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/AdjustedAverages_mathscore.jpg)

![AdjustedAverages_readingscore.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/AdjustedAverages_readingscore.jpg)

# Scores by school spending

There is not big changes spending impact after changing the 9th grade scores.

![old_scorebyspending.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/old_scorebyspending.jpg)

![new_scorebyspending.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/new_scorebyspending.jpg)

# Scores by school size

Thomas High School is a medium size school and there is not big impact by campus size after the 9th grade being replaced.

![old_scorebysize.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/old_scorebysize.jpg)

![new_scorebysize.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/new_scorebysize.jpg)

# Scores by school type

Thomas High School is a charter school type and there is no changes after the 9th grade being replaced.

![old_scorebysize.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/old_scorebytype.jpg)

![new_scorebysize.jpg](https://github.com/jeperes/School_District_Analysis/blob/main/resources/new_scorebytype.jpg)

# Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Thomas High School math average and reading average for the 9th grade tests have been replaced with null values and shows up as NaN.

The overall passing rate for Thomas High School dropped from 91% to 65%.

Thomas High School's ranking dropped from 2nd to the bottom of the list.


