---
layout: page
title: Lecture 5
permalink: /lec05/
---

<h1>Computational Meshing</h1>

<p>This lecture covers 
<a href="{{'assets/slides/Computational_Methods_06___Computational_Meshing.pdf' | relative_url}}">slides 6</a>
.</p>
<h1>Reading Material</h1>
<ul>
    <li>Ferziger, J.H., Perić, M., Street, R.L. (2020). Complex Geometries. In: Computational Methods for Fluid Dynamics. Springer, Cham. <a href="https://doi.org/10.1007/978-3-319-99693-6_9" target="_blank" rel="noopener">https://doi.org/10.1007/978-3-319-99693-6_9</a> , Section 9.1-9.5.</li>
</ul>
<h1>Introduction to Meshing</h1>
<ul>
    <li>This video introduces concepts of structured regular grids versus unstructured meshes such as triangle meshes. It shows how to use NumPy to work with vertex and face arrays, defines the orientation of faces, uses meshplot tool for visualization, and how to various existing meshing tools.</li>
    <li>The aim of this video is to learn practical tools to get up on running with code oneself.</li>
    <li>Try to repeat the examples by yourself in your own Jupyter notebook to become familiar with creating your own mesh examples.</li>
</ul>
<p><iframe src="//www.youtube.com/embed/OJH3A1Vno_Q" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>CSG with Signed Distance Fields</h1>
<ul>
    <li>This video explains how a signed distance field is defined and how one can do constructive solid geometry (CGS) operations to create new objects easily from existing signed distance fields of known objects.</li>
    <li>The aim is to obtain intuition about the intrinsic working of CSG operations with signed distance fields.</li>
    <li>Read chapters 7 and 8 in the book <a href="https://link.springer.com/book/10.1007/b97350">Implicit Objects in Computer Graphics </a>, and the paper <a href="https://dl.acm.org/doi/10.1109/TVCG.2005.49">Signed Distance Computation Using the Angle Weighted Pseudonormal.</a></li>
    <li>Supplementary reading: <a href="https://dl.acm.org/doi/10.1145/15886.15904">Constructive solid geometry for polyhedral objects</a></li>
</ul>
<p>
<iframe src="//www.youtube.com/embed/_Ge1HCkEjOs" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe>
</p>
<h1>Simple 3D Examples with PyDistMesh</h1>
<ul>
    <li>This video shows how to create volumetric tetrahedral meshes using CSG operations of signed distance fields</li>
    <li>Get the DistMesh software from <a href="https://pypi.org/project/PyDistMesh/">https://pypi.org/project/PyDistMesh/</a></li>
    <li>The aim is by example to learn how to use CSG for modeling meshes in 3D.</li>
</ul>
<p>
<iframe src="//www.youtube.com/embed/uL8k00L4YLQ" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe>
</p>
<h1>Data Structure for a Tetrahedral Mesh</h1>
<ul>
    <li>This video shows how a tetrahedral mesh can be stored using Arrays in NumPy, how to read a surface mesh from a file and to use a mesh tool on the surface mesh to obtain a tetrahedral mesh.</li>
    <li>Get code from here <a href="https://wildmeshing.github.io/">https://wildmeshing.github.io/</a></li>
    <li>Supplementary paper reading <a href="https://dl.acm.org/doi/10.1145/3197517.3201353">Tetrahedral meshing in the wild</a> and <a href="https://dl.acm.org/doi/abs/10.1145/3386569.3392385">Fast tetrahedral meshing in the wild</a></li>
</ul>
<p><iframe src="//www.youtube.com/embed/KgJHUrwZvcA" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe></p>
<h1>Marching Triangles Introduction</h1>
<ul>
    <li>This video demonstrates the basic principles behind the marching triangles method and outlines the case-by-case analysis that is the key to understanding how the algorithm works.</li>
    <li>The aim of this video is to learn a simple algorithm for meshing and study some of the difficulties in creating a nice "output" mesh.</li>
    <li>This type of algorithm is closely related to contouring algorithms that are used in computer graphics for visualizing implicit surfaces, often referred to as isosurfaces. The same type of algorithm is often used to extract surface meshes from image segmentations. Like getting bone surfaces from a CT image. The "classical" contouring algorithm is considered to be the "marching cubes" method, see the link below. Today many derived methods exist. The contouring idea has also been extended to volume mesh generation and is sometimes called "stuffing", see the paper link below. The marching triangle method we introduced here in 2D can be trivially extended to 3D. This we leave as an optional home programming exercise for those students that like to explore meshing more.</li>
    <li>Supplementary reading: <a href="https://dl.acm.org/doi/10.1145/37401.37422">Marching cubes: A high-resolution 3D surface construction algorithm</a> and <a href="https://dl.acm.org/doi/10.1145/1276377.1276448">Isosurface stuffing: fast tetrahedral meshes with good dihedral angles</a>.</li>
    <li>Covers
