## Step 1: Selecting the Dataviz:
This dataviz selected from the US Annual Energy Review (2011) tries depicting US energy mix by sources of energy and sector wise comsumption of each source. The information given here is important for a wide variety of audiences as energy mix is considered backbone of economic progress and most of the people find it an interesting topic to read. However, as we expect the topic to be appealing for a range of stakeholders, this dataviz, paradoxically, has made it difficult to understand. It seems a hodgepodge of data, colors, and arrows. Resultantly, I found it fascinating to apply good chart methods to present the same information with more clarity. 

![](https://user-images.githubusercontent.com/116416753/202289254-cd3aa470-328f-4150-b39b-7cd3ae971f33.jpg)
Reference: Total energy annual data - U.S. energy information administration (EIA). Total Energy Annual Data - U.S. Energy Information Administration (EIA). (n.d.). Retrieved November 16, 2022, from https://www.eia.gov/totalenergy/data/annual/ 

# Step 2: Critique of Data Visulailzation
First of all, I started off finding the common issues found in this viz. I applied good chart matrix for evaluating this viz and found some key issues of design execution and contextual awareness. As per my understanding, in terms of design execution, the focus of chart is just to put all availabe information realted to energy mix, sectoral consumption and the breakups of how much each source contributes to differnet sectors and conversely, how much each sector derives from each source of energy. So, too many topics in one chart. In terms of contextual awareness, it is quite confusing that what the presenter wants to convey and it seems that little consideration to extending facilitation to reader has been made in this chart. 

Furter, the title is clear and simple and just by having a glance of title, one expects a simple pie chart or bar chart giving breakdown of energy consumption by source and sector; however, in first glance one gets confused regarding what the chart is trying to convey because it is very busy. A lot of data is being presented in this viz which is working well - only if one has a lot of time to understand what is being presented here otherwise in first impression one gets confused. The idea of staked bar chart seems working well but the basis of calculation of percentages, putting sector and sources together and adding unnecessary arrows to further add some information have made the overall chart quite difficult to process. Further, the use of colors is random, unnecessary, with no association or utility, and there are too many colors. Further, the staked bars depicting sources and sectors are inconsistent i.e., one moving from low to high and other is different from the first. I will prefer two separate bar charts for sources and sectors along with labels while using percentages only and not using too much colors.

Also, keeping in view the topic and the report, the primary audience can broadly be anyone who is interested in knowing about the energy consumption mix of USA. However, it seems that this visualization is prepared only for the researchers working in energy domain as they can spend the time required to unearth what is going on in this dataviz just because too much information is being conveyed through this chart and a common user might just end up avoiding it.  

For critical analysis of the chart, I used techniques mentioned in the Good Charts and Data Visualization Effectiveness Profile books. This method of evaluating the data visualization is effective and almost all the necessary ingredients of good chart design are incorporated in it.  However, it is a little more subjective and depends much on readers' interpretation. However, the Good Charts Methods approach is more structurally designed and requires rumination by the reader. In comparison, where Stephen Few's method of Data Visulaization gives a general approach to evaluate the data visualization, the Good Charts Method specifically gives a framework to think and plan about the type of visualization that can be used for a specific set of data. For this viz, I selected declarative and data-driven approach to plan for the type of chart needed for this visualization. This viz can be made intuitive just by focusing on one topic at a time, choosing bar chart to give clear comparison of categories, using same color of bars to reduce fight for attention effect, and presenting everything in terms of percentages so that reader does not get confused between numbers and their percentages.

# Step 3: Sketching for Clarity
Building upon the analysis, I came up with an idea to sketch two separate staked bar charts for each for the sources of energy and their sector wise consumption. My focus was to reduce the business and make the charts easy to follow for the reader. The sketches I drew for the two topics are as follows: 
In this chart, I used staked bar chart to show percentage of energy consumption in each sector in bars and then within each bar, percentage division by the source of energy is presented.  
![Assignment 3~4](https://user-images.githubusercontent.com/116416753/202303466-a1ead13d-2dc8-4616-9993-f32b58d799a3.jpg)

In this chart, percentage comparison of each source of energy is presented and further within each bar, sector wise consumption is given and each sector is given a specific color which is consistent across all the bars.   
![Assignment 3~4(1)](https://user-images.githubusercontent.com/116416753/202303481-d6c438cd-6240-4027-9cfb-529d2c7f4265.jpg)


# Step 4: Test the Solution
I showed these two cahrts and the original chart to two users for feedback. Their responses to each question are as follows:

## Feedback Prticipant 1:

**- Can you tell me what you think this is?**

These charts are showing energy realted information for the year 2011. 

**- Can you describe to me what this is telling you?**

One is for sources of energy, and the other is for sectorwise consumption.

**- Is there anything you find surprising or confusing?**

I do understand that each color within staked bar charts repersent information coded in the legend and I can compare them but I am not getting any idea about the size represented by that code. But, it is understandable and easy to follow as compared to the original chart you showed me. 

**- Who do you think is the intended audience for this?**

Anyone who is intrested in knowing about the energy mix can be the intended audience.

**- Is there anything you would change or do differently?**

I would prefer presenting this same info in a pie chart.


## Feedback Participant 2: 

**- Can you tell me what you think this is?**

Bar charts for energy mix.

**- Can you describe to me what this is telling you?**

I can see these comparing different sources and sectors of energy usage.

**- Is there anything you find surprising or confusing?**

No

**- Who do you think is the intended audience for this?**

It may be for anyone who is interested in getting information related to energy mix.

**- Is there anything you would change or do differently?**

I would love to see percentages within the bars for each different categories.  

# Step 5: My Solution

In light of the feedback, I tried incorporating percentages within the staked bars, however, I could not find proper way to divide the percentages into further percentages. So, I split up these into two separate bar charts and limited myself to presenting one topic in one chart. For presenting the relationship between sectors and sources of energy, I came up with an idea of using Sankey diagram.  Further, I also got feedback from my peers and they found these three charts better. However, I found a challenge here and could not find any solution for that. The issue is that in the Sankey diagram, I successfully created data link from sources to sectors; however, could not create link when we move from sectors to sources and did not find any option in Flourish as well for these two sided values. So, I think, I can make two sankey diagrams each for sources and sectors of energy consumption. Also, the issue with Sankey is when we print the picture, the dynamic nature of diagram gets affected and we cannot get the information that we want to present through this diagram in printed picture.

All the three charts became easy to follow as can be seen here: 

<div class="flourish-embed flourish-chart" data-src="visualisation/11821278"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


<div class="flourish-embed flourish-chart" data-src="visualisation/11821355"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


<div class="flourish-embed flourish-sankey" data-src="visualisation/11821394"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

