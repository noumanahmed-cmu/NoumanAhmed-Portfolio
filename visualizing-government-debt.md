| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Part 1
<iframe src="https://data.oecd.org/chart/7fa5" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7fa5" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2022</a></iframe>

# Part 2: 

<script type='text/javascript'>
var divElement = document.getElementById('viz1699412131844');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';
vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement); 
</script>

I believe that this visualization does a fairly good job of representing the data. The color scheme makes it easy to identify the over-leveraged population. I like the heat map since there are immense number of data points, and heat map is more suited to capture this much amount of data. I have visualized the data as a geographic map for my third part, but in comparison this one looks better since it makes it easy to see the trend immediately. 

# Part 3:

<script type='text/javascript'>                    
var divElement = document.getElementById('viz1699415573748');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';
vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

For this visualization, I first changed the role of location varibale to 'Geographical - Country'. This allowed me to fetch them lat and long, which in turn allowed Tableau to make a geographical map of it. I then used red-green color scheme, since that made sense in this context where we are trying to highlight the countries with high debt-to-gdp ratio. I reversed the color scheme, added 10 steeps to differentiate more clearly between the countries. I added country as label, and both country and Debt-to-GDP ratio in the tool tip.
