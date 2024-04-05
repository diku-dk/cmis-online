---
layout: page
title: Lecture 6
permalink: /lec06/
---

<h1>Introduction to Finite Element Method </h1>

<p>This lecture covers theory in <a class="instructure_file_link instructure_scribd_file inline_disabled" title="slides_19.pdf" href="https://absalon.ku.dk/courses/72771/files/8258604?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258604" data-api-returntype="File">slides_19.pdf</a>&nbsp;from page 1 to page 48.</p>
<h1>Reading Material</h1>
<ul>
    <li>The Finite Element Method: its Basis and Fundamentals by O.C. Zienkiewicz, R.L. Taylor, J.Z. Zhu, Chapter 1 - The Standard Discrete System and Origins of the Finite Element Method, <a href="https://doi.org/10.1016/B978-1-85617-633-0.00001-0" target="_blank" rel="noopener">https://doi.org/10.1016/B978-1-85617-633-0.00001-0.</a></li>
    <li><a href="https://doi.org/10.1016/B978-1-85617-633-0.00001-0" target="_blank" rel="noopener"></a>The Finite Element Method: its Basis and Fundamentals by O.C. Zienkiewicz, R.L. Taylor, J.Z. Zhu, Chapter 2 - Problems in Linear Elasticity and Fields, <a href="https://doi.org/10.1016/B978-1-85617-633-0.00002-2" target="_blank" rel="noopener">https://doi.org/10.1016/B978-1-85617-633-0.00002-2</a>.</li>
    <li>The Finite Element Method: its Basis and Fundamentals by O.C. Zienkiewicz, R.L. Taylor, J.Z. Zhu, Chapter 6 - Shape Functions, Derivatives, and Integration, <a href="https://doi.org/10.1016/B978-1-85617-633-0.00006-X" target="_blank" rel="noopener">https://doi.org/10.1016/B978-1-85617-633-0.00006-X.</a>&nbsp;</li>
</ul>
<h1>Five steps of the finite element method</h1>
<ul>
    <li>This video presents an overview of the five logical steps in the mathematical recipe that makes up the finite element method.</li>
    <li>This video aims to give an overview of the steps we will learn about in later videos.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/SbIudfXwlTE" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>A simple problem for learning finite element method by example</h1>
<ul>
    <li>This video presents a simple PDE problem that we will use later to learn the five steps of the finite element method recipe.</li>
    <li>The aim is to understand terms such as governing equations, and strong forms, and build intuition about what type of unknown functions are solutions to our problem.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/w0_K1k3JvrI" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Step 1 how to rewrite into a volume integral</h1>
<ul>
    <li>This video explains how a trial function is used to rewrite the original partial differential equation into a volume integral form which is mathematically equivalent, meaning it has the same solution as the original problem.</li>
    <li>The aim is to learn how trial functions enable one to convert a problem with multiple equations into a single scalar equation that is equivalent to the original problem. The key to this is to learn how trial functions work as masks on the domain to extract boundary and interior as needed.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/74gKCaS4xvo" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Step 2 how to apply integration by parts</h1>
<ul>
    <li>This video explains how to rewrite the original volume integral by using integration by parts.</li>
    <li>This video aims to learn that integration by parts reduced the differentiability requirement for the unknown y function and how the trial functions are affected by this.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/63K49iTNO9Q" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Step 3 how to create an approximation</h1>
<ul>
    <li>This video shows how the shape functions are used to create an interpolating approximating function and outline the linear 1D shape function known as the hat function.</li>
    <li>The aim is to understand how approximations are used in the finite element method and to be able to define the hat-function and computational mesh.</li>
    <li>Test yourself: Is it a problem that shape functions are non-smooth at the discrete x-values (the mesh nodes)?</li>
</ul>
<p><iframe src="//www.youtube.com/embed/6bU3cI5ak_4" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Step 4 choosing the trial function</h1>
<ul>
    <li>This video shows how to use the Galerkin assumption to define the trial function and how the substitution of this specific trial function results in a final linear system.</li>
    <li>The aim is to learn how to use the Galerkin method to reuse shape functions and derive a discrete system.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/uCTH1WplXzU" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Step 5 Compute a solution</h1>
<ul>
    <li>This video shows how all pieces come together into a linear system that can be solved using your favourite solver.</li>
    <li>The aim is to show that one needs to add boundary conditions before solving the discrete problem.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/kwP0ogahynk" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Introduction to local shape functions and elements</h1>
<ul>
    <li>This video introduces the idea of local shape functions and the assembly process.</li>
    <li>Test yourself: Obviously, the dimensionality of the integral with global shape functions does not match the dimensionality of the local shape functions are not the same. Hence, the main equation in this video is mathematical incorrect but intuitively correct. Can you explain how to fix the "math" such that the equation is correct, in other words, what went wrong?</li>
</ul>
<p><iframe src="//www.youtube.com/embed/maAXGbYbkNU" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Elements from piecewise continuous integrals</h1>
<ul>
    <li>This video explains how the global setting is connected to the local setting using the property of rewriting the global integral into a sum of piecewise continuous integrals.</li>
    <li>The aim is to learn that the non-smoothness of global shape functions at discrete nodes is not an issue as this vanishes when using the local shape functions.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/on62gZQOJrY" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Redoing simple problems with local shape functions</h1>
