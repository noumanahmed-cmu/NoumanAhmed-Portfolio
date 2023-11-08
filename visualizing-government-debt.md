| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt.md) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Part 1
<iframe src="https://data.oecd.org/chart/7fa5" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7fa5" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2022</a></iframe>

# Part 2: 

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1699418507844');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                   
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

https://public.tableau.com/app/profile/nouman.ahmed6010/viz/Debt-to-GDPVisualization/Debt-to-GDP?publish=yes

I believe that this visualization does a fairly good job of representing the data. The color scheme makes it easy to identify the over-leveraged population. I like the heat map since there are an immense number of data points, and the heat map is more suited to capture this large amount of data. I have visualized the data as a geographic map for my third part, but in comparison, this one looks better since it makes it easy to see the trend immediately. 

# Part 3:

<div class='tableauPlaceholder' id='viz1699418119936' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;Debt-to-GDPGeographicalMap&#47;GeographicalMap&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Debt-to-GDPGeographicalMap&#47;GeographicalMap' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;Debt-to-GDPGeographicalMap&#47;GeographicalMap&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1699418119936');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

https://public.tableau.com/app/profile/nouman.ahmed6010/viz/Debt-to-GDPGeographicalMap/GeographicalMap

For this visualization, I first changed the role of the location varibale to 'Geographical - Country'. This allowed me to fetch them lat and long, allowing Tableau to make a geographical map of them. I then used a red-green color scheme, since that made sense in this context where we are trying to highlight the countries with high debt-to-GDP ratio. I reversed the color scheme and added 10 steps  in color schemes to differentiate more clearly between the countries. I added country as label, and both country and debt-to-GDP ratio in the tooltip.
