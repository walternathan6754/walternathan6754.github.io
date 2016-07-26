---
layout: default
title: Metadynamics
modal-id: 2
date: 2014-07-15
img: Metadynamics.png
keywords: Wikipedia Metadynamics
link: https://en.wikipedia.org/wiki/Metadynamics
publication: <i>Metadynamics Technique Implemented into GROMACS</i>,
publication_status: To be submitted
publication_link: 404

description: Traditionally to study material behavior from an atomistic scale, researchers use molecular dynamics and Monte Carlo simulations to computationally explore the structure and dynamics of materials.  However, molecular dynamics, which numerically integrates Newton's equation of motion, is limited in temporal scale to microseconds.  Similarly, Monte Carlo, which randomly samples system configurations, lacks dynamical information.  To overcome the limitations of molecular dynamics and Monte Carlo, metadynamics has been recently proposed and used to perform advanced sampling simulations for various applications.  Metadynamics applies potential energy penalty functions to bias systems to overcome large energy barriers inhibiting dynamical behavior.  Typically, at low temperatures, these large energy barriers are only overcome during macroscopically long time behavior, orders of magnitude larger in scale than accessible by molecular dynamics.  By utilizing metadynamics, we are able to simulate long time dynamics and transient events.  We have thus used metadynamics to study the long time dynamics of glassy systems experiencing dynamical arrest, the kinetic behavior of crystal nucleation, and look to extend our studies to surface behavior and protein folding.  Other interesting work with metadynamics has used the method to study dislocation diffusion, Arrhenius nature of supercooled liquids, etc. A descriptive schematic movie of the method and a movie of the simulation from the real space and energy space perspective can be found below <div align="center"><iframe width="400" height="300" src="https://www.youtube.com/embed/1oWJ4-69f6E" frameborder="0" allowfullscreen></iframe> <iframe width="400" height="300" src="https://www.youtube.com/embed/C_FAx7GbYmI" frameborder="0" allowfullscreen></iframe></div>

additional_comments: We have implemented the metadynamics method into <strong><a href="http://www.gromacs.org/" style="color:#047878"> GROMACS </a></strong>, an open source molecular dynamics package.  The code has been fully parallelized for efficiency, and has been benchmarked with the Kob-Andersen model liquid and the monoatomic Lennard-Jones model Argon.  For information about the code or to request access to the code, please contact me.

---
