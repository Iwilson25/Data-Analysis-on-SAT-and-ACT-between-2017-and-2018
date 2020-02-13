## SAT/ACT Statistical summaries and inference

### Problem statement
The new format for the SAT was released in [March 2016](https://www.businessinsider.com/the-sat-is-changing-its-format-in-2016-and-will-be-easier-2015-6?IR=T). As an employee of the College Board - the organization that administers the SAT - we are part of a team that tracks statewide participation and recommends where money is best spent to improve SAT participation rates. We will use the provided data and outside research to make recommendations about how the College Board might work to increase the participation rate in certain states.
### Executive Summary
We are focusing on three points that we uncovered through the SAT/ACT 2017 & 2018 data and based on these discoveries the College Board should work towards increasing the participation rate in those region further.
- Through our research we discovered that 3 states are exhibiting significant increase in their SAT particitpation rate due to [regulations](https://www.testive.com/colorado-sat-change-2017/) or [contract changes](https://www.wvgazettemail.com/news/education/wv-chooses-sat-as-new-high-school-standardized-test-for/article_b60d2618-4943-56f6-b180-4b4442172ef8.html)
- There are strong regional affiliations associated with ACT versus SAT preference. Coastal progressive states tend to favor the SAT, while Midwestern and Mountain conservative states tend to favor the ACT.
- The SAT made clear gains in 2018 relative to the ACT. The states making these gains tended to be states in the 10-15% participation range. Targeting states in similar positions in the 2018 distribution should be promising for the College Board moving forward.

### Data Dictionary
#### Data dictionary 2017
|Feature      |Type      |Dataset  |Description|
|---------    |------    |---------|-----------|
|**state**        |object    |sat/act  |states|
|**participation_sat**|float|sat|Statewide SAT Participation Rate, 2017|
|**ebw**|integer|sat|State mean score, SAT Reading/Writing, 2017|
|**math_sat**|integer|sat|State mean score, SAT Math, 2017|
|**total_sat**|integer|sat|State mean total SAT score, 2017|
|**participation_act**|float|act|Statewide ACT Participation Rate, 2017|
|**english_act**|float|act|State mean score, ACT English, 2017|
|**math_act**|float|act|State mean score, ACT English, 2017|
|**reading_act**|float|act|State mean score, ACT Reading, 2017|
|**science_act**|float|act|State mean score, ACT Science, 2017|
|**composite_act**|float|act|State mean ACT Composite Score, 2017|
#### Data dictionary 2018
|Feature      |Type      |Dataset  |Description|
|---------    |------    |---------|-----------|
|**state**        |object    |sat/act  |states|
|**participation_sat_2018**|float|sat|Statewide SAT Participation Rate, 2018|
|**ebw_sat_2018**|integer|sat|State mean score, SAT Reading/Writing, 2018|
|**math_sat_2018**|integer|sat|State mean score, SAT Math, 2018|
|**total_sat_2018**|integer|sat|State mean total SAT score, 2018|
|**participation_act_2018**|float|act|Statewide ACT Participation Rate, 2018|
|**english_act_2018**|float|act|State mean score, ACT English, 2018|
|**math_act_2018**|float|act|State mean score, ACT English, 2018|
|**reading_act_2018**|float|act|State mean score, ACT Reading, 2018|
|**science_act_2018**|float|act|State mean score, ACT Science, 2018|
|**composite_act_2018**|float|act|State mean ACT Composite Score, 2018|

### Conclusions and Recommendations

**Key takeaway:**
- Coastal progressive states tend to favor the SAT, while Midwestern and Mountain conservative states tend to favor the ACT. Therefore, the College Board should continue to focus their growth within the coastal progressive states and at the same time more efforts are needed for growth within the Midwestern and Mountain conservative states.
- SAT made significant gains in 2018 as compared to the ACT. States with lower SAT participation rate between the region of 10-15% are showing gains. Therefore, the College Board should continue to target those States and it will be promising for the board moving forward.
