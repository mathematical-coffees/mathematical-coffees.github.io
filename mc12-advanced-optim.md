---
layout: page
title: "Advanced non-smooth optimization"
description: "Friday January 16th, 14h-16h30"
header-img: "img/2190035671_bed944180e_o.jpg"
---

Slides
----

- [Gabriel Peyré](http://www.gpeyre.com), CNRS and ENS, [First Order Splitting Schemes](../slides/mc12-peyre.pdf).
- [Jalal Fadili](https://fadili.users.greyc.fr/), ENSICaen, [Primal Dual Methods](../slides/mc12-fadili.pdf).


Computational resources
----

- [Scikit-Learn](http://scikit-learn.org/): machine learning in Python, contains implementations of many basic proximal splitting methods.
- [The numerical Tours of Signal Processing](http://www.numerical-tours.com) (in Matlab, Python and Julia) contains a section dedicated to convex optimization, with applications.
- [CVX](http://www.cgal.org/): interface for several conic program for small/medium size linear/quadratic/psd optimization problems. Also in [Python](http://www.cvxpy.org/en/latest/).
- [TFOCS](http://cvxr.com/tfocs/): similar to CVX, but using first order (proximal) splitting scheme instead of interior point methods.
- [SPAMS](http://spams-devel.gforge.inria.fr/): state of the art sparse solver, including homotopy/LARS.

Bibliography
----

Here is a (biased) bibliography related to the lectures.

- [_Convex Optimization_](http://stanford.edu/~boyd/cvxbook/), Boyd and Vandenberghe: basics of convex programming, including interior point methods.
- [_Convex Analysis and Monotone Operator Theory in Hilbert Spaces_](https://link.springer.com/book/10.1007%2F978-1-4419-9467-7), Heinz H. Bauschke, Patrick L. Combettes: the definitive theory-oriented book on proximal methods.
- [Optimization with Sparsity-Inducing Penalties](http://lear.inrialpes.fr/people/mairal/resources/pdf/ftml.pdf), Francis Bach, Rodolphe Jenatton, Julien Mairal and Guillaume Obozinski: a review of proximal splitting schemes for sparsity enforcing regularizations.
- [Proximal Algorithms](http://stanford.edu/~boyd/papers/prox_algs.html), N. Parikh and S. Boyd: another review article (see also [this review](http://stanford.edu/~boyd/papers/admm_distr_stats.html) for ADMM/DR methods).
