Statistics 157: Reproducible and Collaborative Data Science
================

Course Materials for Stat 157: Reproducible and Collaborative Data Science (Fall 2014).

```
TuTh 9:30-11AM
247 CORY Hall UC Berkeley
```

## Description
This course is a project based introduction to reproducible and collaborative statistical research. You will gain experience acquiring, cleaning, and curating data; formulating scientific questions statistically; writing statistical methods in Python from scratch; designing and implementing new features (feature engineering); developing appropriate statistical methods to analyze the data; implementing those methods in robust, testable, reusable, extensible software; applying the methods; visualizing the results; interpreting the results; and communicating the results to others. You will learn this in a way that is computationally reproducible, which is increasingly recognized as key to scientific progress. The software tools will include git, Python, IPython, SQL, LaTeX, laptop-based Virtualization, and Amazon Web Services. There will be a collaborative term project.

## Instructor
```
Yannet Interian
Department of Statistics, UC Berkeley
yannet at berkeley.edu
```
## Graduate Student Instructor
Sindhuja Jeyabal 

## Class Logistics
```
Units/Credits: 3
No Final Exam
```

## Format
This course will focus heavily on in-class participation. There weekly programming assignments and programming labs. 
Your persistent cooperation in group work and contributions to the course will culminate into a collaborative term project. The format will be interactive and will involve your questions, opinions, and participation.

Topics Covered Will Include:

* Reproducibility and Collaboration
* Programming in Python and IPython
* Code Reviews and Unit Testing
* Data Visualization
* Code efficiency
* Unstructured data
* MapReduce and Hadoop
* AWS
* SQL and databases


## Prerequisites
At least one upper­division course in statistics and at least one upper­division course that requires programming or data analysis. Statistics 133 fulfills both requirements.

## Grading
* Lecture Attendance / Participation
* Homework Assigments
* Collaborative Term Project

## Textbooks
* W. McKinney, 2012. Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython, O’Reilly Press. Available as an e­book and a print book.
* James, Witten, Hastie, Tibshirani. An Introduction to Statistical Learning, with Applications in R (2013, free online)

## Data set for the class projects
Predict the click-through rate of ads given the query and user information. 
https://www.kddcup2012.org/c/kddcup2012-track2

## Course Schedule: The following is a tentative schedule.
* Week 1: Introduction and Course Overview. What is data science? Why Python? What is reproducibility? What is the difference between reproducibility, replicability, verifiability, and auditability? Why is reproducibility important to the scientific method? Why are most scientific publications not reproducible? What is the impact of that?
  * Homework 1: Install BCE, get a github account, complete Python codeacademy tuto- rial.
  * Readings: Approaches and Barriers to Reproducible Practices in Biostatistics. M. S. Shotwell and J. M. Alvarez
http://reproducibleresearch.net/
Roger Peng coursera class on Reproducible Research http://rrcns.readthedocs.org/en/cns2013/reproducible research.html

* Week 2: Introduction to the scientific problem for the semester: predict the click-through rate (CTR) of ads given the query and user information. Start data manipulation and analysis in Python. Background on Search advertising, problem definition and CTR.
  * Homework 2: Find, read, and summarize two scientific articles about our problem for the semester. Summarize the scientific problem in your own words. Write your summary in latex.
  * Lab 1: Review of Python basics (strings, lists, dictionary, loops).
  * Readings: Chapter 9, 15. Networks, Crowds, and Markets: Reasoning about a Highly Connected World. By David Easley and Jon Kleinberg.
Chapter 8. Mining of Massive Datasets. Jure Leskovec, Anand Rajaraman, Jeff Ullman. (both books are free online)

* Week 3: Basic Concepts from Statistical Learning / Machine Learning. Classification. Lo- gistic regression.
  * Homework 3: Basic parsing and manipulation of data in Python. (Using the CTR data)
  * Lab 2: Python Quiz.
  * Readings: Chapter 2. An Introduction to Statistical Learning.

* Week 4: Logistic regression R demo. Evaluation methods for classification. ROC and AUC. K Nearest Neighbors (KNN) Classifier. pylint.
  * Homework 4: Basic feature engineering using the CTR data. Computing similarities between queries and ads.
  * Lab 3: Write KNN algorithm from scratch in Python. 
  * Readings: Chapter 4. An Introduction to Statistical Learning. An introduction to ROC analysis, Tom Fawcett.

* Week 5: Validation and Cross-validation. Model selection and Regularization. R demo.
  * Homework 5: More feature engineering using the CTR data. Unittest in Python.
  * Lab 4: Unittest and cross-validation on the KNN code.
  * Readings: Chapter 5 and 6. An Introduction to Statistical Learning.

* Week 6: Bootstrap and Decision Trees. R demo.
  * Homework 6: Quantile function from scratch, bootstrap to compute confidence intervals on the median from scratch. Unittests for the two functions.
  * Lab 5: Write from scratch the ID3 algorithm for decision trees (providing the recursive function.)
  * Readings: Chapter 8.1. An Introduction to Statistical Learning.

* Week 7: More on Decision Trees. Bagging, Random Forest and Boosting. R demo.
  * Homework 7: Functions for: Ginix Index, binary splitting numerical variables for decision trees, prediction with decision trees. Unittests for the three functions.
  * Lab 6: Getting started in git. Random forest from scratch in Python.
  * Readings: Chapter 8. An Introduction to Statistical Learning.

* Week 8: Introduction to Hadoop and MapReduce. Python streaming with Hadoop. Joins and aggregation with MapReduce.
  * Homework 8: Writing mapreduce code in python: - Joins: compute CTR by gender, Two consecutive jobs: Compute the a histogram of the number of ratings per user. (User,Book,Rating dataset)  https://github.com/ucb-stat-157/fall-2014-public/blob/master/assignments/hw8.md
  * Lab 7: https://github.com/ucb-stat-157/fall-2014-public/tree/master/lec-15-lab
  * Readings: 
    * Chaper 2.1-2.2 .Mining of Massive Datasets. Rajaraman, Ullman, Leskovec, Ullman.
    * http://www.michael-noll.com/tutorials/writing-an-hadoop-mapreduce-program-in-python/ 

* Week 9: MapReduce. Data flow, distributed file system, cluster computing. MapReduce algorithms: matrix multiplication, joins, triagles in a graph. 
  * Homework 9: Writing mapreduce code in python: 
  * Lab 8: Recommendation system with MapReduce: https://github.com/ucb-stat-157/fall-2014-public/blob/master/lec-17-lab.md

* Week 10: MapReduce and AWS. How to write and run MapReduce Jobs for AWS.
  * Lab 9: Running MapReduce on AWS. https://github.com/ucb-stat-157/fall-2014-public/tree/master/lec-19-lab
 

*  Week 8-12: Hadoop and MapReduce, AWS. Python streaming. Aggregating CTR data, feature engieneering with MapReduce. Distributed file systems. Implementing a couple of distributed algorithms. Apply machine learning algorithms to different versions (aggregated versions) of the data. Start collaborative projects, set milestones, set up the issue tracker. Collaborative project proposal due on week 10. Code reviewing.

* Week 13-15: Data structures and databases. An introduction to databases using SQLite. Students make 5 minute presentations. Code review and reproducibility review. Ipython, pandas and numpy. Mini lectures on statistical and computational tools needed to complete the project.

