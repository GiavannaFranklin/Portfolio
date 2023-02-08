| [home page](README.md) | [visualizing debt](visualizing-government-debt.md) |

# Critque by Design

## Original Data Visualization

The original data visualization I chose to critique and redesign is from the City of Kansas City, MO’s government website, which gives data on who has received Emergency Rental Assistance funding every month from 2021 to 2022 based on their income group. I am originally from Kansas City, MO and would be open to working for the city as an analyst if I had the opportunity. If I did work for the city, I could potentially analyze and present data such as those on the website. I wanted to work with this particular chart I chose below since I felt there could be aspects of it that could be presented in a better way. 

<iframe allow="geolocation" src="https://data.kcmo.org/dataset/HHs-Receiving-ERAP-Funding-by-Income-Group/iqqj-k2f9/embed?width=800&height=600" width="800" height="600" style="border:0; padding: 0; margin: 0;"></iframe>
Source: https://data.kcmo.org/stories/s/7h3g-6vjw

## Critiquing the Data Visualization

Next, I completed a critique of the visualization. Through the critique, I was able to delve more into what I did and did not like about the visualization and what changes to possibly implement. One critique I had was not being sure of the purpose of the chart. The title did not depict a main idea. Thus, I wanted to change the title. I also wasn’t sure who the audience was, but I assumed government stakeholders and Kansas City residents. I also wasn’t in favor of the stacked bars. It may have been okay, but I could only easily compare one of the groups for each month. I also thought about changing the x-axis so that it didn’t appear too cluttered. Additionally, the abbreviations and acronyms from the legend may not be clear to those viewing it, so I thought it might be best to change that as well.  However, I did like the use of gray for the lines and words and also the color scheme of the chart.

## Sketching Out and Testing the Solution

For my sketches, I first changed the heading to capture a main idea and what was mentioned on the website about this graph, which was, “Most Households Receiving Emergency Rental Assistance Funding are Extremely Low Income (Have <30% Area Median Income).” I decided to include lines over time to represent the data since I thought that would be best to see the representation of changes overtime for more than one group. I decreased the number of groups to those having less than 30% Area Median Income (AMI) and those who make more so I could focus more on those making less than 30% AMI and comparing that group to the others in total. I added a total line so one could still compare the two groups to the overall total. Additionally, I decreased the amount of labels on the x-axis to make it appear less cluttered.  For the legend, I did not include the acronyms/abbreviations to make it clearer.

<img width="696" alt="revised-data-viz-1-assign4" src="https://user-images.githubusercontent.com/123040438/217102360-73bed610-3edf-4a1a-9abe-db9ec5dc9270.png">

To obtain user feedback for the sketch, I talked with two adults in their 50s. Both of them thought the purpose was to keep track of how many people were receiving assistance but did not refer much to the title of the graph, which aimed to focus on comparisons of the income groups. They both thought the main audience were government workers, which is what I expected for them to say. Additionally, they were not aware the graph was based on data on Kansas City. If one was on the government website, it could be assumed that it was from data from the city but not as a standalone.

One of the commenters first comments on the sketch were that the number of those getting assistance was higher in 2022 than in 2021. This was a key insight, as I realized that the trend of the lines is what stood out more than how the lines compared to each other. I wanted to focus more on how the lines compared to each other, so it made me realize that maybe changing the chart form to not focus on the timeline could be best. A timeline would be valuable, however, if I wanted to focus on the trends. For the other person I talked to, he at first thought the gray line was another category before realizing it was the total, so that made me think about how that line could be misinterpreted and if maybe there was another way to indicate the total or if it was actually necessary to keep to be able to compare the groups.

Below is my redesign of the chart using Tableau. I decided to aggregate the data to include the average number of households using Emergency Rental Assistance Funding per month from 2021 to 2022. That way, it wasn’t focusing on the timeline and more on the differences among the groups. I decided to keep it to four groups so one could see how much bigger the first bar is to the others. I also included the city where the data is based.

<div class='tableauPlaceholder' id='viz1675749560434' style='position: relative'><noscript><a href='#'><img alt='Most Households in Kansas City, MO Receiving Emergency Rental Assistance Funding Have Been Extremely Low IncomeAMI = Area Median Income ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_Assign4&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWD_Assign4&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_Assign4&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>               
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1675749560434');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


Next, I shared my sketch and the Tableau visualization to classmates. For both charts, they were not clear on the main idea or what the visualizations were trying to say. One of them said one would expect those with the most need would receive the most assistance. This made me think about how the chart did not seem insightful. For the sketch, one of them also thought the gray line from the time series sketch at first looked like another category. For the bar chart, they also suggested just keeping color for the bar that represents the less than 30% AMI group to emphasize that group more if I wanted to focus on that.

## Building the Solution

From the feedback I received from classmates, I tried to think of a better message for the visualization, which was challenging. Going back to the observation of my sketch about the line graph, one viewer noticed how much more of those who received Emergency Rental Assistance funding in 2022 versus 2021. Thus, I thought that it may be more insightful and interesting to point out the change of those receiving rental assistance overtime for all income groups. Thus, I decided to create another visualization to reflect that and went back to creating another line graph. This time, I decided to keep the groups disaggregated since my focus was no longer on comparing the extremely low income to the others. Additionally, it is interesting to see how the need for assistance increased for almost every group.


<div class='tableauPlaceholder' id='viz1675749301806' style='position: relative'><noscript><a href='#'><img alt='Those receiving Emergency Rental Assistance Funding in Kansas City increased in 2022, especially for those extremely low incomeAMI = Area Median Income ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_Assign4_2nd&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWD_Assign4_2nd&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_Assign4_2nd&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1675749301806');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
