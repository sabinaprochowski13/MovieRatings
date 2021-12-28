# MovieRatings

This was my capstone project for my "Introduction to Data Science" course at New York University.

The premise is as follows: 
The cover story is that you are working for a major entertainment corporation that is trying to get a better handle on both what makes a good movie as well as a better understanding of the viewers. Historically, this process was mostly guided by intuition, but is increasingly infused by data based decision making. This is where you – a budding data scientist – come in. Can you do better, to justify your rather high salary?

Dataset description: This dataset features ratings data of 400 movies from 1097 research participants and is contained in the file “movieReplicationSet.csv”. It is organized as follows:
1st row: Headers (Movie titles/questions) – note that the indexing in this list is from 1
Row 2-1098: Responses from individual participants
Columns 1-400: These columns contain the ratings for the 400 movies (0 to 4, and missing) Columns 401-420: These columns contain self-assessments on sensation seeking behaviors (1-5) Columns 421-464: These columns contain responses to personality questions (1-5)
Columns 465-474: These columns contain self-reported movie experience ratings (1-5)
Column 475: Gender identity (1 = female, 2 = male, 3 = self-described)
Column 476: Only child (1 = yes, 0 = no, -1 = no response)
Column 477: Social viewing preference – “movies are best enjoyed alone” (1 = y, 0 = n, -1 = nr)

Note most of the data munging was already completed (e.g. Python interprets commas in a csv file as separators, so all commas were removed from movie titles), but there are still missing values that needed to be handled for analysis. 

Questions corporate would like you to answer:
1) What is the relationship between sensation seeking and movie experience?
2) Is there evidence of personality types based on the data of these research participants? If so,
characterize these types both quantitatively and narratively.
3) Are movies that are more popular rated higher than movies that are less popular?
4) Is enjoyment of ‘Shrek (2001)’ gendered, i.e. do male and female viewers rate it differently?
5) Do people who are only children enjoy ‘The Lion King (1994)’ more than people with siblings?
6) Do people who like to watch movies socially enjoy ‘The Wolf of Wall Street (2013)’ more than
those who prefer to watch them alone?
7) There are ratings on movies from several franchises ([‘Star Wars’, ‘Harry Potter’, ‘The Matrix’,
‘Indiana Jones’, ‘Jurassic Park’, ‘Pirates of the Caribbean’, ‘Toy Story’, ‘Batman’]) in this
dataset. How many of these are of inconsistent quality, as experienced by viewers?
8) Build a prediction model of your choice (regression or supervised learning) to predict movie ratings (for all 400 movies) from all available factors that are not movie ratings (columns 401- 477). Make sure to use cross-validation methods to avoid overfitting and characterize the accuracy of your model.

