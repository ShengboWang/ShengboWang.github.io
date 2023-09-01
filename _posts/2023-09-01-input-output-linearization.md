---
title: "Input-Output Linearization"
last_modified_at: 2023-09-03
permalink: /blog/input-output-linearization
header:
  overlay_color: "#333"
# classes: wide
author_profile: false
toc: true
toc_label: "My Table of Contents"
toc_icon: "cog"
toc_sticky: true
categories:
  - Research Notes
tags:
  - control theory
  - safety
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

The feedback linearization techniques facilitate more effective control of a nonlinear system. When only partial state variables or given outputs are measurable, input-output linearization (IOL) may simplify the control processes. This note includes the basic idea of IOL with its key assumptions, as well as its application in nonlinear safe control tasks.

### System description
To achieve IOL, the nonlinear system should take the control-affine form with same dimensions in input and output, given as

$$
	\begin{gather}
    \dot x = f(x) + g(x) u, \\
    y = h(x), \label{1}
  \end{gather}
$$

where $$x \in \mathbb{R}^n$$, $$u, y\in \mathbb{R}^m$$. Typically, $$m=1$$ yields a SISO system. The aim of IOL is to obtain a linear relationship between output $$y$$ and (nonlinear) input $$u$$ to simplify the controller design. Different from Jacobian linearization, IOL results in an exact representation of the origin system rather than an approximation at certain points. To this end, the following definitions and assumptions are needed to have a tractable system.

**Definition 1 (relative degree).** 


### Reference

- [1] Michael A. Henson and Dale E. Seborg. [Chapter 4: Feedback Linearizing Control](https://cse.sc.edu/~gatzke/cache/npc-Chapter4-nofigs.pdf).