---
layout: page
title: Lecture 8
permalink: /lec08/
---

<h1>Magnetostatics Simulation with the Finite Volume Method</h1>

<p>This lecture covers slides 13. 

<p><span style="font-size: 24pt;">Reading Material</span></p>
<ul>
    <li>Ferziger, J.H., Perić, M., Street, R.L. (2020). Finite Volume Methods. In: Computational Methods for Fluid Dynamics. Springer, Cham. <a href="https://doi.org/10.1007/978-3-319-99693-6_4" target="_blank" rel="noopener">https://doi.org/10.1007/978-3-319-99693-6_4</a>, Chapter 4.</li>
    <li>Ferziger, J.H., Perić, M., Street, R.L. (2020). Complex Geometries. In: Computational Methods for Fluid Dynamics. Springer, Cham. <a href="https://doi.org/10.1007/978-3-319-99693-6_9" target="_blank" rel="noopener">https://doi.org/10.1007/978-3-319-99693-6_9</a>, Section 9.6-9.8, 9.10-11.</li>
</ul>
<p><span style="font-size: 24pt;">Finite Volume Basics</span><span style="font-size: 24pt;">&nbsp;&nbsp;</span></p>
<p>In this video, we will cover:</p>
<ul>
    <li>Introduction to the finite volume method</li>
    <li>The difference between FVM compared to FDM and FEM</li>
    <li>Various verification techniques for FVM</li>
    <li>Covers: slides 13 (pages 1-8)</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/kKkwpvs09qM?si=St8bxfXKn-ynq0Tk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p><span style="font-size: 24pt;">Finite Volume Toy Example</span></p>
<p>In this video, we will cover:</p>
<ul>
    <li>Introducing the finite volume toy example</li>
    <li>Covers: slides 13 (pages 9-10)</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/8If9N9dnGek?si=3ywGUppq7hy01fpY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p><span style="font-size: 24pt;">Gauss Divergence Theorem</span></p>
<p>In this video, we will cover:</p>
<ul>
    <li>Introducing the Gauss Divergence Theorem</li>
    <li>Showcasing its utility for FVM</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/NKb-iqr8a-o?si=4-xCFTZ933-6SIxB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p><span style="font-size: 24pt;">Transport and Flux</span></p>
<p>In this video, we will cover:</p>
<ul>
    <li>Introducing the concept of transport and flux</li>
    <li>Showcasing its utility for FVM</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/yP-k1g337u8?si=rnE91THKhZBIn5Z0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p><span style="font-size: 24pt;">Finite Volume Traits of the Trade</span></p>
<p>In this video, we will cover:</p>
<ul>
    <li>The steps used in the finite volume method</li>
    <li>How to apply the steps on the toy example</li>
    <li>Using the properties of piecewise continuous integrals</li>
    <li>Using the Leibniz rule for differentiation under the integral</li>
    <li>Applying the Midpoint approximation rule</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/x69tAd5dyZA?si=m7VJEgSAONCLA7o_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p><span style="font-size: 24pt;">Finite Volume Mesh Details</span></p>
<p>In this video, we will cover:</p>
<ul>
    <li>Which mesh layout to use</li>
    <li>Where to store different physical quantities</li>
    <li>Different control volume types</li>
    <li>Covers: slides 13 (pages 27-29)</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/64sL_cpFZuE?si=WyxzzKbWOCGhB1l-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p><span style="font-size: 24pt;">Step-by-Step Solution to The Toy Problem</span></p>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/7yCwoqxl5AQ?si=3zD-lMNoAIzPdMWd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p><span style="font-size: 24pt;">Introduction to the Magnetostatic Problem</span>&nbsp;&nbsp;</p>
<p>In this video, we will cover:</p>
<ul>
    <li>Introduction to the Maxwell equations</li>
    <li>Definitions used for electric and magnetic fields</li>
    <li>Definition of the magnetostatic problem for this week</li>
    <li>Visualizations for the solution of the magnetostatic problem</li>
    <li>Covers: slides 13 (pages 47-48)</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/SGOdAjU0IjA?si=ibwgYLlF60hEXFq-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p><span style="font-size: 24pt;">Implementation Details for the Magnetostatic <br />Problem</span></p>
<p>In this video, we will cover:</p>
<ul>
    <li>Problems with discontinuous integrands</li>
    <li>Handling discontinuous integrands</li>
    <li>Covers: slides 13 (pages 56-60)</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/HjqGtu1x1AE?si=TRJbf8h4fhGmnwbR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p>&nbsp;</p>
<p>&nbsp;</p>