---
published: false
title: Introduction
layout: post
---
The goal of this series of posts will be to archive my
thinking on testing different statistical tests for
complementarities with simulated data. This is an
introduction to the problem.

Let's assume that a firm can use two management techniques
x<sub>1</sub> and x<sub>2</sub>, for instance using
incentive contracts and performance measurement.  The idea
is that the firm can use those management techniques to
maximise the value of the firm, y. In the simplest case y =
b<sub>0</sub> +
b<sub>1</sub>x<sub>1</sub> + b<sub>2</sub>x<sub>2</sub> +
b<sub>3</sub>x<sub>1</sub>x<sub>2</sub> -  d<sub>1</sub>
x<sub>1</sub><sup>2</sup> - d<sub>2</sub> 
x<sub>2</sub><sup>2</sup>. In this formulation, the effects
of interest are linearly separable. The management
accounting techniques may have positive effects on the firm
value (b's) but ultimately diminishing returns takeover
(d > 0). The term of interest is b<sub>3</sub>
x<sub>1</sub>x<sub>2</sub> because it signifies that the two
techniques depend on each other. Incentive contracts are
more valuable with better performance measurement and vice
versa. Some researchers have investigated these type of
relationships with the following OLS regression: 
y = b<sub>0</sub> +
b<sub>1</sub>x<sub>1</sub> + b<sub>2</sub>x<sub>2</sub> +
b<sub>3</sub>x<sub>1</sub>x<sub>2</sub> + e

The problem with this approach (besides neglecting
diminishing returns[^ds]), is that firms will try to optimise
value or less optimistically firms that make bad choices
will disappear. The best choices are not to difficult too
determine.

[^ds]: 
	This is actually more complicated and I will
	probably revisit this later on. Often the y in the
	regression will not be the value of the firm but the
	performance of a division or employee. In that case,
	neglect of the diminishing return can be less of an
	issue. The diminishing returns can often be
	assumed to be mostly driven by the fact that the
	cost of better performance measurement or incentives
	increases very fast than that the accounting
	techniques become less effective at the margin. 
