> 📚 **Sets** are an *unordered* collection of *unique* objects. 

For example, we denote the set of objects 1, 2 and 3 as $S = \{1, 2, 3\}$.

---
## Generating Sets

> 💡Instead of writing down each element in a set, we can use an expression which specifies how to generate these elements. This especially useful for very large or non-finite sets (so basically, most of them!).

For example, if we want to represent the set of all Real solutions to the equation $x^2 + 7 = 12$, we would write the following
$$\{x | x^2 + 7 = 12, x \in \mathbb{R}\}$$
Which translates to: *the set of all* $x$ *such that* $x^2 + 7 = 12$, *and* $x$ *belongs to* $\mathbb{R}$, *the set of all [[Real Numbers]].*

---
## Set relations

Suppose a given set $S$, and an object $o$. If $o$ is a part of $S$, we write 
$$o \in S$$
Conversely, if $o$ is *not* a part of $S$, we write 
$$o \notin S$$
For example:
	$1 \in \{1, 2, 3\}$
	$1 \notin \{\{1\}, 2, 3\}$
	$1 \notin \emptyset$

---
## Set equality

> 📚 Two sets $S$ and $T$ are said to be equal if they are made up of *exactly* the same objects.

$$\{1, 2, 3\} = \{3, 2, 1\} = \{1, 1, 2, 3\}$$
This further means that the *order* or *repetition* of elements in a set does not matter.

---
## Subsets

> 📚 We say set $T$ is a subset of $S$ if all of the elements contained in $T$ are also contained in $S$, s.t $T \subseteq S \iff \forall x \in T, x \in S$

For example:
	$\{1, 2\} \subseteq \{1, 2, 3\}$
	$\{\{1\}, 2\} \nsubseteq \{1, 2, 3\}$

---
## Empty set

> 📚 As a definition, we define the empty set as the *the set consisting of no objects,* denoted as $\emptyset$.
$$\emptyset = \{\}$$
> ℹ️ By convention, the empty set $\emptyset$ belongs to all sets, s.t $\{1, 2, 3\} = \{1, 2, 3, \emptyset\}$ and $\emptyset$ is a *subset* of *all* sets. 

 For example, the subsets of $\{1, 2, 3\}$ are $1$, $2$, $3$ *and* $\emptyset$.