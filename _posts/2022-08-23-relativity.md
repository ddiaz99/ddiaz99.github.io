---
layout: post
title: The theory of relativity
date: 2022-08-23 11:12:00-0400
description: Review of the fundamentals of general relativity
tags: formatting math
categories: sample-posts
--- 
In 1905 Albert Einstein published what would become known as the theory of special relativity in an article titled "Zur Elektrodynamik bewegter Körper", and later in 1915 he published the theory of general relativity, perhaps the most beautiful theory of how the universe works on large scales. In this blog we will explore relativity from physical intuition and mathematical rigor, or well, that is my wish.

First a little context about the problem that plagued physics at the time. It follows from Maxwell's equations that light is not only an electromagnetic wave, but also that it travels with a constant velocity independent of the motion of the source or the observer, something that conflicts with the Galilean transformations on which Newton's laws are based. Maxwell's equations are in fact not invariant under Galilean transformations. In 1904 Hendrik Lorentz managed to find the exact transformations that leave Maxwell's equations invariant as well as the wave equation in vacuum. Einstein affirmed that the Lorentz transformations were precisely the ones that should be used, and from there many consequences were derived that we will see later on. However, we will take a more general route and explore Minkowski space-time, because in 1908 he found that the theory of special relativity, introduced by his former student Albert Einstein, could be best understood as a four-dimensional space.

Let $$V$$ be a $$4$$-dimensional $R$-vector space. Let $$c>0$$ and choose a basis $$e=(e_{1},e_{2},e_{3},e_{4})$$ of $$V$$. Define a inner product on $V$ for two vectors $$u=x_{1}e_{1}+y_{1}e_{2}+z_{1}e_{3}+t_{1}e_{4}$$ and $$v=x_{2}e_{1}+y_{2}e_{2}+z_{2}e_{3}+t_{2}e_{4}$$ by:
$$
\left\langle u,v \right\rangle _{e} := x_{1}x_{2} + y_{1}y_{2} + z_{1}z_{2} - c^{2}t_{1}t_{2}
$$


This theme supports rendering beautiful math in inline and display modes using [MathJax 3](https://www.mathjax.org/) engine. You just need to surround your math expression with `$$`, like `$$ E = mc^2 $$`. If you leave it inside a paragraph, it will produce an inline expression, just like $$ E = mc^2 $$.

Euler

$$
\sum_{n=1}^\infty \frac{1}{n^2} = \frac{\pi^2}{6}
$$

You can also use `\begin{equation}...\end{equation}` instead of `$$` for display mode math.
MathJax will automatically number equations:

\begin{equation}
\label{eq:cauchy-schwarz}
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
\end{equation}

and by adding `\label{...}` inside the equation environment, we can now refer to the equation using `\eqref`.

Note that MathJax 3 is [a major re-write of MathJax](https://docs.mathjax.org/en/latest/upgrading/whats-new-3.0.html) that brought a significant improvement to the loading and rendering speed, which is now [on par with KaTeX](http://www.intmath.com/cg5/katex-mathjax-comparison.php).
