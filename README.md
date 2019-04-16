

### Executive Summary

This report is centered around the test taking data available regarding college-bound students in the USA from the years of 2017 to 2018. The population that is described in these datasets is comprised of graduating High School Seniors who have taken the exams as part of the college application process. The ACT minimum possible score is a 1, the maximum possible score is a 36 and the mean possible is a 21. The SAT minimum score is a 200 for each of the 2 sections for a total minimum of 400, and the maximum score for each of the 2 sections is 800 for a total maximum of 1600. 

It is clear from looking through this data that state contracts play a large role in the success or failure of high participation rates in a state. Although there is little that can be done in states with existing contracts, there is significant opportunity to grow in non-contract bound states. Next steps would include reaching out to those states with no contract in place for the ACT, which include: Alaska, Arizona, Iowa, Kansas, New Mexico, Oregon, South Dakota and West Virginia.


### Problem Statement
In this project, the main focus was to analyze data from a set of data that encompassed the 2017 and 2018 statistics from the SAT and ACT college entrance standardized exams. The focus of this analysis is on the potential relationships between participation rates of each standardized exam, as well as other metrics which may be actionable.


### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
'state'|object|2017/18  ACT/SAT|US State from which data was collected|
'act_2017participation'|float64|2017 ACT|Percentage of graduating hs seniors taking the ACT in 2017, Scored 1-100
'act_2017english'|float64|2017 ACT|Avg test scores by state in English for ACT in 2017, Scored 1-36
'act_2017math'|float64|2017 ACT|Avg test scores by state in Math for ACT in 2017, Scored 1-36
'act_2017reading'|float64|2017 ACT|Avg test scores by state in Reading for ACT in 2017, Scored 1-36
'act_2017science'|float64|2017 ACT|Avg test scores by state in Science for ACT in 2017, Scored 1-36
'act_2017composite'|float64|2017 ACT|Avg Composite score by state for ACT in 2017, Scored 1-36
'sat_2017participation'|float64|2017 SAT|Percentage of graduating HS Seniors taking the SAT in 2017, Scored 1-100
'sat_2017evidence-based_reading_and_writing'|int64|2017 SAT|Avg test scores by state in EBRW for SAT in 2017, Scored 400-800
'sat_2017math'|int64|2017 SAT|Avg test scores by state in Math for SAT in 2017, Scored 400-800
'sat_2017total'|int64|2017 SAT|Avg total test scores by state for SAT in 2017, Scored 800-1600
'act_2018participation'|float64|2018 ACT|Percentage of graduating HS Seniors taking the ACT in 2018, Scored 1-100
'act_2018composite'|float64|2018 ACT|Avg composite score for the ACT in 2018, Scored 1-36
'sat_2018participation'|float64|2018 SAT|Percentage of graduating HS Seniors taking the SAT in 2018, Scored 1-100
'sat_2018evidence-based_reading_and_writing'|int64|2018 SAT|Avg test scores by state in EBRW for SAT in 2018, Scored 400-800
'sat_2018math',|int64|2018 SAT|Avg test scores by state in Math for SAT in 2018, Scored 400-800
'sat_2018total'|int64|2018 SAT|Avg total test scores by state for SAT in 2018, Scored 800-1600


### Outside Research
#### Illinois: 
Illinois has a large change as well, also due to a new state contract signed with the SAT. This resulted in a change of +90% for the SAT participation rates from 2017 to 2018 (from 9% to 99%), and a corresponding change in ACT participation rates of -50% (from 93% to 43%). As expected, the SAT test score mean Total fell, from 1115 to 1019, while the ACT test Composite mean score rose from 21.4% to 23.9%.   https://chalkbeat.org/posts/chicago/2018/07/27/act-protests-state-boards-embrace-of-rival-test-provider/

#### Colorado: 
Colorado has a large swing from 2017 to 2018, most likely entirely due to a new contract acquired by the SAT in partnership with the state of Colorado. This resulted in a change of +89% for the SAT participation rates from 2017 to 2018(from 11% to 100%), and a corresponding change in ACT participation rates of -70% (from 100% to 30%). As expected, the SAT test score mean Total fell, from 1201 to 1025.
"SAT usage also spiked in Colorado because of a contract with the College Board. There, 58,790 in the Class of 2018 took the test, 10 times the total of the previous year." https://www.washingtonpost.com/education/2018/10/23/sat-reclaims-title-most-widely-used-college-admission-test/


#### Rhode Island
Rhode Island had a large change recently, from 71% to 97% participation on the SAT- while ACT participation fell from 21% to 15%. This was due to changes in the requirements for state testing, which became a part of the state's federal education plan. As expected, the SAT test score mean Total fell, from 1062 to 1018, while the ACT test Composite mean score rose from 24% to 24.2%.
https://www.providencejournal.com/news/20181025/with-sat-required-ri-sees-jump-in-participation-decline-in-scores


### Conclusions and Recommendations

The data clearly shows that there is intense competition between the SAT and ACT tests, but it is best to focus on states that do not have any set agreements. There are a handful of states that have no such contracts, yet have high participation in both tests: Florida, Georgia and Hawaii are three that could generate large returns for the effort.

If possible, the ideal situation for the SAT would be: to be a part of the success metric for students, schools, cities, AND states, making it impossible for every level to ignore the impact of the test's importance. In states where there is a clear tie to success, such as Illinois, there are also metrics that incorporate the test scores at the city and school level as well. These are tied to future things such as state and federal funding, so it would make sense for the schools and cities to do as much as they can to speed up adoption of the test.

The states that I would recommend looking into for potential contracts would be: Alaska, Arizona, Iowa, Kansas, New Mexico, Oregon, South Dakota, West Virginia. These are states that have low SAT participation rates as of 2018 and there are no contracts in place. 

The recommendation would be to get as close to the prior mentioned ideal situation as possible. This means locking up a multi-year contract with the state, becoming an integral part of the success metrics for schools, cities and the state itself, and finally mandating pre-SAT (PSAT) starting as early as 9th grade. These steps would ensure revenue generation for at least the duration of the contract.