<ul>
    <li>This video shows how the local linear hat functions are substituted to derive a closed-form solution for the local K matrix of the simple test problem.</li>
    <li>The aim is to show how the local elements are related to the local K matrix's dimensionality.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/glSpoW4dBqg" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>A 2D problem and its computational mesh and shape functions</h1>
<ul>
    <li>This video presents a 2D problem that we will use the FEM method on later. It defines important concepts and notations that will be reused in later videos. In particular, the ideas of a triangular computational mesh are presented and local shape functions for linear triangle elements are derived.</li>
    <li>The aim is to learn how to extend the ideas of the 1D hat shape functions into the equivalent 2D concept for a triangle mesh.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/Qfs87Uquok8" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Computing the value and derivative of local shape functions in 2D</h1>
<ul>
    <li>This video goes into the details of how to compute the value of the local shape functions for a linear triangular element as well as their derivatives.</li>
    <li>The aim is to learn the basic formulas that are needed later when we apply the finite element method to our 2D problem.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/TpTsCW2fNiM" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Getting derivatives of shape functions from geometry</h1>
<ul>
    <li>This video outlines a different approach for deriving equations for the shape function derivatives.</li>
    <li>The aim is to obtain a geometric intuition about gradients of shape functions.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/dmENyEcN6cE" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Applying the finite element method to a 2D scalar problem</h1>
<ul>
    <li>This video shows how to explain local shape functions and Galerkin's assumption to quickly derive a closed-form solution for computing local element matrices.</li>
    <li>The video aims to demonstrate that as soon as computational mesh, shape, and trial functions are chosen the finite element method essentially boils down to doing integration by parts before evaluation/deriving local element matrices/vectors.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/9sQuai1DTgI" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Finite element assembly process using scattering approach</h1>
<ul>
    <li>This video demonstrates the assembly process for a 2D Poisson problem using local element matrices scattering into the global matrix.</li>
    <li>The video aims to learn how a face-indexed array combined with an array of local element matrices can be used for efficient local-to-global indexing in the assembly process, and how the mesh connectivity and memory access patterns in the global matrix are related.</li>
    <li>Test yourself: Consider how to parallelize the scatter-assembly approach. What difficulties can you see with this approach (Hint: think about race conditions and load-balancing).</li>
</ul>
<p><iframe src="//www.youtube.com/embed/-t6FbQhbJIw" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Block indexing in the assembly process</h1>
<ul>
    <li>This video shows how to efficiently index into an array of local element matrices.</li>
    <li>The aim is to learn how to find the block size of element matrices and compute indexing correctly.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/XInSuHIYA1U" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Pseudocode for the assembly process</h1>
<ul>
    <li>This video demonstrates how "scattering" and block indexing are combined into a pseudo-code algorithm for the assembly process. A gathering approach is sketched too.</li>
    <li>The aim is to learn what data structures and computations to use in implementing a finite element assembly process using a two-pass scattering approach and understands parallelization issues.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/WT6gdmg0jQ0" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Implicit assembly process</h1>
<ul>
    <li>This video shows how to avoid doing an assembly process and instead use an implicit representation of the global matrix.</li>
    <li>The aim is to learn how to use the implicit representation to efficiently compute matrix-vector products in an iterative solver, and understand the pros and cons of applying direction methods vs iterative methods. Be able to explain the relationship to a gathering assembly process.</li>
    <li>Self-test: There is an index typo when the pseudocode is written up, can you spot it? (answer, Ke(l,i) should be Ke(l,0) and similar)</li>
</ul>
<p><iframe src="//www.youtube.com/embed/CZBlW1XYvc0" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>The assembly process of higher dimensional problems</h1>
<ul>
    <li>This video shows what happens when the unknown function in the finite element method is a vector function and not a scalar. Elastic forces are used as a working example.</li>
    <li>The aim is to learn how block size is affected for higher-dimensional problems and how to use interlaced vs non-interlaced memory patterns of unknown variables.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/9hANczlXzFM" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Process of elimination to reduce the size of the system of equations</h1>
<ul>
    <li>This video illustrates how boundary conditions after an assembly can be used to eliminate boundary nodes in the final global system.</li>
    <li>The aim is to learn how to use boundary conditions in the assembly process.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/PjClc3-Ctv8" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Algorithm for modified assembly to include boundary conditions</h1>
<ul>
    <li>This video shows how the elimination of boundary values is related to modifying the assembled global matrices/vectors such that boundary conditions are included. It is shown how "full form", "reduced form" and "extended reduced forms" are related to each other.</li>
    <li>The aim is to learn the algorithm for modifying an assembled system to handle boundary conditions and provide an overview of different variations of the modification algorithm.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/xaWYVh_RDyk" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Implicit handling of boundary conditions in reduced forms</h1>
<ul>
    <li>This video shows how to extend the previous algorithm that used an implicit representation of the global to evaluate a matrix-vector product to include boundary conditions too.</li>
    <li>The aim is to learn how the matrix-vector algorithm handles boundary conditions using existing implicit function evaluation and index masks.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/FP9FYcpADCI" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<p>&nbsp;</p>