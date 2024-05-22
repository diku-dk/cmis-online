---
layout: page
title: Lecture 7
permalink: /lec07/
---

<h1>Quasistatic Elastic Simulation with FEM</h1>

<p>This lecture covers theory in 
<a href="{{'assets/slides/Computational_Methods_19___Finite_Element_Method.pdf' | relative_url}}">slides 19</a>
from page 60 to page 66, and contains more detailed explanations of the model of linear elasticity. Furthermore the slides 15, 17 and 18 have relevant supplementary information.
<h1>Reading Material</h1>
<p>We recommend that you spend time making sure you are familiar with tensors and basic definitions from continuum mechanics. Here is a list of resources to help you get up to speed quickly.</p>
<ul>
    <li>Bonet, J., &amp; Wood, R. (2008). MATHEMATICAL PRELIMINARIES. In Nonlinear Continuum Mechanics for Finite Element Analysis (pp. 22-62). Cambridge: Cambridge University Press. <a href="https://doi.org/10.1017/CBO9780511755446.003" target="_blank" rel="noopener">https://doi.org/10.1017/CBO9780511755446.003.</a></li>
    <li>Bonet, J., &amp; Wood, R. (2008). KINEMATICS. In Nonlinear Continuum Mechanics for Finite Element Analysis (pp. 94-133). Cambridge: Cambridge University Press. <a href="https://doi.org/10.1017/CBO9780511755446.005" target="_blank" rel="noopener">https://doi.org/10.1017/CBO9780511755446.005</a>.&nbsp;&nbsp;</li>
    <li>Bonet, J., &amp; Wood, R. (2008). STRESS AND EQUILIBRIUM. In&nbsp;<i>Nonlinear Continuum Mechanics for Finite Element Analysis</i>&nbsp;(pp. 134-154). Cambridge: Cambridge University Press. <a href="https://doi.org/10.1017/CBO9780511755446.006" target="_blank" rel="noopener">https://doi.org/10.1017/CBO9780511755446.006.</a>&nbsp; &nbsp; &nbsp;</li>
    <li>Read chapter 3 in the book notes by Kenny; it outlines the FEM discretization of a linear elastic problem.</li>
</ul>
<h1>Terminology and Notation for the Elastic Cantilever Beam Problem</h1>
<ul>
    <li>This video introduces the basic notation used for describing the domain and boundaries of an elastic beam simulation.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/fZPDmHeuw_A" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>The Equations of Motion for the Beam</h1>
<ul>
    <li>This video introduces the equations of motion (Cauchy equation) for an elastic beam simulation as well as the type of boundary conditions to apply.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/MbvA1dzpEw8" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>The Volume Integral for the Beam</h1>
<ul>
    <li>This video illustrates how the Cauchy equation can be rewritten into a volumetric form, the first step of the finite element method.</li>
    <li>Observe how the change of variables is done to get volume integral into material coordinates.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/zn4qh-jj6SE" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Beam Weak-form Reformulation</h1>
<ul>
    <li>This video shows step-by-step how the volume formulation of the Cauchy equation is changed from the strong form into a corresponding weak form. Step 2 of the finite element method.</li>
    <li>Test yourself: Can you find a slip of tongue in the very last part of this video? (Hint look up definitions of Euler strain tensor and Cauchy strain tensor)</li>
    <li>Test yourself: Observe that in the video the P-terms are sometimes called work other times they are termed (instantaneous) Power, can you explain why (Hint: think of "w" as a virtual displacement or virtual velocity, when would you use one or the other?)</li>
</ul>
<p><iframe src="//www.youtube.com/embed/f44Aw5OjjiI" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Isotropic Linear Elastic Material and Vector (Voigt) Notation</h1>
<ul>
    <li>This video goes into how material behaviour is defined through stress-strain relationships and Lam&eacute; coefficients are introduced.</li>
    <li>The aim is to understand how material modelling works and learn how to convert from tensor to vector notation.</li>
    <li>Covers: <a href="{{'assets/slides/Computational_Methods_19___Finite_Element_Method.pdf' | relative_url}}">slides 19</a> (pages 63-64)</li>
</ul>
<p><iframe src="//www.youtube.com/embed/XgtWrIkXVL8" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Young Modulus and Poisson Ratio</h1>
<ul>
    <li>This video demonstrates how the elasticity matrix from the isotropic linear elastic material can be computed in terms of Young modulus and Poisson ratio. The video builds a little intuition about the Yong modulus and Poisson ratio parameters mean.</li>
    <li>The aim is to learn to work with both Lam&egrave; coefficients and Young modulus and Poisson ratio.</li>
    <li>Test yourself: Argue for how the elasticity matrix depends on the Young modulus.</li>
    <li>Covers: <a href="{{'assets/slides/Computational_Methods_19___Finite_Element_Method.pdf' | relative_url}}">slides 19</a> (page 66)</li>
</ul>
<p><iframe src="//www.youtube.com/embed/VKYmaKv8x8w" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Vector Notation of Strain Definition</h1>
<ul>
    <li>This video shows how the Voight notation can be used for the strain tensor definition</li>
    <li>The aim is to learn the basic math used to convert from tensor to vector notation</li>
    <li>Converting the Cauchy strain tensor definition into the Cauchy strain vector notation.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/R8wW432mF98" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Applying FEM approximation and Galerkin principle</h1>
<ul>
    <li>This video illustrates how to choose the shape function and define the FEM approximation and apply the Galerkin choice for the test functions.</li>
    <li>The aim is to learn that the techniques we have seen for scalar 1D and 2D problems extend to vector problems in 2D and 3D domains, to derive a closed-form solution for the element matrix.</li>
    <li>Test yourself: What is the dimensionality of the B-matrix in 2D for a linear triangle element? What is the dimensionality in 3D for a linear tetrahedral element?</li>
    <li>Test yourself: Prove that you solve K u' = f for a given Young modulus value E then you can find the u-solution for any Young modulus value given by c E where c is some positive number as u = u'/c.</li>
    <li>Covers: <a href="{{'assets/slides/Computational_Methods_19___Finite_Element_Method.pdf' | relative_url}}">slides 19</a> (page 65)</li>
</ul>
<p><iframe src="//www.youtube.com/embed/iPUoSfg-2ZM" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Adding Traction using the FEM method</h1>
<ul>
    <li>This video illustrates how to add traction boundary conditions to an elastic cantilever beam. The video outlines the full process of applying the finite element method to the boundary PDE term all the way through the assembly process.</li>
    <li>The aim is to understand how traction terms are discretized and assembled by defining shape functions for the boundary and using the machinery of the finite element method.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/fYNLj6cQ8ww" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<p>&nbsp;</p>
