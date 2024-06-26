---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

* **Airborne Collision Avoidance System X (ACAS X)**
  * MIT Lincoln Laboratory - Group 42
  * Software for generating airborne collision avoidance advisories for manned and unmanned aircraft
    * Logic formulated as a Markov decision process
    * Computational strategies employed for handling large state space, including
      * Multilinear interpolation
      * Parallel computing
    * Contributed visualization tool for analysis of policy evolution through the course of the value iteration algorithm
  * C++, Julia, MATLAB

* **ClutteredEnvPathOpt.jl** [(repo)](https://github.com/raulgarcia66/ClutteredEnvPathOpt.jl)
  * Rice University - with Illya V. Hicks, Joey Huchette and Miles Olson
  * Package for solving optimal path planning problems in cluttered environments for robots and drones
    <!-- * Formulated as a mixed-integer quadratically-constrained quadratic program (MIQCQP) with disjunctive contraints for assigning footsteps or waypoints to obstacle-free regions -->
    * Implemented the independent branching scheme to formulate obstacle avoidance disjunctive constraints, including an algorithm for obtaining the necessary biclique covers on a special class of graphs
    * Includes infrastructure for creating obstacles, generating obstacle-free regions, and constructing the associated graphs
    <!-- * Disjunctive constraint formulation approaches: -->
      <!-- * Independent branching scheme -->
      <!-- * Big-M -->
  * Julia

* **Audubon_F21** [(repo)](https://github.com/RiceD2KLab/Audubon_F21/tree/SP22)
  * Rice University - Data to Science (D2K) Lab
  * Package for identifying and censusing various colonial waterbird species from UAV imagery of nesting islands
    * Sponsored by Houston Audubon for real-world deployment in their waterbird monitoring studies
    * Employs a Faster R-CNN object detector with a ResNet-50 feature pyramid network backbone, implemented with Detectron2
    * Capable of detecting 10+ species, with the 3 most populous (constituting over 70% of the population) being detected with an AP of over 90% (at an IoU of 0.5)
    * Led experimentation of a customized implementation of Faster R-CNN utilizing a DenseNet backbone
    * Bayesian hyperparameter optimization used for selection of learning rate and decay factor
    * Data augmentation techniques for minority species include horizontal and vertical mirrorings, 90 degree rotations, and random brightness and contrast adjustments
  * Python

* **Forecasting Yearly Battery Replacements**
  * Rice University - Data to Science (D2K) Lab
  * Mentored a team of students on a capstone data science project focusing on forecasting yearly battery replacements for LivaNova's vagus nerve stimulator medical device
  * Team employed survival analysis to generate battery durations for implants for both existing patients and new patients
    * Existing patients: Survival function modeled with a Log-normal Accelerated Failure Time model
    * New patients: Survival function modeled with a Kaplan-Meier estimator
  * 1st Place in the Fall 2022 D2K Showcase