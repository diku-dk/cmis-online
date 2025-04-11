---
layout: page
title: Jupyter Notebooks
permalink: /notebooks/
---
<h1>General information</h1>

<p>Jupyter notebooks are used throughout this course. In order to make the installation of the relatively old meshign libraries we rely on as easy as possible, we have set up different ways of getting the Jupyter notebooks to run. Please choose below if you are a UCPH student or participating in the course online. </p>
    

<h1>UCPH students</h1>

<p>For UCPH students we have prepared a containerized environment where all notebooks run smoothly. In order to access it, UCPH students need to sign up for/into the Electronic Research Data Archive at University of Copenhagen (also called ERDA) at erda.dk. 

Once you have an account, follow this step by step procedure:

* When you are signed in you can see a welcome page.

* Choose the Jupyter icon which brings you to the Data Analysis Gateway (DAG).

* Start your DAG server. This will allow you to choose from a variety of containerized environments, where you choose the 'Computational Models in Simulation'.

* Once you have chosen it, you just have to wait. Especially th first time it will take some time to start up.

* Once it is started you are in a regular jupyter environment. You can make a folder CMIS and upload all the exercise notebooks and files that we make available throughout the course.

And you are ready to code!


<h1>Online students</h1>

<p>Anaconda is used to set up a conda environment for the notebooks. Youc na do this via a local install on your machine or you can also use Google's Colaboratory to work with the notebooks.</p>

<h2>Anaconda</h2>
<p>In order to install Anaconda, go to <a href="https://www.anaconda.com/distribution/">https://www.anaconda.com/distribution/</a> and download the Python 3.7 version. If you already have it installed, you can just downgrade Python like below.</p>
<h3>Conda Environment</h3>
<p>This is how to install and setup your conda environment inside the Anaconda Prompt/Terminal</p>
<pre>conda create -n cmis python=3.7<br />conda activate cmis<br />conda config --add channels conda-forge<br />conda install meshplot<br />conda install ipympl<br />conda install igl<br />conda install wildmeshing<br />conda install jupyter</pre>
<p>When you want to run the Jupyter notebook you have to do</p>
<pre>conda activate cmis<br />jupyter notebook</pre>
<h2>Anaconda issues</h2>
<h3>New MAC chips</h3>
Since Python 3.8 had been released for about a year when Apple Silicon hit the market, Python 3.7 builds for osx-arm64 were never part of the regular build matrix for Conda Forge. This means we need to find a work around for this. Replace the first line in the code box above with the following:
<pre>
## create empty environment <br /> conda create -n cmis <br /> ## activate <br /> conda activate cmis <br /> ## use x86_64 architecture channel(s) <br /> conda config --env --set subdir osx-64 <br /> ## install python, numpy, etc. (add more packages here...) <br /> conda install python=3.7 <br /> </pre>
<h3>Jupyter notebook not opening</h3>
In some cases the Jupyter client gives issue. Go to your Anaconda Prompt/Terminal and enter the cmis environemnt. Once in your cmis environment, it helps to upgrade the jupyter_client like below:
<pre>
pip install --upgrade jupyter_client 
</pre>

<h1>&nbsp;Python Tips in General</h1>
<p>&nbsp;The official site offers documentation, tutorials, references to books, etc.</p>
<ul>
    <li>For Python Basics: <a href="http://www.python.org">www.python.org</a>.</li>
    <li>A nice tutorial on Python basics including some numpy and scipy. <a href="http://cs231n.github.io/python-numpy-tutorial/">http://cs231n.github.io/python-numpy-tutorial/&nbsp;</a></li>
    <li>Whirlwind tour of Python: <a style="font-family: sans-serif; font-size: 1rem;" href="https://github.com/jakevdp/WhirlwindTourOfPython">https://github.com/jakevdp/WhirlwindTourOfPython</a><span style="font-family: sans-serif; font-size: 1rem;"> .</span></li>
    <li>For Data Science in Python: <a style="font-family: sans-serif; font-size: 1rem;" href="http://github.com/jakevdp/PythonDataScienceHandbook">http://github.com/jakevdp/PythonDataScienceHandbook</a><span style="font-family: sans-serif; font-size: 1rem;">&nbsp;</span></li>
</ul>
<p>The last two links are excellent books, freely available online with Jupyter notebooks for the examples.</p>
