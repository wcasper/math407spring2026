---
layout: page
title: Homework 1
permalink: /homework/hw1
---

### Directions
Solve the following problems and type up your solutions.  Your solutions should be provided in one of the following formats (in order of preference)
* typed up in $$\LaTeX$$ and submitted as a PDF on Canvas
* written legibly on blank paper, scanned into a PDF and then uploaded on Canvas
* written on ancient parchement with a quill and then flown to the instructor via owl post like in Harry Potter

If you go with the first strategy, you may wish to check out Overleaf which is a free and intuitive website for generating $$\LaTeX$$ documents online.
If you wish to use the second method and don't own a scanner at home, you can check out the numerous scanning apps available for smartphones.


**Special instructions:**
Throughout this assignment, let $$n>0$$ be an integer, let

$$\omega_n = e^{2\pi i/n},$$

and let $$U_n$$ be the set of $$n$$'th roots of unity.

**Problem 1:**

Prove that if $$z,w\in U_n$$, then the product $$zw\in U_n$$. 

**Problem 2:**

An $$n$$'th root of unity $$w\in U_n$$ is called **primitive** if

$$U_n = \{w^k: k\in\mathbb{Z}\}.$$

Thus for example $$\omega_n$$ is a primitive $$n$$'th root of unity.  (As an aside, we sometimes call $$\omega_n$$ the **canonical** primitive $$n$$'th root of unity).

* (a) Prove that $$w\in U_n$$ is primitive if and only if there exists an integer $$k\in\mathbb Z$$ with $$\omega_n=w^k$$.
* (b) Let $$k\in\mathbb Z$$.  Prove that $$\omega_n^k=1$$ if and only if $$n$$ divides $$k$$.
* (c) Suppose $$w = \omega_n^j$$ for some integers $$j$$.  Prove that $$w$$ is primitive if and only if $$j$$ and $$n$$ are relatively prime.

<details>
  <summary>Reveal hint</summary>

  Remember that $$j$$ and $$n$$ are relatively prime if and only if there exists $$a,b\in\mathbb Z$$ with $$aj+bn=1$$.
</details>


**Problem 3:**

Let $$m$$ and $$n$$ be positive integers.

* (a)  Show that the roots of the polynomial

$$1 + z + z^2 + \dots + z^m$$

are $$\omega_{m+1},\omega_{m+1}^2,\dots,\omega_{m+1}^m$$.

* (b)  Suppose that $$p(z)$$ is a polynomial whose roots include all the roots from part (a).  Use the Fundamental Theorem of Algebra to explain why $$1+z+z^2+\dots+z^m$$ will divide $$p(z)$$.

* (c)  Determine, with proof, the values of $$m$$ and $$n$$ where the polynomial divides

$$1 + z^n + z^{2n} + \dots + z^{mn}.$$


<details>
  <summary>Reveal hint</summary>

  Remember the geometric sum:

  $$1 + z + z^2 + \dots + z^m = \frac{1-z^{m+1}}{1-z}.$$

</details>

**Problem 4:**

Suppose that $$z_1,z_2,z_3$$ and $$z_4$$ are the solutions of the equation

$$3 + kz - 2z^2 + 5z^3 + z^4 = 0,$$

where here $$k$$ is some unknown integer.

Determine the value of each of the following expressions
*  $$z_1^2+z_2^2+z_3^2+z_4^2$$
*  $$z_1^2z_2^2z_3z_4 + z_1^2z_2z_3^2z_4 + z_1^2z_2z_3z_4^2 + z_1z_2^2z_3^2z_4 + z_1z_2^2z_3z_4^2 + z_1z_2z_3^2z_4^2$$


**Problem 5:**
Find a solution of the system of equations

$$\begin{align*}
z_1 + z_2 + z_3 + z_4 &= 3\\
z_1z_2 + z_1z_3 + z_1z_4 + z_2z_3 + z_2z_4 + z_3z_4 &= -39\\
z_1z_2z_3 + z_1z_2z_4 + z_1z_3z_4 + z_2z_3z_4 &= -47\\
z_1z_2z_3z_4 &= 210
\end{align*}$$




