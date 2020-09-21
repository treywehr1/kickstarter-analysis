# Kickstarting with Excel
 An analysis of Kickstarter campaign data.
## Overview of Project
    Louise has ambitions to form a kickstarter to fund a play in the United States. Historical kickstarter data was collected and analyzed to determine potential campaign optimizations, while also determining what strategies could possibly limit campaign success. Criteria such as launch date of campaign, amount requsted (or goal) of campaign, descriptive statistics using succesful and failed US play data, and more was analyzed to supply louise with an inventory of information to formulate beneficial decisions for her own future campaign. 
### Purpose
  The purpose of this anlaysis is to generate quantifiable advantages and disadvantages of certain fundraising decisions when running a Kickstarter campaign. Specifically, this analysis was performed with Louise's US kickstarter campaign to fund a play in mind.
## General Analysis 
  Kickstarter data from 2009 to 2017 containing information such as 
   - Goal amounts 
   - Pledged amounts 
   - Timestamps of campaign initiation 
   - Whether the campaign was succesful, canceled, or failed
   were analyzed by organizing corresponding charts snd statstical analysis. This was accomplished by utilizing filters, Vlookups, and pivot charts in order to effectively format said data for various analytical endeavours.
   
### Analysis of Outcomes Based on Launch Date
  The attached line graph suggests a campaign launch for her play would be most effective in the early summer months of May or June. Another conclusion reached by the data/graph is that although there are generally less campaigns launched in the fall than in the summer, campaigns are significantly less succesful during this time.

![Imgur](https://imgur.com/ifQv6TY)


### Analysis of Outcomes Based on Goals
  Upon analysis of collected data via kickstarter campaigns from around the world, specifically the US and Great Britain - we were able to conclude that in order to optimize Louise's odds of successfully funding her US kickstarter, she should lower her goal amount closer to a more common goal of success. 
   - According to analysis, her plans for a $12,000.00 USD play campaign sits above the upper quartile + 1.5*IQR ($10,250.00 USD). 
   - In fact, of the 5 kickstarters for plays she's been specifically inspired by (Be Prepared, Checkpoint 22, etc.), the average goal sits at $2,100.00 USD - vastly under her expected $12,000.00 USD goal.
  
  The below graph also illustrates that outcomes based on goals suggest that a lower goal usually equates to a higher percentage of successful campaigns except for a slight increase in probability for plays 

![Imgur](https://imgur.com/JZZKOCy)


### Challenges and Difficulties Encountered
  Some challenges faced included 
  - Filtering in correct order so as to not preliminarily eliminate any required data. 
  - The formula containing the COUNTIF function for 'Outcomes Based on Goals' information was initially incorrectly utilized (=COUNTIFS(Kickstarter!D:D,">=1000",Kickstarter!F:F,"successful",Kickstarter!D:D,"<=4999",Kickstarter!R:R,"plays") was originally dictated as (=COUTNIFS(Kickstarter!D:D,">=999",Kickstarter!F:F,"successful",Kickstarter!D:D,"<=5000",Kickstarter!R:R,"plays") which yielded faulty results.
  
## Results
  Analysis of the provided Kickstarter data suggests that an early summer (May, June) launch date would establish Louise's campaign during a time with a historically higher volume of succesful campaigns. Should she decide to launch at another time of the year, especially from October to December, there is less historical succsess for campaigns launched at this time.
    
  

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?


