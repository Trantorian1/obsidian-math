> 📚 A **direct proof** is a proof which proceeds directly from the given assumptions to the conclusions via a series of implications.

*ex:*
$$P(x):= the \; sum \; of \; an\; odd \; integer \; is \; odd$$
proof:
	$\underline {suppose} \; x, \; an \; odd \; integer \; s.t \; x = 2k + 1$
	
	$\underline{then}, \; x^2 = (2k + 1)^2  = 4k^2 + 4k + 1 = 1 + 4(k^2 + k)$
	$\underline{however}, \; 4(k^2 + k) \equiv 0 \mod 2$
	$\underline{therefore}, 1 + 4(k^2 + k) \equiv 1 \mod 2$
	
	$\implies P(x) \; is \; true, \forall x \equiv 1 \mod 2$

> ℹ️ Whilst this proof could have been made much simple by a continuous chaining of mathematical implication $\implies$, that would also have made it much less readable. In practice, it is a good habit to use *words of inference*, such as *then*, *however*, *therefore*... to make mathematical proofs more readable. 
> 
> Also try and break down your proof into multiple sub-steps, as it will not only help with improving readability but might also help you with finding solutions to harder proofs.

---
*related:* [[Proof Basics]], [[Proof by Contradiction]], [[Proof by Contraposition]], [[Proof by Case]], [[Disproof by Counterexample]]