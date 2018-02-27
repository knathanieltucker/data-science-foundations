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

#### Supplementary material

#### Supplementary Exercises

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
