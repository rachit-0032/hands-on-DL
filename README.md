# Hands-on Deep Learning

Bar X-Tract
A Pipeline for the Extraction of Data from Images of Bar Charts
15.S04: Hands on Deep Learning
Massachusetts Institute of Technology
Spring 2023
Rachit Jain, Ayush Shukla, Gavin Findlay, Dafne Badilla


### Introduction
Millions of students have a learning, physical, or visual disability that prevents a person from reading con-
ventional print, making the majority of educational materials for STEM fields inaccessible to them. As part
of the [Benetech - Making Graphs Accessible](https://www.kaggle.com/competitions/benetech-making-graphs-accessible) Kaggle competition, we would like to democratize the access to data visualizations, leveraging deep learning tools.

The objective is to predict the data series represented by four kinds of scientific figures (or charts); but given the different topics covered over the semester, we would like to take a step further and scrape the information of the data visualizations using ML. As an extension of this project, we would also like to develop an AI generated text summarizing the content of the plots, which could be easily used as a voice note, successfully helping us to reduce the accessibility gap to be addressed.


### Project Rescoping
Due to the timeline of the project and the scale of the Kaggle competition, the scope of this project for this course was updated. Since, the course is on Deep Learning, we focused our efforts on developing strong models for the chart classifier, and the origin detector/bounding box models. Due to this, in the stages after the deep learning models we only focus on charts that are classified as vertical bar. We will expand efforts to the other chart types for the Kaggle competition. Additionally, the stretch goal of creating an AI model to text summarize the data was removed from the scope.

### Model Pipeline:
![Model Pipeline](https://github.com/rachit-0032/hands-on-DL/blob/main/15S04_Model_Pipeline.png)
