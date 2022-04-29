# Project 1: Analysing Trends in ACT Composite Scores across all states from 2017 to 2019



## Problem Statement:
- Analyse trends in ACT composite scores across all states from 2017 to 2019 in order to give suggestions / feedbacks on ways to improve the scores in some specific states.
- Identify states with low participation rates and suggest ways to improve them


## Background and Relevant Information:
-The ACT is an entrance exam used by most colleges and universities to make admissions decisions. It is a multiple-choice, pencil-and-paper test administered by ACT, Inc. Its rival, SAT is also an entrance exam for similar purposes. 
- The ACT has four sections: Reading, Math, Science Reasoning, English. There is an additional Essay Writing section thats optional. The ACT is 2 hours and 55 minutes long. If you choose to take the ACT with Essay, the test will be 3 hours and 35 minutes long.Each section of the ACT is scored on a 1 to 36 point scale. Your composite ACT score is the average of your four section scores, also on a scale from 1 to 36. If you take the ACT with Writing Test, you will receive a separate score on the Writing Test.([source](https://www.princetonreview.com/college/act-information))
- Since the early 1980s SAT has always been more popular than ACT. Until 2012, the SAT’s popularity exceeded that of the ACT—in market share it was about 55% versus 45%. Coastal high school students living in places generally chose the SAT, while students in the interior of the U.S, generally took the ACT. 
-In 2012, the ACT surpassed the SAT in market share and the college prep testing world shook. The main reason is believed to be that the questions in ACT was more straigthforward and those students who preferred english over math, started choosing ACT. More colleges also started accepting ACT as the official state test for juinors. As a reaction, SAT revamped its test content in 2015 and also changed its scoring from 2400 to 1600 to look more similar to the ACT. 
-As of 2019, the SAT is officially more popular than the ACT with 55% of the market share. More than 2.2 million students in the class of 2019 took the SAT compared to about 1.8 million students who took the ACT. [source](https://theolivebook.com/sat-vs-act-which-is-more-popular/)

-As of today, all colleges in the USA either accept both ACT and SAT and show no preference for one over another. This makes it an even playing field and opportunity to grow the ACT test market.


## Datasets selected:
- act_2017.csv
- act_2018.csv
- act_2019.csv

The datasets provides data on the **participation rates** and **average composite ACT score** by each state for the years 2017,2018 & 2019. This data was used to identify trends of composite scores across the 3 years for different states.

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|act_combined_changed.csv|state in which students (high school graduates) who took ACT stay|
|participation_2017|float|act_combined_changed.csv|%(2 decimal format)of state's students who took ACT in 2017. For eg 0.5 means 50%.
|composite_2017|float|act_combined_changed.csv|Average total ACT score of students in 2017 by state.
|participation_2018|float|act_combined_changed.csv|%(2 decimal format)of state's students who took ACT in 2018. For eg 0.5 means 50%.
|composite_2018|float|act_combined_changed.csv|Average total ACT score of students in 2018 by state.
|participation_2019|float|act_combined_changed.csv|%(2 decimal format)of state's students who took ACT in 2019. For eg 0.5 means 50%.
|composite_2019|float|act_combined_changed.csv|Average total ACT score of students in 2019 by state.
|sumof_deltas_171819|float|act_combined_changed.csv|The difference in mean composite scores between 2017 and 2019. This essentially shows whether the scores are becoming better or worse over the 3 year period.
|avg_participation|float|act_combined_changed.csv|Average participation for each state across the 3 years.
|avg_composite|float|act_combined_changed.csv|Average composite score for each state across the 3 years.

## Findings

1. The number of states that have been doing well have continued to improve while those that have been performing mediocre have become slightly worse.
2. The worse performing states in terms of average ACT scores are Nevada, Mississippi, South Carolina, Louisiana, Hawaii, Alabama and North Carolina.
3. In terms of highest rate of deterioration, its Ohio, Nebraska, Louisiana, Oklahoma and Montana.
4. There is an inverse relationship between ACT scores and participation rates. This could be because as more students write the exam, they bring the average down. In the states that have higher scores and lower participation rates, they could be having stiff competition from students writing SATs.

## Recommendations

1. The amount of funding needs to increase in states with lower ACT scores that is mentioned above. The following can be done:
 - There needs to be a re-evaluation of the ACT coaching classes and how its run. 
 - More students should be encouraged to attend coaching sessions 
 - As participation rates are high anways, the ACT test rates can be subsidised. Some states already give a free test for the first time. For these cases, they can provide subsidies for the 2nd test.
 - ACT is known for being more straightforward than other tests. This could be used as a key marketing point
 
2. There should be an indepth analysis done on the states that are performing well in terms of ACT scores and use those findings and techniques to implement in the less performing states.
3. For the states with the lower participation rates (Maine, Rhode Island, New Hampshire, Delaware and Pennsylvania), more awareness and reach about ACT should be created to tap into students, especially those who are stronger in English and weaker in Maths. 

