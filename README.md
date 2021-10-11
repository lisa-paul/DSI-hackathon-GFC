# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  Data Science Venn Diagram
_Creator: Alexander Combs, NYC_

-------------------

Today we are going to have a team-based competition. The goal is to create the best performing model on a hold-out sample of data. Simple right?

Well, there is a catch.

This will be a constrained optimization. To understand what that means, let's take a look at the Project Management Venn Diagram, below.

![](https://berkonomics.com/wp-content/uploads/2015/11/goodfastcheap1-1.png)

The idea is that for any project you can have any two of these. You can have good work done cheap, but it will take a long time. You can have good work done fast, but it won't be cheap. Or you can have work done fast and on the cheap, but it won't be good.

Today we will apply this concept to data science.

You will be given a dataset and teams will be randomly assigned to one constraint: samples, features or algorithm.

---

### Team Sample Constraint
- Your choice of algorithm
- Your choice of features
- **Must use the cheap train sample**

### Team Features Constraint
- Your choice of algorithm
- **Limited to a maximum of 20 features**
- Your choice of samples

### Team Algorithm Constraint
- **Must use a Random Forest**
- Your choice of features
- Your choice of samples

## Deliverables
Your team will have until 5pm EST / 2pm PST (presentation time) to build the best model possible under those constraints.

- Modeling, predictions csv, and slide deck done by 5pm EST / 2pm PST (presentation time)
- Group presentations (_5 min, semi-technical audience_) with slide deck between 5-6pm EST / 2-3pm PST (presentation time)
- Repo with organized notebooks and README.md due by 11:59 pm EST / 8:59pm PST

# ![](https://media.giphy.com/media/aL4bDxt8fbpy8/giphy.gif)

 Descriptions of the data can be found [here](https://archive.ics.uci.edu/ml/datasets/adult).

### Submission
---

The task is to predict if a person's income is in excess of $50,000 given certain profile information, and more specifically to generate the labels for income being **above** $50,000 for each row in the test set. This will simply be a _**csv called `group#-group-submission.csv`, for example `1-group-submission.csv`**_, with a single column of the predictions [0,1]. One member from each group will Slack the csv with your predictions to Patrick by 5pm EST / 2pm PST. Only one member from each group should submit the link to your GitHub repository to Google Classroom with final changes made by 11:59am EST / 8:59pm PST.

Good luck!
