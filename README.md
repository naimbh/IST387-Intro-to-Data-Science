# IST 387: Introduction to Data Science

**Author:** Naim Bin Hasan

This is a plain-language study companion for IST 387 (Introduction to Data Science) at Syracuse University. It is written for students who are new to R and statistics. Every function, symbol and term is explained the first time it appears, and every code output was checked in R.

It is an **unofficial** resource. It does not contain any lecture slides, homework, labs, exams or other original course materials. Use it alongside the course, not instead of it, and follow the course's academic integrity policy.

## What's inside

| File | What it is |
|---|---|
| [`guides/r-guide.html`](guides/r-guide.html) | The main study guide: every week explained, with key terms, code examples, common traps, a quiz per week, hand-writing drills and a timed mock exam. |
| [`guides/statistics.html`](guides/statistics.html) | Every statistic in the course in plain words: descriptive statistics, sampling, the Law of Large Numbers and the Central Limit Theorem, regression output and model accuracy. It includes an interactive calculator and charts. |
| [`guides/r-crash-course.html`](guides/r-crash-course.html) | A shorter first version of the guide, for a quick review. |
| [`practice/midterm-practice.Rmd`](practice/midterm-practice.Rmd) | A 30-question practice lab in the same format as the weekly labs. It uses only data sets built into R. |
| [`practice/midterm-practice-key.Rmd`](practice/midterm-practice-key.Rmd) | The full answer key for the practice lab. |

## How to use it

1. **Read the guides:** download the repository (the green **Code** button, then **Download ZIP**) and double-click any `.html` file in `guides/`. It opens in your web browser and works offline.
2. **Practice in RStudio:** open `practice/midterm-practice.Rmd`, write your code in each empty chunk and run it. Compare your answers with the key only after you have tried every question.
3. **Study in short sessions:** one topic per day works better than cramming. The R guide includes a six-session plan.

The practice lab needs these R packages:

```r
install.packages(c("tidyverse", "jsonlite", "maps", "mapproj", "caret", "kernlab", "rpart", "rpart.plot"))
```

## Weeks covered

| Week | Topic | Status |
|---|---|---|
| 1 | What data science is, vectors and R Markdown | Done |
| 2 | Data frames and manipulating data | Done |
| 3 | Functions and descriptive statistics | Done |
| 4 | Sampling, the Law of Large Numbers and the Central Limit Theorem | Done |
| 5 | Importing data: CSV, Excel, databases and JSON | Done |
| 6 | Visualization with ggplot2 | Done |
| 7 | Maps | Done |
| 8 | Machine learning overview and linear regression | Done |
| 9 | Decision trees, support vector machines and model accuracy | Done |
| 10 | Ethics and association rules | Preview only |
| 11 and later | To be added as the course goes on | Planned |

## Coming from SQL or PHP?

The R guide starts with a translation table that maps R onto SQL, PHP and Laravel. For example, `filter()` is `WHERE`, `group_by()` with `summarize()` is `GROUP BY`, and `df$email` is `$user->email`.
