---
layout: page
title: Lecture 4
permalink: /lec04/
---

<h1>Curvature Flow an Advanced Example</h1>

<p>This lecture covers slides 12.</p>
<h1>Reading Material</h1>
<ul>
    <li>Level Set Methods and Dynamic Implicit Surfaces by Stanley Osher and Ronald Fedkiw, Chapters 1, 2, 3, 4 and 7, <a href="https://link.springer.com/book/10.1007/b98879" target="_blank" rel="noopener">https://link.springer.com/book/10.1007/b98879</a> (<a class="instructure_file_link instructure_scribd_file inline_disabled" title="osher.fedkiw.03.pdf" href="https://absalon.ku.dk/courses/72771/files/8258596?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258596" data-api-returntype="File">osher.fedkiw.03.pdf</a>)&nbsp;</li>
</ul>
<h1>Introduction to Mean Curvature Flow</h1>
<p>This video will</p>
<ul>
    <li>Introduce the mean curvature flow problem and the partial differential equation (PDE) that describes this flow problem</li>
    <li>Test yourself: Explain to the person sitting next to you intuitively what a mean curvature flow does, what do you think it will be useful for?</li>
    <li>Covers: slides 12 (pages 2-3)</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/HjAd6UvF-Pg?si=rSVKoZcpcHP4Rvbt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<h2>Mathematical Rewriting The Mean Curvature Flow Problem</h2>
<p>This video will</p>
<ul>
    <li>Show how to rewrite the curvature term of the mean curvature flow PDE</li>
    <li>Test yourself: Why does one do this rewrite? Is it not just a lot of fun math for nothing? The two curvature formulas are algebraic equivalent? Try and find good reasons for the rewrite.</li>
    <li>Covers: slides 12 (pages 4-7)</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/DI0qKmke_OU?si=TsQpqdHvaQZY8NVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<h2>Spatial Discretization of Mean Curvature Term</h2>
<p>This video will</p>
<ul>
    <li>Walk through the spatial discretization steps of the&nbsp; mean curvature flow curvature term</li>
    <li>Covers: slides 12 (pages 8-10)</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/QyHeELY3REE?si=XLN4V-aG3ILEIraU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<h2><a href="https://youtu.be/QyHeELY3REE" target="_blank" rel="noopener"></a>Handling Numerical "Side-effects"&nbsp;</h2>
<p>This video will</p>
<ul>
    <li>Show how to deal with numerical considerations such as noise, round-off errors and other things that can destroy your computations</li>
    <li>Test yourself: Make some illustrations of contour shapes on a grid that will cause the numerical issues that are covered in the video. Try and account for the nature that causes the issues to pop up.&nbsp;</li>
    <li>Covers: slides 12 (pages 11-13)</li>
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/YqMJ16qAxG4?si=p4lyHatQkEh2TJtl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<h2>Adding Temporal Discretization</h2>
<p>The video will</p>
<ul>
    <li>Show how to do the temporal discretization of the&nbsp; mean curvature flow temporal derivative</li>
    <li>Test yourself: Try and explain to the person next to you what the intuition is behind the CFL condition. Exactly what is the main idea behind this condition? Try and come up with a flow example problem where a CFL condition would be necessary in order to get the numerical solution correct.</li>
    <li>Covers: slides 12 (pages 14-16)
</ul>
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/wZRX6FFZn0I?si=UGP2GA7ZBgN3YSyK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>