# Reduce-TeenBirthRate-Baltimore-
## Introduction
Teen pregnancies carry extra risks to both the mother and the baby. There are also societal, economic, and generational consequences to teen births. Baltimore city has a teen birth rate twice as high as the state of Maryland and the national average. This project uses linear regression and cluster analysis to explore the racial and economic factors contributing to teen birth rate in Baltimore, hopefully giving an insight into how initiatives can be improved to reduce the rate. 

Cluster analysis groups show that teen birth rate occurs in areas with higher minorities and lower income. Linear regression also shows that racial factors can contribute greatly to teenage birth rate. After the data analysis, we believe that current initiatives that include education, prevention, and follow-up need to be more targeted to neighborhoods where Hispanic, AIAN and NHOPI residence rate is higher. 
  
Further studies on additional factors that contribute to teen birth rate and how to improve the education, prevention, and follow-up cautions on teenage pregnancy are needed to solve the identified problem at several measures such as campaigns and community resources can be more precisely targeted at high-risk groups.

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
- [Teen Pregnancy Prevention Initiative (TPPI)](https://youth.gov/evidence-innovation/investing-evidence/teen-pregnancy-prevention-initiative)
This is a program that was originally launched by the Department of Health and Human Services (HHS) in 2010 to reduce teen birth rates across the nation. This is an evidence-based program used in cities across the nation that has been shown to be effective in reducing teen birth rates.
As part of the [B'more for Healthy Babies programs](https://www.healthybabiesbaltimore.com.), Baltimore City has instituted the Teen Pregnancy Prevention Initiative (TPPI) to reduce teen births. TPPI has four key strategies: a Teen Pregnancy Prevention Task Force, Provider Engagement and Outreach, Youth Advisory Council, and a Social Marketing Campaign. 

- [Healthy Teens & Young Adults (HTYA)](https://health.baltimorecity.gov/node/223)
The Healthy Teens and Young Adults' (HTYA) mission is to reduce unintended pregnancies and to improve pregnancy outcomes by providing reproductive health services to young women and men 10 - 24 years of age.  Services also available include: Contraception (birth control) including IUDs and subdermal implant (Nexplanon). This program serves as an indirect sub program to reduce teenage birth rate.


## Business Question
How can we reduce teen birth rates in Baltimore City?

## Data Question
What are the factors impacting teen birth rate in Baltimore, and how do they weight differently? Waht are the features of different representitive groups in Baltimore?

## Data Metrics
- Teen birth rate  
- % of families living below the poverty line per neighborhood
  - Can be a general indicator of family income level, but not a precise one because it does not reflect range, standard deviation etc.
- % of Hispanics per neighborhood
  - The total number of persons that identify their ethnicity as being Hispanic or Latino out of the total number of persons living in an area. 
- % of NHOPI & AIAN per neighborhood
  - The total number of persons that identify themselves as being of either American Indian, Alaskan Native, Native Hawaiian or Other Pacific Islander, or some other race (non-Hispanic) out of the total number of persons living in an area. 


## Data Sources
Vital Signs Open Data: This is a collection of publically available data on Baltimore City neighborhoods to paint a picture of each neighborhood's quality of life and overall health. It includes information and datasets on census demographics, housing and community development, children and family health, crime and safety, workforce and economic development, arts and culture, education and youth, and sustainability. Data from 2015-2018 were used in this project.
1. [Teen Birth Rate per 1,000 Females (aged 15-19)](https://vital-signs-bniajfi.hub.arcgis.com/datasets/2d91057e9a1642e19bfab911cb755672_0.) - This dataset shows the rate of female teens aged 15-19 that gave birth per 1,000 females aged 15-19 in each Baltimore City neighborhood.
2. [Percent of Family Households Living Below the Poverty Line](https://vital-signs-bniajfi.hub.arcgis.com/datasets/74337e706ee94cd8a8b8272564497946_0.) - This dataset shows the percentage of households living below the poverty line in each Baltimore City neighborhood.
3. [Percent of Residents - All Other Races (Hawaiian/ Pacific Islander, Alaskan/ Native American Other Race) (Non-Hispanic)](https://vital-signs-bniajfi.hub.arcgis.com/datasets/percent-of-residents-all-other-races-hawaiian-pacific-islander-alaskan-native-american-other-race-non-hispanic.) - This dataset shows the percentage of residents who identify their ethnicity as Hawaiian/Pacific Islander or Alaskan/Native American in each Baltimore City neighborhood.
4. [Percent of Residents - Hispanic](https://vital-signs-bniajfi.hub.arcgis.com/datasets/percent-of-residents-hispanic-1) - This dataset shows the percentage of residents who identify their ethnicity as Hispanic in each Baltimore City neighborhood.

## Data Analysis
### Initial Findings  
<img width="673" alt="Screen Shot 2020-12-17 at 17 53 37" src="https://user-images.githubusercontent.com/70663111/102553410-cb95ea00-4090-11eb-8cc3-276127f86eb3.png">   

The figure above reinforces our background research for our problem statement. In the past four years, teen birth rate has been declining in every region of Baltimore City. Notably, the Northwest region of Baltimore City experienced a -83.5% decline in teen birth rates over 2015-2018. However, this bar chart also shows the dichotomy of percent change between the regions. Not every region was as successful as the Northwest region in reducing teen birth rate. For example, the Southeast region experienced the least percent change decline in those years. Although teen birth rates have been declining due to the initiatives in place, there is room for improvement.


### Linear Regression
<img width="564" alt="Screen Shot 2020-12-17 at 17 54 25" src="https://user-images.githubusercontent.com/70663111/102553481-e7998b80-4090-11eb-88b1-1004f9b96813.png">   

The equation indicated by the linear regression analysis summary is: 
<img width="564" alt="Screen Shot 2020-12-17 at 17 55 23" src="https://user-images.githubusercontent.com/70663111/102553561-0ac43b00-4091-11eb-8da3-1ca54241f4c5.png">

This suggests that as the percentage of families living under the poverty line, percentage of AIAN or NHOPI populations, and percentage of Hispanic population increase, so does teen birth rate. In the figure above, you can easily see that all three factors are positively correlated with teen birth rate (Figure 4). The percentage of Hispanic population has an especially high correlation coefficient, which indicates that it is doing a better job of explaining the outcome and has a greater effect on teen birth rate compared to the other two factors.

<img width="675" alt="Screen Shot 2020-12-17 at 17 55 59" src="https://user-images.githubusercontent.com/70663111/102553613-1fa0ce80-4091-11eb-8331-0ef5aa03592d.png">

The R-squared value is 0.4854415, which means that about 48.5% of the data can be predicted with the model. The regression model also had a low F-significance value of 1.7994E-07, which indicates that these factors matter for the end model. All factors also have p-values of less than 0.05, which means that they are significant in predicting the outcome (Table 1).


### Cluster Analysis
<img width="632" alt="Screen Shot 2020-12-17 at 17 56 48" src="https://user-images.githubusercontent.com/70663111/102553681-3d6e3380-4091-11eb-8446-a6fd2551d415.png">

This suggests that each of the three different cluster groups anchored as 1, 2, and 3 is represented by Greenmount East, Northwood, Brooklyn/Curtis Bay/ Hawkins. Group 1 has a slightly lower than average teen birth rate, a much higher than average home below poverty line rate, a much lower percent of Hispanic or H&AIAN&NHOPI  minority residence rate. Group 2 has an extremely lower than average teen birth rate, an extremely less than average home below poverty line rate, a less than average residence of Hispanic or Asian or H&AIAN&NHOPI minority. Group 3 has an extremely high teen birth rate, a high less than average home below poverty line rate, and a lot more residents of Hispanic and H&AIAN&NHOPI  minorities. 

<img width="583" alt="Screen Shot 2020-12-17 at 17 57 09" src="https://user-images.githubusercontent.com/70663111/102553702-4959f580-4091-11eb-927b-2b308b5d6b9c.png">

<img width="630" alt="Screen Shot 2020-12-17 at 17 57 32" src="https://user-images.githubusercontent.com/70663111/102553734-57a81180-4091-11eb-8e9b-a99ba262e718.png">
<img width="704" alt="Screen Shot 2020-12-17 at 17 58 35" src="https://user-images.githubusercontent.com/70663111/102553825-7d351b00-4091-11eb-90b8-daf78404965f.png">



## Recommendation
The linear regression suggests a significant positive relationship between the factors and teen birth rate. The correlation coefficient calculations indicate that Hispanic, AIAN, and NHOPI ethnicities and low income are positively correlated with the outcome. This means that Baltimore City should focus their initiatives on reducing teen birth rates among minority populations (specifically Hispanic, AIAN, and NHOPI) and low income families. Baltimore City should also focus their efforts in regions that have seen a smaller reduction in teen birth rates, such as the Southeast, North, and West Baltimore regions.

The results of the cluster analysis shows that 81% of the counties in Baltimore do not have serious problems with teenage birth. Among the 81%, 37% (Group 2) have significantly more families above poverty lines and significantly less teenage birth rate. Sharing relatively similar Hispanic/ non Hispanic/Black minority diversity, Group 1 and Group 2 also share relatively close teenage birth rates (lower than average) despite their home under poverty rate has a great difference. On the other hand, Group 3 has a similar home under poverty rate to Group 1, but this does not stop them from having extremely high teenage birth rates. They are also the only group having significantly more Hispanic and non-Hispanic/Black residency. 

This leads to the conclusion that in Baltimore, although the teenage birth rate does not occur with a low home below poverty line rate,  teenage birth rates occur more with racially-determined factors rather than family income level. 

### Improving Baltimore City’s Teen Pregnancy Prevention Initiative (TPPI) 

We believe that the best way to address the issue of teen births in Baltimore is to build on the already existing initiative. Government employees and the Baltimore community are already familiar with this initiative, so it would not make sense to create a new one. Based on our analysis, we recommend improving TPPI in the following ways:

Targeted initiatives: focus more on minority races (especially Hispanic, AIAN, and NHOPI females) and low income populations
Offer education for parents of at-risk teens to talk about safe sex, contraception, and pregnancy planning
Make the Teen Pregnancy Prevention Task Force and Youth Advisory Council more diverse
Offer sex education and pregnancy information in ethnic minority native languages
Expand the social marketing campaign

At the moment, TPPI’s strategy addresses the general population and does not really focus on specific at-risk populations aside from foster care youths. Since Hispanic, AIAN, NHOPI, and low income were significant factors in the outcome, with Hispanic race being the highest correlated with teen birth rate, we believe that TPPI should target these at-risk groups. 

As mentioned in the problem statement, a child of a teen parent often experiences teen pregnancies themselves. Since our analysis points to Hispanic, AIAN, NHOPI, and low income populations as significant at-risk groups, we recommend providing education for parents within these groups. This education will teach parents how to communicate with their child(ren) about safe sex, contraception, and pregnancy planning. This way, parents will get accurate, important information on this topic.

[Research](https://govinfo.library.unt.edu/hcquality/meetings/mar12/papch08.htm.) has shown that focusing initiatives on at-risk populations allows for better and more effective results. By targeting the at-risk populations explored in this analysis, Baltimore City would be able to decrease the teen birth rate more quickly and efficiently.

Another way to improve TPPI is to make the task force and council more diverse. This way, the Baltimore community would get better and more accurate support and recommendations. One thing to note about working with and supporting ethnic minorities is that they often have different experiences from other ethnicities and may be more comfortable speaking, reading, and writing in their native language. By diversifying the task force and council, TPPI would be more equipped to handle different scenarios and would be more prepared to offer more services. For example, including Spanish speaking members in the task force could help with reaching out to Hispanic individuals.

Along the same line, we also recommend diversifying TPPI’s social marketing campaign. We would recommend expanding the campaign to target the at-risk groups discussed in this analysis. For example, if AIAN individuals are more likely to join certain FaceBook groups, TPPI could partner with those groups to increase awareness on information about sexual health and teen pregnancy and births. TPPI should also consider expanding their campaign onto ehealth and m-health platforms to increase exposure. 75% of consumers believe that technology is essential to managing health, and [48%](https://liquid-state.com/mhealth-apps-market-snapshot/.) of healthcare consumers are using m-health apps. These numbers continue to rise year-by-year. Additionally, TPPI should campaign in multiple languages to increase comprehension and awareness in ethnic minority communities.

From 2010 to 2015, CDC’s federal Office of Adolescent Health evaluated the effectiveness of interventions that focus on at-risk groups like the ones discussed in this analysis. [These interventions](https://www.cdc.gov/teenpregnancy/practitioner-tools-resources/diverse-communities.html.) increased awareness about community factors that are positively linked to teen birth rates and offered culturally and linguistically tailored educational programs. This program is very similar to the changes we recommend for TPPI. [Their subsequent study](https://pubmed.ncbi.nlm.nih.gov/27913658/.) confirmed the effectiveness of their approach.

### Improving Healthy Teens & Young Adults Clinic Accessibility (HTYA) 
After doing further research into this program in, we believe that it could be improved with two strategies: increasing campaigns and decreasing barrier to utilize. This program is open to the general public, but it could also be more well-informed to at-risk groups with brochures or [instagram feeds](https://www.classy.org/blog/instagram-tips-modern-nonprofit/.). Online and offline in the community campaigns can help more teens know about the help they could get. 

The program’s [pricing and insurance policy](https://health.baltimorecity.gov/node/223.) can also be clearer and more open with a quote calculator, which could reduce the economic barriers for at-risk groups seeking help. It is also a good idea to add finder of a Healthy Teens & Young Adults clinic system that allows helo seeker to find the neareast clinic, make appointments, and read experience from other help seekers. This could not only decrease their pressure of being in a clinic to talk about teen pregnancy, but also find a community of people sharing the same experience that could possibly support them.

### Initiatives
Our recommendations can be implemented relatively quickly at a low cost. Diversifying the task force, council, and social marketing campaign can be done by implementing more diverse hiring and recruiting practices and providing training to members so they are more equipped to deal with at-risk groups. Training should take up to three months and would cost up to $2,000 per employee. Therefore, we expect to be able to start implementing these initiatives in Q2 of 2021. This is a very cost-effective method of improving the program because of the social and economic implications of reducing teen birth rates.
To evaluate the efficacy of our recommendation, annual data analysis should be conducted to look at the teen birth rate in each of the at-risk groups. Based on our analysis, we predict that the teen birth rate will decrease, which will benefit Baltimore City’s social and economic standing in the future. This will also help to reduce the generational pattern of teen birth and its consequences in at-risk groups.

### Further Research
About 48.5% of the data can be predicted with the linear regression model, which means that about 51.5% of the data can be predicted with other factors not included in this analysis. Further analysis could consider looking at whether the teen is living in a single or dual parent household, level of communication between the teen and parents/guardians, amount of available and accurate sexual and reproductive health information in the community, average age of puberty, and average age of first relationship or sexual encounter.


## Appendix
### Initial Findings
Step-by-step creation of the visualization: Google Collaboratory

### Step-by-Step Excel Analysis
- Linear Regression 
1. Dataset was downloaded from Google Collaboratory (linked above)
2. Regression function of the Data Analysis tool was used to summarize the output of the simple linear regression with outcome (y input)  being “teenbir17” and factors (x input) being “hhpov17”, “ppac17”, and “phisp17”
3. Correlation function of the Data Analysis tool was used to calculate correlation coefficients between the outcome and each of the factors

- Cluster Analysis
1. Dataset cleaned and downloaded from Google Collaboratory
2. Cluster analysis from Solver tool was used to group data into three clusters based on “teenbir17”, “hhpov17”, “ppac17”, and “phisp17”
3. Sort data by anchor number to find counties that belonged to each group
4. Use “COUNTIF” to count the numbers of each group and graph into a pie graph


