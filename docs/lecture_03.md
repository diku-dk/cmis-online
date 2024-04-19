---
layout: page
title: Lecture 3
permalink: /lec03/
---

<h1>Advanced Finite Difference Method Techniques</h1>

<p>This lecture covers slides 11</p>
<h2>Reading Material</h2>
<ul>
    <li>Real-time Fluid Dynamics for Games by Jos Stam (2003), GDC 2003 Conference proceedings: Game Developers Conference. <a href="https://www.josstam.com/_files/ugd/cf1fd6_9989229efbd34a26ba5ccd913721a2ac.pdf" target="_blank" rel="noopener">https://www.josstam.com/_files/ugd/cf1fd6_9989229efbd34a26ba5ccd913721a2ac.pdf</a>&nbsp;</li>
</ul>
<h2>"Straightforward" Time Integration</h2>
<p>This video will</p>
<ul>
    <li>Introduce you to the aspect of spatial vs. time derivatives</li>
    <li>Introduce what a scalar field is</li>
    <li>Show how to perform "simple" time-integration&nbsp;</li>
    <li>Covers: slides 11 (page 51)
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/nhoJRMTFfhs?si=TTxpsn522-0RmJF4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<h2>Advanced Time Integration</h2>
<p>This video will</p>
<ul>
    <li>
        <p>Explain the idea and concept behind the semi-lagrangian time integration method</p>
        <li>Covers: slides 11 (pages 52-60)
    </li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/gPw2e7Ife8w?si=mfg2EU24QAoCMgWb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<h2>Advection Examples</h2>
<p>This video shows one simulation run of a rotating peak-like shape. Observe that the advection problem simply rotates the shape of the function. Hence, if the "numerics" is done well then the shape of the peaks should be preserved when doing one full revolution.</p>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/ORo8pJ-aAOU?si=2vAo5HPOJfBTm2as" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<p>In this video, we show a sequence of simulation results demonstrating what happens when the time-step size and grid spacing are changed. Observe that the shape of the peak function changes after doing one full revolution. This way one can find a time-step and grid-spacing size that preserves the shape of the peaks sufficiently well.</p>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Gf084_Jqbq0?si=PnlyQDjlPSP7m58H" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
