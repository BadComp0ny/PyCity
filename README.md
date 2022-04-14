# PyCity
## Overview of the school district analysis.
The local school board has notified the business of potential academic dishonesty.  As a result we have been tasked to omit the grades of the students in question to ensure state-testing standards.

## Results
Upon initial review of the data it was identified that Thomas High School (THS) scores for the 9th graders appeared to have been altered.  The percentages of the student population which was passing for THS was well below the average and did not reflect that the average scores for this school in both reading and math had been above 70%.
As such the resolution was to NaN out the scores for the affected population and re-review the data.
Once the affected grouping of students had been removed from the scores we saw the percentages of the THS students passing in math, reading, and overall increased significantly.

- The percentage passing in math increased to 93.19% from 66.91%
- The percentage passing in reading increased to 97.02% from 69.66%
- The percentage passing in both increased to 90.63% from 65.08%

This moved THS from being ranked as one of the worst schools in the district when compared by percentage of overall passing to the second best school in the district.

The 9th grade scores for THS had been omitted as such there was no score for that grade recorded for THS.  In implementing this change it was observed that THS results far exceed the other schools which are spending approximately the same per student ($631 – $645).
This may also be due to the fact that it is the only school in this per capita group that has less than 2000 students.  When comparing the results to the school size it is found that similar results are achieved by other schools which are spending below the per capita that THS is utilizing.
Scores by school type (Charter vs. District) remained relatively unchanged and we saw that average scores and percentage of the student population which is passing continues to remain higher in the charter schools vs the district schools.

## Summary
Once the THS 9th grade scores were replaced with NaN we saw the following.
1.	An immediate improvement in reported percentage of student population as passing in reading, math, and overall for Thomas High School
2.	The average scores for the students at this school were relatively unchanged (less than 1%) as the 9th graders at THS represented such a small portion of the overall population.
3.	The per capita spending was unchanged as we did not remove those students from the total student count as the school still spend the funds on each student even though we had removed their scores.
