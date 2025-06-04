This repository contains a python-implementation of the FC-GCG method for a specific model problem.
The model problem is a non-smooth optimization problem of the form $$\min_{v_j\in\mathbb{R}^n,j=1,\dots,N}\frac{1}{2}\lVert\sum_{j=1}^NK_jv_j-y_d\rVert_2^2+\alpha\sum_{j=1}^N\lVert v_j\rVert_2$$.
