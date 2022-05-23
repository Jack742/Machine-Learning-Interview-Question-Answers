# Linear Algebra
## Introduction

Algebra is the expression of a problem through a collection of objects, and a set of rules to manipulate them. Linear algebra uses *vectors* as the objects to be manipulated. 
We will consider vectors to take the  form $a \in \R^{n}$ e.g. 

$b = \begin{bmatrix}0\\1\\2\end{bmatrix} \in \R^{3} $

An object is considered a valid vector if it can be added to other vectors, or scaled by a real scalar value $\lambda \in \R$. In mathematics, *closure* is the set of outcomes that can occur as a result of a proposed operations. For vectors, this becomes the problem of what vectors can result from a small set of vectors, given that we can add or scale them? The answer to this problem gives us a vector space.

## Systems of Linera Equations
Many problems can be formulated as a system of linear equations, and linear algebra can be used to solve them. Linear equations can be geometrically interpreted (i.e. they can be represented as a line or hyper-plane).

Since a solution to a system of linear equations must satisfy all equations, the solutions exists at the intersection of these lines. The set of solutions can be either empty (i.e. no solution exists), a point (i.e. one solution), or infinitely large (i.e. the lines are the same).

To solve these systems, we introduce a compact notation, such that the equations:

$4x_{1} + 4x_{2} = 5$

$2x_{1} + 4x_{2} = 1$

can be written as:

$\begin{bmatrix}4\\4
\end{bmatrix}x_{1} + \begin{bmatrix}4\\2
\end{bmatrix}x_{2} = \begin{bmatrix}5\\1
\end{bmatrix}$

and the general form:

$\begin{bmatrix}a_{11}\\...\\a_{m1}
\end{bmatrix}x_{1} + \begin{bmatrix}a_{12}\\...\\a_{m2}
\end{bmatrix}x_{2} + ... + \begin{bmatrix}a_{1n}\\...\\a_{mn}
\end{bmatrix}x_{n}= \begin{bmatrix}b_{1}\\...\\b_{m}
\end{bmatrix}$

which is finally reducible to the matrix form:

$\begin{bmatrix}a_{11}, a_{12}, ... , a_{1n}\\a_{21}, a_{22}, ... , a_{2n}\\
...\\a_{m1}, a_{m2}, ... , a_{mn}
\end{bmatrix}\begin{bmatrix}x_{1}\\x_{2}\\...\\x_{n}\end{bmatrix} = \begin{bmatrix}b_{1}\\b_{2}\\...\\b_{n}\end{bmatrix}
$