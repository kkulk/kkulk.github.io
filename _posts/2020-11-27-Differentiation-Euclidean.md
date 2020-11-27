---
layout: post
title: Differentiation on Euclidean Spaces 
---

Differentiation and integration are natural operations that serve as the 'inverse' of each other, in the sense made precise by the fundamental theorem of calculus. The standard (Riemann) theory tells us the following: 

$$\begin{equation}
\int_{a}^{x} f(t) dt = F(x)
\end{equation}$$
where $$F'(x) = f(x)$$. This establishes a link between "area under the curve" and "rate of change" notions that are common in calculus. The Lebesgue theory of integration is a vast generalization of the notion of area under the curve for functions that are unable to return answers in the Riemannian theory. So, we naturally end up asking the question: what about the derivative? 

This post covers the theory of Hardy-Littlewood maximal functions. The core idea here is: can we extend basic notions that surround the fundamental theorem of calculus to higher dimensional Euclidean spaces? Some prerequisites for this post include: the construction of Lebesgue measure, and the formal statement of the Radon-Nikodym theorem for one-dimensional Euclidean space ($$\mathbb{R}$$).
