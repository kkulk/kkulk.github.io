---
layout: post
title: The Hopf Fibration
---

$$  \def\acts{\curvearrowright}$$

### This post is based on John Lee's "Introduction to Smooth Manifolds" and lectures by Prof. Richard Bamler at UC Berkeley. 

The action of the circle $$\mathbb{S}^1$$ on the higher dimensional sphere $$\mathbb{S}^{2n+1}$$ is one of the most profound objects in differential geometry. We study the consequences of this action here.

First, we note that the manifold $$\mathbb{S}^{2n+1} \subset \mathbb{R}^{2n+2} \subset \mathbb{C}^{n+1}$$ consists of elements of the form: 

$$\begin{align} \{(z_1, \dots, z_{n+1} ) \in \mathbb{C}^{n+1} | |z_1|^2 + \dots + |z_{n+1}|^2 = 1\} \end{align}$$

The circle $$\mathbb{S}^1$$ acts on the sphere in the following way. We have that $$\mathbb{S}^1 \acts \mathbb{S}^{2n+1}$$ as: 

$$ \begin{align}
\lambda \cdot (z_1, \dots, z_{n+1}) = (\lambda z_1, \dots, \lambda z_n)
\end{align} $$

The orbits of this action are $$ \{ ( \lambda z_1, \dots, \lambda z_{n+1}) : \lambda \in S^1 \} $$ for any $$(z_1, \dots, z_{n+1} ) \in \mathbb{S}^{2n+1}$$ and the orbit space is: 

$$\begin{align}
\mathbb{S}^1 \backslash \mathbb{S}^{2n+1} = \{ [z_1 , \dots, z_n ] \} = \mathbb{C} P^n
\end{align}$$

This is remarkable! The action of the circle on the $$2n+1$$-dimensional sphere splits the sphere into complex projective spaces of $$n$$-dimension. Further, we can check that the map: 

$$\begin{align}
\pi: \mathbb{S}^{2n+1} \rightarrow \mathbb{C} P^n \\ 
\pi(z_1, \dots, z_{n+1})  = [z_1, \dots, z_{n+1} ]
\end{align}$$

is a submersion. 

We can also take another perspective: that of vector fields. For any $$\lambda \in \mathbb{S}^1$$, we can define the map $$\phi_{\lambda} : \mathbb{S}^{2n+1} \rightarrow \mathbb{S}^{2n+1}$$ that takes $$\phi_{\lambda}(z_1,\dots, z_{n+1} ) = (\lambda z_1, \dots,\lambda z_{n+1} )$$. However, this can simply be seen as the restriction of the following diagonal matrix: 

$$\begin{align}
\begin{bmatrix}
\lambda & 0 & \dots & 0 \\ 0 & \lambda & \dots & 0 \\ \dots & \dots & \dots \\ 0 & 0 & \dots & \lambda 
\end{bmatrix} \in U(n+1)
\end{align}$$

and we can see that we can view the derivative of $$\phi_{\lambda}$$ as a velocity vector: 

$$\begin{align}
\frac{d}{dt} \phi_{e^{it}} (z_1, \dots, z_{n+1} ) = (i e^{it} z_1, \dots, i e^{it} z_{n+1} ) = i \phi_{e^{it}} (z_1,\dots, z_{n+1}) 
\end{align}$$

Further, we see that $$i \phi_{e^{it}} (\bar{z})$$ and $$\phi_{e^{it}} (\vec{z})$$ are orthogonal, and thus $$i \phi_{e^{it}} (\vec{z}) \in T_{\phi_{e^{it}}(\vec{z})}\mathbb{S}^{2n+1}$$, the tangent space to the sphere at the point $$\phi_{e^{it}}(\bar{z})$$.

Further, we can view $$X_{\vec{z}} = i \vec{z}$$ can be viewed as a vector field on $$\mathbb{S}^{2n+1}$$ and therefore: 

$$\begin{align}
\frac{d}{dt} \phi_{e^{it}} (\vec{z}) = X_{\phi_{e^{it}}(\vec{z})}
\end{align}$$

which lets us compute $$\theta_{t}(\vec{z}) = \phi_{e^{it}} (\vec{z})$$, the flow of the vector field $$X$$. 

We can now consider the $$3$$-dimensional example (i.e. $$n = 1$$), and we see that $$\mathbb{S}^1 \acts \mathbb{S}^{3}$$, and thus we have:

$$\begin{align}
\pi : \mathbb{S}^3 \rightarrow \mathbb{C} P^1 \cong S^2 
\end{align}$$
