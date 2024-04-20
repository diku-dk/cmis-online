---
layout: page
title: Lecture 9
permalink: /lec09/
---

<h1>Dynamic Elastic Simulation with FDM, FVM, and/or FEM</h1>

<p>This lecture covers
<a href="{{'assets/slides/Computational_Methods_21___Build_Your_Own_Simulator.pdf' | relative_url}}">slides 21</a>
.</p>

<h1>Reading Material</h1>
<p>Here is a list of resources to help you learn more.</p>
<ul>
    <li>Chapter 2 and Section 3.4 in <a href="{{'/assets/slides/erleben.13.book.pdf' | relative_url}}">Kenny's book notes</a></li>
    <li>
        <div class="csl-right-inline">J. Teran, S. Blemker, V. Ng Thow Hing, and R. Fedkiw. 2003. Finite volume methods for the simulation of skeletal muscle. In Proceedings of the 2003 ACM SIGGRAPH/Eurographics symposium on Computer animation (SCA '03). Eurographics Association, Goslar, DEU, 68&ndash;74. <a href="https://dl.acm.org/doi/10.5555/846276.846285" target="_blank" rel="noopener">https://dl.acm.org/doi/10.5555/846276.846285.</a>&nbsp;</div>
        Eftychios Sifakis and Jernej Barbic. 2012. FEM simulation of 3D deformable solids: a practitioner's guide to theory, discretization and model reduction. In ACM SIGGRAPH 2012 Courses (SIGGRAPH '12). Association for Computing Machinery, New York, NY, USA, Article 20, 1&ndash;50. <a href="https://doi.org/10.1145/2343483.2343501" target="_blank" rel="noopener">https://doi.org/10.1145/2343483.2343501.</a>&nbsp;
    </li>
    <li>
        <div class="csl-right-inline">Theodore Kim and David Eberle. 2022. Dynamic deformables: implementation and production practicalities (now with code!). In ACM SIGGRAPH 2022 Courses (SIGGRAPH '22). Association for Computing Machinery, New York, NY, USA, Article 7, 1&ndash;259. <a href="https://doi.org/10.1145/3532720.3535628" target="_blank" rel="noopener">https://doi.org/10.1145/3532720.3535628.</a></div>
    </li>
</ul>
<h1>Idealization of a Dynamic Elastic Beam</h1>
<ul>
    <li>This video summarizes the physics equations that are used as part of the finite volume method discretization.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/utHGmsnYQAs" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Median Dual Vertex Centred Control Volume</h1>
<ul>
    <li>This video defines the median dual vertex-centered control volume.</li>
    <li>The aim is to learn how to create and define this type of volume.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/PyDEcsPGqME" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Control Volume Notation and Terminology</h1>
<ul>
    <li>This video introduces notation and terminology that is used when working with the median dual vertex-centred control volume.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/rNBCfHJq8Jo" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Finite Volume Method on The Cauchy Equation</h1>
<ul>
    <li>This video introduces the steps that need to be done in the spatial discretization process.</li>
    <li>The aim is to provide an overview of the process such that students can work out the details themselves.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/8q_Z8SJR22M" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Computing The Deformation Gradient</h1>
<ul>
    <li>This video outlines the math behind computing the deformation gradient.</li>
    <li>The aim is to learn how linear elements and differentials can be exploited to derive an efficient computational formula.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/ezhS3XP8DeI" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Picking The Mesh Layout</h1>
<ul>
    <li>This video outlines a possible mesh layout for how to create a data structure for storing values during simulation.</li>
    <li>The aim is to learn that vector/control volume quantities are stored at vertices and tensors are stored at triangles and edges only keeping geometry information about themselves.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/B3dXubpI0Lo" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>The Clever Rewrite</h1>
<ul>
    <li>This video demonstrates a convenient transformation of the elastic surface (line in 2D) can be conveniently transformed.</li>
    <li>The aim is to learn the technicalities in the mathematical rewrite and be able to account for how this rewrite is connected to the choice of the control volume.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/-JPzaaX8uSI" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Adding Time Discretization</h1>
<ul>
    <li>This video outlines the math for proper time discretization.</li>
    <li>The aim is to learn how the semi-implicit first-order time-stepping method is derived.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/kx7Db71YmR8" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>The Final Numerical Method</h1>
<ul>
    <li>This video summarizes all the past derivations into a step-by-step guide on how to implement the computations</li>
    <li>The aim is to learn how to order the computations and gives an idea for structuring one's own code when implementing a simulator.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/--6CBQdh17U" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Oh no! The Model Collapse Issue</h1>
<ul>
    <li>This video analyzes how the Saint Venant Kirchoff model behaves under extreme extension/compression.</li>
    <li>The aim is to understand when and how material failures may occur with this material model.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/DmF27lbF-Zc" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>