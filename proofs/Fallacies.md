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
	*"This puzzle is confusing, therefore everything that is confusing must be a puzzle."*

$let \; P \; := \; "is \; a \; puzzle"$
$let \; C \; := \; "is \; confusing"$

$(P \implies C) \centernot\implies (C \implies P)$

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

**False Cause** *(Correlation is not Causation):* Assuming a causal relationship between two events based on their correlation without sufficient evidence for such a causation.

> 📚 **Correlation:** an association between properties, $A$ is *related* to $B$.

> 📚 **Causation**: changes in on property brings about changes in another, $A$ *causes* $B$ or $B$ if $A$.

*ex:*
	*"The number of people using phones over the last decade has increased, and so has the rate of cancer. Therefore phones must cause cancer."*

> 📝 **Note:** in this case, while both arguments are true on their own (phone usage and cancer rates), there is no direct proof correlating one to the other.

**Non Sequitur:** Making a conclusion that does not logically follow from the premises.

*ex:*
	*"Rosie in class with me again therefore she must like me"*

**Equivocation:** Changing the meaning of a word or phrase within the argument, leading to incorrect conclusions.

*ex:*
	*"The solution to this problem is rational"*

> 📝 **Note:** here there is an ambiguity between the English meaning of rational (reasonable) and it's mathematical meaning ($x \in \mathbb R$).

---
*related:* [[Proof Basics]] [[Rules of Inference]]