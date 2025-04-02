| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Animal Rights Index


## Step one: [the visualization](https://theswiftest.com/animal-rights-index/#:~:text=Animal%20rights%20laws%20vary%20greatly,cruelty%20any%20way%20they%20can) 
I chose this visualization because it is about an interesting topic, but it is hard to understand the information in it. I saw this and knew that there was a better and simpler way to convey the story of this dataset. This is what I intend to do with my redesign.



## Step two: the critique
The visualization has a good story, but it overcomplicates it which makes it hard to read. The best part is the overall index score because it clearly represents if a country is good or bad for animal rights. Additionally, I like the corresponding grades to the index score. It makes it easy to compare two countries. I can better visualize the difference between an "A" and a "B+" more than I can the difference between a score of 519 and a score of 463. That's about where my compliments end. The rest of the table is messy, mostly due to the fact that 5 of the 9 factors that affect the index have their own custom icons. Each icon has 3 different variations to represent "full", "partial", and "none". To make matters worse, the key is at the top of the page, so I have to constantly scroll up and down to learn information about any country that is more than 10 or so down the list.

My focus for the redesign will be simplification. The data here is good information, but no one will look at it long enough to get the story. I will want to focus solely on the index score because that is where the message lies. I will try out a map to visualize it clearly. 

## Step three: Sketch a solution
I decided to use a map to visualize this data. I chose a sliding color scale to represent the index values with red being a lower index and blue being higher. I did this because a lower index score means less animal rights and a higher score means more animal rights. 

![sketch image](https://github.com/jackmasonrooney/rooney-dataviz-portfolio/blob/main/Animal%20Rights%20Sketch.png?raw=true) 

This is just an image file, but when this was live, you could hover over a country and the name and index score would appear.

## Step four: Test the solution

Questions to ask: 
1) What do you think this is?
2) What do the red and blue mean?
3) Is this too little information?

Results: 



| Question | Interview 1 | Interview 2 | Interview 3 | 
|----------|-------------|-------------|-------------|
|     1     |     A measure of how many animal rights a country has.        |  How many rights a country gives animals.  But, I think you should add a small descrition of what the index means exactly.        |     How good a country is at animal rights.        |
|      2    |      What Interview 2 said       |    Blue means a country has a lot of animal rights and red means the opposite.         |       Agreed.      |
|      3    |       No.      |   No.          |      I would like to see the country name and score more clearly (Interview 3 spoke last, 1 and 2 agreed after they said this)       |

Synthesis: 

I did a good initial job at simplifying the visualization, which was my main goal. I will implement what interview 2 said in question 1 and what interview 3 said in question 3 because both of these suggestions will improve clarity of what the visualization is showing. 

## Step five: build the solution
<div class='tableauPlaceholder' id='viz1743631704441' style='position: relative'><noscript><a href='#'><img alt='Animal Rights IndexThe index was calculated by combining nine different factors related to animal rights. A higher index score corresponds to better animal rights.Source: https:&#47;&#47;theswiftest.com&#47;animal-rights-index&#47;#:~:text=Animal%20rights%20laws%20vary ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;Animalrights&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Animalrights&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;Animalrights&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1743631704441');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                   
  vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>

I implemented the feedback I got and it resulted in a much cleaner visualization. I think this accomplished the goal of making a much more readable visualization of the data. A lot of my process came down to figuring out what I could simplify before sketching out a solution. I was also still able to tell the same story with this data, but it is way more readable.

## References
[Source](https://theswiftest.com/animal-rights-index/#:~:text=Animal%20rights%20laws%20vary%20greatly,cruelty%20any%20way%20they%20can) 

## AI acknowledgements
None.

