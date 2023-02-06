# Frege-Hilbert Controversy

the nature of geometry

* Frege
  * arithmetic is founded oin logic
  * geometry is founded on the intuition of space
  + Pb: Russell's Paradox
* Hilbert: geometry is founded is founded by its axioms.
  + show this axioms system is both consistent and complete
  + **Hilbert's Program**
  + to show by proof in logic / by a logical deduction
  + Godel's Incompleteness Theorem

## Frege

* start with definitions, then gives axioms.
* Statement of arithmetic are analytic a-priori.
* It's not the content of the judgement, but the justification.
* existence implies truth, and truth implies consistency

> For Kant, it's the construction of the statement.

To logically define the concept Number $\mathbb{N}$,
then it can deduce the truth of arithmetic (the piano axioms).

**Hume's Principle**
$\#F = \#G \iff$ they can be put into 1-1 correspondence, injective.

define number as concepts/predicates
* $\vdots$
* $T(x)L x = 0 \lor x \neq x$, there is 2
* $O(x): x = 0$ just 1
* $Z(x): x \neq x$ there is 0 such thing

**Basic Law 5**
every concept is given by an extension.
<!-- every extension/predicate will define a well founded concept. -->

### Russell's Paradox

Consider
$$
S: \{x | x \not \in x \}
$$

Question: is $S \in S$?
$S \in S$ if $S \not\in S$, and
$S \not \in S$ if $S \in S$.

Then
$$
S \in S \iff S \not\in S.
$$

### Type Theory
* $\vdots$
* Concepts of concepts $\mathbb{R}$
* concepts $S$
* individual $x$

### Extensions

* naive set theory - Cantor
* (formal) set theory - ZFC, Zermelo–Frankel and axiom and choice
* class theory - Godel Bernays
  * Grothendieck Universes

## Hilbert

* Start with axioms and these axioms gives definition.
* Given some terms, axioms are thought to be the truth about these terms.
* Whatever satisfies the axioms is the term.
* many interpretations
* axioms are scheme
* consistency implies truth and existence

Example: point, line, and plane

### Hilbert's program

* Relative consistency proof
  * geometry is consistent relative to analysis
* absolute consistence proof of arithmetic
  * Godel's Theorem
  1. no consistent system of axioms whose theorem are effective that can prove all the truth of arithmetic
  2. any such system cannot prove its own consistency