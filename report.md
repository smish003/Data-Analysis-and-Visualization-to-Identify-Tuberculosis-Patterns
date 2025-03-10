# CS625-HW8
## Submitted By: Swati Mishra

Due: Thursday, December 8, 2022 by 11:59pm

# <ins>Global Tuberculosis Programme </ins>

Click on the hyperlink to access the earlier part of the exploration of data analysis.[HW-6](https://github.com/odu-cs625-datavis/fall22-hw6-smish003/blob/master/report.md)

Click on the hyperlink to access the earlier part of the exploration of data analysis.[HW-7](https://github.com/odu-cs625-datavis/hw7---questions-smish003/blob/master/report.md)

For my project, I've chosen the WHO's Global Tuberculosis Programme, which strives for a TB-free world with no TB-related deaths, illnesses, or suffering. The team's goal is to lead and coordinate the worldwide campaign to end the TB epidemic via multisectoral action, innovation, and universal access to people-centered prevention and care.
The provided dataset consist of two parts as shown below:
WHO TB burden estimates
Data provided by countries and territories

## WHO TB Burden Estimates:

This includes estimates from the WHO for TB incidence, mortality, case fatality ratio, treatment coverage (previously known as case detection rate), and latent TB infection among children under the age of five. It also includes breakdowns by age, sex, risk factors, HIV status, and rifampicin resistance.
The following datasets are included:
* [WHO TB burden estimates [>1Mb]](https://extranet.who.int/tme/generateCSV.asp?ds=estimates)
* [WHO TB incidence estimates disaggregated by age group, sex and risk factor [>0.5Mb]](https://extranet.who.int/tme/generateCSV.asp?ds=estimates_age_sex)
* [WHO MDR/RR-TB burden estimates](https://extranet.who.int/tme/generateCSV.asp?ds=mdr_rr_estimates)
* [WHO latent TB infection estimates for 2021](https://extranet.who.int/tme/generateCSV.asp?ds=ltbi_estimates)


## Data Provided By Countries and Territories:

This included data from all countries and Territoires and are updated on regular basis.It includes the following datasets:

* [Case notifications [>2Mb]](https://extranet.who.int/tme/generateCSV.asp?ds=notifications)
* [Drug resistance testing in pulmonary bacteriologically confirmed TB patients since 2017](https://extranet.who.int/tme/generateCSV.asp?ds=dr_surveillance)
* [Zoonotic TB in 2018](https://extranet.who.int/tme/generateCSV.asp?ds=zoonotic)
* [Laboratory diagnostic services](https://extranet.who.int/tme/generateCSV.asp?ds=labs)
* [Non-routine surveillance of HIV prevalence in TB patients](https://extranet.who.int/tme/generateCSV.asp?ds=tbhivnonroutinesurv)
* [Treatment outcomes [>1Mb]](https://extranet.who.int/tme/generateCSV.asp?ds=outcomes)
* [Screening and TB preventive treatment for contacts of TB patients](https://extranet.who.int/tme/generateCSV.asp?ds=contact_tpt)
* [TB policies and services in 2021](https://extranet.who.int/tme/generateCSV.asp?ds=policies)
* [Community engagement activities for TB](https://extranet.who.int/tme/generateCSV.asp?ds=community)
* [Budgets for TB since fiscal year 2018](https://extranet.who.int/tme/generateCSV.asp?ds=budget)
* [Expenditure and utilization of health services for TB since fiscal year 2017](https://extranet.who.int/tme/generateCSV.asp?ds=expenditure_utilisation)

I'll be selecting few  datasets from both categories (*i.e., WHO TB Burden Estimates and Data Provided By Countries and Territories) out of the total collection of datasets mentioned above.*)

To track the transmission of disease, it is quite interesting to analyze this dataset. In addition, I discovered a [report](https://www.who.int/news-room/fact-sheets/detail/tuberculosis) published by the WHO on there website on "*27th October,2022*" that reports that 1.6 million individuals worldwide passed away from TB in 2021. (including 187 000 people with HIV). TB is the second most common infectious killer after COVID-19 and the 13th leading cause of death globally.

# Part-2 Exploratory Data Analysis
## Data Provided By Countries and Territories:

In this section I choosed the budget dataset (Budgets for TB since fiscal year 2018).

Additionally, I cleaned this dataset using open refine in my previous assignment, and following that cleaning, the following questions are possible:

* How the different types of budgets are been distributed(i.e. Required Budget and Expected Budget)

Additonally, it will be interesting to validated how its utilize which may require another dataset for analysis.

Furthermore, I discovered additional dataset to validate how the budget is used in various segments.In order to do that, I'll be using the dataset **"Expenditure and utilization of health services for TB since fiscal year 2017"** .

**Note:** *Please refer to the Steps section in [HW-7](https://github.com/odu-cs625-datavis/hw7---questions-smish003/blob/master/report.md) for details on the process being taken to clean the dataset.*

# Exploratory Analysis

Below is the exploratory analysis done for both the dataset:

### Analysis of (Budgets for TB since fiscal year 2018):

The following facts were discovered through data exploration, as illustrated below:

![image](https://user-images.githubusercontent.com/89666159/206514669-4dc27e5a-5ee3-4879-9738-549ad8ce5c5b.png)

The above graphs display the average drug cost per patient for various TB treatments in US dollars ($). 

The above demonstrates that the majority of the drug cost per patients was for Pre-XDR/XDR-TB Treatment in Africa.On the otherhand,in the Eastern Mediterian region Drug Susceptible costed higher w.r.t other treatment.Addiotnally, in Western Pacific region for MDR-TB treatment the average cost of drug per patient was higher than other treatments.
    It was also interesting to observe that the average cost of drugs per patient in various TB treatments in Europe and South-East Asia was quite low.
    
 ![image](https://user-images.githubusercontent.com/89666159/204386526-bebd962a-17eb-4dae-93e9-23dd7a617466.png)

The above graphs display the Number of patients expected to start TB treatment in different categories based on Region.
By looking at the above graph below key points are observed:
* Majority of the patients are expected to start there TB Preventive treatment.
* Very few number of patient are expected to start MDR-TB Treatment and Pre-XDR/XDR-TB Treatment.
* Lots of patient even opted for Drug-Susceptible TB treatment.
* It can also be seen from the graph that Africa and South-East Asia region have majority of patients to start TB treatment.

![image](https://user-images.githubusercontent.com/89666159/206515587-9d677509-90d8-4b75-81b5-35461dfb6400.png)

The above graphs display Different Programme Cost  in different region(US Dollars($)).

The key findings from the graphs are listed below:
* The Buget and Expected funding for the the listed programme ***(i.e. National TB Programme Staff and Treat Drug-Sussceptible)***  are shown.
* Europe has the highest budget and expected funding needed for different programme w.r.t other regions.


<img width="811" alt="image" src="https://user-images.githubusercontent.com/89666159/204389530-f68ab75c-8629-4d3f-9849-c3b1a235f614.png">

The table above shows the current budget in various categories (in US dollars ($)) based on various regions.

<img width="808" alt="image" src="https://user-images.githubusercontent.com/89666159/204389480-43939e4f-38ed-4c17-a21d-cc7cceda992c.png">

The table above shows the Expected Funding in different categories(US Dollars($)) based on various regions.


### Analysis of (Expenditure and utilization of health services for TB since fiscal year 2017):

Below graph demonstrate the National TB Programme Staff Cost(Actual Expenditure and Fund Received) in Different Region(US Dollars($))

![image](https://user-images.githubusercontent.com/89666159/204389870-264b16fa-6b9b-4ddb-8fe9-be16ec52ab24.png)

Additionally, by examining the graph, it can be seen that the America has the lowest National TB Program Staff Cost, while the European region has the most.


Below graph demonstrate the Programme costs to treat drug-susceptible TB in Different Region(US Dollars($))

![image](https://user-images.githubusercontent.com/89666159/204390580-c0956239-e873-4e12-9b46-a3f6992cb81d.png)

South-East Asia has the highest actual spending, followed by the Western Pacific and Africa, while Europe has the lowest program cost to treat drug-susceptible TB, as can be seen from the graph above.
In contrast, the Western Pacific region received the most funding for the treatment of drug-susceptible TB, followed by Europe, South-East Asia, and Africa, while the Eastern Mediterranean received the least.

Below graph facilitates the Facilites used if MDR-TB patients are hospitalized.

![image](https://user-images.githubusercontent.com/89666159/204391775-6d3686f1-5fd0-4f84-8512-ceb8a311c0b8.png)

By examining the above graph, it is seen that the majority of MDR-TB patients are admitted to tertiary-level hospitals, with the hospitalization rate for these facilities being greater in the American region.

Graph represnting Typical number of visits to a health facility after diagnosis for patients opting different Treatment .

![image](https://user-images.githubusercontent.com/89666159/206516045-a0390ca2-e495-4a7e-a975-2b2bff0a8d59.png)

The aforementioned graph demonstrated that MDR-TB/XDR-TB treatment accounts for the majority of patient visits to medical facilities following diagnosis.Additionally, the majority of patient visits for MDR-TB/XDR-TB treatment are in the American region.

Actual Expenditure in different Categories Based on Regions:

![image](https://user-images.githubusercontent.com/89666159/204392796-0983895c-a2f4-484f-bf52-159ce1fcfb9f.png)

Funding Received in different Categories Based on Regions

![image](https://user-images.githubusercontent.com/89666159/204392925-43947133-e533-47ac-8bc9-f22d51a5b074.png)


After looking at the above cleaned dataset below questions are possible:

* What are the cost of different Programme (including Budget,Expected Funding,Acutual Expenditure and Funds Received)?
* What are the expenses in different categories?
* Number of patient expected to start MDR-TB treatment w.r.t to the facilities they choose.


## Drafted Charts:

The charts that can be used to create the final charts are shown below in draft form.

![1-draft](https://user-images.githubusercontent.com/89666159/204636483-b6afb346-0fd3-4c5d-b37f-80f5076804ca.jpeg)

***The above graph shows the number of cases in relation to various geographic regions and the risk factors associated to them.***

![2-draft](https://user-images.githubusercontent.com/89666159/204636485-76690e48-be33-4ab7-b454-0a8c79906d13.jpeg)

***The graph above displays several estimations of the total population based on various regions.***

![4-draft](https://user-images.githubusercontent.com/89666159/204636489-3a54b757-e4c2-4cd2-b965-ae856cce979d.jpeg)

***The image above provides an illustration of how much each program costs in each region.***

![3-draft](https://user-images.githubusercontent.com/89666159/204636488-2939ba7d-b4ba-4f8e-9f0d-abd20f1f6c53.jpeg)

***The graph above shows the anticipated number of patients undergoing MDR-TB treatment as well as the facilities each patient chooses in each region.***

## Final Question:

Following the completion of the data investigation in the previous assignment, I developed the following questions:

* What are the risk factors involved in TB case infections with respect to different region?
* What is the low,high,best estimate for each country with respect to the total poulation?
* What are the cost of different Programme (including Budget,Expected Funding,Acutual Expenditure and Funds Received)?
* Number of patient expected to start MDR-TB treatment w.r.t to the facilities they choose.

By developing a Grouped Bar, Stacked Bar chart, the above questions can be represented graphically.

The data analysis for this project will also be displayed in a Tableau dashboard that I intend to build.

## Refined Charts

To generate the final chart for this part and provide the answers to the questions above, I used Tableau.

* What are the risk factors involved in TB case infections with respect to different region?

![image](https://user-images.githubusercontent.com/89666159/206513621-471b1d0b-d7ba-4a6d-abc1-ac15815d3da9.png)

***It is clear from the graph above that the majority of the patients consumes alcohol, which is considered  a high risk of contracting tuberculosis.***

* What is the low,high,best estimate for each region with respect to the total poulation?

![image](https://user-images.githubusercontent.com/89666159/206514109-134e4259-e513-4a67-bce8-aaf012f8ab25.png)

***The graph above shows various estimations of the total population depending on various regions.***

* What are the cost of different Programme (including Budget,Expected Funding,Acutual Expenditure and Funds Received)?

![image](https://user-images.githubusercontent.com/89666159/206534369-ac67635f-a7e8-4a6f-8af7-9d09b684092a.png)

* The following conclusion can be drawn from the graph above:
    * The Western Pacific area has the most budget to treat drug-susceptible patients.Additionally, it is clear that less funding than expected is being allocated to treat drug-susceptible patients.
    * With regard to the Drug-Susceptible Program, the European Union region has the highest budget for national TB program staff, and it is also planned that the anticipated financing needs for the program staff is satisfied.
    * In comparison to other regions, the Western Pacific region has a greater actual cost of treating drug-sensitive tuberculosis, and the funds received to do so is lower.
    * Comparing the Eastern Mediterranean region to other regions, it can be noted that the actual expense for national TB program staff is higher, and the funding received for the same is less than the actual expenditure.

**Note:** ***The graph's average line band displays the average cost for each program (i.e., to treat Drug-Susceptible TB nd Nation TB Programme Staff) in each region.***

* Number of patient expected to start MDR-TB treatment w.r.t to the facilities they choose.

![image](https://user-images.githubusercontent.com/89666159/206515136-01d535c4-7967-4b8b-8b1e-d67bac6f3357.png)

   ***From the above graph it can be seen that most of the patient*** *(i.e. 312,405)* ***opted for Tertiary-Level Hospital facility for MDR-Tb treatment in Shouth-East asia***
   
  ## Design Decision
The following choices were made from a designing standpoint for the project:
* I initially decided to use open refine to clean the dataset.
* The data was then imported into Tableau and merged to create the visualizations.
* Exploratory analysis was been carried out to analyse the data.
* Additionally, in order to provide answers to the aforementioned final questions, I created graphs utilizing bar charts,stacked bar charts and grouped bar chart.
* In order to illustrate the analysis, I also created  dasboards and integrated them all into a story.

**Bar Chart:** *In a bar chart, numerical levels of a classified feature are represented by bars. Values are plotted on one axis of the chart, and levels are plotted on the other. One bar is claimed by each categorical value, and the value of each bar determines the length of the bar. To make value comparisons simple, bars are drawn on a similar baseline.*

**Stacked-Bar Chart:** *The regular bar chart is extended to look at numerical values across two categorical variables via the stacked bar chart. Each sub-bar that makes up a normal bar chart represents a level of the second categorical variable, and they are all stacked on top of one another.*

**Grouped Bar Chart:** *The bar chart is expanded into a grouped bar chart, which instead of using just one categorical variable, plots numerical values for levels of two. For levels of a single categorical variable, bars are grouped by position, with color designating the secondary category level within each group.*
 
## Dashboards
A dashboard is a tool for condensing different kinds of visual data. Typically, a dashboard's purpose is to present various, linked facts in an easy-to-understand style.

#### Global Tuberculosis case detection rate and risk factor involved in  different Region

![image](https://user-images.githubusercontent.com/89666159/206544851-17236474-3c51-4034-9a76-db72cb6d18cf.png)

#### Estimates and Budget facilitated to diiferent categories based on Region

<img width="960" alt="dashboard-2" src="https://user-images.githubusercontent.com/89666159/206545425-b216c832-64aa-4bb0-bad7-c0d3e7cab2df.png">

#### Programme and Treatment Cost

<img width="960" alt="dashbpard-3" src="https://user-images.githubusercontent.com/89666159/206546426-f22cb219-2300-4298-9efb-20d8a1bc8260.png">

### Facilites and Diagnosis Usage

<img width="960" alt="dashbpard-4" src="https://user-images.githubusercontent.com/89666159/206546479-4d53c3e0-d631-4be4-8b80-3a243fea626d.png">

### Programme Cost
<img width="960" alt="dashobard-4 1" src="https://user-images.githubusercontent.com/89666159/206547516-fa0f4942-08fe-49ef-8213-0fb9206e4985.png">

### Different Categories costing based on Region

<img width="960" alt="dashbpard-5" src="https://user-images.githubusercontent.com/89666159/206547546-d76a69df-dfba-46c2-baae-9dc531d11954.png">

### Different types of Costing based on Programme and Region

<img width="960" alt="dashboard-6" src="https://user-images.githubusercontent.com/89666159/206547570-26b97c5d-e291-4d7a-925c-01ba1db36707.png">


## Story
A Tableau story is a collection of graphics that collectively tell a story. Stories are a potent tool for conveying data narratives, giving context, illustrating how choices affect outcomes, or just making a strong argument.

<img width="960" alt="story-1" src="https://user-images.githubusercontent.com/89666159/206552269-3f65344e-1d27-443a-97d8-a81153c3cd3e.png">

  
<img width="960" alt="Story-2" src="https://user-images.githubusercontent.com/89666159/206552283-6a17c2a2-8175-4b26-b0c6-06b73bcc2a8a.png">

**The visualization principles from the semester that were incorporated into the final visualization are listed below:**
* Selecting the appropriate visualization format for the task.
* Effective data ordering principles.
* Analyzing the dataset for patterns.
* Picking the appropriate color for visualization
* Simple viewpoints with thorough captions
* Effective use of geometry in data display.
* Principle of effectiveness.

 ## Final Thoughts
Data cleaning and exploratory data analysis took up the most of the project's working hours. Data cleaning and exploratory data analysis for all four datasets took, in my estimation, around eight hours. The final chart's sketch took another two hours to draft, and the final visaulization took, on average, about three to four hours to complete. To add to that, I put in two hours to the complete project's dashboard and story.

In my opinion, dividing the project into three smaller assignments rather than one large project assignment was beneficial. As a result, you have enough time to investigate and analyze your data and adequate time to concentrate on the desired work during each phase of the assignment. Additionally, I found it interesting to spend more time on the topic . In order to learn more about it, explore new ideas, and put what I had learned in class into practice.

## Presentation and Tableau Dashbaord Links

Below is the tableau dashbaord links for reference:

https://prod-useast-a.online.tableau.com/#/site/smish003/workbooks/784022?:origin=card_share_link

https://prod-useast-a.online.tableau.com/#/site/smish003/workbooks/784148?:origin=card_share_link

Below is the presentation link for the reference:

https://drive.google.com/file/d/1TUHP2LzbpEW55SQJbfxfcxXxHrZkWqKH/view?usp=sharing

 ## References
 * https://www.who.int/teams/global-tuberculosis-programme/data
 * https://www.who.int/news-room/fact-sheets/detail/tuberculosis
 * https://r4ds.had.co.nz/exploratory-data-analysis.html
 


