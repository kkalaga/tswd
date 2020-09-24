# Assignment 3&4: Critique by Design
# Week 3

### **Original Visualization**
###### Link to the website: https://graphics.reuters.com/world-coronavirus-tracker-and-maps/countries-and-territories/india/

![alt text](Original_screenshot.PNG)
Source: Thomson Reuters COVID-19 Tracker (India) (https://graphics.reuters.com/world-coronavirus-tracker-and-maps/countries-and-territories/india/)
The visuals I am using are the graphs "Infections in Asia and Middle East" and "Infections, globally" under "Total infections and deaths". I thought these same redesigns are also applicable for "Deaths in Asia and Middle East" and "Deaths, globally"

There have been many recent visualizations on COVID-19 cases trackings. As many have been already used to make false assumptions and criticized, there have also been many visuals that provided insights on the progression of the pandemic. As I was keeping track of the number in India as my family lives there, I have come accross this website that tracks and highlights India and its position. When I saw it, I immediately wanted to understand and analyse the visualization.

### **Critique, Thought process and Wireframe sketch:**
> - The first thing that stood out to me is the truthfulness in the website, where above the graphs it mentions what the graph represents but most importantly what it **"doesn’t"** and I thought that was very important. But this same aspect again gave me thought on why not just use an appropriate graph like number of cases per capita instead, which might be of a better representation of the pandemic spread. But with the help of critique method, I releazied it was not necessary untruthful visual. This gave me an epiphany that sometimes it is important to plot just the number of cases as well and given the context about how the numbers in India have surged, it dismissed by doubt. Similar to some exploratory analysis where simple graphs also give us some much needed insight.
>- What worked for me was the clever, simple and clean representation of the plots. They are not too busy, pleasant to look at, highlights India’s numbers and also give us the basic idea. I have never seen such graph and I was impressed informative it was after spending some time on it.
But what did not work for me is that the other countries were marked as thin gray line with a black background. It took me quite some time to spot them. And then came the next challenge on finding out which line each country was. I searched for some sort of guide/legend to decipher it until I hovered over them and found the names popping up. This does work for an interactive graphic but for a static visual, I thought there was far too less information except India’s and left me a little frustrated.
>- When I was critiqueing each aspect of the visual, I also simultaneosly starting thinking what change would increase the score. Then I came up with a few mental images of changes that would work better and started sketching them like changing background color or the color for other countries in order to get a contrast. I believe that this graph is less intuitive, unfamiliar and is not necessarily extremely easy to understand quickly especially for general public. So, I thought I would rather use a column or a horizontal bar chart which shows the differences quickly. But a bar/column was global cases was proving to be different due to number of countries to be displaced. So I thought the focus would be on the Top 10 or 15, which will enable us to understand the position of India. So, I thought using a tree map would be good.
FInally, I came up with the following wireframe/sketch. 


![alt text](sketch.jpg)

### **Feedback on the sketches**
>To capture the opinion of general public as the intended audience, I got feedback from three different people. All in completely different age groups and careers.
>1. My friend in India
>2. My roommate
>3. My Older brother
>The questions were:
>- Can you tell me what you think this is?
>- Can you describe to me what this is telling you?
>- Is there anything you find surprising or confusing?
>- Who do you think is the intended audience for this?
>- Is there anything you would change or do differently?
>- Approximately how much time did it take for you to understand the main point?

>The answers for the column graph was almost exactly as I was hoping. The main point was easily converyed within a time ranging from 5-10 seconds. One feedback I received from my friend was that the countires with low numbers are occupying a lot of space and the white space is too much because of that. So, I have thought of an idea to not emphasize that in the first glance by filtering top countries (with more than 20,000 total cases) and trying a horizontal bar chart.

>The answers for the treemap ranged from "I know exactly what it is and what it means" to "I have no idea what that plot is but I know what it means". So I was satisfied that it was in higher end of "Intuitive" spectrum but not in the lower or middle. Changes suggested were either using the per-capita graph or changing the color scheme of the blue. I have changed the color scheme and as for the per-capita cases, it would need additional information that is not in the dataset and I did not want to change the dataset but work with the same one to create a better plot. So, I did not make any other changes.

### **Final Visuals:**
>After the necessary changes, these the final visuals that might be easier to understand for the context.
<div class='tableauPlaceholder' id='viz1600911745452' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;as&#47;assignment3_16009105626970&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='assignment3_16009105626970&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;as&#47;assignment3_16009105626970&#47;Sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1600911745452');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


