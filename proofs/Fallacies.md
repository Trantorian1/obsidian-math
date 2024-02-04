> 📚 **Fallacies** are common forms of incorrect reasoning.
`Here are a few basic but noteworthy fallacies`

**Proof by example:** assuming that a statement is true for all cases because it is true for one specific case.

*ex:*
	*"This flower is red, therefore all flowers must be red."*

$let \; F \; := \; "a \; flower"$
$let \; R \; := \; "the \; color \; red"$

$\exists \; F \; s.t \; F \implies R \centernot\implies \forall \; F, \; F \implies R$

**Circular reasoning:** when the proof of a statement relies on the statement itself either directly or through a chain of implications.

*ex:*
	 *"We should have won the championship, we are the best players around."*

$let \; W \; := \; "winning \; the \; championship"$
$let \; B \; := \; "we \; are \; the \; best \; playets \; around"$

$B \implies W, \; however \; \overline W \implies \overline B$

**Converse Error:** Assuming that the converse of a true statement is also true without proof. For example, assuming that if $A \implies B$, then $B \implies A$.

*ex:*
	*"This man rides a horse, therefore all horses must be ridden by men."*

**Undistributed Middle:** A logical fallacy that occurs when an argument assumes that just because two categories share a property, they are the same thing. For example, if all A are C, and all B are C, concluding that all A are B.

*ex:*
	*"humans are mammals, and whales are mammals, therefore all humans are whales."*

$let \; H(x) \; := \; "x \; is \; a \; human"$
$let \; W(x) \; := \; "x \; is \; a \; whales"$
$let \; M(x) \; := \; "x \; is \; a \; mammal"$
$let \; S_m \; = \; \{x | M(x) = true\}, \; the \; set \; of \; all\; mammals$
$let \; S_h \; = \; \{x | H(x) \land x \in S_m = true\}, \; the \; set \; of \; all\; human \; mammals$
$let \; S_w \; = \; \{x | W(x) \land x \in S_m = true\}, \; the \; set \; of \; all\; whale \; mammals$

$S_h \subseteq S_m \land S_w \subseteq S_m \centernot\implies S_h \subseteq S_w$

**Equivocation:** Changing the meaning of a word or phrase within the argument, leading to incorrect conclusions.

🚧 **TODO** 🚧

**False Cause:** Assuming a causal relationship between two events based on their correlation without sufficient evidence for such a causation.

🚧 **TODO** 🚧

**Non Sequitur:** Making a conclusion that does not logically follow from the premises.

🚧 **TODO** 🚧