# time-series

VISUALIZING TIME SERIES DATA
Please click to watch the overview video : https://youtu.be/BEXvYDzjWes

URL link: https://narnimah.github.io/Time-Series-Visualization-on-Unemployment-Rate-of-USA-/slider_var.html

Abstract: Here we are using the unemployment rates among the different states in USA as an example to visualize time series data by extracting data from the Bureau of Labor and Statistics. Firstly I have plotted the graph of the USA map and made use of line graph at the bottom taking x axis as ‘unemployment rate in percentage’ and y axis as ‘years’. On hovering the mouse over the map, I have added a tool tip where the corresponding state names are displayed.
 On selecting a particular state in the map, below we see the unemployment line graph of the same being displayed. Here also a tool tip is been implemented, where hovering on the line graph displays which state it represents. The user can select one or more states, and can see the graph of the same being displayed. 
Also I have made sure on hovering the mouse over a particular state in the graph, the line graph of other states are made invisible so that the user can see clearly what is the rise or drop for that state over the years. I have also implemented the slider function, where here the use can slide across horizontally and see how the graph fluctuates between the months in a year or between years.
There is also Select All states checkbox been implemented, where the user can see the unemployment rates of all the states in the country at once. Similarly we have the national unemployment rate check box, which displays the line graph of the same.
Further I have implemented the rise and drop function, which shows the corresponding state which had a rise or drop based on a particular value after selecting on all states checkbox. 

Software Requirements:
Text Editor: Sublime
Languages used : javascript and D3 
Operating System: windows 7/8/10
Server : wamp server

SCREENSHOTS
Home Page 
![ScreenShot](https://github.com/narnimah/time-series/blob/master/home_pg_1.PNG)
![ScreenShot](https://github.com/narnimah/time-series/blob/master/home_pg_2.PNG)

On hovering the mouse over the states in the US Map, the corresponding state name is displayed.
![ScreenShot](https://github.com/narnimah/time-series/blob/master/state_name.png)

On clicking on Texas State, the corresponding unemployment graph for the same is displayed in the same color as the state color in the map
![ScreenShot](https://github.com/narnimah/time-series/blob/master/state_linegraph.png)

On clicking on two or more states the corresponding unemployment graphs of the states are displayed
![ScreenShot](https://github.com/narnimah/time-series/blob/master/multiple_lines.PNG)

On moving the slider horizontally across the screen, we see that the line graph also fluctuates based on rise or drop between months in a year
![ScreenShot](https://github.com/narnimah/time-series/blob/master/slider.PNG)

On selecting two or more states, the line graphs of the same are displayed. Next if we hover the mouse on one state in the graph, the other line graphs are made invisible so that we get a clear picture.
![ScreenShot](https://github.com/narnimah/time-series/blob/master/invisible_1.PNG)

On hovering over one state in the graph, the other lines are made invisible
![ScreenShot](https://github.com/narnimah/time-series/blob/master/invisible_2.png)

On clicking the “National Unemployment Rate” checkbox 
![ScreenShot](https://github.com/narnimah/time-series/blob/master/nationalunemp.PNG)

On clicking the “Select All States” checkbox. 
![ScreenShot](https://github.com/narnimah/time-series/blob/master/selectall.PNG)

After clicking on ‘All States’ checkbox, in order to see which state had a rise in 03.00% over span of years, I enter the same in text box and click on rise. The corresponding state with 03.00% rise is displayed.
![ScreenShot](https://github.com/narnimah/time-series/blob/master/rise_1.PNG

States with 03.00% rise
![ScreenShot](https://github.com/narnimah/time-series/blob/master/rise_2.PNG)

After clicking on ‘All States’ checkbox, in order to see which state had a drop in 03.00% over span of years, I enter the same in text box and click on drop. The corresponding state with 03.00% drop is displayed.
![ScreenShot](https://github.com/narnimah/time-series/blob/master/drop_1.PNG)

States with 03.00% drop
![ScreenShot](https://github.com/narnimah/time-series/blob/master/drop_2.PNG)

COMPARISON OF UNEMPLOYMENT RATES OF DIFFERENT YEARS AND STATES
![ScreenShot](https://github.com/narnimah/time-series/blob/master/comp_states_yrs.PNG)





