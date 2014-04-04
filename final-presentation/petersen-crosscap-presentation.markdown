% Embedding the Petersen Graph on the Cross Cap
% Julius Plenz and Martin Zänker
% 8 April, 2014

Overview
========

1. The *Petersen graph* and its properties
1. Construction of the *cross cap* and its properties
1. Creating an animation in Maya
    1. The cross cap
    1. The Petersen graph
1. Showcasing of the animation

The Kneser Graph
================

**Definition:**
The *Kneser graph of n, k* (denoted $KG_{n,k}$) consists of
the $k$-element subsets of $\{1,\ldots,n\}$ as vertices, where an
edge connects two vertices if and only if the two sets corresponding
to the vertices are disjoint.

* Regular with ${n-k}\choose k$ edges at each vertex
* Chromatic number $n - 2k + 2$

The Petersen Graph
==================

The *Petersen graph* realized as the Kneser graph $P = KG_{5,2}$

\begin{figure}
\centering
\includegraphics[height=0.6\textheight]{../planar-graphs/petersen-grundlage.pdf}
\end{figure}

The Petersen Graph (II)
=======================

\begin{figure}
\centering
\includegraphics[width=0.45\textwidth]{../planar-graphs/petersen-vertex-threecoloring.pdf}\hfill
\includegraphics[width=0.45\textwidth]{../planar-graphs/petersen-edge-fourcoloring.pdf}
\end{figure}

A vertex 3-coloring and edge 4-coloring of the Petersen graph

The Petersen Graph (III)
========================

**Definition:** A *Snark* is a connected, bridgeless cubic graph with chromatic
index 4 (i.e. it does not have an edge 3-coloring).

* Petersen graph is a snark
    * In fact the smallest possible snark (discovered 1898)
    * Tait 1880: Four Color Theorem equivalent to: No snark is planar
* Crossing number of Petersen graph is 2
* Cannot be embedded into $\mathbb{R}^2$

The Petersen Graph (IV)
=======================

\begin{figure}
\centering
\includegraphics[height=0.6\textheight]{../planar-graphs/petersen-zweikreuzungen.pdf}
\end{figure}

The minimum number of edge intersections in the plane is 2

Real Projective Plane and Cross Cap
===================================

**Definition:**
The *real projective space* $\mathbb{R}P^n$ consists of the lines
passing through the origin of $\mathbb{R}^{n+1}$. In the case $n=1$,
this is called the \emph{real projective line}; in the case $n=2$,
*real projective plane*.

* Equivalent constructions
    * Identify antipodal points of $S^n$
    * Identify antipodal border points of $D^{n-1}$

Real Projective Plane and Cross Cap (II)
========================================

\begin{figure}[H]
  \centering
  \includegraphics[keepaspectratio=true,width=0.8\textwidth,height=0.8\textheight]
  {../planar-graphs/crosscap-construction.pdf}
\end{figure}

How to construct $\mathbb{R}^2$ from $[0,1]\times[0,1]$ by identifying border points

Real Projective Plane and Cross Cap (III)
=========================================

* Cross cap is a real 2-manifold homeomorphic to $\mathbb{R}P^2$
* Surface is a path-connected, compact, closed, non-orientable manifold
* Surface cannot be embedded in $\mathbb{R}^3$
    * Homology in degree 1: $H_1(\mathbb{R}P^n;\;\mathbb{Z}) = \mathbb{Z}/2\mathbb{Z}$
    * Alexander duality: Homology of $X\subset\mathbb{R}^n$ has no torsion in degrees $n-1$ and $n-2$
* Instead has to be *immersed* (“local embedding”)

Embedding the Petersen Graph on the Cross Cap
=============================================

... Slide show ...