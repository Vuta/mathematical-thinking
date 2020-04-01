#### Q1. Build a truth table to prove the claim I made earlier that φ ⇔ ψ is true if φ and ψ are both true or both false, and φ ⇔ ψ is false if exactly one of φ, ψ is true and the other false. (To constitute a proof, your table should have columns that show how the entries for φ ⇔ ψ are derived, one operator at a time.)

A:

ϕ | ψ | ϕ ⇒ ψ | ψ ⇒ ϕ | ϕ ⇔ ψ
--- | --- | --- | --- | ---
T | T | T | T | T
T | F | F | T | F
F | T | T | F | F
F | F | T | T | T

#### Q2. Build a truth table to show that (φ ⇒ ψ) ⇔ (¬φ ∨ ψ) is true for all truth values of φ and ψ. A statement whose truth values are all T is called a logical validity, or sometimes a tautology.

ϕ | ψ | ¬ϕ | ϕ ⇒ ψ | ¬ϕ v ψ | (ϕ ⇒ ψ) ⇒ (¬ϕ v ψ) | (¬ϕ v ψ) ⇒ (ϕ ⇒ ψ) | (ϕ ⇒ ψ) ⇔ (¬ϕ v ψ)
--- | --- | --- | --- | --- | --- | --- | ---
T | T | F | T | T | T | T | T
T | F | F | F | F | T | T | T
F | T | T | T | T | T | T | T
F | F | T | T | T | T | T | T

#### Q4. The ancient Greeks formulated a basic rule of reasoning for proving mathematical statements. Called modus ponens, it says that if you know φ and you know φ ⇒ ψ, then you can conclude ψ.

(a) Construct a truth table for logical statement [ϕ ^ (ϕ ⇒ ψ)] ⇒ ψ

(b) Explain how the truth table you obtain demonstrates that modus ponens is a valid rule of inference

A:

(a)

ϕ | ψ | ϕ ⇒ ψ | ϕ ^ (ϕ ⇒ ψ) | [ϕ ^ (ϕ ⇒ ψ)] ⇒ ψ
--- | --- | --- | --- | ---
T | T | T | T | T
T | F | F | F | T
F | T | T | F | T
F | F | T | F | T

(b) Assume modus ponens is valid. Let's say ϕ ^ (ϕ ⇒ ψ) is T (1), and [ϕ ^ (ϕ ⇒ ψ)] ⇒ ψ is true (2)

From (1) and (2) we have ψ is T.

Now if we check the truth table above, we can see that ϕ ^ (ϕ ⇒ ψ) and [ϕ ^ (ϕ ⇒ ψ)] ⇒ ψ are both true when ψ is true.

So we can conclude that modus ponens is a valid rule of inference.

#### Q5. 

One way to prove that ¬(φ ∧ ψ) and (¬φ) ∨ (¬ψ) are equivalent is to show they have the same truth table. Thus, negation has the affect that it changes ∨ into ∧ and changes ∧ into ∨. An alternative approach way to prove this is to argue directly with the meaning of the first statement:

1. φ ∧ ψ means both φ and ψ are true.

2. Thus ¬(φ ∧ ψ) means it is not the case that both φ and ψ are true.

3. If they are not both true, then at least one of φ, ψ must be false

4. This is clearly the same as saying that at least one of ¬φ and ¬ψ is true. (By the definition of negation).

5. By the meaning of or, this can be expressed as (¬φ) ∨ (¬ψ)

Provide an analogous logical argument to show that ¬(φ ∨ ψ) and (¬φ) ∧ (¬ψ) are equivalent.

A:

1. ϕ v ψ means at least one of ϕ, ψ must be true.

2. Thus ¬(ϕ v ψ) means both ϕ and ψ must be false.

3. This is the same as saying both ¬ϕ and ¬ψ must be true.

4. And by the meaning of and, this can be expressed as (¬ϕ) ^ (¬ψ)

Thus we can conclude ¬(ϕ v ψ) and (¬ϕ) ^ (¬ψ) are equivalent.

#### Q6. By a denial of a statement φ we mean any statement equivalent to ¬φ. Give a useful (and hence natural sounding) denial of each of the following statements.

(a) 34,159 is a prime number.

(b) Roses are red and violets are blue.

(c) If there are no hamburgers, I’ll have a hot dog.

(d) Fred will go but he will not play.

(e) The number x is either negative or greater than 10.

(f) We will win the first game or the second.

A:

(a) 34,159 is not a prime number.

(b) Roses aren't red or violets aren't blue.

(c) There are no hamburgers but I won't have a hot dog. 

(d) Fred will play or he won't go.

(e) The number x is non-negative and less than or equal to 10.

(f) We won't win both the first and the second game.

#### Q7. Show that φ ⇔ ψ is equivalent to (¬φ) ⇔ (¬ψ)

A:

(1). ϕ ⇔ ψ means both (ϕ ⇒ ψ) and (ψ ⇒ ϕ) are true

(2) (ϕ ⇒ ψ) means (¬ϕ v ψ), (ψ ⇒ ϕ) means (¬ψ v ϕ)

(3) Thus ϕ ⇔ ψ is equivalent to (¬ϕ v ψ) ^ (¬ψ v ϕ)

