# Mathematical Structuralism

## Previous Quote

### Hilbert

> we think of points, lines and planes as having certain mutual relations: "are situated", "between", "parallel", "congruent", "continuous".

These are all relations set by the axioms. what axioms do is to give relations, and the relations defines that points, lines, and plans.

In virtual of relations, we implicitly defines the objects.

> the complete and exact description of those relations follows as a consequence of the axioms.

"points", "lines", "planes" is whatever satisfies the axioms

### Bernays

> the<u> axiomatic method</u> is presented and practiced in the spirit of the <u>abstract conception</u> of axiomatic/mathematics.
>
> Thus, an axiom system is regarded not as a system of statements about a subject matter but as a system of conditions for what might be called a **<u>relational structure</u>**.

A structure specified by the axioms.

**Axiomatic Method**

* axioms _as if they were true first principles_ $\implies$ as-ifism
* relational structure
* whatever satisfies the structure is what the axioms are about

## Peano-Dedekind Axioms

| Structure                                     | Abstract Structure |
|:----------------------------------------------|:-------------------|
| $\mathbb{Q}: r+ib, i = \sqrt{-1}$             | field (group)      |
| $\mathbb{R}$                                  | field (group)      |
| $\mathbb{Q}: m/n$                             | field (group)      |
| $\mathbb{Z}: \ldots, -2, -1, 0, 1, 2, \ldots$ | ring               |
| $\mathbb{N}: 0, 1, 2, \ldots$                 | semi-ring          |

### Second order Piano Axioms $P^2 A$

1. $x$ is a natural number
2. For every $n$, $S(n) \in \mathbb{N}$
3. for $m, n$, $S(m) = S(n) \implies m = n$
4. For any $n$, $S(n) = x$ is false
5. (_Induction Axioms_) If $S$ is a set such that $x \in S$ and for every $n$,
   $n \in S \implies S(n) \in S$, then $S$ contains every natural numbers.

theory is _categorical_:
all the systems that satisfies the axioms are equivalent up to isomorphism.

## Dedekind

From Hilbert, Numbers is whatever satisfies the Piano Axioms.
Dedekind: "What Numbers should be".

* system is whatever satisfies the axioms
  + a set of objects that satisfies the relationships as said out in the axioms
* question: how do we know such a system is possible
  + example: my thought, the thought of my thought, ...

---

* any system that is an $\omega$-sequence is going to satisfies the axioms

**Defn** (Dedekind Infinite):
A set is *countably infinite* if it is isomorphic to any its infinite subset.
