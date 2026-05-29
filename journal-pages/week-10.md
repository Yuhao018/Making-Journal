---
layout: default
---

# Week 10

[← Back to Home](../index.md)

# In-Class Activities

## Progress Reports

Record of feedback received.

My questions：

Q1: Are there other visual approaches that could make the project more engaging?

Q2: What should be improved before the next iteration?

Peers' Feedback:

A1: 

I think it would be easier to read the pie chart if selecting a country displayed the corresponding number of visitors.

Adding some text explaining the source of the data would make it easier for users to utilise the data.

It is clear already. I like the combination of the map and the graph because it shows both location and trends.

A2:

The map looks good, but some country labels are too small to read.

It might be worth testing the addition of a 3D perspective to pie charts to enhance their visual appeal.

When selecting several countries at once, are the colours easy to distinguish?

## Gallery Walk



## Action Plan

I've received a lot of useful suggestions. These suggestions can help me improve the project's practicality and visual experience. A colleague suggested adding some data source descriptions to the charts, which I think is very helpful. This will reduce user confusion when using the data. In addition, a colleague suggested that users should be able to see the exact number of visitors when selecting a specific country pie chart. This will help users to read the chart easily. These suggestions can all help me improve the readability of the charts. Although displaying the data may be a bit difficult in further development, it's worth a try.

The feedback also raised some visual issues. For example, some country labels on the map are difficult to recognise due to the small font size. I've also noticed these problems, but because the differences between countries are too great. For example, the fonts between Japan and South Korea are overlapping, making them difficult to identify. I've also tried it from a development perspective, but I've found that it's really difficult to achieve a good data presentation in the overall chart. In addition, some people have suggested adding a 3D effect to the pie chart, which may improve visual appeal, but I need to test it out. I'm not sure what the effect will be.

Based on this feedback, I've made some trade-offs. The next stage of development will involve two approaches. The first is to add chart descriptions so that users understand where the data comes from and why it is data from eight countries. The second is to try adding hover-over number displays on the pie chart.

# Independent Study

Two iterations were made:

Firstly, the width of the chart canvas was adjusted from 800 to 1000. The additional 200 was used to add a rectangular grey block. This block contains text providing the data source and usage instructions.

Secondly, when hovering the mouse over a pie chart segment, a description of the number of tourists from that country appears. The first line displays the country name and total number of tourists. The second and third lines show the number of tourists for three different visit purposes, respectively.

<iframe src="https://editor.p5js.org/yuhaochen018/full/fre0u5TTa" width="1000" height="600"></iframe>

During the program modification, after adding the explanatory text, the entire font appeared to shift downwards. This was because using textAlign(LEFT, TOP) when adding the text adjusted the text alignment. Adding textAlign(LEFT, BASELINE) reset the alignment and resolved the issue. Furthermore, after moving the mouse away from the hover area, the floating text was not disappearing. After checking the program, it was found that the frame count was not being reset to null after the hover event. This was adjusted, and the problem was resolved.