# Mathematical Realism

## Realism

also called **Platonism**.

> Realism v.s. Non-Realism is a debate on metaphysics
> we focus on **method**

$\implies$ *As-ifism*

* Pb: Epistemic Access

## Non-Realism

* Pb: reference $\implies$ No uniform semantic
  + in Non-Realism, we don't have "(.*)" refers to (.*)

> "the ball is red" is true $\iff$ "ball" refers to ball and ball satisfies the predicate "red"
>
> "two is even" is true $\iff$ "2" refers to 2 and 2 satisfies the predicate "even

## **Defn** *Benacerraf Dilemma*

*realist*:

If we want shared uniform semantics, we need mathematical reference.
But if we have mathematical reference, 
then we face the problem of epistemic access.

*Non-realist*:

If start with reasonable (casual) epistemology, 
then no mathematical reference, 
thus no uniform semantics.

# Structure

Mathematics doesn't really focus on objects, 
in stead, it focuses on what the structures.

## $\mathbb{N}$ Natural Numbers

For example, recall
$$
\mathbb{N} = \{1, 2, \ldots\}
$$

the structure is defined by the **Peano axioms**.
1. for some set $S$, there is $\sigma \in S$ which is a natural number
2. there is a function $f(n) = n + 1$ defined as the successor functions
3. $\not\exist n$ such that $f(n) = \sigma$
4. $f(n_1) = f(n_2) \implies n_1 = n_2$
5. Induction axiom

this axioms can generate $\mathbb{N}$.

> what are the natural numbers?

what if 
$$
\{ \emptyset, \{\emptyset\}, \{\{\emptyset\}\}, \ldots \}
$$
* or [Church Numerals](https://eyh0602.github.io/2021/03/21/Lambda2/)

notice that this sets also satisfies the Peano axioms.

This "numbers" are not objects.

## Structuralist

Let *systems i* denote each of the sets we listed above that satisfies the Peano axioms.
Is there a *the SYSTEM* that overwrite all the other *systems*?

the *actual abstract* object struct v.s. the *possible system* that have the structure 
$\implies$ 
Structural-Realism v.s. Structural-Nominalism

**BUT**
* actual abstract $\implies$ Epistemic access
* possible system $\implies$ shared uniform semantics

For example, 

```haskell
class Eq a where
  (==) :: a -> a -> Bool
  (/=) :: a -> a -> Bool

instance Eq Integer
  -- Defined in ‘integer-gmp-1.0.0.0:GHC.Integer.Type’
instance (Eq a, Eq b) => Eq (Either a b)
  -- Defined in ‘Data.Either’
instance Eq a => Eq [a] -- Defined in ‘GHC.Classes’
instance Eq Word -- Defined in ‘GHC.Classes’
...
```

* Non-realist/In-Re
  + `Eq` is a name and is instantiated by all its instances `Integer, Either, [a], Word, ...`
* Realist/Ante-rem
  + `Eq` is an abstract object and is exemplified by instances `Integer, Either, [a], Word, ...`

**NOTE** instances here is the *systems* defined in the last section
