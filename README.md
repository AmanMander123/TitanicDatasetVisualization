#Summary  
This visualization describes the percentage of passengers that surived during the Titanic disaster. The circles represent the susbet of passengers categorized by sex, passenger class and point of embarkation. The size of the circle corresponds to the percent value; the higher the proportion of survivers, the larger the circle.

#Design  
This purpose of this visualization is to elegantly convey relationships between the survival rates amongst different categories of passengers. This message is delivered with the size of each circle. The circles are lined up horizontally since the natural tendancy for most people is to glance at a visual from left to right. There is enough space in between each circle so that they don't overlap but close enough that they can all fit on a regular computer monitor screen. The radius of the circle is aligned with the square root of percentage of survivors so that each circle, then multiplied by a factor of 8 to make them large enough to be visible. This is a reasonable choice since the cirlces are large enough to be visible yet small enough for them all to fit on the a single screen. The colors of the circle and the text are paste blue and white, respectively. This combination was selected because it does not strain the eyes when looking at it for a long time. The font of the text is the standard sans-serif and the size of the font is small enough to fit within all of the circles, yet large enough to be readable. When hovering over each cirlce, the tooltip feature is used to display the labels. The labels states the category of the passengers and the associated survival rate, as well as the actual count of survivors. The color of box is light pink, which was selected due to its contrast with the blue circles. Both are easy on the eyes separately and when displayed together. Because of the slight opacity of the labels, font color was chosen to be black so that it can be clearly read. In order to create a visual separation between the categories, a vertical line is added between the sex, passenger class and port of embarkation categories.

#Feedback  
##Feedback #1  

-	Noticed that gender, passenger class and port of embarkation were being compared
-	Noticed that survival rate was higher in females than males and was correlated with passenger class
-	Suggestion was to use pastel palette instead of dark colors since they are too bright.   
	o	Circle color changed
-	Questioned as to the meaning of the port of embarkation letters  
	o	Addressed in the Data Story section

##Feedback #2  

-	Noticed circles of different sizes lined across a horizontal line with labels 
-	Noticed that hover certain circles are larger than others
-	Upon looking at the details while hovering over the circles, noticed that the size of the circle was related to the survival rate
-	Suggestion was to add a title so that it can be made more clear what we are looking at  
	o	Title added to visualization
-	Noticed that females had a higher survival rate than males, as well as a decreasing survival rate when moving from passenger class 1 to 2 to 3
-	Question was raised as to why Port C had a larger survival rate than the other ports  
	o	Addressed in the Data Story section

##Feedback #3  

-	Noticed that there are different categories for survival rates: gender, passenger class and port of embarkation
-	Noticed that the size of the circle is used to visually convey the survival rates relative to each other
-	Noticed that females had the largest survival rate; even beating out those in passenger class one
-	A question was raised as to the meaning of point of embarkation  
	o	Since this issue came up 2nd time, text was added below the visualization that explained what the ports letters meant (S, C and Q → Southampton, Cherbourg, Queenstown)

##Feedback #4  
- Include the actual count of passengers in the tooltip under the percentage of survivors  
	o	Count of survivors added
- Instead of using the actual percentage values for the radius, use the square root of the values  
	o	Changed
- Separate the circles for the different categories  
	o	Vertical lines added between the categories to create separation

