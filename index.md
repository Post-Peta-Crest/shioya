---
title: Development of a Numerical Library based on Hierarchical Domain Decomposition for Post Petascale Simulation
---

# Team Description

* PI: Ryuji Shioya (Toyo University)
* co-PI: Masao Ogino (Nagoya University) and Seiichi Koshizuka (University of Tokyo)
* Research Period: 2011 -- 2018
* [Research highlights in pdf]({{ site.baseurl }}/brochure-shioya-2017.pdf)

# Published Software

* [LexADV Library](https://adventure.sys.t.u-tokyo.ac.jp/lexadv/)

---

# ADVENTURE System - Easy to Run Faster with Large Data On Post-Petascale Supercomputers

## Overview
We have been developing an open source system software called ADVENTURE system. The ADVENTURE system is a general-purpose parallel finite element analysis system and can simulate a large scale analysis model with supercomputer like the Earth Simulator or K-computer. In the ADVENTURE system, HDDM (hierarchical domain decomposition method), a very effective technique for large-scale analysis, was developed.
 
Our aim in this project is to develop a numerical library based on HDDM that is extended to pre and post processing parts, including mesh generation and visualization of large scale data, for the Post Petascale simulation.

In this project, LexADV, an open source software library, is developed for the extreme-scale numerical simulations in continuum mechanics.

# DDM Iterative Solver (LexADV_TryDDM)
* Linear solver for Schur complement (condensed) system
* Fast and stable convergence by using a Scaled-BDD method
* High parallel efficiency by 2-level domain decomposition

![f1]({{ site.baseurl }}/img/fig01.jpg)

# Parallel Framework for Particle Simulations (LexADV_EMPS)
* Bucket-based domain decomposition
* Dynamic load balancing
* Halo exchange pattern generation for communication

![f2]({{ site.baseurl }}/img/fig02.jpg)

# DSL for Continuum Mechanics (LexADV_AutoMT)
* Convenient tool to program vector/matrix/tensor operations
* LaTeX equation conversion to C/Fortran code

![f3]({{ site.baseurl }}/img/fig03.jpg)

# Examples of Numerical Simulation
Tsunami running-up and inundated simulation for Fukushima Daiichi Nuclear Power StationÅ\using explicit MPS method and dynamically load balancing technique

![f4]({{ site.baseurl }}/img/fig04.jpg)

# Project members:

Ryuji Shioya (Toyo Univ.), Masao Ogino (Nagoya Univ.), Seiichi Koshizuka (Univ. of Tokyo), Hiroshi Kawai, Yasushi Nakabayashi, Hongjie Zheng (Toyo Univ.), Yoshitaka Wada (Kindai Univ.), Amane Takei (Univ. of Miyazaki), Daisuke Tagami (Kyushu Univ.), A.M.M. Mukaddes (SUST), Shin-ichiro Sugimoto, Yasunori Yusa (Tokyo Univ. of Science), Hiroshi Kanayama (Japan Women's Univ.)
Contact: shioya@toyo.jp

![f5]({{ site.baseurl }}/img/fig05.jpg)
