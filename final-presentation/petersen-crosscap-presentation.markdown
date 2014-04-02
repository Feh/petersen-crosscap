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

The Petersen Graph (IV)
=======================

\begin{figure}
\centering
\includegraphics[height=0.6\textheight]{../planar-graphs/petersen-zweikreuzungen.pdf}
\end{figure}

The minimum number of edge intersections in the plane is 2
