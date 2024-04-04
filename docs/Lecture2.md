<h1>Introduction to Finite Difference Methods (FDM)</h1>

<p>This lecture covers <a class="instructure_file_link instructure_scribd_file inline_disabled" title="slides_11.pdf" href="https://absalon.ku.dk/courses/72771/files/8258608?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258608" data-api-returntype="File">slides_11.pdf</a></p>
<h1>Reading Material</h1>
<ul>
    <li>Ferziger, J.H., Perić, M., Street, R.L. (2020). Finite Difference Methods. In: Computational Methods for Fluid Dynamics. Springer, Cham. <a href="https://doi.org/10.1007/978-3-319-99693-6_3" target="_blank" rel="noopener">https://doi.org/10.1007/978-3-319-99693-6_3</a>, Chapter 3.</li>
</ul>
<h1>Finite difference method basics</h1>
<ul>
    <li>Sampling on a regular grid</li>
    <li>Finite difference approximations in 1D</li>
    <li>Higher-order finite difference approximations</li>
    <li>Covers: <a class="instructure_file_link instructure_scribd_file inline_disabled" title="slides_11.pdf" href="https://absalon.ku.dk/courses/72771/files/8258608?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258608" data-api-returntype="File">slides_11.pdf</a><span class="instructure_file_holder link_holder">&nbsp;(pages 8-16)</span></li>
</ul>
<p><a href="https://youtu.be/kvtzrB5nLKc" target="_blank" rel="noopener">https://youtu.be/kvtzrB5nLKc</a></p>
<h2>Going to higher dimensions</h2>
<ul>
    <li>Extending finite differences to higher-order spatial dimensions</li>
    <li>2D toy example</li>
    <li>Covers: <a class="instructure_file_link instructure_scribd_file inline_disabled" title="slides_11.pdf" href="https://absalon.ku.dk/courses/72771/files/8258608?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258608" data-api-returntype="File">slides_11.pdf</a><span class="instructure_file_holder link_holder">&nbsp;(pages 17-19)</span></li>
</ul>
<p><span class="instructure_file_holder link_holder"><a href="https://youtu.be/PeRqR9nwAtI" target="_blank" rel="noopener">https://youtu.be/PeRqR9nwAtI</a> <br /></span></p>
<h2>Solutions for a 2D toy example</h2>
<ul>
    <li>What is a stencil?</li>
    <li>Definition of the computational domain</li>
    <li>Update formulas</li>
    <li>Covers: <a class="instructure_file_link instructure_scribd_file inline_disabled" title="slides_11.pdf" href="https://absalon.ku.dk/courses/72771/files/8258608?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258608" data-api-returntype="File">slides_11.pdf</a><span class="instructure_file_holder link_holder">&nbsp;(pages 20-23)</span></li>
</ul>
<p><span class="instructure_file_holder link_holder"><a href="https://youtu.be/R6mf-zuSAhU" target="_blank" rel="noopener">https://youtu.be/R6mf-zuSAhU</a> <br /></span></p>
<h2>Boundary conditions</h2>
<ul>
    <li>Dirichlet and von Neumann boundary conditions</li>
    <li>Covers: <a class="instructure_file_link instructure_scribd_file inline_disabled" title="slides_11.pdf" href="https://absalon.ku.dk/courses/72771/files/8258608?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258608" data-api-returntype="File">slides_11.pdf</a><span class="instructure_file_holder link_holder">&nbsp;(pages 24-28)</span></li>
</ul>
<p><span class="instructure_file_holder link_holder"><a href="https://youtu.be/Do_p0cmCnLg" target="_blank" rel="noopener">https://youtu.be/Do_p0cmCnLg</a> <br /></span></p>
<h2>Boundary approaches</h2>
<ul>
    <li>Applying a von Neumann boundary condition on a computational domain</li>
    <li>Eliminating dependent variables</li>
    <li>Using ghost nodes</li>
    <li>Covers: <a class="instructure_file_link instructure_scribd_file inline_disabled" title="slides_11.pdf" href="https://absalon.ku.dk/courses/72771/files/8258608?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258608" data-api-returntype="File">slides_11.pdf</a><span class="instructure_file_holder link_holder">&nbsp;(pages 29-31)</span></li>
</ul>
<p><span class="instructure_file_holder link_holder"><a href="https://youtu.be/zMCnvwC99Jk" target="_blank" rel="noopener">https://youtu.be/zMCnvwC99Jk</a> <br /></span></p>
<h2>Overview of the approaches</h2>
<ul>
    <li>Using update-equations vs. matrix form</li>
    <li>Ghost nodes vs. elimination of variables</li>
    <li>Covers: <a class="instructure_file_link instructure_scribd_file inline_disabled" title="slides_11.pdf" href="https://absalon.ku.dk/courses/72771/files/8258608?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258608" data-api-returntype="File">slides_11.pdf</a><span class="instructure_file_holder link_holder">&nbsp;(page 48)</span></li>
</ul>
<p><span class="instructure_file_holder link_holder"><a href="https://youtu.be/Bstn1L7tyoM" target="_blank" rel="noopener">https://youtu.be/Bstn1L7tyoM&nbsp;</a> <br /></span></p>
<h2>Matrix form</h2>
<ul>
    <li>What is the matrix form?</li>
    <li>Conversion between update-equations and the matrix form</li>
    <li>Covers: <a class="instructure_file_link instructure_scribd_file inline_disabled" title="slides_11.pdf" href="https://absalon.ku.dk/courses/72771/files/8258608?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://absalon.ku.dk/api/v1/courses/72771/files/8258608" data-api-returntype="File">slides_11.pdf</a><span class="instructure_file_holder link_holder">&nbsp;(pages 32-37)</span></li>
</ul>
<p><span class="instructure_file_holder link_holder"><a href="https://youtu.be/sjbtsVFI2TE" target="_blank" rel="noopener">https://youtu.be/sjbtsVFI2TE</a> </span></p>

