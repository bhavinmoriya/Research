# Summary of Thesis: *Some Zero Sum Problems in Combinatorial Number Theory*

**Author:** Bhavin K. Moriya
**Institution:** Harish-Chandra Research Institute (HRI), Allahabad
**Supervisor:** Prof. S. D. Adhikari

---

## 1. Background and Motivation

Zero-sum problems form a central topic in **additive combinatorics** and **combinatorial number theory**, focusing on subsequences of group elements that sum to zero. Rooted in the classic **Erdős–Ginzburg–Ziv (EGZ) Theorem**, this field explores invariants such as:

* **Davenport’s constant (D(G))** – the minimal length required so that any sequence over a finite abelian group G has a non-empty zero-sum subsequence.
* **E(G) (EGZ constant)** – the least length ensuring a subsequence of size |G| with zero sum.
* **s(G), η(G)** – constants requiring zero-sum subsequences of length tied to the group’s exponent.
* **Weighted zero-sum invariants (DA(G), EA(G))** – extensions where group elements are combined with coefficients from a fixed set A.

These invariants are important for understanding **non-unique factorizations**, **factorization algorithms (like the quadratic sieve)**, and broader combinatorial structures.

---

## 2. Contributions of the Thesis

The thesis presents three major results, each in its own chapter, along with background and preliminaries.

### **Chapter 2: Bounds on Davenport’s Constant**

* For a finite abelian group $G = \mathbb{Z}_{n_1} \oplus \cdots \oplus \mathbb{Z}_{n_r}$ (with invariants $n_1 | n_2 | \cdots | n_r$), it is conjectured (Śliwa) that:

  $$
  D(G) \leq \sum_{i=1}^r n_i
  $$
* The thesis improves upper bounds by using **Alon–Dubiner constants (c(r))**:

  $$
  D(G) \leq n_r + n_{r-1} + (c(3)-1)n_{r-2} + \cdots + (c(r)-1)n_1 + 1
  $$
* Applications include links between Davenport’s constant and **smooth numbers** in the **quadratic sieve** (used in integer factorization).

---

### **Chapter 3: Higher-Dimensional EGZ Theorem**

* Extends the EGZ theorem to groups of higher rank.
* For cyclic and rank-2 groups, $s(G)$ and $η(G)$ are well-studied, but higher ranks remained open.
* Main result: for groups $\mathbb{Z}^r_{nm}$, under certain constraints,

  $$
  s(\mathbb{Z}^r_{nm}) = (a_r + 1)(nm - 1) + 1
  $$

  where $a_r$ is a constant depending on r, and bounds involve the Alon–Dubiner constant.
* Provides progress towards conjectures such as:

  $$
  s(\mathbb{Z}^3_n) =
  \begin{cases}
  8n - 7 & \text{if $n$ is even}\\
  9n - 8 & \text{if $n$ is odd.}
  \end{cases}
  $$

---

### **Chapter 4: Weighted Zero-Sum Problems**

* Introduces **weighted versions** of Davenport and EGZ constants:

  * $D_A(G)$: minimum t such that any sequence of t elements has a weighted zero-sum subsequence with coefficients in A.
  * $E_A(G)$: analogous for subsequences of length |G|.
* Focuses on $A = \{x^2 : x \in (\mathbb{Z}/n\mathbb{Z})^* \}$, i.e., quadratic residues modulo n.
* Main results provide exact or sharp bounds for $D_{R_n}(n)$ and $E_{R_n}(n)$ (where $R_n$ is the set of quadratic residues).
* Techniques combine **Yuan–Zeng’s results**, **Chowla’s theorem**, and **Kneser’s theorem**.

---

## 3. Key Theorems

Some highlighted contributions include:

1. **New bounds on D(G):** tighter than previously known general results.
2. **Link between quadratic sieve and zero-sum constants:** showing Davenport constants govern smooth-number subsequence requirements.
3. **Exact formula for s(G) in structured cases:** extending knowledge beyond rank-2 groups.
4. **Weighted zero-sum constants:** explicit formulas for quadratic residues modulo n.

---

## 4. Significance

* Advances **understanding of Davenport’s constant**, one of the core invariants in additive number theory.
* Establishes connections between **zero-sum theory and computational number theory** (e.g., factoring methods).
* Extends classical EGZ-type results to **higher dimensions and weighted settings**, broadening the scope of additive combinatorics.
* Provides techniques (like use of Alon–Dubiner bounds and Kneser’s theorem) that are applicable to further open problems.

---

## 5. Structure of the Thesis

1. **Introduction** – overview of EGZ theorem, Davenport constant, Kneser’s theorem, and weighted zero-sum ideas.
2. **On Davenport’s Constant** – new upper bounds and applications.
3. **Higher-Dimensional Analogue of EGZ Theorem** – results on s(G), η(G) for higher rank groups.
4. **Weighted Zero-Sum Theorems** – bounds for quadratic-residue weighted invariants.
5. **Bibliography** – extensive references including Alon, Dubiner, Reiher, Gao, Geroldinger, and others.

---

## 6. Conclusion

The thesis contributes substantially to **zero-sum problems in combinatorial number theory**, offering:

* Stronger bounds for Davenport’s constant,
* New results for higher-dimensional EGZ analogues,
* Progress in weighted zero-sum problems with quadratic residues.

These results advance the state of knowledge and open avenues for further research on precise values of constants for higher rank groups and weighted settings.

---


