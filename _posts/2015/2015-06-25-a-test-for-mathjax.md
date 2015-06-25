---
layout: post
title: a test for Mathjax 
description: 这是Mathjax测试文章。

comments: true
share: true

category:
- science

tags:
- math
---

# 在此处输入标题

这是Mathjax测试文章。

We work on $$E^3\times P^3$$.


{Distribution Function}

Distribuation function $$f(\bf t,\bf x,\bf p)$$ is defined as $$\mathrm d N(\bf x,\bf p)=f\mathrm d \bf x\mathrm d\bf p$$.


{Redshift}
Redshit adds a weighting factor to distributation funtion. The photon which has energy $$E_0$$ measured by today's observer possesses energy $$E_0/a$$. Thus the distribution function
\begin{eqnarray}
\bar f_0=\frac1{e^{aE/T_0}-1}
\end{eqnarray}



{Energy-Momentum Tensor}
Energy momentum tensor is $$T^{\mu\nu}=(\rho+p)U^\mu U^\nu+p g^{\mu\nu}$$.

Energy momentum tensor reads
\begin{eqnarray}
T^{\mu\nu}=\int{\frac{\mathrm d \bf p}{\sqrt{-g}}\frac{p^\mu p^\nu}{p^0}f(\tau,\bf x,\bf q)}
\end{eqnarray}
To understand this equation, consider the 00 component, we can integrate with $$\mathrm d\bf x$$, the LHS gives the total energy of the system and the RHS should give that to, i.e.,
\begin{eqnarray}
\int T^{\mu\nu} \sqrt{-g}\mathrm d\bf x&=&\int{ \sqrt{-g}\mathrm{d}\bf{x} }\int \frac{\mathrm d \bf p}{\sqrt{-g}}\frac{p^\mu p^\nu}{p^0}f(\tau,\bf x,\bf q) \
\mathrm{RHS}&=&\int{\mathrm dN\frac{p^\mu p^\nu}{p^0}f(\tau,\bf x,\bf q)}
\end{eqnarray}

Then
\begin{eqnarray}
\delta T^0{\phantom{0}0}&=&-\delta \rho \
\delta T^0{\phantom{0}i}&=&(p+\rho)(v_i+B_i) \
\delta T^i{\phantom{i}j}&=&\delta p\delta^i{\phantom{i}j}+\Pi^i{\phantom{i}j}
\end{eqnarray}
in which $$\delta\rho=\frac1{a^4}\int{q^2\mathrm d q\mathrm d \Omega q^0\delta f(\tau,\bf x,\bf q)}$$.



{Boltzmann Eqn}

Define $$q^i=a^2p^i$$, $$q=\sqrt{(q^1)^2+(q^2)^2+(q^3)^2}$$, $$p=\sqrt{(p^1)^2+(p^2)^2+(p^3)^2}$$.

The full Boltzmann equation is $$\frac{\partial f}{\partial\tau}+\frac{\partial f}{\partial x^i}\frac{\partial x^i}{\partial \tau}+\frac{\partial f}{\partial q^i}\frac{\partial q^i}{\partial \tau}=\mathrm{Collision}$$

The variation 
\begin{eqnarray}
\frac{\partial \delta f}{\partial \tau}+\frac{\partial \delta f}{\partial x^i}\frac{\partial x^i}{\partial\tau}+\frac{\partial f}{\partial x^i}\frac{\partial \delta x^i}{\partial\tau}+\frac{\partial\delta f}{\partial q^i}\frac{\partial q^i}{\partial \tau}+\frac{\partial f}{\partial q^i}\frac{\partial \delta q^i}{\partial \tau}=\delta\mathrm{Collision}
\end{eqnarray}

{\color{red}
{It is said that $$\frac{\partial f}{\partial x^i}\frac{\partial \delta x^i}{\partial\tau}$$ vanishes in the background and $$\frac{\partial\delta f}{\partial q^i}\frac{\partial q^i}{\partial \tau}$$ is second order term. 
}}

Drop the two terms and we get
\begin{eqnarray}
\frac{\partial \delta f}{\partial \tau}+\frac{\partial\delta f}{\partial q^i}\frac{\partial q^i}{\partial \tau}+\frac{\partial f}{\partial q^i}\frac{\partial \delta q^i}{\partial \tau}=\delta\mathrm{Collision}
\end{eqnarray}

