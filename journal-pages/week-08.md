---
layout: default
---

# Week 08

[← Back to Home](../index.md)

# In-Class Activities

## Progress Reports

Feedback received from my progress report:

Technical Feedback

The current line graphs are easy to read, especially with the use of colour to separate countries and the improved spacing. There was agreement that converting the original tourism dataset to CSV format and combining different travel purposes into one system was a strong technical improvement.

They also discussed the next development stages involving the world map and pie charts. A peer suggested I could consider how much information is displayed at once, as too much data may be difficult to read. Another suggested improving the interaction design by allowing users to focus on specific countries or specific travel purposes individually. The feedback also suggested I could try different ways to represent the data, rather than only depending on traditional charts.

Conceptual Feedback

An important point raised by peers was that the project should go beyond simply displaying numbers, and instead convey the relationships between countries, tourist numbers and travel purposes. A peer suggested exploring why tourists from different countries visit New Zealand for different purposes, and whether cultural background, distance or season might influence tourist behaviour. The tutor suggested I think about whether the visualisation could allow the audience to interact with the data in different ways.

## Critical Design Propositions

My parter's project is emotion data visualisation.

This project treats emotions as data. Emotions are categorised into four aspects: happy, calm, stress, and sad, each represented by a different colour. The intensity is then indicated by size, the time by position, and changes by movement, recording the evolution of these emotions over several days with an intensity from 1 to 5. I think this representation is easy to understand at a glance. The idea of transforming personal emotions into visualisations is also novel.

Currently, the area for improvement in this project is to clarify who the target users are and what benefits they will gain from using this system.

My Design Proposition is to plan this as an interactive emotional diary map. Users regularly record their emotional state each day. Dates can be set as the horizontal axis, and each day's time can be set as a vertical axis. Add a categorisation of the reasons for each emotion. Each reason appears as a differently shaped graphic. The shape's colour represents the four emotion types, and the size reflects the emotion intensity from 1-5. Shapes of different colours and sizes are displayed on the timeline. Through this record, users can observe their daily emotional changes and discover the reasons.


# Independent Study

## Reflective Summary

Although at the time of my report, the development progress was only halfway completed. But based on the feedback from the progress report, I began to rethink the technical implementation and concept transfer of the data visualization project. The most important information in the feedback is that this project should not only be a graphical display of tourism statistics, but also convey the relationship between different countries and personnel mobility. This has transformed my understanding of projects from simply presenting digital information to creating more meaningful narratives through the combination of data and text.

The feedback mentioned that users can select individual countries or travel destinations to filter the data, so as to clearly monitor the changes in specific data. This is a great suggestion. I want to try to do it. But I feel that data filtering is a bit difficult for the program, and I don't know if it can be successful. But it can be a direction for experimentation, as it allows the audience to explore deeper information.

Another suggestion in the feedback is to consider how to make the charts more interactive and enhance the user experience. My current approach is to set up a line chart with country selection, allowing users to view the changing trends of tourists from different countries. Set a time slider on the map, and the pie chart on the map will change over time. To increase the overall readability of the data, it is possible to increase the distance from the center point to various countries, with New Zealand as the central point.

This feedback also allowed me to explore the deeper meaning of these tourism data themselves. Colleagues question why tourists from different countries have different travel patterns and what social or cultural factors influence these patterns. In the future, I hope to further investigate these associations and use visualization not only as a tool for presenting data, but also as a medium for conveying different social behaviors. This will help expand my design thinking, explore the depth of the project and the breadth of its applications.

## Project Development

This week's development has primarily focused on the unfinished upper portion of the world map and the time slider section.

Results of the initial development:
<iframe src="https://editor.p5js.org/yuhaochen018/full/4ocAbeud3" width="800" height="600"></iframe>

Programe by the prompt (OpenAI, 2026).

Main issues with this version:

The world map JSON includes Antarctica, so the world map JSON needs to be re-downloaded.

World map visual distortion. The world map height needs to be reduced.

The overall image is too high, and the text and slider need to be adjusted downwards.

Result after adjustments:
<iframe src="https://editor.p5js.org/yuhaochen018/full/prQMoQ-k_" width="800" height="600"></iframe>

What I learned:

After re-uploading the JSON, as long as the filename remains the same, there's no need to adjust the program. The system updates automatically.

# References
  OpenAI. (2026). ChatGPT (May 13 version) [Large language model]. https://chat.openai.com/chat

