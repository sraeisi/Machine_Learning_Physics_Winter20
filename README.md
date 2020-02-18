---
Machine Learning in Physics
===

This is to facilitate the “Machine Learning in Physics” course that I am
teaching at Sharif University of Technology for winter-20 semester. For more
information, see the course page at

<http://sharif.edu/~sraeisi/ML>

Requirements:
=============

-   Decent understanding of programming and python and the following
    libraries

    -   Numpy

    -   Pandas

    -   Plotting and graphical presentation tools in python

-   Git and Github (if you not familiar, let me know.)

-   Basic understanding of quantum mechanics and statistics.

-   Basic understanding of machine learning

Marking Scheme
==============

This is a tentative plan and we may change it as we move on.

-   Course Project: 40%

-   Assignments: 30%

-   In-class exercises 10%

-   Final exam (set for Thursday, June 20th, 9AM): 30% 

These add up to 110% which include the bonus as well.

Course Projects
===============

This is a group project and counts towards 40% of the final grade.

The idea is that each group decides on a project at the beginning of the course
and apply everything that we cover to their project. Here are some of the
expectations for the course project:

-   Some initial proposal: Clear statement of the problem and some primary
    assessment of why using ML could help answer this problem. (Due Feb 28th)

-   Data collection/generation and preparation: (Due March 15th => <span style="color:red">Extended to March 20th</span> )
    - Create a folder for this part
    - Have a description (readme file) for the data
    - Describe your data: Where it comes from, different feautres and their physical significance, your target value(s)
    - Create a notebook and implement the following in different sections:
        - Clean up the data (remove the missing data and convert everything to numerical values)
        - Scale your data
        - Analysis of features and target (Histograms and )
        - Feature selection (Try different techniques and assess how well they work on your data)
        - Feature extraction (Try different techniques and assess how well they work on your data)

-   Application of the basic ML techniques: (Due April 15th)

    -   A table of assessment (Will give an example later.)

    -   Investigation of variance and bias of the techniques investigated.

    -   Learning and validation curves

-    Application of NN and setting the hyperparameters (Due April 30th)

-   Oral presentation (See me to set up the time, it should be before **June 24th**.)

-   Written term paper (It should be submitted by **July 5th**.)

__Some notes:__
- Make sure you include citations to all the resources you use!
- You should submit your work as a group rather than separate individual submissions.
- Scripts, notebooks and figures without description would not count toward your grade.
- Your codes should include enough comments and information that can be easily followed.
- It is essential that all group members contribute (make commits) to their repositories, this is the only way I can make sure that everyone participated in their project. 



Assignments
==================

| Assigment  | Deadline and Submission link | Solutions |
|------------|------------------------------|-----------|


Reading Materials
=============
- Mehta, Pankaj, et al. "A high-bias, low-variance introduction to machine learning for physicists." Physics Reports (2019).

- Nielsen, Michael A. Neural networks and deep learning. Vol. 25. San Francisco, CA, USA:: Determination press, 2015. ([Available online](http://neuralnetworksanddeeplearning.com) )

- Chollet, François,  ["Deep Learning with Python." (2018)](http://bioserver.cpgei.ct.utfpr.edu.br/disciplinas/eeica/papers/Livros/%5BChollet%5D-Deep_Learning_with_Python.pdf).


Table of contents 
==================

The course material is posted here and you can use either [Google
Colab](http://colab.research.google.com/) or [Mybinder](http://mybinder.org/) to
work with these Jupyter notebooks.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sraeisi/MachineLearning_Physics/master)

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/) 


Basics of Machine Learning

| Topic                                 |  Lecture notes                                                                                                                                                                                              | Notebook(s) |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| Introduction            | (Lec1/MLP_1_Introduction)  |       |
|Regression|pdf|   [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_2/Basics_techniques.ipynb)  <br><br> <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_2/Kernels.ipynb) |
| Clustering  |pdf | code |

 


Cheat sheets and guides
=======================

See the files in the CheatSheet folder.

| Item                                  | Description                                                                                                                                                        |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Jupyter](CheatSheets/Jupyter%20Notebook_CheatSheet.pdf)    | Jupyter provides an interactive environment for programming. We will be mostly using the python 3 kernel.                                                               |
| [Git and Github](CheatSheets/git-CheatSheet.pdf)                        | Git provides a strong infrastructure for version control. Github is web-based hosting service for version control and it also provides services for collaboration. |
| [Python](CheatSheets/Python_CheatSheet.pdf)                               | It is the programming language that we will be mostly using for this course.                                                                                       |
| [NumPy](CheatSheets/NumPy_Basics_CheatSheet.pdf  )                               | It’s a python library that provides strong and efficient tools for manipulation of high-dimensional arrays.                                                        |
| [SciPy](CheatSheets/SciPy_CheatSheet.pdf)                                 | It’s a python library, built on NumPy for mathematical and scientific computing.                                                                                   |
| [Pandas_basics Pandas 2](CheatSheets/Pandas_basics_CheatSheet.pdf ) <br> [Importing data](CheatSheets/Pandas_2_CheatSheet.pdf) | It’s a python library, built on NumPy that provides efficient tools for handling and analysis of data.                                                             |
| [Matplotlib](CheatSheets/Matplotlib_CheatSheet.pdf) <br> [Seaborn](CheatSheets/Seaborn_CheatSheet.pdf)                    | These are two of the most common python library for visualization.                                                                                                 |
| [Scikit-Learn](CheatSheets/Scikit-Learn_CheatSheet.pdf)                          | It’s a python library that provides a nice and fairly efficient implementation of most the machine learning techniques and ideas.                                  |
| [Keras](CheatSheets/Keras_CheatSheet.pdf)                                 | It is python library that provides a high-level and easy-to-use interface for Tensorflow and some other deep learning libraries.                                   |





