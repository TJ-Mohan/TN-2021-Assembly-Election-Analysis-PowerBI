# TN-2021-Assembly-Election-Analysis-PowerBI
Interactive Power BI dashboard analyzing the 2021 Tamil Nadu General Assembly election results. Includes an overview of key outcomes, party-wise performance, and constituency-level insights. Designed to provide clear visual understanding of vote share, seat distribution, and electoral trends

## PROBLEMS TO BE SOLVED

#### Overview & Alliances

* Who are the top two parties by seats won and vote share in the 2021 TN Assembly Election?
* How are seats and votes distributed among “Other” parties?
* How do major alliances compare when switching between seats contested and seats won?
* Which parties contested under different symbols within alliances?

#### Party-Level Analysis

* What is a party’s vote share, total votes, and strike rate?
* Which constituencies did a party win, lose, or contest, and how is this distributed geographically?
* How does party performance change when filtering between won and lost constituencies?
* What is the gender and category split of candidates for a selected party?

#### Constituency-Level Analysis

* What are the electors, voters, and turnout percentage for a constituency?
* How did parties perform vote-wise within a selected constituency?
* Who are the winner, runner-up, and third-place candidates, and what are their margins?
* How does gender-wise voter participation compare within the constituency?
* What are the constituencies where the winner was determined by a very less margin ? (Give an option to the user to choose the margin)

#### Comparative Analysis

* How do parties rank across different KPIs such as seats won, vote share, and strike rate?
* How does party ranking change when comparison metrics are switched dynamically?
* Which are the Top-N (0–25) constituencies based on electors, votes polled, or vote percentage?
* Give an insight on the third place results.

## DATA SET 

Source : **Official Data from the Election Commission of India**
-<a href = "https://old.eci.gov.in/files/file/13680-tamil-nadu-general-legislative-election-2021/">Data_set_link</a>  

## TECH STACK

 Tech Stack

* Power BI Desktop – Data modeling, interactive dashboard development
* DAX (Advanced) – CALCULATE, RANKX, FILTER, ALL, dynamic measures, performance optimization
* Power Query  – Data transformation and cleansing
* Data Modeling – Star schema, relationships, calculated measures
* Interactivity – Bookmarks, Field Parameters, What-If (Top-N) parameters, slicers, drill-through
* Visuals & Maps – Bar, clustered bar, gauge, pie, donut, matrix, JSON/shape maps
* Version Control – Git & Github


## SCREENSHOTS 


<img width="1382" height="865" alt="Screenshot 2025-12-23 171514" src="https://github.com/user-attachments/assets/783271a1-698a-4c02-b71c-c0a66a4db093" />
<img width="1396" height="863" alt="Screenshot 2025-12-23 171540" src="https://github.com/user-attachments/assets/fef2a5ba-52dd-4476-8537-643827d83647" />
<img width="1382" height="865" alt="Screenshot 2025-12-23 171604" src="https://github.com/user-attachments/assets/b39f7562-63e4-48f9-b4a8-a04bc55f1c9e" />
<img width="1391" height="862" alt="Screenshot 2025-12-23 171627" src="https://github.com/user-attachments/assets/cebd8f07-1c8a-41f1-930a-11e44285579a" />

## SHORT VIDEO WALKTHROUGH

https://github.com/TJ-Mohan/TN-2021-Assembly-Election-Analysis-PowerBI/releases/download/v1.0/Screen.Recording.2025-12-23.205201.mp4

## COMPLETE DASHBOARD EXPLANATION

https://github.com/TJ-Mohan/TN-2021-Assembly-Election-Analysis-PowerBI/releases/download/V01.1/Complete.Dashboard.Walkthrough.mp4

## BUSINESS IMPACT 


* Delivered a performance-optimized Power BI dashboard enabling state, party, and constituency-level election analysis through interactive and drill-down reporting.
* Enabled self-service analytics using dynamic slicers, bookmarks, and parameters, reducing dependency on static reports.
* Implemented dynamic KPI and ranking comparisons (seats won, vote share, strike rate) to support data-driven evaluation of party performance.
* Identified highly competitive, low-margin constituencies using user-defined thresholds to surface critical electoral insights.
* Designed a scalable and reusable BI framework applicable to future elections or similar analytical domains.

## KEY TAKE-AWAYS 

#### Strike Rate Matters
* Despite DMK leading the alliance, the Indian National Congress recorded a higher strike rate—winning 18 out of 25 constituencies (72%), highlighting efficiency over scale.

#### The Rise of a Young Third Force
* Naam Tamilar Katchi (NTK) emerged as the third-largest party by presence, with an average contestant age of 34 and a 6.5% vote share. The party secured third place in 177 constituencies, yet did not convert this into a single seat win.

#### Gender Representation Leadership
* NTK stands out for near-equal gender representation, with 118 male and 116 female candidates, setting a benchmark for electoral inclusivity.

#### Seats vs Vote Share Paradox
* DMK secured 133 seats compared to 66 by ADMK, yet the vote share gap between the two stands at just 5% (38% vs 33%), underscoring the impact of constituency-level margins and alliances.

#### Alliance Effectiveness
* In the Secular Progressive Alliance (DMK-led), 9 of 13 parties contributed winning seats, whereas in the NDA (ADMK-led), only 3 of 10 parties made a seat contribution—raising questions about alliance depth versus dependency.

#### Close Contests to Watch
* 39 constituencies were decided by margins under 5,000 votes, making them critical battlegrounds for future electoral strategies.

#### Highest Voter Engagement
* Palacode recorded the highest voter turnout in the state at 87%, reflecting exceptional civic participation.

## FUTURE ENHANCEMENTS

* What-If Alliance Simulation :
An interactive scenario analysis that allows users to form custom political alliances and instantly evaluate their hypothetical impact on seats won, vote share, and overall election outcomes.



