# Why UFC?

Honestly we were sitting together trying to pick a dataset and someone just said "UFC" and we all agreed immediately. We're fans of the sport so it made sense to work on something we actually care about.

The idea was straightforward fighters have stats, fights have outcomes, so maybe we can connect the two. Reach, age, striking accuracy, takedown rate... all of this exists before a fight even happens. So why not use it?

## What we found out

The Red corner fighter (usually the higher ranked one) wins more often than not. Like almost twice as often. So the first challenge was making sure our model wasn't just learning to always pick Red.

We fixed that with SMOTE to balance the classes, then trained a Random Forest and a Logistic Regression and compared them.

Random Forest ended up at 78% accuracy. Not perfect, but good enough to say that yes, the data does tell a story.

The most important features? Significant strikes landed, takedown accuracy, reach difference. Which actually makes a lot of sense if you watch the sport.

## What we learned

Data cleaning takes way longer than you expect. And an imbalanced dataset will destroy your model if you don't deal with it early.

Also Random Forest is just built different.

 Zied, Amine, Ryan
