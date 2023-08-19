# Introduction 

<!--- TODO: fis this part --->
A very good knowledge of calculus in one and multiple variables is needed, as well as linear algebra: basis, vectors, change of basis, diagonalization, eigenvectors and eigenvalues. This is the basic which is needed to understand basic physics concepts of classical mechanics and ED; further mathematical methods will be taught during the courses and will be needed to (try to) understand qm and approach qft in eventual major studies

and differential equations 

<!--- end here --->


These are my notes for undergraduate Classical Mechanics. I'll add a bunch more stuff here later I think but for now this is about it. This document is being created using notes from the classical mechanics classes I took as well as from the book Classical Mechanics by John R. Taylor {cite}`taylor2005classical` with some supplementary material from the book Classical Mechanics of Particles and Systems by Thornton and Marion. {cite}`thornton2004classical`

This is a combination of 2 classes and those 2 classes cover chapters 1-11, and chapter 15 in Taylor. 

The goal of Classical Mechanics is to learn to think in a more advanced way. We will begin by reviewing some basic stuff from introductory physics but solving them in possibly a more sophisticated manner or by removing some assumptions that we made in introductory physics. For example in many problems we will no longer ignore air resistance or friction. 

The other important bit about these notes is that they are written almost entirely in Jupyter Notebooks. This means that we can more easily make plots and solve problems numerically. This is done with the python libraries `numpy`, 
`matplotlib`, and `scipy`. We can also sometimes solve some problems analytically with the `sympy` library and aside from markdown (and LaTeX) we can use the `display` function and `Math` class from `IPython.display` to render nice looking equations. 

```{tableofcontents}
```