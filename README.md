# League of Legends Match Analysis

Analyzing 150,000 League of Legends matches using R.

**Dataset:** [Kaggle](https://www.kaggle.com/datasets/nathansmallcalder/lol-match-history-and-summoner-data-80k-matches)

# Requirements

Describe your data.
Why you picked the data.

Possible tests to use (at least 5):
 - Two-sample t-test (indepndent t-test)
 - Paired t-test
 - One-way ANOVA
 - Welch's ANOVA
 - Two-way ANOVA
 - Mixed-effects ANOVA
 - Mann-Whiteney U test
 - Kruskal-Wallis test
 - Chi-square test of independence

Include at least 5 different images related to the analysis performed 
(5 total)
All images should be referenced and given a description of what the image is telling us

The lead up to each test performed must have a narrative of what is going to be done and why.

Conclusions to be derived.

Presentation can be done in R (Quarto Presentatio) but can be done in any software.

⭐ Make sure the statistics are correct
⭐ Make it look nice


# Possible Tests
- 2 way ANOVA on predicting damage based on role(Top, Mid, Jungle, Bot) and Keystone or Champion and Keystone (Does taking X keystone over Y increase damage on average)
- Logistic Regression on gold gained and damage dealt/taken to predict win or loss glm
- Chi^2 Test of Independence on champions and winrate (Make our own meta predictor)?
- Could do some kind of simple machine learning to predict win loss on some combination of stats?
- Effect of Mastery Points on kills or win/loss?
