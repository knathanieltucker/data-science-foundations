# Setup

There are two parts to the setup:
1. Bookmark the [course page](https://github.com/knathanieltucker/data-science-foundations), and star/follow the repository
2. Either follow the instructions on the course page or the ones below:

Download the repo, and install the virtual env

```bash
git clone https://github.com/knathanieltucker/data-science-foundations.git
cd data-science-foundations
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

# Updates

Before each lesson make sure to update the repo by running the following commands:

```bash
git fetch origin
git rebase origin/master
```



# Lessons

## Lesson 1

#### Exercises

* Do the code for the comprehension questions in practicals/01
* Do exploratory data analysis on the [data/classics.csv](https://think.cs.vt.edu/corgis/python/classics/classics.html) dataset (write the code in a separate ipython notebook)
  - How would I write a popular book?
  - What are the characteristics of polarizing books?
  - When was the best time to be a writer?
  - When was the best time and place to be alive as an avid reader?
  - When should I publish? Does it depend on anything?

#### Supplementary material

Highly recommended, for more information on seaborn (aka visualizing data), do check out my series [here](https://www.youtube.com/watch?v=fWuPIGVPo7o&list=PLgJhDSE2ZLxYlhQx0UfVlnF1F7OWF-9rp)

For tutorials on pandas, I would suggest using [10 minutes to pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)

#### Supplementary Exercises

* Do exploratory data analysis on the [data/broadway.csv](https://think.cs.vt.edu/corgis/python/broadway/broadway.html) dataset
  - Have the good times of broadway come to a close?
  - If I want to make money I should use which theater?
  - What is the most underrated broadway show?

* Do exploratory data analysis on the [data/airlines.csv](https://think.cs.vt.edu/corgis/python/airlines/airlines.html) dataset
  - Which airport should I get lounge access to?
  - I live in Chicago, which should be my go to airline?
  - My flight has been delayed 15 minutes, how much longer should I expect to wait?

# Tentative Schedule

1. Introduction to Data
    1. Summary Statistics
    1. Visualizations
1. Random Variables
    1. Random Variables
    1. Simulating Randomness
    1. IID
    1. Dummy Random Variables
    1. KDE
1. Out of Sample
    1. Bootstrapping
    1. Confidence Intervals and Hypothesis Tests
1. The Learning Problem
    1. Feature Transformations
    1. Supervised Learning
    1. Unsupervised Learning
    1. Single Hypothesis Learning
    1. Multiple Hypothesis Learning
    1. Feature Selection
1. Added Complexities
    1. KNN
    1. Test Set
    1. Validation Set
    1. Error and Noise
    1. Error Measures
    1. Infinite Hypothesis Sets
    1. Linear Regression
1. Two Tradeoffs
    1. Approximation and Generalization Tradeoff
    1. Bias Variance Tradeoff
    1. Logistic Regression
    1. Decision Trees
1. Understanding and Dealing with the Tradeoff
    1. Stochastic and Deterministic Noise
    1. Regularization
    1. Cross Validation
1. Meta Estimators and Conclusion
    1. Bagging
    1. Boosting
    1. Inductive Bias and Beyond


# Slideshow

`jupyter nbconvert mynotebook.ipynb --to slides --post serve`
