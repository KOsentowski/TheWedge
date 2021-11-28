# TheWedge


## Feedback

Glad for the learning, even if the frustration is regrettable (but inevitable). 

You've got some semi-big discrepancies in the row counts. I'm not going to ask you to fix those, since that 
would mean digging back into the whole project. But I *do* think it'd be worthwhile to diagnose what's going on. 
Here's what I'd like you to do: 

1. Write a query that gives you row counts by year and month for your Wedge data. Store the results for R or in Excel.
2. Run the same query against my tables and store those results.
3. Plot the records over time and look for discrepancies. I think that might show where the issue arose. 

For Task 1, did you manually swap out the table names? That's a super tedious process and it seems like you'd just be a few
`for` loop lines away from avoiding that. This clearly has worked, but I'd encourage you to use more of the 
power of programming rather than this brute force approach. Everything in the code looks like it's doing what 
it should, though. 

Task 2 is good except for one small point, that seems worth calling out. You create a query object called random_trans and then you do some things like print the first row. That will "use" the first row for printing and then, when you ask for the next record, will start on record 2. So be careful playing around with objects and then not "refreshing" them when you go to do the real work. I'm guessing you're missing the first transaction row for your random sample. Just something to keep in mind.

Task 3 looks pretty good. There are some slightly fancier ways you can do it (see solutions) but this works.

Nice job getting to the finish line.

Please do that comparison analysis, but consider this complete otherwise. 

## Kaylee's Note

Thanks for taking the time to look this over. I've included an image of the graph created of the row count discrepancies. The issue is in 2016 months 5 and 6... I did manually swap out table names. And it was super tedious. I got to the point some answer was better than none, however I wish I would have been able to get it with the power of programing. Lesson learned. 
