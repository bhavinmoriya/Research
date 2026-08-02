## Abstract

This thesis comprises three results, each addressed in separate chapters. The first chapter is introductory, as the title suggests. The other three chapters are devoted to three different problems. Below is a brief introduction to our results.

---

### 1. Davenport Constant for Finite Abelian Groups
Let $G$ be any finite abelian group of rank $r$ with invariants $n_1, n_2, \ldots, n_r$. In other words,
$$
G = \mathbb{Z}_{n_1} \oplus \mathbb{Z}_{n_2} \oplus \cdots \oplus \mathbb{Z}_{n_r},
$$
where the $n_i$'s are integers satisfying $1 < n_1 \mid n_2 \mid \cdots \mid n_r$.

The **Davenport constant** of a group $G$, denoted $D(G)$, is defined as the smallest positive integer $t$ such that every sequence of $t$ elements of $G$ has a non-empty zero-sum subsequence.

In the direction of a conjecture by Śliwa, it has been conjectured that:
$$
D(G) \leq \prod_{i=1}^r n_i.
$$
We have obtained the following upper bound on $D(G)$:
$$
D(G) \leq n_r + n_{r-1} + (c(3) - 1)n_{r-2} + (c(4) - 1)n_{r-3} + \cdots + (c(r) - 1)n_1 + 1,
$$
where $c(i)$ are the **Alon-Dubiner constants** for respective $i$'s.
Additionally, we provide an application of Davenport’s constant to the **Quadratic Sieve**.

---

### 2. Constants $s(G)$ and $\eta(G)$ for Finite Abelian Groups
Let $G$ be a finite abelian group with $\exp(G) = e$. Define:
- $s(G)$: The minimal positive integer $t$ such that any sequence $S$ of length $t$ of elements of $G$ contains a non-empty subsequence of length at most $e$ with sum zero.
- $\eta(G)$: The minimal positive integer $t$ such that any sequence $S$ of length $t$ of elements of $G$ contains an $e$-term subsequence with sum zero.

For groups of rank at most two, $s(G)$ has been completely determined (see [45]). For higher ranks, we address the problem of determining $s(\mathbb{Z}_{n^m}^r)$ under constraints on $n$, $m$, and $r$.

**Result:**
Let $n, m,$ and $r$ be positive integers with $m \geq 3$. Then:
$$
s(\mathbb{Z}_{n^m}^r) = (a_r + 1)(n^m - 1) + 1,
$$
where $a_r$ is a constant depending on $r$ and $n$, and:
$$
\eta(\mathbb{Z}_{n^m}^r) = a_r(m - 1) + 1.
$$
Here, $c(r)$ is the **Alon-Dubiner constant**, and the lower bound on $n$ is fixed.

---
### 3. Weighted Davenport Constants and Erdős–Ginzburg–Ziv Constants
Given an abelian group $G$ of order $n$, and a finite non-empty subset $A \subseteq \mathbb{Z}$, we define:
- **$DA(G)$:** The least positive integer $t$ such that every sequence $(x_1, \ldots, x_t)$ of length $t$ of elements of $G$ has a subsequence $(x_{j_1}, \ldots, x_{j_l})$ and $a_i \in A$ with:
  $$
  \sum_{i=1}^l a_i x_{j_i} = 0.
  $$
- **$EA(G)$:** The least positive integer $t$ such that every sequence $(x_1, \ldots, x_t)$ of elements of $G$ has a non-empty subsequence with sum zero.

For $G = \mathbb{Z}/n\mathbb{Z}$, we denote $DA(G)$ and $EA(G)$ by $DA(n)$ and $EA(n)$, respectively.

**Result:**
We extend results from an article by Adhikari et al. [5] and determine bounds for $DR_n(n)$ and $ER_n(n)$, where:
$$
R_n = \{x^2 : x \in (\mathbb{Z}/n\mathbb{Z})^*\},
$$
and $(\mathbb{Z}/n\mathbb{Z})^*$ is the group of units modulo $n$. Our approach uses:
- A recent result by Yuan and Zeng [79],
- A theorem by I. Chowla [24],
- **Kneser’s theorem** [52].
