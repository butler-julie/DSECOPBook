# Introduction to the Machine Learning Workflow with Linear Regression

## Summary of Module

This module aims to teach students about the workflow typical in most machine learning problems, using a simple machine learning algorithm called linear regression. Though linear regression is not complex, using it in the context of a machine learning problem has the same five steps as any machine learning application:

1. Import and format the data set
2. Split the data set into a training set and a test set
3. Train the machine learning algorithm using the training set
4. Evaluate the performance of the trained algorithm using the test data set
5. If the results from step 4 are not sufficient, make adjustments to the model and repeat

These five steps are introduced in Notebook 1 with a guided coding problem to walk students through applying these steps to solve a machine learning problem with linear regression. Notebook 2 uses the same process introduced in Notebook 1 but uses a data set generated by modeling a planet's orbit of a star. Students will perform the machine learning workflow on the given data set and extract the star's mass from the resulting trained linear regression model.


## Table of Contents
* **Notebook 1**: The notebook starts with an overview of machine learning and linear regression. Then it covers the five steps in the machine learning workflow (described above) and applies them to an example (fitting a noisy quadratic data set). There are questions for the students to answer throughout the notebook (both coding and concept), as well as a "Practice What You Have Learned" question at the end, where the students will have to write longer pieces of code based on earlier sections of the notebook. There is also an optional bonus problem where students are asked to create a linear regression algorithm from scratch and compare it to the Scikit-Learn implementation used in the rest of the notebook.
* **Notebook 2**: Notebook 2 applies the machine learning workflow introduced in Notebook 1 to a physics problem. Students are given data on the position, velocity, and acceleration of a planet as it orbits a star. Next, they are taught how to use linear regression and the machine learning workflow to extract the star's mass. Concept and coding questions are scattered throughout the notebook for students to answer as they work through it. The longer "Practice What You Have Learned" problem at the end asks students to find the mass of two objects that interact through a given force. The steps to complete this section are the same as earlier in the notebook, but students must make changes to the problem set-up to match the new problem.

## Prerequisites

### Python Prerequisites
The only Python prerequisite is a basic knowledge of the Python programming language and the libraries NumPy and Matplotlib. Many coding questions are simplified to account for students who have a lower level of programming knowledge to be mainly fill-in-the-blank questions or make minor changes to prior code. Only some optional bonus questions will ask students to ask for code without guidance and a template.

Please note that these notebooks are designed to run on Google Colab, a cloud-based implementation of Jupyter Notebooks. This means all notebooks and data files should be saved to a Google Drive account. The notebooks can be run locally with some edits.

### Physics Prerequisites
It is assumed that students will have a basic knowledge of Newton's second law, kinematic equations, and Newtonian gravitation.

## Learning Goals

### Physics Learning Goals
 * Reinforce previous lessons on Newtonian Gravitation and Newton's second law
 * Understand net force equations and how they relate to Newton's second law, setting up net force equations for a two-body system

### Data Science Learning Goals
* Understand the steps of the machine learning workflow and how to apply them to different data sets
* Understand how linear regression works and how to implement it using the Scikit-Learn library
* Be able to frame a set of equations as a linear regression problem with a design matrix and apply physical meaning to the linear regression weights

## Suggested Course to Plug Into
The physics content in these notebooks aligns well with the material taught in an introductory mechanics or classical mechanics course. A computational physics course could also utilize this module.

## Time Needed to Complete the Module
The total class/lab time needed to complete this module is estimated as _1-2 hours_ and the time for students to complete out-of-class assignments is estimated as _2-4 hours_. When creating the module, we envisioned that Notebook 1 would be given to students as a homework assignment, and Notebook 2 would be completed in class or lab. Completing Notebook 1 as a homework assignment should take approximately _2 hours_, but it may be longer for students who are not as familiar with Python. This time estimate also does not include completing the optional bonus question. Completing the central part of Notebook 2 as a class or lab assignment should take approximately _1 to 2 hours_ with the "Practice What You Learned" question taking an additional _1-hour_. The "Practice What You Learned" could also be assigned as a homework assignment for a shorter class.  