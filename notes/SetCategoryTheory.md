# Theory of Structure

> **NOTE** Hilbert/Dedekind Structuralism
>  
> relative consistent axioms -> concepts -> truth -> existence

*background mathematical theory* instead of background metaphysical theory
fir structure (ante rem) | system that has a structure (in re)

1. set theory
   1. ZFC
   2. ZF (without choice)
   3. Type Theory
   4. GB (class theory)
   5. GU (universe)
2. category theory
   1. <u>as if</u> it is the foundation

* set theory as a foundation
  * Fregeian: sets fixes reference or meaning
  * Carnap: 

## ZFC Set Theory

*Axioms*
1. Extensionality: if $X$ and $Y$ have same members, they are the same set.
2. Null set: $\emptyset$ exists
3. Pairing: there is a unique pair set for each $x$ and $y$m $\{x, y\}$
4. Power set: every set has a unique power set
5. Unions: there is a unique union of any set $\cup$
6. Infinity: there is a unique set with infinitely many numbers. (guaranty at least one $\omega$-sequence)
7. Separation: for any set $S$, we can form the subset of $S$ using predicate
8. Replacement: For every given *definable function* with domain a set A, there is a set whose elements are all the values of the function.
9. Regularity: Every non-empty set $A$ contains an $\in$-minimal element, that is, an element such that no element of A belongs to it.
10. Choice:  For every set $A$ of pairwise-disjoint non-empty sets, there exists a set that contains exactly one element from each set in $A$

* Fregeian: does this tells us what set is/what set means?
* Hilbert: any thing satisfies these axioms is a set

## Category

A category $C$ is an <u>aggregate</u> $Ob$ of abstract elements called objects of $C$,
and abstract elements $Map$ called mappings of $C$.
* The objects are in fact abelian group
* the maps between them are natural transformations

*Axioms*, let $\alpha$ be mappings
1. **Associative**: $\alpha_3(\alpha_2\alpha_1) \equiv (\alpha_3\alpha_2)\alpha_1$
2. **Composition**: $\alpha_3\alpha_2\alpha_1$ is defined whenever $\alpha_3\alpha_2$ and $\alpha_2\alpha_1$ is defined
3. **Identity**: for each $\alpha$ there is an identity mapping s.t. $\alpha e_1 \equiv \alpha \equiv e_2\alpha$
4. The mapping $e_x$ corresponding to each object $X$ is an identity
5. for each identity $e$ there is a unique object $X$ of $C$ such that $e_x = e$

**Defn**:
A category $C$ can be defined as a set $Ob$ of objects,
satisfying the following:
1. **Morphism** (arrow): for every pair $X, Y \in Ob$, there is a set $(X, Y)$ called morphism from $X$ to $Y$ in $C$.
   If $f$ is a morphism, we write $f: X \rightarrow Y$.
2. **Identity**: for every $X \in Ob$, there is morphism $id_x \in Hom(X, X)$ called identity
3. **Composition**: for every $X,Y,Z \in Ob$, there exist operation $\circ: Hom(X, Y) \times Hom(Y, Z) \rightarrow Hom(X, Z)$.
4. 
   1. **Associative**: $(f \circ g) \circ h = f \circ (g \circ h)$
   2. **Identity Map**: $id_y \circ f = f$ and $f \circ id_x = f$

> category theory being founded on set theory?

A category $C$ is two sorted system, the sorts are $Ob$ and $Hom$, satisfying 2,3,4 above.

> Treat this things as undefined terms and predicates,
> just as Hilbert's idea of point, line, and plane

* "$Ob$" and "$Hom$" are undefined terms or predicates
* Take the category axioms as a Hilbertian schema at the meta-level

Example.
* The category $Set$
  * objects as set,
  * morphism as functions
* $Top$
  * topological spaces
  * continues functions
* $Vec$
  * vector spaces
  * linear maps
* $Lat/Bool$
  * lattices / boolean algebras
  * homomorphisms (true, false, and, or)
* $Heyt$
  * Heyting algebra
  * homomorphisms (true, false, and, or, $\implies$)

(Lambek) Any deductive system $T$ that can take object as formulas,
morphism are just proofs of the formulas.