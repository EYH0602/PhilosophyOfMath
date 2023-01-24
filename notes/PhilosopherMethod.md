# The Philosopher's Method

> That is the idea of "the good"
>
> Before you become a great philosopher, you have to study mathematics for 20 years.

## The Divided Line

### The Visible

**"Believe"**

* not clear
  + imagination
  + images, shadows
------
* clear
  + opinion
  + clouds, animals, artifacts

For Plato, the only to have knowledge is to have stable object.

### The Intelligible

* hypothetical
  + mathematical
  + the square, the diagonal themselves, the odd, the even
  + known by thought
---
* the clearest
  + metaphysics
  + known by understanding (knowledge)

> Question: is Plato a mathematical realist (platonist)?
>  
> $\implies$ are mathematical objects forms?
>  
> $\implies$ is the hypothetical method part of the dialectical method?

## Hypothetical Method

* begin with a hypothesis
* act **as if** it was a first principle (whose truth cannot be doubted)
* reason consistently down to a conclusion with the aim of solving a problem

$$
H \implies \cdots \implies C
$$

**mathematicians** only need stable definition.
Hypothesis are conjectures

which is very different from the dialectical method, which

* begin with a hypothesis as a hypothesis
* then we reason up to a first principle
* once we reach our first principle, then we can reason down to a conclusion

$$
\begin{aligned}
& FP \implies \cdots \implies C \\
& \Uparrow \\
& H
\end{aligned}
$$

**philosophers** need stable objects.

## Mathematical Objects

Geometric theory of proportion - cosmology
* 3rd geometry 
* 2nd geometry 
* 1st geometry 
* arithmetic

gives a good ordering
* asthenic
* moral notion

```haskell
class  (Eq a) => Ord a  where
    compare              :: a -> a -> Ordering
    (<), (<=), (>), (>=) :: a -> a -> Bool
    max, min             :: a -> a -> a
    
    compare x y = if x == y then EQ
                  -- NB: must be '<=' not '<' to validate the
                  -- above claim about the minimal things that
                  -- can be defined for an instance of Ord:
                  else if x <= y then LT
                  else GT

    x <  y = case compare x y of { LT -> True;  _ -> False }
    x <= y = case compare x y of { GT -> False; _ -> True }
    x >  y = case compare x y of { GT -> True;  _ -> False }
    x >= y = case compare x y of { LT -> False; _ -> True }

        -- These two default methods use '<=' rather than 'compare'
        -- because the latter is often more expensive
    max x y = if x <= y then y else x
    min x y = if x <= y then x else y
    {-# MINIMAL compare | (<=) #-}
```

$$
a:b \text{ and } b:c \implies a:c
$$

* arithmetic theory of proportion: $a, b, c \in \mathbb{N}$
* geometrical theory of proportion: $a, b, c$ are geometric measures
  * include irrational length