\subparagraph{$$\frac{\partial f}{\partial q^i}\frac{\partial \delta q^i}{\partial \tau}$$}

\begin{eqnarray}
\frac{\partial f}{\partial q^i}\frac{\partial \delta q^i}{\partial \tau}&=&\frac{\partial f}{\partial q}\frac{\partial q}{\partial q^i}\frac{\partial \delta q^i}{\partial\tau} \
&=&\frac{\partial f}{\partial q}n_i\frac{\partial \delta q^i}{\partial \tau}=\frac{\partial f}{\partial q}n^i\frac{\partial \delta q^i}{\partial \tau} \
&=&\frac{\partial f}{\partial q}n^i\frac{\partial \delta (a^2p^i)}{\partial\tau}=\frac{\partial f}{\partial q}n^i(2a\frac{\partial a}{\partial \tau}\delta p^i+a^2\frac{\partial \delta p^i}{\partial\tau}) \
&=&\frac{\partial f}{\partial q}n^i(2a^2H\delta p^i+a^2\frac{\partial \delta p^i}{\partial \tau})
\end{eqnarray}
H is Hubble constant. The term $$a^2n^i\frac{\partial \delta p^i}{\partial \tau}$$ can be simplified by applying the geodesic equation 
\begin{eqnarray}
\frac{\mathrm d p^\mu}{\mathrm d t}&=&-\Gamma^\mu_{\nu\sigma}p^\nu p^\sigma \
\Rightarrow \frac{\mathrm d p^i}{\mathrm d t}&=&-\Gamma^i_{\nu\sigma}p^\nu p^\sigma \
{\color{red}{\Rightarrow}} \frac{\partial p^i}{\partial \tau}&=&-\frac1{p^0}\Gamma^i_{\nu\sigma}p^\nu p^\sigma 
\end{eqnarray}

Purbation
\begin{eqnarray}
\frac{\partial \delta p^i}{\partial \tau}=\frac{\delta p^0}{(p^0)^2}\Gamma^i_{\nu\sigma}p^\nu p^\sigma-\frac1{p^0}\delta\Gamma^i_{\nu\sigma}p^\nu p^\sigma-\frac2{p^0}\Gamma^i_{\nu\sigma} \delta p^\nu p^\sigma
\end{eqnarray}
The 2 in the last part is based on the symmetric property of $$\Gamma^i_{\nu\sigma}$$.

The variation of line element is $$\delta g_{\mu\nu}\mathrm d x^\mu\mathrm d x^\nu=a^2(-2\psi\mathrm d\tau^2+2B_i\mathrm d\tau\mathrm dx^i+2H_{ij}\mathrm dx^i\mathrm dx^j)$$ in which $$H_{ij}=\phi\delta_{ij}+\frac1 2(D_{ij}E+\frac1 2(H^{(V)}_{i,j}+H^{(V)}_{j,i})+H^{(T)}_{ij})$$

Put that into Boltzmann equation
\begin{eqnarray}
q^0\frac{\partial \delta f}{\partial \tau}+q^0\frac{\partial x^i}{\partial \tau}\frac{\partial \delta f}{\partial x^i}&=&q^0\mathrm{Collision}-\frac{\partial f}{\partial q}(2a^2n^iH\delta p^i-2a^2Hn^i\delta p^i-a^2p^0[n^i\partial_i\psi+n^iB_i' \
&&+\frac{p_0^2-p^2}{ap_0^3}n^iB_i+\frac p {p^0}n^in^jH_{ij}'+\frac{p^2}{(p^0)^2}n^in^jn^k\partial_kH_{ij}])
\end{eqnarray}

Rearrange the terms
\begin{eqnarray}
q^0\frac{\partial \delta f}{\partial \tau}+qn^i\partial_i \delta f&=&q^0\mathrm{Collision}-\frac{\partial f}{\partial q}(2a^2n^iH\delta p^i-2a^2Hn^i\delta p^i-a^2p^0[n^i\partial_i\psi+n^iB_i' \
&&+\frac{p_0^2-p^2}{ap_0^3}n^iB_i+\frac p {p^0}n^in^jH_{ij}'+\frac{p^2}{(p^0)^2}n^in^jn^k\partial_kH_{ij}])
\end{eqnarray}




$$