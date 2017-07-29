---
layout: default
title: Guided Practice 4.3
---

# Guided Practice for 4.3: The Definite Integral

## Overview

In the last two sections, we have been addressing the question, *How do we find the distance that an object has traveled, if we're only given its velocity, which could be changing continuously over time?* To answer this question, we developed a method of approximating the distance traveled by using a sum of rectangles attached to the velocity graph, which we eventually called a *Riemann sum*. We've noted that as we increase the number of rectangles used in the Riemann sum, the approximation to the area under the curve -- and therefore the distance traveled -- improves. In this section, we formalize this process by defining the last main idea in this course: the **definite integral** of a function.  We introduce the definite integral, discuss methods for evaluating definite integrals, and introduce some helpful computational properties of definite integrals. 

## Learning objectives

__Basic objectives__: Each student is responsible for gaining proficiency with each of these tasks _prior_ to engaging in class discussions, through the use of the learning resources (below) and through the working of exercises (also below). 

- State the definition of the *definite integral* of a function y = f(x) on an interval [a,b]. 
- Given an integral, identify the *limits of integration* and the *integrand*. 
- Explain in plain English what the definite integral of a function tells you. 
- Evaluate the definite integral of a function if the function is defined as a graph with nice geometric properties. (See Activity 4.7.)
- State the properties of a definite integral given before Activity 4.8 and use them to evaluate a definite integral in terms of a previously-known definite integral. 
- Find the average value of a function on an interval. 

__Advanced objectives__: The following objectives are the subject of class discussion and further work; they should be mastered by each student _during_ and _following_ class discussions. 

- Find the *exact* value of the total distance travelled by an object, given its velocity function, if the velocity function is piecewise linear. 
- Given a function g(x) that is a simple linear or polynomial function, find an antiderivative for g(x) and use the antiderivative to evaluate a definite integral.
 

## Learning resources 

To gain proficiency in the learning objectives, use the following resources. You may include other resources if you wish, in addition to or in replacement of the following. 

__Textbook__: In _Active Calculus_, read Section 4.3. Make sure to read actively, working through examples and activities as you go. 

__Video__: Watch the following videos at the MTH 201 YouTube playlist (http://bit.ly/GVSUCalculus). 

- [Quick review: The definite integral](http://www.youtube.com/watch?v=Lp5KsXN4UOQ&list=PL9bIjQJDwfGuXQHuS5Jkmum_CFILoCZX-&index=84) (3:01) 
- [Calculating a definite integral using geometry](http://www.youtube.com/watch?v=oHIH69Ou4DE&list=PL9bIjQJDwfGuXQHuS5Jkmum_CFILoCZX-&index=85) (6:47)
- [Evaluating a definite integral using integral properties](http://www.youtube.com/watch?v=1SqpYAAyBCk&list=PL9bIjQJDwfGuXQHuS5Jkmum_CFILoCZX-&index=86) (8:15)
- [Average value of a function](http://www.youtube.com/watch?v=MQG9Nur4fdM&list=PL9bIjQJDwfGuXQHuS5Jkmum_CFILoCZX-&index=87) (7:35)



## Activities

The following activity is to be done _during_ and _following_ your reading and viewing of the resources. Go to [student.desmos.com](https://student.desmos.com/?prepopulateCode=SA82S) and enter the code `SA82S` along with your name in the format `Last, First`. For example, I would enter my name as `Ballif, Serge`. Complete each part of the activity. Some of these problems will require you to work them out on paper before entering your answer. Practice producing high quality work so that your work is readable and meaningful. You will receive a mark of __Pass__ if each item response shows a good-faith effort to be right and is submitted prior to the deadline. __Remember to use the Piazza discussion board to ask about any questions you have.__
