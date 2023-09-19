---
content_type: page
description: This section contains course meeting times, course description, course
  goals, course requirements, collaboration policy, prerequisites and calendar table.
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: 0fe70028-e5b8-3fb2-cf17-324c4c113b28
---

Course Meeting Times
--------------------

Lectures: 2 sessions / week, 1.5 hours / session

Course Description
------------------

This course will cover a collection of geometric techniques that apply broadly in modern algorithm design. The exact topics covered will depend on student interest, but a (perhaps overly ambitious) set of possibilities includes:

### Spectral Graph Theory

Graph Laplacians and their eigenvalues, connections to random walks and mixing, isoperimetric and Cheeger inequalities, expanders, and random graphs. Applications to include graph cutting, clustering, approximate counting, disjoint path problems, routing, and graph drawing.

### Convex Geometry

Geometric properties of high-dimensional convex bodies, Fritz John's theorem and isotropy, Brunn-Minkowski and isoperimetric inequalities, concentration of measure and connections to probability theory. Applications to include volume computation and convex programming.

### Multiplicative Weights

The multiplicative weights update method, its geometric meaning, and the many ways that it appears in modern computer science, with a focus on its use in optimization. Applications to include fast approximation algorithms for graph problems, "boosting" in learning and complexity theory, online algorithms, and zero-sum games.

### Iterative Methods for Linear Algebra

How to use geometric information to quickly solve linear systems and eigenvalue problems. Will cover basic iterative methods, the Lanczos algorithm, conjugate gradients, preconditioning, and how spectral graph theory can be used to improve the construction of preconditioners.

### Lattices and Basis Reduction

Basic properties of lattices, Minkowski's theorem, and the LLL algorithm. Applications to include solving low-dimensional integer programs and breaking cryptosystems.

### LP- and SDP-based Approximation Algorithms for NP-Hard Problems

Linear and semidefinite programming relaxations of NP-hard problems, rounding techniques, and primal-dual methods.

Course Goals
------------

*   To learn a collection of powerful (and interrelated) mathematical techniques for algorithm design
    *   Topics picked to be both mathematically interesting and practically useful
    *   Will sometimes have long mathematical interludes, but always with proportional algorithmic payoffs
*   To be able to apply these tools directly to your research
    *   Whether your work is theoretical or applied
    *   I'll suggest open research questions whenever possible

Course Requirements
-------------------

The course requirements will comprise two parts:

1.  Problem sets, and
2.  Scribe notes

### 1\. Problem Sets

I do not want this course to present an onerous workload, but I do want to give out enough problems to allow people to really learn the material. Since this is an advanced graduate class, I believe that students are capable of deciding for themselves how best to make this tradeoff. As such, I will hand out problem sets for each major topic and correct them, but I will not expect you to do all of the problems that I distribute. I will expect students to do as many as is necessary for a good-faith effort to learn the material. I recommend a total equivalent to at least two graduate problem sets over the course of the semester. Undergraduates taking this class will have a slightly more concrete set of requirements in which the number of required problems will be specified more precisely.

### 2\. Scribe Notes

I would like to have scribes for every lectures. Each student should do his/her fair share of these.

Collaboration Policy
--------------------

Collaboration is encouraged on the problem sets. However, you should think about the problems yourself before discussing them with others. Furthermore, you must write your solutions up individually and understand anything that you hand in. If you do collaborate, you must acknowledge your collaborators in your writeup. Use of outside sources is strongly discouraged; if, however, you do use an outside source, you must reference it in your solution.

Prerequisites
-------------

This is a graduate-level class and will move fairly quickly. We shall assume a significant level of mathematical maturity. The formal prerequisites are fairly minimal however; they consist of:

*   Multivariable Calculus (18.02)
*   Linear Algebra (18.06)
*   Basic Algorithms, and
*   Basic Probability

Some experience with algorithms beyond the introductory level will be helpful, but it is not strictly necessary.

Calendar
--------

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
SES #
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
KEY DATES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Spectral Graph Theory**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Linear algebra review, adjacency and Laplacian matrices associated with a graph, example Laplacians
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
Properties of the Laplacian, positive semidefinite matricies, spectra of common graphs, connection to the continuous Laplacian
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
Courant-Fischer and Rayleigh quotients, graph cutting, Cheerger's Inequality
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
(Lazy) random walks, their stationary distribution and l2-convergence, normalized Laplacian, conductance, Monte Carlo methods
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
Monte Carlo methods continued, approximate DNF counting, approximating the permanent of 0-1 matrices
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}
Diameters and eigenvalues, expander graphs
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}
Nonblocking routing networks, local and almost-linear time clustering and partitioning, Lovasz-Simonovits Theorem
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
Local and almost-linear time clustering and partitioning (cont.), PageRank, introduction to sparsification
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}
Sparsification (combinatorial and spectral), effective resistance, matrix pseudoinverses and tail bounds
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}
Spectral sparsification (cont.), introduction to convex geometry
{{< tdclose >}}
{{< tdopen >}}
Problem set 1 due
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Convex Geometry**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}
Polar of a convex body, separating hyperplanes, norms and convex bodies, Banach-Mazur distance, Fritz John's theorem
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}
Separating hyperplanes (cont.), Banach-Mazur distance, Fritz John's theorem, Brunn-Minkowski inequality
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}
Brunn-Minkowski inequality (cont.), Brunn's theorem, isoperimetric inequality, Grunbaum's theorem
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
Approximating the volume of a convex body
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}
Random sampling from a convex body (cont.), grid walk, introduction to concentration of measure
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}
Concentration of measure and the isoperimetric inequality, Johnson-Lindenstrauss theorem
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}
Johnson-Lindenstrauss theorem (cont.), Dvoretsky's theorem
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Lattices and Basis Reduction**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}
Lattices, fundamental parallelepiped and dual of a lattice, shortest vectors, Blichfield's theorem
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}
Minkowski's theorem, shortest/closest vector problem, lattice basis reduction, Gauss' algorithm
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}
LLL algorithm for lattice basis reduction, application to integer programming
{{< tdclose >}}
{{< tdopen >}}
Problem set 2 due
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Iterative Methods for Linear Algebra**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}
Iterative methods to solve linear systems, steepest descent
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}
Convergence analysis of steepest descent and conjugate gradients
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
23
{{< tdclose >}}
{{< tdopen >}}
Preconditioning on Laplacians, ultra-sparsifiers
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Multiplicative Weights**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
24
{{< tdclose >}}
{{< tdopen >}}
Multiplicative weights
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
25
{{< tdclose >}}
{{< tdopen >}}
Multiplicative weights and applications to zero-sum games, linear programming, boosting, and approximation algorithms
{{< tdclose >}}
{{< tdopen >}}
Problem set 3 due
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}