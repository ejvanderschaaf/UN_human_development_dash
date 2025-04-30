# UN_human_development_dash
This is a dashboard created using R shiny to explore education, income, and gender differences in the 10 most populous countries.

### Background

I found this dataset on kaggle. It comes from the UN Human Development Report and contains information about education, population size, income, and other characteristics of the nations of the world. One aspect of this data set that intrigued me was that it contained information concerning differences in gender across various metrics for individual countries. I wanted to investigate gender-based differences in education and how this might play into income. I was also curious about the more general relationship between income and education.

As it would be overwhelming to examine the data for all countries in a single dashboard, I decided to focus on the top ten most populous countries. I figured that this would give a good representation of the world's population.

My target audience are those concerned with the economic well-being of the world's population, especially those with an interest in gender equality. These may be people in positions of power or those crafting public policy. They may also be curious citizens. Perhaps these people have some knowledge of affairs in their own country but not how their nation compares with the rest of the world. They may be interested in general trends or historical insights.

The big idea I attempted to illustrate is that there is a general positive relationship between education and income and also that many women receive less years of schooling than men.

For the *Education and Income* dashboard I created a scatterplot showing average years of education and gross income per capita for the ten most populous countries. This plot can be filtered by year via a slider (or animated). There are a couple of annotations included (years 1990 and 1997) to illustrate key findings. More information is available upon hovering over the points. Below the scatterplot is a combo chart with the same metrics, but plotted over time along the x-axis and able to be filtered by country. This gives the user an opportunity to investigate the data via a different approach. A link to the data source is included at the bottom.

The *Gender Differences* dashboard contains a grouped bar chart comparing average years of education for males vs. females by country. Below this is a scatterplot of these differences in education between the two genders along the x-axis and gross income per capita along the y-axis. Both plots can be filtered by year using the same slider. There are a few annotations included on the scatterplot (years 1990, 1992, and 2005) highlighting key points.

### Reference

*Human Development Index Dataset [1990-2022].* (2024, December 31). Kaggle. https://www.kaggle.com/datasets/lucasyukioimafuko/human-development-index-hdr-dataset-1990-2022

![image](https://github.com/user-attachments/assets/eca68d45-8161-494d-9f58-d277158741c6)




![image](https://github.com/user-attachments/assets/ffaad348-e6ad-4151-8fe7-e6749bc7e33d)

