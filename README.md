# kickstarter_challenge
performing analysis on Kickstarter data
---

## *** Finding the data 

The purpose of this analysis is to show the difference in failed and successful theater plays in the US. The data also shows the plays that met their goals and the years of when the plays took place.

---
#### Challenges 

The challenges I faced during this assignment was trying to understand how =COUNTIFS() worked without filtering the data to one set outcome. I ended up figuring out that using the code below would be my first step into finding my data needed to see the goal and the status of failed, canceled and successful outcomes.

 use the code =COUNTIFS(' Kickstarter'!$D:$D,"<1000",' Kickstarter'!$F:$F, "SUCCESSFUL",' Kickstarter'!$R:$R, "plays")
 The second code i used was =COUNTIFS(' Kickstarter'!$D:$D,">=1000",' Kickstarter'!$F:$F, "SUCCESSFUL",' Kickstarter'!$D:$D,"<=4999",' Kickstarter'!$R:$R, "plays") 
 
  
I had to understand Kickstarter columns was the criteria and the range was the data I was using to get the data. I also had to understand that the same columns could be used twice when filtering data.


When using the pivoting charts, I had to remember that some rows have multiple variables for data and to remove some variables to see the data I need.
The theater outcome by launch date data shows that there are more successful plays in May and June. The data also revealed that theater plays are rarely canceled.
The data from the outcomes based on goals show that the higher the goal ranges are the less successful the plays are. The data also shows that theater plays are never canceled.

Some limitation on this dataset is the time from it starts in 1970 then jumps to 2009. It’s a huge gap in the timeframe.

Using this data, we could create another graphs and tables such as film and video and theater musicals and different publishing types.
