---
title: 'Chapter 1'
description: 'This is a template chapter.'
---

## Quantitative Variables

```yaml
type: NormalExercise
key: c909bf2ad2
lang: r
xp: 100
skills: 1
```

**Histogram**

The most common method for visualizing distributions is the histogram. A histogram is a special kind of bar chart: in a histogram, the range of the variable is divided into equally-sized “bins” and each bin is given a bar with a height that corresponds to the number of values in that bin.

In R, we will usually load our data sets from a file, rather than entering them by hand at the command prompt. (You can load a data set from a file on your computer, if you want to experiment with your own data, but for examples in this book you will load data sets from an online repository.) We’ll start with a fictional data set which represents daily sales at four locations of a restaurant chain located in various cities. This command loads this data set and gives it a name (we’ll call it store.sales).

store.sales <- read.csv("https://bitbucket.org/biz-stats/data/raw/master/store.sales.csv")

**Looking at the data**

In R, you can refer to a variable in a data set by typing the name of the data set, then a dollar sign ($), and then the name of the variable. (Remember that R is “case-sensitive,” meaning you must use the exact capitalization that is used in the data set when referring to it.)

Like functions you are familiar with from algebra, functions in R take a number of inputs and produce a single output—in R, the output can be a single number, a list of numbers, or even more complicated structures. To see a list of the variable names in this data set, apply the names function to the store.sales data set. Also try just typing store.sales to see the whole data set.

`@instructions`
Like functions you are familiar with from algebra, functions in R take a number of inputs and produce a single output—in R, the output can be a single number, a list of numbers, or even more complicated structures. To see a list of the variable names in this data set, apply the names function to the store.sales data set. Also try just typing store.sales to see the whole data set.

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`
```{r}
# Load datasets here.
store.sales <- read.csv("https://bitbucket.org/biz-stats/data/raw/master/store.sales.csv")
```

`@sample_code`
```{r}
# Your
# sample
# code
# should
# be
# ideally
# 10 lines or less,
# with a max
# of 16 lines.
```

`@solution`
```{r}
# Answer goes here
# Make sure to match the comments with your sample code
# to help students see the differences from solution
# to given.
store.sales

```

`@sct`
```{r}
# Update this to something more informative.
success_msg("Good job! You got it!")
```
