---
layout: default
modal-id: 3
title: LiquidLib
date: 2014-07-15
img: LiquidLib.png
keywords: LiquidLib Registration
link: http://zhang-group.github.io/LiquidLib/
publication: <i>LiquidLib&#58 A comprehensive tool for post processing of molecular dynamic simulations of liquids with application to neutron scattering experiments</i>,
publication_status: To be submitted
publication_link: 404

description: Neutron scattering is a highly successful experimental technique for studying structure and dynamics of materials. Often to understand the results of such experiments, computer simulations, including classical and <i>ab initio</i> molecular dynamics, are used to compare to neutron scattering experiments. LiquidLib is a post-processing package for analyzing trajectory data of computer simulations of liquids with application to neutron scattering experiments. LiquidLib allows computation of various statistical quantities including <div class="col-md-6"><ul><li>the pair distribution function</li><li>the structure factor</li><li>the mean squared displacement</li><li>the non-Gaussian parameter</li><li>the four-point correlation</li></ul></div><div class="col-md-6"><ul><li>the velocity auto correlation</li><li>the self and coherent van Hove correlation</li><li>the self and coherent intermediate scattering function</li><li>the bond order parameter</li><li>more to come</li></ul></div><p style="text-align:justify">New quantities to compute can easily be integrated into to the library in the future.  LiquidLib can read molecular dynamics trajectories from the open source packages <strong><a href="http://lammps.sandia.gov/" style="color:#047878"> LAMMPS </a></strong> and <strong><a href="http://www.gromacs.org/" style="color:#047878"> GROMACS </a></strong> and the commercial package <strong><a href="https://www.vasp.at/" style="color:#047878"> VASP </a></strong>. LiquidLib also offers an easy platform to extend the program to be able to read simulation trajectories organized in other file formats not included or from other packages.  Incorporation of materials' neutron scattering lengths to weight the quantities' computations provides results comparable to neutron scattering measurements.  Lastly, LiquidLib is dimensionally independent, which allows for trajectories in higher dimensions to be analyzed. </p>   

additional_comments: LiquidLib was a collaborative development effort by the <strong><a href="http://zhang.npre.illinois.edu/" style="color:#047878"> Zhang Research Group </a></strong>.  The package is open source and licensed under the MIT license.  It was written in C++.  The package is parallelized with OpenMP to increase speed of computation.  The package was developed with intent to be used on UNIX/LINUX like systems (including clusters) but can also run on a Windows machine, however, a make file is not provided for windows users.
---
