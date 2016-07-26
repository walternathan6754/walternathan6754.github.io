---
layout: default
title: Plasticity
modal-id: 5
date: 2014-07-15
img: Plasticity.png
keywords: Strain Space Hyperplasticity
link: http://www.sciencedirect.com/science/article/pii/S0378475412001693
publication: <i>Extending a Strain Space Formulation for Plasticity to Rate-Hardening Materials and Finite Rotations</i>,
publication_status: Submitted to Mathematics and Computers in Simulation
publication_link: 404

description: We explore, for the first time, the use of an analytical solution for associative flow, von Mises plasticity with rate hardening in a hydrocode, in particular an arbitrary Lagrangian-Eulerian (ALE) hydrocode.   The analytical solution explored is of particular relevance for hydrocodes because high-speed deformation causes rate hardening to play a more important role.  Its importance stands in contrast to other analytical solutions that are for lower speed flows and that do not accommodate rate hardening.  Also in this article, using a previously published approach as an example, the analytical solution for the rate hardening solution is recast into a method wherein deviatoric stress is algebraically related to the current total and plastic strain, i.e., it is not dependent on the previous time step’s value for deviatoric stress.  That recasting allows for strain to become the primary advection variable as opposed to stress, which is the traditional variable but for which there is no conservation law.  Various aspects of the analytical solution’s value is explored, including how it mitigates issues with the underlying flow stress model, its sensitivity to ALE mesh relaxation, and the impact of artificial viscosity.

additional_comments:  We performed this exploration with the Los Alamos production code FLAG.  FLAG is a large scale program for studying material deformation on a continuum scale.  The code set is written in a mixture of AJAX and FORTRAN77.  We extended the program to be able to solve the constituent equations for plasticity with our new analytical solution.
---
