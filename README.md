# applied_statistics

************************
Applied Statistic repository
************************

by Monika Dabrowska

This repository is for the the practical assignments for the Applied Statistics module in the Higher Diploma in Data Analytics course at [ATU](https://www.atu.ie/) in the winter semester of 2025/26.



My work is presented in a [Jupyter Notebook](https://domino.ai/data-science-dictionary/jupyter-notebook) and focuses on analysing statistical problems using [Python](https://www.python.org/doc/essays/blurb/), [NumPy](https://numpy.org/). 

Goals
---

The purpose of this module is to demonstrate my ability to: 
* Describe the **stochastic nature** of real-world measurements.
* Source documentation to **programmatically perform a statistical test**.
* **Select an appropriate statistical test** to investigate a claim.
* Perform a **statistical test** on a data set.


## Get Started

To begin with Jupyter Notebook files you need Python installed on your machine. To do that, you can use the following: 

**Anaconda** \
[Download](https://www.anaconda.com/download) \
The easiest way to install Python and the necessary packages for this course.

**Visual Studio Code** \
[Download](https://code.visualstudio.com) \
The editor we will use to create Python scripts and Jupyter notebooks. 

**Git** \
[Download](https://git-scm.com) \
The software we will use to track our progress.


## If you want to use GitHub Codespaces 

GitHub Codespaces is a cloud-based integrated development environment (IDE) that provides their users with a fully configured and customizable coding workspace, that is accessible from anywhere. It is tightly integrated with GitHub, allowing developers to easily spin up development environments for their repositories with minimal setup. The codespace can be created directly from user GitHub repository and it has a monthly number of hours of free use. 

GitHub Account: You need a GitHub account. If you don't have one, create it at [GitHub](https://github.com/).

### How to open GitHub Codespaces:

- You can open any GitHub repository in Codespaces. You can create a new repository on GitHub or see existing project like mine below.
- Copy the repository from [here](https://github.com/mondbr/computer_infrastructure) and paste in your browser
- Click on the green `<>Code` button
- Select `Create codespace on main` 

<img src="https://github.com/mondbr/applied_statistics/blob/main/images/codespaces.png" width=20% height=20%> 

- This will open a new cloud-based development environment in your browser. You can interact with it just like a local development environment:

    -   Write Code: Use the built-in editor (VS Code) to write, edit, and       manage your code.
    -   Run Code: Open a terminal in your Codespace and run your application just as you would locally.

    -   Version Control: You can commit changes and push them back to GitHub directly from the Codespace. Git and GitHub integration is built-in, allowing easy management of your source code.

Before exiting your Codespace, ensure all your changes are committed and pushed to the repository. 

You can stop a Codespace by going to your GitHub account, navigating to *Settings > Codespaces*, and selecting the *Stop* option for your active Codespace. This will save your work and stop the environment, and you can resume later.

You can restart your Codespace at any time from the GitHub repository page. Go to the Code button again and select *Reopen in Codespaces*.




Assessment Problems
---
*Problem 1 - Extending the Lady Tasting Tea*

> This problem uses simulation to explore hypothesis testing through Fisher’s famous Lady Tasting Tea experiment. By repeatedly shuffling labels and calculating test statistics, we estimate how often results as extreme as the observed outcome occur by chance. This demonstrates the logic behind permutation tests and the interpretation of p-values

*Problem 2 - Normal Distribution*

> This problem investigates the sampling distribution of the standard deviation by drawing repeated samples from a standard normal distribution. We compare the population SD `(ddof=0)` and sample SD `(ddof=1)`, show how their distributions differ for small samples, and illustrate how these differences shrink as sample size increases. Additional histograms of sample means and raw values highlight how averaging reduces variability.

*Problem 3* - t-Tests

> The goal of this problem is to examine how the Type II error rate changes as the difference in means between two populations increases. By repeatedly simulating two samples and applying an independent samples t-test, we estimate how often the test fails to reject the null hypothesis when it is false. This allows us to see how increasing the mean difference improves the test’s ability to detect a real effect.

*Problem 4* - ANOVA
> The goal of this problem is to compare multiple group means using both pairwise t-tests and a one-way ANOVA, and to understand how their conclusions differ. By applying ANOVA followed by Tukey’s HSD post-hoc test, this problem demonstrates why ANOVA is preferred when comparing more than two groups, as it controls the overall Type I error rate while identifying which specific group means differ.


Usage
---
Clone the repository and open the Jupyter notebook to explore the solutions.


To open my jupyter notebook click [here](https://github.com/mondbr/applied_statistics/blob/main/problems.ipynb)




Tools and Libraries
---

* Python 3.11.14
* Jupyter Notebook
* Python NumPy
* Python `pandas`
* Python `math`
* Python `itertools`
* Python `random`
* Python `matplotlib`
* Python `scipy.stats`
* Python `statsmodels`
* Python `seaborn`




## About me: 

My name is Monika Dabrowska and I am an [ATU](https://www.atu.ie/) student of the Applied Statistic module on the Higher Diploma in Data Analytics course during Winter 2025/26.


If you wish to contact me directly, please email me @ mondbr133@gmail.com


## References

- Libraries: <br>
https://docs.python.org/3/library/math.html
https://docs.python.org/3/library/itertools.html
https://www.w3schools.com/python/module_random.asp
https://www.w3schools.com/python/numpy/numpy_intro.asp
https://www.w3schools.com/python/matplotlib_pyplot.asp
https://www.geeksforgeeks.org/python/scipy-stats/
https://www.geeksforgeeks.org/data-science/statsmodel-library-tutorial/
https://seaborn.pydata.org/


- Fisher’s Lady Tasting Tea Experiment: <br>
https://en.wikipedia.org/wiki/Lady_tasting_tea

- Combinations: <br>
https://en.wikipedia.org/wiki/Combination

- Factorials: <br>
https://en.wikipedia.org/wiki/Factorial

- Hypothesis Testing: <br>
https://www.datacamp.com/tutorial/hypothesis-testing

- Null Hypothesis: <br>
https://en.wikipedia.org/wiki/Null_hypothesis

- Alternative Hypothesis: <br>
https://en.wikipedia.org/wiki/Alternative_hypothesis

- P-value Explanation: <br>
https://en.wikipedia.org/wiki/P-value

- Statistical Significance: <br>
https://en.wikipedia.org/wiki/Statistical_significance

- Statistical Hypothesis Tests: <br>
https://en.wikipedia.org/wiki/Statistical_hypothesis_test


- NumPy Documentation: <br>
https://numpy.org/
https://www.w3schools.com/python/numpy/numpy_intro.asp

- Python `math.comb`: <br>
https://docs.python.org/3/library/math.html#math.comb

- Python `ttest_ind`: <br>
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html#ttest-ind

- Permutations & Combinations: <br>
https://www.geeksforgeeks.org/maths/permutations-and-combinations/
https://www.geeksforgeeks.org/maths/permutation/

- Python Factorial: <br>
https://docs.python.org/3.12/library/math.html#math.factorial

- itertools Combinations: <br>
https://docs.python.org/3/library/itertools.html#itertools.combinations

- random.sample: <br>
https://docs.python.org/3/library/random.html#random.sample

- Python Sets: <br>
https://docs.python.org/3/tutorial/datastructures.html#sets

- Sorting Dictionaries: <br>
https://www.geeksforgeeks.org/python/python-sort-python-dictionaries-by-key-or-value/

- Python I/O: <br>
https://docs.python.org/3/tutorial/inputoutput.html

- Normal Distribution: <br>
https://numpy.org/doc/stable/reference/random/generated/numpy.random.normal.html
https://en.wikipedia.org/wiki/Normal_distribution
https://www.w3schools.com/statistics/statistics_standard_normal_distribution.php

- NumPy Mean: <br>
https://numpy.org/devdocs//reference/generated/numpy.mean.html

- Flatten a Matrix: <br>
https://www.geeksforgeeks.org/python/flatten-a-matrix-in-python-using-numpy/

- Degrees of Freedom: <br>
https://medium.com/@caiocvelasco/degrees-of-freedom-part-2-a-brief-mathematical-introduction-8a8bf5d1dae7

- Unbiased Estimator: <br>
https://www.geeksforgeeks.org/machine-learning/unbiased-estimator/

- Bessel’s Correction: <br>
https://www.geeksforgeeks.org/machine-learning/bessels-correction/

- Video Explanation of SD Estimation: <br>
https://www.youtube.com/watch?v=E3_408q1mjo

- Type I and II errors:<br>
https://www.scribbr.com/statistics/type-i-and-type-ii-errors/
https://www.geeksforgeeks.org/data-science/type-i-and-type-ii-errors/

- Plotting:
https://seaborn.pydata.org/generated/seaborn.stripplot.html
https://seaborn.pydata.org/generated/seaborn.boxplot.html

- Student t-test: <br>
https://en.wikipedia.org/wiki/Student%27s_t-test
https://www.w3schools.com/statistics/statistics_students_t_distribution.php

- ANOVA: <br>
https://www.geeksforgeeks.org/python/how-to-perform-a-one-way-anova-in-python/
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f_oneway.html
https://www.geeksforgeeks.org/machine-learning/f-test

- Tukey's HSD Test: <br>
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.tukey_hsd.html


## Technologies

* Python 3.11.14
* VS Code Version: 1.107.1 

END
---