[Go back to the main page](/README.md)
# Data Visualization Critique and Redesign 
For this assignment, I will select a published data visualization that could be better designed, identify the areas of improvement, sketch out a potential solution, test out the solution by asking opinions of other people, and offer a different way of presenting the data. 


## Original Visualization 
<img width="599" alt="image" src="https://github.com/YLtryingcode/Yilin-Lyu-portfolio/assets/122923571/56a505f5-bf1f-4433-b140-d66b1694ed95">




"Exhibit 1", Accessed September 20, 2023. https://www.mckinsey.com/industries/automotive-and-assembly/our-insights/autonomous-drivings-future-convenient-and-connected

This data visualization is from McKinsey's report *'Autonomous driving’s future: Convenient and connected'*. The visiualization is meant to demonstrate the significant increase in revenue by all levels of autonomous driving by 2035, as suggested by the title of the visualization, 'Passenger car advanced driver-assistance systems and the autonomous-driving system could create $300 billion to $400 billion in revenues by 2035'. When first approaching this data visualization, my attention was drawn to the different shades of blue and grey boxes that form a block for each year. My initial interpretation was that those are different levels different level of autonomous driving and their revenue size will grow differently for each level and together they form the entire industry's revenue growth. The message itself is not hard to receive, but it took me a while to identify what each individual box meant since tree maps are not meant to be compared to each other to demonstrate growth over time. Therefore the visualization makes it hard to come to the conclusion as the title states. In addition, for the general audience who is not familiar with autonomous driving, the meanings of terms levels 1-4 are unclear, especially with how different levels are related to advanced-driver-assistance systems (ADAS) and autonomous driving (AD). It took me an additional search to learn about what each level means. Level 1 & 2 belong to ADAS and level 3 & 4 belong to AD. Lack of this this information makes the graph seem incomplete and not very reader-friendly for general public. 

Overall, this data visualization is very useful and does seem true to its data. It does have a clean look which gives it a decent aesthetic score and it will inspire audience to share the main message with others. However, the design of the visualization and the main message it tries to deliver are not well aligned with each other which makes it lack intuitiveness. The different size of the block over the year make it lack of perceptibility. 
 
## Sketch 

### Sktech idea:
To improve the visualization, I would like to change the graph format to a stacked bar with a trend line. This way the audience can clearly tell the growth trend over the year while also learning about how each level grows differently. In addition, I want to change the color scheme of the graph by having different levels in different shades of the same color, so it will give a neater and cleaner look and cause less distraction to the audience's eyes. I also want to change the legend a little bit so the audience knows what each level belongs to.  And a sketch of to improve the data visualization looks like the following: 

![69bf5bad679447c72682dde0f3e924e](https://github.com/YLtryingcode/Yilin-Lyu-portfolio/assets/122923571/50b5ee3f-e203-4676-b2c3-170a6a606fbf)



## Feedback: 
After I was done with sketch, I presented it to two people who had never seen the initial visualization before and asked for their thoughts on the sketch. 

#### Repondent 1: Male student, late 20s 
- What does the graph tell you?

  This is a graph of revenue for self-driving cars in the future. There will have a big increase in revenue in the next 10-12 years and the increase is not linear. There will a greater portion of Level 4 in 2035 while we do not have any level 4 now yet. At the same time, the revenue share for Level 1 will shrink over time. 
- Who do you think is the target audience for this visualization?

  Someone high level in a car company, regulator for public transportation, general public who is interested in the topic.
- Anything stand out for you? Anything confusing?

  There is not enough color contrast between levels 1 & 2. And what each level mean is uncealr so it will be nice if that can be explained. The number is showing a range so how do you decide the height of the bar? 
- How do you like the overall aesthtics and format?

  I like it, it is enjoyable and interesting to look at and the idea of total revenue is increasing each pretty clear. The stack bar chart works well. The change between each bar is dramatic so it's easy to identify the change and the trend line allows a easy guidance to see the change.


#### Repondent 2: Male Friend, late 30s.
- what does the graph tell you?

  It tells me that overall autonomes driving at all level will increase.  High driving automation will be the biggest market share by the end of the decade. I am suprised that level 1 will decrease over time
- Who do you think is the target audience for this visualization?

  Investors in the automated driving 
- Anything stand out for you? Anything confusing?

  Yes, what is the difference between ADAS and AD. I am also confused by the term of different levels. What does different level mean?
- What else do you wish you knew or being included in the visualization?

  Reference, where the data comes frome and the percentage of each each level at each year.
- How do you like the overall aesthetic and format?

  I like it. the reader can easily understand the graph with minimal effort. The graph represents what the title introduce. It is an engaging graph, and yes I am willing to share the information with others.

#### Feedback takeaways & thoughts
- More explanation  about different level is needed for the general audience to understand the graph
- Change the color of each level so it is a greater contrast between each other
- For the range problem, an alternative solution is to change to a box plot but it can make the graph very messy. I would rather keep the current stacked bar format and add a footnote that the height of the bar is at the midpoint of the range.
- Add reference for data source
- Put the number for each level's range back so audience can look into the detailed change for each level.  

##  Visualization Redesign 
So after reflecting on the feedbakcs, here is final version of the redesign for the visualization using tableau. 


https://public.tableau.com/views/Autonomousdriving/Sheet1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

<div class='tableauPlaceholder' id='viz1695261512891' style='position: relative'><noscript><a href='#'><img alt='Autonomous Driving System at all levels will create significant revenues in the coming decade Passenger car advanced driver-assistance systems and autonomous-driving systems could create $300 billion to $400 billion in revenue by 2035Data source: McKins ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Au&#47;Autonomousdriving&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Autonomousdriving&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Au&#47;Autonomousdriving&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1695261512891'); 
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; 
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);    
</script>
