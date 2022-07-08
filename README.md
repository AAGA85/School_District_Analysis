# School_District_Analysis

## Overview of the school district analysis

Maria,  the chief data scientist for a city school district is responsible for analyzing information and report the insights that are used for strategic decisions at the school and distric level. In this module, I helped Maria to analyze and prepare some charts to report on student funding and students' standarized test scores in order to discover trends around the schools' performance. These information will be used by the school board and superintendent to define the school budgets and priorities. 

Nevertheless, after the first release of this analysis, the school board warned us that one of the data source (the students_complete.cvs) shows evidence of academic dishonesty; specifically with the 9th graders scores for Thomas High School. Maria asked me to rerun the overall analysis removing the suspicious data. 

The porpuse of this report is summarize the results of updated analysis and show how these changes affected the overall results reported previously.

## Resources
a) [**schools_complete.csv**](https://github.com/AAGA85/School_District_Analysis/blob/bd8700fb341286c880ca581afbc84bb52f3f5179/Resources/schools_complete.csv)
 
b) [**students_complete.csv**](https://github.com/AAGA85/School_District_Analysis/blob/a479273545acae2057c7bd792fd3753b40913d5f/Resources/students_complete.csv)


## Results: 

***Distric Summary***

The following images show the data before and after taking the Thomas High School 9th graders out of the calculation:

![District summary old](https://user-images.githubusercontent.com/106939511/177912103-ca43fe4c-63a8-43cd-b5f5-2ba67a6cedde.png)
*Figure 1.1 District Summary before data cleanup*



![District summary new](https://user-images.githubusercontent.com/106939511/177912101-ab4a2bd3-63b0-4c9b-b8ce-476c4e61cc8e.png)
*Figure 1.2 District Summary after data cleanup*


* Conclusion: There were not significant changes in any of the District Summary metrics 

Note: Please note that the image before data cleanup does not have format in order to not make wrong conclusions because the decimals and roundings 




***School Summary***

The following images show the data before and after taking the Thomas High School 9th graders out of the calculation:

![Thomas High School Performance Old](https://user-images.githubusercontent.com/106939511/177912936-99593a66-1331-4b94-ad03-3599cb0e52a1.png)
*Figure 2.1.0 School Summary (just THS data)  before data cleanup*

![School_summary old](https://user-images.githubusercontent.com/106939511/177913349-6cca6404-6659-483a-8f7e-6ff8453e2f02.png)
*Figure 2.1.1 School Summary (complete)  before data cleanup*

![Thomas High School Performance New](https://user-images.githubusercontent.com/106939511/177912952-f3b717f8-ab18-4a8e-98a9-131dfd1d3afe.png)
*Figure 2.2.0 School Summary (just THS data)  after data cleanup*

![School_summary new](https://user-images.githubusercontent.com/106939511/177913398-4fb10e84-04fb-4275-ba09-8cc6d49b3088.png)
*Figure 2.2.1 School Summary (complete)  after data cleanup*

Conclusion:
As seen in these figures the Thomas High School Performance had a minimal impact on the metrics listed below
   * Average Math Score: Decreased by 0.07 
   * Average Reading Score: Increased by 0.05
   * % Passing Math: Decreased by 0.11%
   * % Passing Reading: Decreased by 0.29%
   * % Overall Passing: Decreased by 0.32%
The rest of the metrics remain as the first analysis




***Thomas High School’s performance relative to the other schools***

![THS Overall performance comparison old](https://user-images.githubusercontent.com/106939511/177913640-0c3178f4-8fa3-41b9-b2ac-13325b59bbbe.png)
*Figure 3.1 Thomas High School performance  before data cleanup*


![THS Overall performance comparison new](https://user-images.githubusercontent.com/106939511/177913678-2ccae069-46fb-4476-b664-8bf8da16f050.png)
*Figure 3.2 Thomas High School performance  after data cleanup*

Conclusion:
As seen in these figures despite having a reduction in the overall performance, Thomas High School kept the second place in the top 5 of the schools of the district.




***Overall metrics impact***


- Math and reading scores by grade

As seen in these figures, the Thomas High School 9th graders are out the summaries. The data was replace with NaNs

![Math scores new](https://user-images.githubusercontent.com/106939511/177913921-9d147620-6f4a-448d-b4a7-836f0bd308f1.png)

*Figure 4.1 Math Scores*

![Reading scores new](https://user-images.githubusercontent.com/106939511/177913922-f8cfa865-2639-460a-82c4-71abc5e4b1f5.png)

*Figure 4.2 Reading Scores*



- Scores by school spending: No changed

![spending old sum](https://user-images.githubusercontent.com/106939511/177914076-0318ee79-fe80-4e23-a5da-7d293635802f.png)

*Figure 5.1 School spending before data cleanup*

![spending new sum](https://user-images.githubusercontent.com/106939511/177914073-ce13bf30-7b63-4ba7-8a59-8c25aa7e2a78.png)

*Figure 5.2 School spending after data cleanup*



- Scores by school size: No changed

![size summary old](https://user-images.githubusercontent.com/106939511/177914283-6837450d-f8c5-45a7-8923-e0ac390827d3.png)

*Figure 6.1 School size before data cleanup*

![size summary new](https://user-images.githubusercontent.com/106939511/177914282-4be6b8ac-1745-4c9a-9273-4eabd5cc520f.png)

*Figure 6.2 School size after data cleanup*



- Scores by school type: No changed

![school type old](https://user-images.githubusercontent.com/106939511/177914382-4a458c1e-5895-4aa1-8537-4e7a070e5e30.png)

*Figure 7.1 School type before data cleanup*

![school type new](https://user-images.githubusercontent.com/106939511/177914379-0b874013-5c46-4e1b-a30e-18cf75402a35.png)

*Figure 7.1 School type before data cleanup*




## Summary: 

After reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs and repeated the school district analysis, I can conclude that the impact on the overall analysis was minimum. There was a minimum degradation in the overall performance of Thomas High School because the data that was removed from the 9th graders in comparison with the rest of the graders followed the same trend, as you can see in the Math and Reading scores. So when we recalculated the averages those kept quite similar percentages. 
