> 📚 For a given statement $P$, a **proof by contradiction** begins by assuming that $P$ is false -in other words, assuming $\overline P$. The goal of the proof is then to arrive at a conclusion $C$ that is palpably false, proving $P$ true.
$$if \; \overline P \implies C \land C = false, \; \underline{then} \; \overline C \implies P \implies P = true$$

*ex:*
$$P(n) := n \equiv 0 \mod 3,\forall n \in \mathbb R, n^2 \equiv 0 \mod 3$$
*or:*
$$P(n) := \; "n \; is \; a \; multiple \; of \; 3, \; for \; any \; n \in \mathbb R, \; where \; n^2 \; is \; a \; multiple \; of \; 3"$$
proof:
	$suppose \; n \; is \; \underline{not} \; a \; multiple \; of \; 3.$
	
	$\underline{then} \; n \equiv 1 \mod 3$
	$\implies n^2 = (1 + 3k)^2 = 1 + 6k + 9k^2 = 1 + 3(2k + 3k^2) \not\equiv 0 \mod 3$
	$\underline{or} \; n \equiv 2 \mod 3$
	$\implies n^2 = (2 + 3k^2) = 4 + 12k + 9k^2 = 1 + 3(1 + 4k + 3k^2) \not\equiv 0 \mod 3$
	
	$\underline{this \; is \; a \; contradiction}, \; as \; we \; are \; given \; the \; condition \; n^2 \equiv 0 \mod 3$
	$\underline{therefore} \; P(n) \; is \; true, \; \forall n \in \mathbb R, \; s.t n^2 \equiv 0 \mod 3$
	

---
*related:* [[Proof Basics]], [[Direct Proof]], [[Proof by Contradiction]], [[Proof by Contraposition]], [[Proof by Case]], [[Disproof by Counterexample]]