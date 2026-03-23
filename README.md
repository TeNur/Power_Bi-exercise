** THE DATA ANALYSIS IS STILL WORK IN PROGRESS - I WILL UPDATE THE FINAL ANALYSIS SHORTLY **

Below is a description of the analysis process and my findings on the data:

Data description:

Two tables with data of students and test scores. The original data files can be found in this repository under name StudentData.csv and StudentTestingData.csv

Tables and their columns:

[Student]: Student Number, Name, Extracurricular Activities

[TestScores]: School Year, District, City, State, StudentID, Grade, Math Score, Reading Score, Math Tutor, Math Tutor Hours, Math Tutor Period, Reading Tutor,
Reading Tutor Hours, Reading Tutor Period

Data cleansing: 

Once I uploaded the data in PowerBi, I started by checking the available data in PowerQuery. 
This consists of having an overall look at the tables, their columns and types of data available to understand what type of data I am 
dealing with and what types of findings I could extract with this data. I also check if there are any empty values in data that could hinder my analysis. 
In this data I find lots of empty values, particularly in [TestScores]Tutoring Hours fields as well as [Student] Extracurricular Activities, and I 
decided to give them value ‘null’. This means I could still work with them and measure the number of empty fields. I find this the correct action as the 
detail of empty field gives as much information in this case – namely that if the field is empty, the student does not have extracurricular activities or 
has not had tutoring hours. 

Data relationship checking:

After being sure I can work with the data, I created the relationship. This was fairly simple as there is one clear Primary Key in the [Student] that can 
link the data to [TestScores] table: Student ID number. With this key I can pinpoint each test result to a particular student. 

Analysis:
My initial goal was to include the whole analysis on one page but quickly found there would not be reader-friendly way to shove it all on one page. 
As such I divided my analysis to two parts: School performance and Student performance. I do not find much value to analyse merely student performance 
as individual number, so I wanted to concentrate on external factors and how they impact student performance: extracurricular activities, tutoring offered 
and tutoring available. 

School Analysis: (this will be updated shortly)
