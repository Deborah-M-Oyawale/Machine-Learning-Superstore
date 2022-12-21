# Machine-Learning-Superstore
A Superstore Giant is interested in determining what would work best for them given the rising needs and fierce competition in the market.
They want to know which products, regions, categories, and consumer segments they ought to concentrate on or steer clear of.
Additionally, they are interested in learning what their profit projections are.

#Data Sourcing
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

#Transformation
I removed all columns that were really contributing vital information to the  analysis and insights needed to be drawn. I noticed that the dataset was somewhat clean as there wasn't any missing values nor duplicate values and  no strange  characters in the data points.
There after I used INDEX-MATCH to match the Fullname in the Titanic_analzed spreedsheet from the passengers spreedsheet. Using this fuctions to create the Fullname and Sex column.

There after I used IF function to create the age ranges, having used Measure of Tendency to fill in the missing records in the Age Column, precisely Age 30 as the mean as there are no outliers. Using this idea for the missing records in fare- Mean for fare 36$. Nesting IF and ISBLANK Function.

I transformed Q,S and C to Queenstown, Southampton and Cherbourg respectively using IF function.

Next I created my Calculation on another spreedsheet using pivottable.

Having created the all my calculations with pivot tables, Then I used the piviot tables to create a dynamic Dashboard.
