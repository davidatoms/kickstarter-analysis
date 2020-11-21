# An Analysis of Kickstarter Campaigns

Performing analysis on Kickstarter data to uncover trends.

Written by David Adams

November 21, 2020

## Overview
### Background
  Louise's play _Fever_ came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, we will visualize campaign outcomes based on their launch dates and their funding goals. This is important to understand her data and further her fundraising efforts. For example, she can use this data when pitching to theaters or other investors about the strength of her idea with data points to support her dream of making _Fever_ a real-life play on the stage.
  
  Kickstarter is a crowdsourcing platform that connects creators with capital and audience. The data the application connects is used to understand campaign performance and further used to draw potential conclusions as to why or why not campaigns succeed or fail given the information provided from the creator. It is a platform for those with ideas to gain capital and audience. It is the first theater that the idea of Louise's play will find its first external engagement from potential customers and viewers.
  
  
### Purpose

  The purpose of this report is to compare Louise's Kickstarter campaign to similar campaigns on the crowdfunding platform given the launch date and funding goals. Her project gained real traction and now we need to determine how the traction was gained, how that traction compares to other campaigns--both similar and different from hers, and what other variables could influence a quick and successful campaign on the Kickstarter crowdsourcing application.
  
  Furthermore, this is the first step to understanding key metrics that drive success of her play. These metrics of fundraising and engagement should be able to help Louise visualize the actions taken by others in regards to her idea for a play. Similar data should also be framed in future events to help her understand the variables affecting the success of bringing her play to life.

## Analysis and Challenges

  The _Fever_ spread quickly--the play was hot. The data below shows how this play compares to other campaigns in theater and in general based on campaign start dates. With further information on attendance at plays given different months, the interest in attending plays after seeing it online, and how many people saw the play, we could could conclude how successful her raise was with more confidence and accuracy.
  
  Challenges include not knowing when Louise started her campaign and other data from her campaign that could easily be put into the spreadsheet. By adding her data and highlighting it throughout all the analysis could stack it up next to the other campaigns. This could even be done by freezing the panes on the kickstarter worksheet to see exactly how it differs and is similar to the other campaigns given.
  
  The results contained herein show how I looked at the information in perspective with the information of Louise's campaign. 

### Analysis of Outcomes Based on Launch Date

![Theater Outcomes vs. Launch Date](https://github.com/davidcodescool/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

  Campaign start dates suggest months that are more likely to succeed. Summer seems to have the greatest chance of success for theater campaigns. I performed my analysis by looking at which months had the highest successful outcome count. Then I looked at how many successful campaigns there were total. I believe this helps better understand how successful campagins compare against each other and then how much they vary based on on failed during the same month.
  
  May and June had the highest count of successful outcomes. December was not a great month to start a campagin in theater. It was almost equally as likely to fail as it was to succeed in that month. Given this information, we can better understand which secondary information about the theater market I could include in another report about Louise's fundraiser on Kickstarter. 
  
  If I were to provide further data points to compare, I would look at data from theaters around the world and compare which dates were more popular. This may be different in a worldwide pandemic, but I think that would also provide information to bolster any conculsions explored from my report.

### Analysis of Outcomes Based on Goals

![Outcomes Based on Goals](https://github.com/davidcodescool/kickstarter-analysis/blob/main/outcome_based_on_goal.png)

  _Fever_ was successful at raising £4000. Louise's play fell in the mode. There are 932 other campaigns that wanted to raise between 1000 and 5000 currency units. Although Louise's project was in the mode, success rate for campaigns with this goal were 66%. That success rate is the second highest but not the first. Her goal likely attributed to the successful raise of her play.
  
  The play may have flopped had she attempted to raise more money. Chances of a successful raise go down when goal amounts increase. This inverse relationship shows us that the goal amount is indicates potential of success for any given project on Kickstarter. Louise can use this insight to further her fundraising goals say she decides to start a GoFundMe.

### Challenges and Difficulties Encountered

  The analysis of Outcomes Based on Launch Date and Outcomes Based on Goals were dervived from different styles of data visualization. Outcomes Based on Launch Date was also filtered more than the Outcomes Based on Goals. This meant that each analysis were not on the same lateral level. Any analysis on the outcomes based on goals included the whole scope of projects while the outcomes based on launch dates were only projects with the "theater" platform.
  
  Furthermore, the analysis of percentages is different than that of pure numeric outcomes. Outcomes based on launch date does not include the percentages of success, failed, and canceled while the Outcomes Based on Goal do. Similarly, I could look at the mode of each data set. This shows the most successful point in both situations. With that as a starting point, I also looked at the worst months. The approach to look at the greatest and smallest values frames the range of the data where all other data sits. 
  
   Writing this report was also difficult. My analysis seems more like observational comments on the data and I don't know if that is what is required. I also don't know if I should frame the two datasets on an equallateral level--meaning that when I analyze the data of theaters on launch dates, I'd like to also analyze  outcomes based on goals with the theater filter.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. The summer months are more likely to succeed than the winter months. If the creator needs more time to finish their project during a season, the creator must decide whether or not it would be worth it to wait for a favorable month.
    2. Any creator should feel confident in starting a theater campaign at any given time of the year. There is at least a 50% chance of successful fund raising. The worst month, given the data, would be to start a campaign in December.
    
- What can you conclude about the Outcomes based on Goals?
    1. Goals between 1000 and 4999 currency units were the most successful. Whether this be because of the size of the audience and their interest in the campaign or some other variable is limited by the dataset.
    2. It is important to set a fundraising goal that is attainable and sufficient for a project to be successful in recieving funds and attention.

- What are some limitations of this dataset?
    * Kickstarter is the marketplace on which all these campaigns live or die. This does not include a more traditional form of fund raising, word of mouth, or other forms of marketing. 
    * As times advance, older forms of entertainment like theater or musicals may change. The demographic of users on the application may not be as interested in certain categories of entertainment as those who do not use technology as often.
    * The data does not include any branding or positive brand reinforcement. Whether or not this affects the success of the data is also not included in the dataset. 
    
- What are some other possible tables and/or graphs that we could create?
    * I'd like to focus on the worst possible month to start a campaign. I'd like to see what the attributes of those successful plays were and how they compare to the successful campaigns in the 'hot' season. By doing this, I hope to uncover exactly which attributes of a certain campaign make it successful no matter the time of year.