<a href="{{'assets/slides/Computational_Methods_06___Computational_Meshing.pdf' | relative_url}}">slides 6</a> (pages 13-17)</li>
</ul>
<p>
<iframe src="//www.youtube.com/embed/WA6pdAxThMY" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe>
</p>
<h1>Marching Triangles made Efficient</h1>
<ul>
    <li>This video explains how to use bitmasks and stencils to efficiently encode all the triangle cases of the marching triangles method.</li>
    <li>The aim of this method is to learn how to efficiently implement typical mesh operations efficiently.</li>
    <li><strong>Test yourself</strong>
        <ul>
            <li>How would you change the algorithm such that vertices in the triangle mesh are only generated once without using comparison of coordinates or advanced data structures like dictionaries etc. (Hint: think about the multipass algorithm and smart indexing)?</li>
            <li>How would you create an embarrassingly parallel version of this algorithm that could run on a GPU?&nbsp; (Hint: think about using a thread for every cell in the grid, how do you avoid race conditions when generating vertices and triangles?)</li>
        </ul>
    </li>
    <li>Covers
<a href="{{'assets/slides/Computational_Methods_06___Computational_Meshing.pdf' | relative_url}}">slides 6</a> (pages 23-25)</li>
</ul>
<p>
<iframe src="//www.youtube.com/embed/SXWtFj-kBfA" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe>
</p>
<h1>Introduction to quality measures</h1>
<ul>
    <li>This video introduces quality measures and histograms as tools to verify if a computational mesh can be expected to behave nicely for simulation purposes.</li>
    <li>The aim is not to get deep into the theory of quality measures but to achieve a good practice of always using multiple measures to inspect a mesh before using that mesh.</li>
    <li>Read about different quality measures in this paper <a href="https://people.eecs.berkeley.edu/~jrs/papers/elemj.pdf">What Is a Good Linear Finite Element? Interpolation, Conditioning, Anisotropy, and Quality Measures</a>. The paper is dense so focus on fair measures in section 6. Particular Table 7 is a quite useful reference.</li>
    <li>Covers
<a href="{{'assets/slides/Computational_Methods_06___Computational_Meshing.pdf' | relative_url}}">slides 6</a> (pages 29-30)</li>
</ul>
<p>
<iframe src="//www.youtube.com/embed/FJVptzqUPEI" width="560" height="314" allowfullscreen="allowfullscreen" data-mce-fragment="1"></iframe>
</p>
<h1>(Optional) Learn more</h1>
<ul>
    <li>You have seen examples of meshing algorithms that use stuffing into an implicit representation above. However, two other types of algorithms are frequently used. One is based on constrained Delaunay triangulations and the other is based on variational meshing. Read these papers for an introduction <a href="https://dl.acm.org/doi/10.1145/2629697">TetGen, a Delaunay-Based Quality Tetrahedral Mesh Generator</a>, and <a href="https://dl.acm.org/doi/pdf/10.1145/1073204.1073238">Variational Tetrahedral Meshing</a>.</li>
    <li>Adaptive quality meshing is another interesting topic. You can play with some 2D software from this <a href="https://h2020-msca-itn-rainbow.github.io/">GRIT</a>.</li>
    <li>There are many open and free tools for segmentation. If you want to create your own meshes to simulate human tissue you may want to check out <a href="https://www.slicer.org/">3D slicer</a>. Here is a link for a tutorial on how to do <a href="https://slicer.readthedocs.io/en/latest/user_guide/image_segmentation.html">image segmentation</a>.</li>
</ul>