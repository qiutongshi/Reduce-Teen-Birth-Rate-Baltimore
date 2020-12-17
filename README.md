# Reduce-TeenBirthRate-Baltimore-
## Introduction
Teen pregnancies carry extra risks to both the mother and the baby. Baltimore city has a teen birth rate twice as high as the state of Maryland and three times as high as the national average. This project uses linear regression and cluster analysis to explore the racial and economical factors contributing to teen birth rate in Baltimore, hopefully giving an insight into the services and initiatives to reduce the rate.  

While cluster analysis groups teenage birth rate with its distinct corresponding minority residence rate, linear regression also shows that racial factors can contribute greatly to teenage birth rate. After the data analysis, we believe that current initiatives that include education, prevention and follow-up need to be more targeted to counties where Hispanic, AIAN and NHOPI residence rate is higher. 	

Further studies on how to improve the education, prevention and follow-up cautions on teenage pregnancy are needed to better solve the identified problem at several measures such as campaigns and community resources can be more precisely targeted at high-risk groups.

## Background
According to the [Baltimore City Health Department](https://health.baltimorecity.gov/node/170.), Baltimore City has an average teen birth rate of 43.4 out of 1,000 teenage females (ages 15-19). This rate is about twice as high as the national average (26.5 out of 1,000). Although this rate has been steadily declining over the past decade, there is more that can and should be done.

Teen birth is a serious social and economic problem. [According to one study](https://www.childtrends.org/wp-content/uploads/2010/01/child_trends-2010_01_22_FS_diplomaattainment.pdf.), teen pregnancies and births are a significant contributor to dropping out of school. Females who dropout of school face social stigma, fewer job opportunities, lower salaries, and a [higher probability of criminal activity](https://www.doe.mass.edu/dropout/overview.html?section=consequences#:~:text=Dropping%20out%20of%20school%20has,with%20the%20criminal%20justice%20system.). There is also a social ripple effect. Like their mothers, [children of teen births](http://webarchive.urban.org/publications/901199.html#:~:text=Teenage%20motherhood%20costs%20taxpayers%20about,teenage%20parents%20and%20their%20children.) are more likely to achieve lower education, be incarcerated, experience teen pregnancy, and have difficulty finding employment. Due to the socioeconomic status of their teen mother, they are also more likely to have health problems.

This is an urgent problem that needs to be addressed as soon as possible because of the significant short- and long-term consequences. If teen pregnancy is not addressed, our society could be looking at generations of families impacted by the aforementioned social repercussions. These effects impact teen families and the larger community’s functionality, efficiency, and productivity.



### Racial factors in teen birth
[Several articles and studies](https://www.npr.org/2014/04/14/302906835/why-do-more-latina-teens-get-pregnant.) found that Latinas have one of the highest teen pregnancy rates in the United States. 
<img width="688" alt="Screen Shot 2020-12-17 at 17 32 26" src="https://user-images.githubusercontent.com/70663111/102551638-d602b480-408d-11eb-8f5d-7c4d9df2c944.png">
The bar chart shown above is from [data analysis](https://www.cdc.gov/teenpregnancy/about/index.htm#:~:text=In%202017%2C%20the%20birth%20rates,highest%20among%20all%20race%2Fethnicities.) conducted by the Centers for Disease Control (CDC, Figure 1). Due to their high teen pregnancy rates, Hispanic females also have one of the highest teen birth rates in the United States. Black, American Indian/Alaska Native (AIAN), and Native Hawaiian/Other Pacific Islander (NHOPI) also have very high teen birth rates that exceed the rate of all races and origins. [Another study](https://pubmed.ncbi.nlm.nih.gov/23450881/.) found that socioeconomic conditions, such as living under the poverty line, could contribute to high teen birth rates. 

Baltimore City has more people living under the poverty line [(21.8%)](https://datausa.io/profile/geo/baltimore-city-md#:~:text=21.8%25%20of%20the%20population%20for,and%20then%20Females%2055%20%2D%2064.) than the national average (13.1%), with the largest demographic group living in poverty being females. Baltimore City is also [largely made up of racial minorities](https://datausa.io/profile/geo/baltimore-md/#:~:text=The%205%20largest%20ethnic%20groups,%2DHispanic.). Since [prior research](https://urbanhealth.jhu.edu/_archive/2019/_downloads/reducing_teen_births_execsumm.pdf.) on teen birth rates was generally focused on analyzing general or African American populations, we wanted to focus our data analysis on low income, Hispanic, AIAN, and NHOPI populations to see if the aforementioned national trends persist in Baltimore City. We wanted to analyze if racial demographics and socioeconomic status could contribute to the teen birth rate in Baltimore City to answer our business question: how can the Baltimore City Health Department reduce teen birth rates in Baltimore City?

### Current Initiatives  
- Teen Pregnancy Prevention Initiative (TPPI)
As part of the [B'more for Healthy Babies programs](https://www.healthybabiesbaltimore.com.), Baltimore City has instituted the Teen Pregnancy Prevention Initiative (TPPI) to reduce teen births. TPPI has four key strategies: a Teen Pregnancy Prevention Task Force, Provider Engagement and Outreach, Youth Advisory Council, and a Social Marketing Campaign. 

- Healthy Teens & Young Adults (HTYA)  
The Healthy Teens and Young Adults' (HTYA) mission is to reduce unintended pregnancies and to improve pregnancy outcomes by providing reproductive health services to young women and men 10 - 24 years of age.  Services also available include: Contraception (birth control) including IUDs and subdermal implant (Nexplanon). This program serves as an indirect sub program to reduce teenage birth rate.


## Business Question
How do educational characteristics differ by race in the U.S.? How can these differences inform potential policy action regarding the US educational system? 

## Data Question
What are the similarities and differences between racial disparities in education between Florida, California, Pennsylvania, and Illinois, and what are the possible reasons behind these disparities? 

## Data Metrics
- Academic performance by race: 
  - Average test scores: Average test scores are influenced by opportunities to learn at home, in the neighborhood, during child-care, at preschool and after-school programs, from classmates and friends, and at -most obviously- school.
    - SAT and AP test scores
  - Chronic Absenteeism: Students who are chronically absent means that they miss at least 15 days of school in a year. Chronic absences affects student achievement, as well as student attitude and behavior at school. An increase in absences increases the risk of dropping out of school.
  - High-school graduation rates by race: a less specific yet helpful indicator of general educational performance outcome of students by race
- Population distribution across race in the four states: a basic description of racial divergence in the states, might differ in terms of their impacts on racial disparities


## Data Sources
- High School Graduation Rates: Taken from various state websites with available data, 2017/18 school year
  - [CA](https://www.kidsdata.org/topic/755/graduates-race/table#fmt=1154&loc=2,127,347,1763,331,348,336,171,321,345,357,332,324,369,358,362,360,337,327,364,356,217,353,328,354,323,352,320,339,334,365,343,330,367,344,355,366,368,265,349,361,4,273,59,370,326,333,322,341,338,350,342,329,325,359,351,363,340,335&tf=130&ch=7,11,726,85,10,72,9,73)
  - [FL](http://www.fldoe.org/core/fileparse.php/7584/urlt/GradRates1718.pdf)
  - [IL](https://www.illinoisreportcard.com/state.aspx?source=trends&source2=graduationrate&Stateid=IL)
  - [PA](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/2017-2018%20Pennsylvania%204-Year%20Cohort%20Graduation%20Rates%20(1).xlsx)

- SAT Scores by Race: Taken from College Board open data, 2017/18 school year
  - [CA](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/2018-california-sat-suite-of-assessments-annual-report.pdf)
  - [FL](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/2018-florida-sat-suite-of-assessments-annual-report.pdf)
  - [IL](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/2018-illinois-sat-suite-of-assessments-annual-report.pdf)
  - [PA](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/2017-2018%20Pennsylvania%204-Year%20Cohort%20Graduation%20Rates%20(1).xlsx)
  
- AP Scores by Race: Taken from College Board open data, 2017/18 school year
  - [CA](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/california-summary-2018.xlsx)
  - [FL](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/florida-summary-2018.xlsx)
  - [IL](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/2018-illinois-sat-suite-of-assessments-annual-report.pdf)
  - [PA](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/pennsylvania-summary-2018.xlsx)
  
- [Chronic Absenteeism](https://github.com/vickidecastro/racial-disparities-education-US/blob/main/Chronic-Absenteeism%20(1).xlsx): Taken from Civil Rights Data Collection open data source, 2013/14 school year estimates
  
 
## Data Analysis
We decided to do a three-cluster analysis for each state using high school graduation rate, average SAT test score, average AP test score, and percentage of chronically absent students by race (7 races). We used these variables as we could access them across states, CB data is consistent, and because they are common indicators of educational performance across the board. 

### California
- Cluster 1: Multiracial: avg hs grad, high mean SAT, low/avg chronic abs, high mean AP
  - Asian, White, Multiracial
- Cluster 2: Hispanic/Latino: avg hs grad, low mean SAT, high chronic ab, low mean SAT
  - Hispanic/Latino
- Cluster 3: Black/African American: low hs grad, low mean SAT, avg chronic abs, low mean AP
  - American Indian/Alaska Native, Black/African American, Native Hawaiian/Pacific Islander
  
<img width="888" alt="Screen Shot 2020-10-29 at 12 02 46 AM" src="https://user-images.githubusercontent.com/70858878/97524896-070f1480-197c-11eb-8599-ae313dcb65f7.png">




### Florida
- Cluster 1: Asian: high hs grad, high mean SAT, low chronic abs, high mean AP
  - Asian
- Cluster 2: Hispanic/Latino: avg hs grad, avg mean SAT, high chrnic abs, high/avg mean AP
  - Hispanic/Latino, White, Multiracial
- Cluster 3: low hs grad, low mean SAT, low chronic abs, low mean AP 
  - American Indian/Alaska Native, Black/African American, Native Hawaiian/Pacific Islander

<img width="992" alt="Screen Shot 2020-10-29 at 12 07 26 AM" src="https://user-images.githubusercontent.com/70858878/97524320-bf3bbd80-197a-11eb-90ab-054f1f3c7c60.png">


### Illinois
- Cluster 1: Native Hawaiian/Pacific Islander: low-avg hs grad, avg mean SAT, low chronic abs, avg mean AP
  - Native Hawaiian/Pacific Islander, American Indian/Alaska Native, Multiracial
- Cluster 2: Black/African American: low hs grad, low mean SAT, high chronic abs, low mean AP
  - Black/African American, Hispanic/Latino
- Cluster 3: Asian: high hs grad, high mean SAT, avg chronic abs, high mean AP
  - White, Asian

<img width="858" alt="Screen Shot 2020-10-29 at 12 10 52 AM" src="https://user-images.githubusercontent.com/70858878/97524504-3c673280-197b-11eb-82f4-8ff6f7b6c0fd.png">


### Pennsylvania
- Cluster 1: American Indian/Alaska Native: low hs grad, low mean SAT, low chronic abs, low mean AP
  - American Indian/Alaska Native, Black/African American, Multiracial
- Cluster 2: White: high hs grad, high mean SAT, avg-high chronic abs, high mean AP
  - White, Asian, Native Hawaiian/Pacific Islander
- Cluster 3: Hispanic/Latino: low hs grad, low mean SAT, high chronic abs, avg mean AP
  - Hispanic/Latino
  
<img width="888" alt="Screen Shot 2020-10-29 at 12 02 46 AM" src="https://user-images.githubusercontent.com/70858878/97524559-602a7880-197b-11eb-8211-45e32b8516bc.png">
