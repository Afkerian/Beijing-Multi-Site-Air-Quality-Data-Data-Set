# Beijing-Multi-Site-Air-Quality-Data-Data-Set
The present project aims to predict air pollution in Beijing, China, using the data set "Beijing Multi-Site Air-Quality Data Data Set"

The present project aims to predict air pollution in Beijing, China, using the
"Beijing Multi-Site Air-Quality Data Data Set" data set, available at ![Beijing Multi-Site Air-Quality Data](http://archive.ics.uci.edu/dataset/501/beijing+multi+site +air+quality+data).
This data set includes hourly air pollutant data from 12 air pollution monitoring sites.
nationally controlled air quality. The air quality data comes from the Monitoring Center
Beijing Municipal Environmental. The meteorological data of each air quality site are related
with the nearest weather station of China Meteorological Administration. The period of time
It runs from March 1, 2013 to February 28, 2017.

A few years ago, China established the Air Quality Index (AQI) based on the level of five pollutants
atmospheres, namely sulfur dioxide (SO2), nitrogen dioxide (NO2), particulate matter (PM10),
carbon monoxide (CO) and ozone (O3) measured at the monitoring stations in each city. at each level
pollutant is assigned an individual score, and the final AQI is the highest score of those five
contaminants. Pollutants can be measured quite differently. SO2, NO2 and PM10 are measured
as a daily average. CO and O3 are more damaging and are measured as an hourly average. The end value of
AQI is calculated per day and has the interpretation shown in the following table.

![Table 1](/images/Health_Implications.jpg)


This project consists of the development of a Machine Learning model that is capable of predicting the AQI or the
Air Pollution Level for a given day. You must start with the data set of one of the
monitoring sites and then, if possible, extend the study to the other monitoring sites.

----------

# Tasks

Using the data set mentioned above, the following are a set of main tasks
to be carried out, as described. Also, students have the freedom to include other tasks
to increase the value of your work.

## Task 1: Data import, cleanup, and preprocessing

Focus should be on importing the data provided in a suitable format so that subsequent analysis is
more easy. Also verify if it is necessary to perform any data cleaning and/or preprocessing steps.

## Task 2: Exploratory data analysis
Summarize and visualize data in useful ways. Students must think of interesting questions that
they could be verified with the available data and give textual answers or through data visualization.

## Task 3: Predictive modeling
A predictive task must be defined that can help predict air pollution, through the value of the
AQI or Air Pollution Level, depending on its characteristics. After defining the task, you must
use the available data to select and obtain a good model for this task. You must justify the
suggested model.

# Deliverables
The project must be carried out by groups of two students and must be sent through the virtual classroom in the
Corresponding task, with the following files:

1. A report (no more than 5 pages) in PDF format with the identification of the members of the group, and with
a structure similar to the following:
-  Introduction;
-  Definition of the problem;
-   Data preprocessing;
-   Exploratory data analysis;
-   Predictive modeling: experimental setup and results obtained;
-   Conclusions, limitations and future work;
-   Annexes (optional).

2.  A dynamic Jupyter/RMarkdown/Colab notebook ready to run that generates your final report with everything
the code needed to get the results you present.

3. Any supplementary files needed to run your report (for example, data files,
data objects).

------
# Important notes

- Any data pre-processing steps must be presented and justified.
- All algorithms and parameters used must be indicated.
- The organization of the text and presentation, clarity of language and ideas are rewarded.
- Long sequences of poorly formatted results are penalized.
- The report should also make reference to any source used and make explicit which part of the
work was influenced by her.
- It is important that your code does not depend on an absolute path, so that it can be executed anywhere.
computer.
- The source code should not appear in the report, only the output of the report.
- If the notebook contains code that takes a long time to run, it should be included with the option
eval=FALSE so that the code is not executed. If the output of your code is needed, you can execute it
locally on your computer, save it to a binary file, and load it into your report.

