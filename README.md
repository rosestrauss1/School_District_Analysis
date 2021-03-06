# School District Analysis

  ## Overview
  The purpose of this analysis is to understand the impact of replacing inaccurate student grades on the math and reading scores fo students at Thomas High School.
  
  ## Results

* How is the district summary affected?

In the district summary without the 9th grade math and reading scores, the average reading score was 81.9 and the average math score was 78.9. The percent passing math was 74.8% and the percent passing reading was 85.7%. In the district summary including these scores, the reading score average was 81.9 and the average math score was 79. The percent passing math was 75% and the percent passing reading was 86%. This shows that these scores did have a small impact on the district analysis, and had a larger impact on the math score than the reading score. 

* How is the school summary affected?

In the school summary without the 9th grade math and reading scores where the reading and math scores are replaced with the data just from 10th-12th graders, the average reading score was 83.9 and the average math score was 83.3. The percent passing math was 93% and the percent passing reading was 97%. The overall passing percentage was 90.6%. In the school summary including these scores, the reading score average was 83.8 and the average math score was 83.4. The percent passing math was 93% and the percent passing reading was 97%. The overall passing percentage was 90.9%. This shows that when Thomas High School's scores were replaced with the 10th-12th grade scores only, it caused the average reading score to slightly increase, and the average math score to slightly increase. The precent passing slightly decreased. This could mean that the 9th grade scores were inflated so more students passed, but not past a threshold that would have increased the average math and reading scores.

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the math and reading scores decreases Thomas High School's performance relative to other school, mostly relating to the overall percent of students passing at Thomas High School.

* How does replacing the ninth-grade scores affect:

    - Math and reading scores by grade

    The math and reading scores by grade are not impacted by replacing the 9th grade scores. The 9th grade scores are replaced by 'NaN' and the remaining grade         values stay the same.

    - Scores by school spending

    The scores by school spending were impacted just in the 630-644 bin for spending per student. The changes were very slight, but indicate that the scores for the     spending per students was slightly lower for that spending range.

    - Scores by school size

    The score by school size was very slightly impacted in the medium sized school bracket, which indicates that because Thomas High School was a medium sized 
    school the percent overall passing was a bit higher.

    - Scores by school type

    Because Thomas High School was a charter school, there was a slight impact on the overall percent passing of students, from 90% without the changes to the 9th       grade data to 92% passing with these changes.

## Summary

Four changes to the school district analysis that occured due to changing the 9th grade values to NaN was the performance of Thomas High School related to other schools, specifically with the percentage of students passing overall. The scores by school spending, scores by school size, and scores by school type were also all altered by replacing the 9th grade values with NaN's because Thomas High School's overall passing percentage affected the results of the scores in its bin. 
