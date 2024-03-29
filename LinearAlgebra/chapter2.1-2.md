---
layout: post
title: Problem Set 2.1 Part 2
---

# Problem Set 2.1 Part 2

## Problem 16
- a) What 2 by 2 matrix $R$ rotates every vector by $90^\circ$? $R$ times
$\bigl[\begin{smallmatrix}x \\ y\end{smallmatrix}\bigr]$ equals
$\bigl[\begin{smallmatrix}y \\ -x\end{smallmatrix}\bigr]$

- b) What 2 by 2 matrix $R^2$ rotates every vector by $180^\circ$?

## Solution 16
- a) $\begin{bmatrix}0 & 1 \\ -1 & 0\end{bmatrix}\begin{bmatrix}x \\
    y\end{bmatrix} = \begin{bmatrix}y \\ -x\end{bmatrix}$

- b) $\begin{bmatrix}-1 & 0 \\ 0 & -1\end{bmatrix}\begin{bmatrix}x \\
    y\end{bmatrix} = \begin{bmatrix}-x \\ -y\end{bmatrix}$

## Problem 17
- Find the matrix $P$ that multiples $(x,y,z)$ to give $(y,z,x)$.
- Find the matrix $Q$ that multiplies $(y,z,x)$ to bring back $(x,y,z)$.

## Solution 17
- $
P =
\begin{bmatrix}
    0 & 1 & 0 \\
    0 & 0 & 1 \\
    1 & 0 & 0
\end{bmatrix}
\longrightarrow
\begin{bmatrix}
    0 & 1 & 0 \\
    0 & 0 & 1 \\
    1 & 0 & 0
\end{bmatrix}
\begin{bmatrix}x \\ y \\ z \end{bmatrix}=
\begin{bmatrix}y \\ z \\ x\end{bmatrix}$

- $
Q =
\begin{bmatrix}
    0 & 0 & 1 \\
    1 & 0 & 0 \\
    0 & 1 & 0
\end{bmatrix}
\longrightarrow
\begin{bmatrix}
    0 & 0 & 1 \\
    1 & 0 & 0 \\
    0 & 1 & 0
\end{bmatrix}
\begin{bmatrix}y \\ z \\ x \end{bmatrix}=
\begin{bmatrix}x \\ y \\ z\end{bmatrix}$

## Problem 18
- What 2 by 2 matrix $E$ subtracts the first component from the second component?
- What 3 by 3 matrix does the same?

$
\qquad E\begin{bmatrix}3 \\ 5\end{bmatrix}=\begin{bmatrix}3 \\ 2\end{bmatrix}
\qquad E\begin{bmatrix}3 \\ 5 \\ 7\end{bmatrix}=\begin{bmatrix}3 \\ 2 \\ 7\end{bmatrix}
$

## Solution 18
$
E = \begin{bmatrix}
    1 & 0 \\
    -1 & 1
    \end{bmatrix}
\qquad
E = \begin{bmatrix}
    1 & 0 & 0\\
    -1 & 1 & 0 \\
    0 & 0 & 1
    \end{bmatrix}
$

## Problem 19
- What 3 by 3 matrix $E$ multiplies $(x, y, z)$ to give $(x, y, z+x)$?
- What matrix $E^{-1}$ multiplies $(x, y, z)$ to give $(x,y,z-x)$?
- If you multiply $(3,4,5)$ by $E$ and then multiply by $E^{-1}$, the two results are $?$ and $?$

## Solution 19
$
E = \begin{bmatrix}
    1 & 0 & 0\\
    0 & 1 & 0 \\
    1 & 0 & 1
    \end{bmatrix}
\qquad\qquad
E^{-1} =
\begin{bmatrix}
    1 & 0 & 0\\
    0 & 1 & 0 \\
    -1 & 0 & 1
\end{bmatrix}
$

$
\begin{bmatrix}
    1 & 0 & 0\\
    0 & 1 & 0 \\
    1 & 0 & 1
\end{bmatrix}
\begin{bmatrix}3 \\ 4 \\ 5\end{bmatrix}=
\begin{bmatrix}3 \\ 4 \\ 8\end{bmatrix}\qquad
\begin{bmatrix}
    1 & 0 & 0\\
    0 & 1 & 0 \\
    -1 & 0 & 1
\end{bmatrix}
\begin{bmatrix}3 \\ 4 \\ 8\end{bmatrix}=
\begin{bmatrix}3 \\ 4 \\ 5\end{bmatrix}
$

