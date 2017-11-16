
# Titanic Data Visualisation

**This report is in submission for the Udacity Project: Create a Data Visualisation.<br>
Gary Thomerson. November 2017**

## Summary

The data visualisation I have created is to compare the survival rate for passengers from the tragic Titanic maiden voyage, split by the 3 Passenger classes and by gender. The visualisation uses a transition between gender.

## Design
**Index1.html**

I wanted to show the survival rates by both passenger class and gender. My 1st choice was to draw a stacked bar for each class for males, so that it could be seen how many of the passengers in each class died. I used simple black and grey shades with a legend to clearly show the 2 categories and to not distract from the data. To show the female passengers separately I created a transition. Before going any further I decided to get feedback on this version.

## Feedback 1:

**Rich:**
Rich is a colleague. He was interested in the results and was able to talk me through the visualisation. However he wasn’t very clear on the axis title and suggested these were clarified. Also he said the stacked bar didn’t throw out the data. I suggested a clustered column graph which he said would probably work better. He also pointed out that in the transition the y-axis scale changed, which was altering his perception of the data.

## Design Update 1
**Index2.html**

Following the feedback from Rich, I decided to change the chart to a clustered chart, clearly showing total passengers in each class against survivors in each class. This required me to alter the .csv file to re-arrange the data. I also updated the y-axis and x-axis labels to clarify what they represented. I then fixed the y-axis at the maximum value of 350, keeping a minimum value of 0, to ensure the data was not skewed and was comparable between males and females. Following these changes I gathered further feedback.

## Feedback 2:

**Nicola:**
Nicola loves the titanic history (including the film!) and was very interested to see my visualisation. She easily understood the data and the axis labels, the results came across very quickly to her. She suggested I update the colours though, saying the black and grey were a bit dull. Also she wanted the transition time to be slowed down so she could study the charts better before they transitions.

**Alan:**
Alan is a colleague who produces many charts for business presentations. He like the clustered bars on the chart and said these clearly displayed the data. However he didn’t like the automatic transition on the chart. He would like to be able to pause it, or select the data himself. He also commented on the colours and suggested blue / green shade colours would work better in this case, with a green for survived (essentially using the ‘traffic light’ chart approach). Alan also said the text at the bottom should clearly state the reference for the data.

## Design Update 2
**Index_final.html**

Following the feedback from Nicola and Alan I further updated the visualisation. I decided to add buttons to allow the reader to select the male passenger data and female passenger data manually. This would satisfy the comments from them both. On clicking the button I had to ensure the chart was labelled correctly showing which data was being displayed. I also updated the colours to make the chart more pleasing but not distracting from the data. I updated the text at the bottom to confirm the reference and ensure the reader understood the data was just a sample.

## Final Feedback

On completion of my 3rd iteration, I showed the visualisation again to Rich, Nicola and Alan. They all much preferred the new version and said the message was very clear and visually pleasing. They all liked the buttons to manually transition the data. They had no negative feedback and all liked the final visualisation. 

I am very pleased with my final visualisation. The data is clearly communicated to the reader and the transition is performed at their readiness. Also the visualisation is not harsh and has very easy colours to understand.


## Resources

I used the following resources while completing this visualisation:

1) Titanic data set and description :<br>
https://www.kaggle.com/c/titanic/data<br>
2) dimples.js documentation:<br>
https://github.com/PMSI-AlignAlytics/dimple/wiki<br>
3) dimples.js examples:<br>
http://dimplejs.org/examples_index.html<br>
4) Override y axis for min / max:<br>
https://stackoverflow.com/questions/26562129/how-to-overridemin-max-for-time-axis-in-dimple<br>
5) d3 colours guide:<br>
http://d3-wiki.readthedocs.io/zh_CN/master/Ordinal-Scales/<br>
6) Use of buttons help:<br>
https://stackoverflow.com/questions/20905429/update-dimple-js-chart-when-select-a-new-option<br>
7) Draw rectangle to cover old text:<br>
https://stackoverflow.com/questions/42568992/how-to-draw-a-rectangle-in-d3-js-with-only-2-coordinates<br>
8) Write legend text:<br>
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control<br>






```python

```
