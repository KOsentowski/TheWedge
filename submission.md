
# Applied Data Analytics
Kaylee Osentowski

## Wedge Project

Holy cow! This is tough stuff and something I will certainly hire someone to do for me in my future career. I love analyizing data so it is sort of painful to just build this stuff and move on without really digging into results. 

I have learned a lot though and completely embodied the MSBA motto of "if you are furustrated it means you are learning"

### Task 1

* Files for this task: 
Task1.ipynb:This notebook handles taking the wedge data from a zipped file into GBQ tables. 
 



### Task 2

* Files for this task: 
Task2.ipynb: This notebook connects to GBQ, builds a list of the owners, and then takes a sample of 400 owners
 


### Task 3

* Files for this task: 
Task3.ipynb: This notebook builds a SQLite database via Python that has 3 tables: sales by date by hour, sales by owner by year by month, and sales by product description by year by month. 



## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - my_results)/my_results)`. 



|  Query  |  Your Results  |  My Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  |87561182   |85760139   |1,801,043  | 0.021  |
| January 2012 Rows  |1070905 |1070907   | -2  | -0.00000187 |
| October 2012 Rows  |1042285 |1042287   | -2  | -0.00000192  |
| Month with Fewest  |2   |2   | No  | NA  |
| Num Rows in Month with Fewest  |6556769   |6556770   | -1  |-0.00000015  |
| Month with Most  |5   |5  | No  | NA  |
| Num Rows in Month with Most  |8517138  |7578372   |938,766   | 0.1239  |
| Null_TS  |7448515   |7123792   |324723   | 0.046  |
| Null_DT  |0   |0   | 0  | 0 |
| Null_Local  |241276 |234843   |6433   | 0.027  |
| Null_CN  |0  |0  |  0 | 0|
| Num 5 on High Volume Cards  |14987.0   |14987.0   | No  | NA  |
|  Num Rows for Number 5 |470692   |460630 | 10,062 |0.022   |
| Num Rows for 18736  |12803   |12153   |650   |0.053   |
| Product with Most Rows  |banana organic   | banana organic  |No  | NA  |
| Num Rows for that Product  |928055|908639   |19,416   | 0.02  |
| Product with Fourth-Most Rows  |avocado hass organic   | avocado hass organic  | No  | NA  |
| Num Rows for that Product  |462665   |456771   | 5,894  | 0.013  |
| Num Single Record Products  |2691| 2769 | -78 |-0.03   |
| Year with Highest Portion of Owner Rows  |2014   | 2014 | No  | NA |
| Fraction of Rows from Owners in that Year  |0.7591 |0.7591   | 0   |  0 |
| Year with Lowest Portion of Owner Rows  | 2011  | 2011 | No  | NA |
| Fraction of Rows from Owners in that Year  |0.7372 | 0.7372  | 0  |0   |

## Reflections

<!-- I'd love to get 100-200 words on your experience doing the Wedge Project --> 
My experience with the wedge project was frustrating, time consuming, but very beneficial. I now know of new tools such as Google Big Query, how to use SQL to look at Python data, how to take new approaches and work in a non-linear fashion. The non-linear approach was the most challenging part. I struggled to build code for Task 3 that was using different files than what the final project would be. This challenged my thinking and was the most confusing part of where to start. 
All in all, I'm just happy it's done. This semester has been incredibly challenging- I moved back to MT, started an over full time salary job, and have had to pick up more responsibility in my life that makes attending classes on a regular basis challenging. I really leaned on my peers, my google abilities, Zoom/Teams calls and chats, and class recordings to complete this project. It has taken me more time than the average person... but I am so incredibly proud that I, someone who never once looked at code until a year ago, completed a huge data engineering project. It feels as if I can do anything now!