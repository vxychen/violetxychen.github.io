---
title: 'Block Coordinate Descent Methods for Training Fair Support Vector Machines'
collection: working
permalink: /publications/2021-07-01-working
venue: ''
pubdate: ''
authors: 'Violet (Xinying) Chen'
---

<br/>

**Keywords: fair machine learning, quadratic programming**

Support Vector Machine (SVM) is a popular class of machine learning methods whose training via specialized algorithms tends to outperform general-purpose optimization solvers. Motivated by this advantage, I propose specialized algorithms to train SVMs with fairness guarantees, which is an important task in the growing field of fair machine learning. I focus on SVM formulations that contain a set of convex fairness constraint(s). Utilizing the structure of the dual formulation of this particular form of fair SVM, I design block coordinate descent algorithms to solve these fair SVM models. These algorithms all guarantee an asymptotic convergence to an optimal solution. Numerical experiments demonstrate that these specialized algorithms allow fairness to become a routine of SVM training without increasing the runtime and computational cost relative to training standard SVMs.
