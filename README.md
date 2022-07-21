# Tasks
### 
---
>Using Pandas and Jupyter Notebook, create a report that includes the following data. 
>>
     District Summary: 
    Create a high-level snapshot, in a DataFrame, of the district's key metrics.
>>
     School Summary: 
    Create a DataFrame that summarizes key metrics about each school.
>>
    >> Highest-Performing Schools (by % Overall Passing): 
     Create a DataFrame that highlights the top 5 performing schools based on % Overall Passing. 
>>
     Lowest-Performing Schools (by % Overall Passing): 
    Create a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing.
>>
    Math Scores by Grade: 
    Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
>>
    Reading Scores by Grade: 
    Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
>>
    Scores by School Spending: 
    Create a table that breaks down school performance based on average spending ranges (per student).
>>
    Scores by School Size: 
    Create a table that breaks down school performance based on school size (small, medium, or large).
>>
    Scores by School Type: 
    Create a table that breaks down school performance based on type of school (district or charter)..

>Your report must include a written description of at least two observable trends based on the data.

# Description
  From the included [schools_complete.csv] and [students_complete.csv] this notebook analyses a school district of 15 schools based on the Tasks listed above in order to observe if there are any noticeable trends across the schools, notably in their math and reading scores and the overall percentage of students passing in those subjects. That overall percentage of students passing is tested against several different circumstances from structured DataFrames. I think the notebook is well described within, so I think the most beneficial use of this description I can provide is the general layout of the notebook. As a point of order, I can only recommend someone familiar with Jupyter Notebook try and use or view this notebook.

Each italicized `[]` below is a broken up by a header with a brief summary of the goal of the code below it.

For example:

---

>>## Notebook Layout
>>>The descending layout of the notebook found here. Will hopefully assist with navigation of the notebook. Each section is broken up by its header, which has the code below it that will find and organize the desired data. There is also a table of contents that can hopefully be utilized to navigate the notebook with ease. The table of contents was placed near the bottom as when the notebook is asked "Restart and Run All" the landing place is the bottom of the notebook. There are also links at the very bottom of the notebook to navigate back to the table of contents and to the top of the Notebook. Each section also contains a link at the start to return to the table of contents. 

---

 `[NoteBook Start]` <- General dependencies and csv import. 
	
*`[District Summary]`*
	
 *`[School Summary]`* 
	
*`[Top Five Schools]`* 
	
*`[Bottom Five Schools]`*
	
*`[Math Scores by Grade]`*
	
*`[Reading Scores by Grade]`*
	
*`[Scores by School Spending]`*
	
 *`[Scores by School Size]`*
	
 *`[Scores by School Type]`*
	
`[Table of Contents]` <- Links to each header

 `[Written Report]` < Summarized observations on the data found.
	
`[Visualized DataFrame from each section in order]` <- Has observations of each one under respective DataFrame.

` [References] `

`[Book End]` <- Has links back to top and Table of Contents.

---
In regards to some of the DataFrames, I added some columns and cleaned up some of the long decimals. Notably, I added counts for each range found under the `[Scores by School Spending]`, `[Scores by School Size]`, and `[Scores by School Type]` into their own columns for stronger information visualization.


### 

---
# Contents
Found in this repo is a Jupyter Source File that contains the notebook and a Resource Folder.
Inside that Resource Folder are the two csv files `[schools_complete.csv]` and `[students_complete.csv]` that the notebook is dependant on for its data analysis. 

All work done in this notebook was done in a specific designated kernel named PythonData38. 

### Sources
##### Data generated by Mockaroo, LLC. (2021) Realistic Data Generator. [https://www.mockaroo.com/](https://mockaroo.com/). Modified by Trilogy Education Services, LLC.

##### © 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