(4) (¬φ) ⇔ (¬ψ) means both (¬ϕ ⇒ ¬ψ) and (¬ψ ⇒ ¬ϕ) are true

(5) (¬ϕ ⇒ ψ) means (ϕ v ¬ψ), (¬ψ ⇒ ¬ϕ) means (ψ v ¬ϕ)

(6) Thus (¬φ) ⇔ (¬ψ) is equivalent to (¬ϕ v ψ) ^ (¬ψ v ϕ)

(7) From (3) and (6), we have φ ⇔ ψ is equivalent to (¬φ) ⇔ (¬ψ)

#### Q8. Construct truth tables to illustrate the following:

(a) φ ⇔ ψ

(b) φ ⇒ (ψ ∨ θ)

A:

(a)

ϕ | ψ | ϕ ⇒ ψ | ψ ⇒ ϕ | ϕ ⇔ ψ
--- | --- | --- | --- | --- 
T | T | T | T | T
T | F | F | T | F
F | T | T | F | F
F | F | T | T | T

(b) 

ϕ | ψ | θ | ψ v θ | ϕ ⇒ (ψ v θ)
--- | --- | --- | --- | ---
T | T | T | T | T 
T | T | F | T | T
T | F | T | T | T
T | F | F | F | F
F | T | T | T | T
F | T | F | T | T
F | F | T | T | T
F | F | F | F | T

#### Q9. Use truth tables to prove that the following are equivalent: φ ⇒ (ψ ∧ θ) and (φ ⇒ ψ) ∧ (φ ⇒ θ)

A:

ϕ | ψ | θ | ϕ ⇒ (ψ ^ θ) | (ϕ ⇒ ψ) ^ (ϕ ⇒ θ)
--- | --- | --- | --- | ---
T | T | T | T | T
T | T | F | F | F
T | F | T | F | F
T | F | F | F | F
F | T | T | T | T
F | T | F | T | T
F | F | T | T | T
F | F | F | T | T

#### Q10. Verify the equivalence in the previous question by means of a logical argument. (So, you must show that assuming φ and deducing ψ ∧ θ is the same as both deducing ψ from φ and θ from φ.)

A:

1. ϕ ⇒ (ψ ^ θ) means that all ϕ, ψ, θ are true; or ϕ is false

2. (ϕ ⇒ ψ) ^ (ϕ ⇒ θ) means that both (ϕ ⇒ ψ) and (ϕ ⇒ θ) are true.

3. (ϕ ⇒ ψ) is true means that ϕ is false; or ϕ and ψ are both true.

4. (ϕ ⇒ θ) is true means that ϕ is false; or ϕ and θ are both true.

5. From (2), (3), (4): ϕ is false; or ϕ, ψ and θ are all true

6. From (1) and (5), we have ϕ ⇒ (ψ ^ θ) and (ϕ ⇒ ψ) ^ (ϕ ⇒ θ) is equivalent.

#### Q11. Use truth tables to prove the equivalence of φ ⇒ ψ and (¬ψ) ⇒ (¬φ).

(¬ψ) ⇒ (¬φ) is called the contrapositive of φ ⇒ ψ. 

The logical equivalence of a conditional and its contrapositive means that one way to prove an implication it is to verify the contrapositive. This is a common form of proof in mathematics that we’ll encounter later.

A:

ϕ | ¬ϕ | ψ | ¬ψ | ϕ ⇒ ψ | ¬ψ ⇒ ¬ϕ
--- | --- | --- | --- | --- | --- 
T | F | T | F | T | T
T | F | F | T | F | F
F | T | T | F | T | T
F | T | F | T | T | T

#### Q12. Write down the contrapositives of the following statements:

(a)  If two rectangles are congruent, they have the same area.

(b)  If a triangle with sides a, b, c (c largest) is right-angled, then a² + b² = c².

(c)  If 2ⁿ − 1 is prime, then n is prime.

(d)  If the Yuan rises, the Dollar will fall.

A:

(a) If two rectangles don't have the same area, they are not congruent.

(b) If a triangle with sides a, b, c (c largest) and a² + b² ≠ c², then it's not right-angled.

(c) If n is not a prime, then 2ⁿ - 1 is not prime.

(d) If the Dollar doesn't fall, the Yuan won't rise.

#### Q13. It is important not to confuse the contrapositive of a conditional φ ⇒ ψ with its converse ψ ⇒ φ. Use truth tables to show that the contrapositive and the converse of φ ⇒ ψ are not equivalent.

A:

ϕ | ¬ϕ | ψ | ¬ψ | ψ ⇒ ϕ | ¬ψ ⇒ ¬ϕ | 
--- | --- | --- | --- | --- | --- 
T | F | T | F | T | T
T | F | F | T | T | F
F | T | T | F | F | T
F | T | F | T | T | T

#### Q14. Write down the converses of the four statements in question 12.

A:

(a) If two rectangles have the same area, they are congruent.

(b) If a triangle with sides a, b, c (c largest) and a² + b² = c², then it's right-angled.

(c) If n is prime, then 2ⁿ - 1 is prime.

(d) If the Dollar falls, then the Yuan will rise.
