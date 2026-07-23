# Chapter 2

## 2.1 Histograms and Measures

### Probability Vectors and Histograms
A vector

$$
\mathbf{a} = (a_1,\ldots,a_n)
$$

is a **probability vector** if it belongs to the **probability simplex**

$$
\Sigma_n
\coloneqq
\left\{
\mathbf{a}\in\mathbb{R}_+^n
:
\sum_{i=1}^{n} a_i = 1
\right\}, \qquad

a_i \geq 0,\
\text{for every } i=1,\ldots,n.
$$


Each component $a_i$ represents the probability or mass assigned to the
$i$-th position.

## Remark 2.1: Discrete Measures

Let

$$
x_1,\ldots,x_n\in\mathcal{X}
$$

be locations, and let

$$
\mathbf{a}=(a_1,\ldots,a_n)
$$

be their weights.

A **discrete measure** is written as

$$
\alpha = \sum_{i=1}^{n} a_i\delta_{x_i}.
$$

- $x_i$ is the location of the $i$-th mass;
- $a_i$ is the amount of mass placed at $x_i$;
- $\delta_{x_i}$ is the **Dirac measure** at $x_i$.

The Dirac measure $\delta_x$ represents one unit of mass concentrated entirely
at the single point $x$.

Therefore,

$$
\alpha =
a_1\delta_{x_1}
+\cdots+
a_n\delta_{x_n}
$$

means that the measure places mass $a_i$ at each location $x_i$.

### Probability measure

The discrete measure $\alpha$ is a probability measure when

$$
\mathbf{a}\in\Sigma_n.
$$

This means

$$
a_i\geq 0
\qquad\text{for every }i,
$$

and

$$
\sum_{i=1}^{n}a_i=1.
$$

Thus, the weights $a_i$ can be interpreted as probabilities.

### Positive measure

$\alpha$ is a positive measure if

$$
a_i\geq 0
\qquad\text{for every }i.
$$

The weights do not need to sum to $1$ in this case.

### Assumption

We usually assume

$$
a_i>0
\qquad\text{for every }i.
$$

This avoids including locations that have zero mass.

## Assignment and Monge Problem

Cost Matrix ($C_{}$)
