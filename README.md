# ChartRace-AEP
![image](https://github.com/morenicogs/ChartRace-AEP/blob/main/Example_anim_1_total_2.gif)
![image](https://github.com/morenicogs/ChartRace-AEP/blob/main/Example_anim_2_total_2.gif)


This week I decided to come at it from a different angle. My previous submissions where mostly an expression of my wild imagination and thinking out of the box. This week’s submissions on the other hand i tried to look at it from the perspective of an actual user.
This is why I decided to create a template for Adobe After Effects. The overall industry standard for motion graphics like these animations is After Effects and gives the end user who most likely wants to create video content the ability to customize their graphs with all the tools and power of After Effects. 
### How to use it
Open the MAIN comp.

Settings layer: Change the size of all the graphs

Controller layer:
* Start: Start point of your graph from the data (0 = first value)
* End: End point of your graph (0 = first value)
* Radius: Tangent radius between points (create bezier curve)
* Max: The max value (graph will be scaled based on this)

Graph controller layer: 
* Adjust the stroke size and trim paths for all the graphs in the comp

Each shape layer can contain a graph. To change the index of the shown graph use the slider. 
Simply duplicate the shape layer or the composition will let you create a new animation and or graph

The power of having this data in an after effects shape layer is unmatched by any kind of web tool. I initially wanted to use p5.js or a canvas tool but the fact that the only way someone could export it was as a recorded video and be limited by the fact that it was a video and/or the tools I would’ve created, I eventually decided to go for an After Effects template. Giving the user the possibility to use it in any kind of project with animation and video in mind. 

![image](https://github.com/morenicogs/ChartRace-AEP/blob/main/Example_anim_3_total.gif)
