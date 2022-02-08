# Assignment 3 & 4: Critique by Design

## Step one: find a data visualization

Link: https://datausa.io/profile/soc/police-officers

Title: Yearly Wage

<iframe width="720px" height="480px" src="https://datausa.io/profile/soc/police-officers/employment/wage_by_industry?viz=false" frameborder="0" ></iframe>

For this step, I used the resources available on Canvas to find some good data visualization. I explored the Data USA site to find some data, which gives inetersting information but at the same time can be improved. I chose the police officer database to find some good stats on the occupation of police officers as that field is something I was interested in, as a young girl. 

I chose this particular visualization because it grabbed my attention with the orange bar which I looked further to understand the information it was telling. As it was juxtaposed with other occupations, I tried to understand what that visualization is about. I found out it was telling that police officers earns more than national average salary, which is good to know data because they are underpaid in some other countries like India, etc. 

## Step two: critique the data visualization

I think Few, Stephen. “Data Visualization Effectiveness Profile,” approach worked fine. It made me think about the visualization from different angles and in different ways, criteria, which made us realize the aspects to look after when we are creating the visualizations. 
My main recommendation was around the information displayed:
-Give a title that summarizes the intention behind the visualization
-Highlight the national average salary

I also found other insights which are captured in the Google form. This exercise not only helped me have a third perspective to a visualization, but also to understand how I can improve the data visualization further. 

## Step three: wireframe a solution

I wireframed the solution using my iPad. I did not choose to use tool for this step, as I wanted to able to able to draw the visualization as I want and not be limitied to the tools, which I believe was a good decision because later when I designed the final solution, it took a lot of time to configure settings just to visualize what I wanted. With iPad, I was able to quickly draw what I thought was important. 

![Untitled (Draft)-1-6](https://user-images.githubusercontent.com/90984614/152914577-5d867986-534b-4010-aa42-44ec355f7202.jpg)

I majorly focused on a few things like:
 1. Give an explanatory title 
 2. Mark the national average salary with a line 
 3. Change colors in a way that it highlitghts the portion of the salary more than national avearge salary 
 4. I also changed the color from orange to yellow, because I could not associate orange color with police officers. 
 5. I also did not put a lot of values in the x-axis because I felt it was unnecessary. 

## Step four: Test the solution

I tested my solution with 4 of my friends, two of them understand design and visualization, one understands data analysis and the last one is completely in a different field that is automobiles. I wanted to have different views from different people, because I wanted to make sure it is technically design correct and also wanted to understand if a person who doesn't deal with data also understands it. It proved to be helpful because some of the things which I liked and were intuitive  for me, wasn't the same with my friends.

Some of the positive patterns that I saw was: 
1. The information was clear: they were able to understand what I wanted to convey, that was an achievement because it wasn't clear before. 
2. They liked how I highlighted the national average salary line

Some of feedback to improve visualization was:
1. Make the average salary line darker, it is visible now but darker would look good
2. The key information - the takeaway is still not clear.
3. Put more than 5 occupations 
4. Revert the x and y axis, because we tend to see value on the y-axis than x-axis. 
5. show the difference between the salaries 
6. Put salary number on the bar
7. Title is too long
8. Shorten the occupations names
9. Couldn't associate the yellow color with police officer
10. Who are the other designers? 

I got a lot of good feedback and some of the things that were consistent across was the information aspect. I can not do much about it because of the limited information provided on the site and the only motive behind this visualization was about showing that police officers' average salary is more than national average salary. 

Some of key things I wanted to test with the in-class critque sessions to make changes in the final solution were:
1. Title - does it make sense? : I found out that I should put more informative and lesser complex and shorter title.
2. Revert x and y axis: I got mixed reponse towards it.
3. National Average Salary line: It was again brought up saying that I should highlight it more.
4. x- axis label doesn't look good: It got mixed with the title. 

I also got positive feedback about color selection and minimalist design.

## Step five: Build your solution

Based on the feedback I got till now, I made the following final changes:
1. I reverted the x and y axis, it looks better now because users tend to see values on the y- axis and it is visually more clear on the difference between the average salary and national average salary. 
2. I changed the police officer's bar color to blue - as it looks more associated color than yellow.
3. I shortened the occupation names , which is easy to read.
4. I put the salary value as the label over the bar, which becomes easy to see the salary than mapping it manually.
5. I put a simple title - might not have a major takeaway, but tells what the user is expected to see. The subtitle conveys why there are 5 occupations in the visualization. 

I tried to keep the visualization simple, yet it was a good learning experience to see how different elements contribute towards the overall visualization. 

I made the final solution using the Tableau. I used the data provided on the DATA USA webiste, and after hours of efforts I made the following visualization:

<div class='tableauPlaceholder' id='viz1644288873072' style='position: relative'><noscript><a href='#'><img alt='Police Officers&#39; Salary is greater than National Average Salary And other occupations that have comparable average salary  ' src='ZF&#47;ZFJ7JP3JK&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;ZFJ7JP3JK' /> <param name='toolbar' value='yes' /><param name='static_image' value='ZF&#47;ZFJ7JP3JK&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1644288873072');
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
