# COS2661 - Formal Logic II

# Language Proof and Logic

## Chapter 04 - The Logic of Boolean Connectives

## The Logic of Boolean Connectives
### 4.1 Tautologies and logical truth

#### 🧒 Explain to me like I am 10
Tautologies are like magic sentences in logic that are always true, no matter what! It's like saying "It's either raining or not raining." One of those has to be true, right?

#### 🎓 A formal explanation explained
A tautology in formal logic is a formula that is true under every possible interpretation or assignment of truth values. This means that it holds universally, irrespective of the truth or falsity of its atomic components.

#### 📖 Definition
A tautology is a formula \( \phi \) such that for every interpretation \( I \), \( I(\phi) = \text{True} \).

#### 📐 Example

\`\`\`text
Example 1: \( P \lor \lnot P \)  (Law of Excluded Middle)
Example 2: \( (P \land Q) \lor (\lnot P \lor \lnot Q) \)
\`\`\`

#### 💡 Hints/Tips/Rules
- Tautologies are important for proofs and logical reasoning.
- They act as the logical equivalent of a "universal truth."

#### 🎯 Why is it relevant and when to use it
Tautologies are foundational in logic because they're always true. They're often used in proofs and logical reasoning as steps that are undeniably true, making your argument stronger.

#### 📚 Symbols and notations used

| Name                  | Symbol                  | Description                                          |
|-----------------------|-------------------------|------------------------------------------------------|
| Individual Constant   | \( ( a, b, c, \ldots ) \) | Symbols that uniquely identify specific objects      |
| Atomic Sentence       | \( ( P(a), Q(b), R(c) ) \) | Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point
Tautologies are formulas that are always true, regardless of the truth values of their components. They are fundamental in logical reasoning and proofs.

---

## The Logic of Boolean Connectives
### 4.2 Logical and tautological equivalence

#### 🧒 Explain to me like I am 10
Imagine you have two different LEGO sets, but you can build the exact same spaceship with both. They might look a little different at first, but they end up being the same. In logic, when two sentences mean the same thing, we say they are "equivalent."

#### 🎓 A formal explanation explained
Two logical formulas are said to be tautologically equivalent if they have the same truth values in every possible scenario. That is, substituting one for the other in any logical statement will not change the truth value of the statement.

#### 📖 Definition
Two formulas \( \phi \) and \( \psi \) are tautologically equivalent, written as \( \phi \equiv \psi \), if and only if \( \phi \leftrightarrow \psi \) is a tautology.

#### 📐 Example

\`\`\`text
Example 1: \( P \land Q \) is equivalent to \( Q \land P \)  
Example 2: \( P \lor (Q \land R) \) is equivalent to \( (P \lor Q) \land (P \lor R) \)
\`\`\`

#### 💡 Hints/Tips/Rules
- Use truth tables to check for tautological equivalence.
- Equivalence is reflexive, symmetric, and transitive.

#### 🎯 Why is it relevant and when to use it
Understanding equivalence is key for simplifying logical expressions, solving logical equations, and proving theorems. It allows you to substitute one expression for another without changing the meaning.

#### 📚 Symbols and notations used

| Name                  | Symbol                 | Description                                              |
|-----------------------|------------------------|----------------------------------------------------------|
| Individual Constant   | \( ( a, b, c, \ldots ) \) | Symbols that uniquely identify specific objects          |
| Atomic Sentence       | \( ( P(a), Q(b), R(c) ) \) | Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point
Logical and tautological equivalence is a fundamental concept in logic that deals with the equality of meaning between different logical formulas. It is essential for simplification, substitution, and proof in logical reasoning.

--

## The Logic of Boolean Connectives
### 4.3 Logical and tautological consequence

#### 🧒 Explain to me like I am 10
Imagine you have a puzzle. If one piece fits into another, then it's like saying the second piece is a 'consequence' of the first. In logic, if one statement makes another statement always true, then the second is a consequence of the first.

#### 🎓 A formal explanation explained
In logic, a formula \( \phi \) is a logical consequence of a set of formulas \( \Gamma \) if every model that makes all formulas in \( \Gamma \) true also makes \( \phi \) true. In other words, \( \phi \) has to be true whenever \( \Gamma \) is true.

#### 📖 Definition
A formula \( \phi \) is a tautological consequence of a set of formulas \( \Gamma \), written \( \Gamma \models \phi \), if every truth assignment that makes all formulas in \( \Gamma \) true also makes \( \phi \) true.

#### 📐 Example
\`\`\`text
Example 1: \( Q \) is a logical consequence of \( P \rightarrow Q \) and \( P \).
Example 2: \( P \lor Q \) is a tautological consequence of \( P \).
\`\`\`

#### 💡 Hints/Tips/Rules
- Use truth tables to test for logical consequence.
- A formula can have multiple consequences.

#### 🎯 Why is it relevant and when to use it
Understanding logical consequence is crucial for making valid arguments and proofs. It helps you know what must be true given certain assumptions.

#### 📚 Symbols and notations used

| Name                  | Symbol                     | Description                                              |
|-----------------------|----------------------------|----------------------------------------------------------|
| Individual Constant   | $( a, b, c, \ldots )$       | Symbols that uniquely identify specific objects          |
| Atomic Sentence       | $( P(a), Q(b), R(c) )$      | Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point
Logical and tautological consequence are foundational concepts in logic. They help you understand what must necessarily follow from a given set of statements, aiding in argumentation and proof.




--

## The Logic of Boolean Connectives
### 4.4 Tautological consequence in Fitch

#### 🧒 Explain to me like I am 10
Think of Fitch like a game of clues. You have clues, or "premises," and you want to find out something true based on those clues. A "Tautological Consequence" in Fitch is like finding a clue that always leads you to the same answer, no matter what.

#### 🎓 A formal explanation explained
In Fitch, a statement is a "Tautological Consequence" if it is always true whenever the premises it is based on are true. This means you can prove this statement using the rules of the game (Fitch), without needing any extra clues.

#### 📖 Definition
In Fitch, a proposition \( P \) is a tautological consequence of a set of propositions \( \Gamma \) if, whenever all propositions in \( \Gamma \) are true, \( P \) must also be true.

#### 📐 Example
\`\`\`
1. \( P \lor Q \)  (Premise)
2. \( \lnot P \)   (Premise)
----------------
3. \( Q \)         (Tautological Consequence)
   \`\`\`

#### 💡 Hints/Tips/Rules
- Make sure to follow the rules of inference in Fitch.
- Take your time to understand the premises before jumping to conclusions.

#### 🎯 Why is it relevant and when to use it
Understanding "Tautological Consequence" helps you build strong arguments and understand when a statement must be true, based on the clues you have. It's a powerful tool in logic and reasoning.

#### 📚 Symbols and notations used

| Name                      | Symbol            | Description                                         |
|---------------------------|-------------------|-----------------------------------------------------|
| Proposition               | \( P, Q, R \)     | Basic statements that can be true or false          |
| Tautological Consequence  | \( \vdash \)      | Symbol showing that one thing is a consequence of another |

#### 📝 Summary of Key Point
A Tautological Consequence in Fitch is a statement that is always true when the premises it is based on are true. Understanding this helps you make strong logical arguments.



--

## The Logic of Boolean Connectives
### 4.5 Pushing negation around (optional)

#### 🧒 Explain to me like I am 10
Imagine you're playing with building blocks. Some blocks are red, and some are blue. Saying "not red" means it has to be blue. "Pushing negation around" is like playing with these "not" rules to make your building game easier!

#### 🎓 A formal explanation explained
In formal logic, pushing negation around refers to using specific rules to move the negation symbol (\( \lnot \)) within logical expressions. This helps simplify complex statements into a more manageable form.

#### 📖 Definition
Pushing negation is the process of applying De Morgan's laws and double negation elimination to simplify logical expressions involving negation (\( \lnot \)).

#### 📐 Example
\`\`\`plaintext
Original Expression: \( \lnot (P \land Q) \)
After Pushing Negation: \( (\lnot P) \lor (\lnot Q) \)

Truth Table:
| P | Q | \( \lnot (P \land Q) \) | \( (\lnot P) \lor (\lnot Q) \) |
|---|---|-------------------------|--------------------------------|
| T | T |           F             |                F               |
| T | F |           T             |                T               |
| F | T |           T             |                T               |
| F | F |           T             |                T               |
\`\`\`

#### 💡 Hints/Tips/Rules
- Use De Morgan's laws to push negation over conjunction (\( \land \)) and disjunction (\( \lor \)).
- Eliminate double negatives when possible.

#### 🎯 Why is it relevant and when to use it
Pushing negation is useful for simplifying logical expressions, making them easier to analyze or prove. It's often used in mathematical proofs, computer science algorithms, and even legal arguments.

#### 📚 Symbols and notations used

| Name                      | Symbol         | Description                                         |
|---------------------------|----------------|------------------------------------------------------|
| Negation                  | \( \lnot \)    | Symbol used to indicate logical negation             |
| Conjunction               | \( \land \)    | Symbol used to indicate logical AND                  |
| Disjunction               | \( \lor \)     | Symbol used to indicate logical OR                   |

#### 📝 Summary of Key Point
Pushing negation around simplifies complex logical expressions, making them easier to understand, analyze, and prove. It involves using specific rules like De Morgan's laws and double negation elimination.


--

## The Logic of Boolean Connectives
### 4.6 Conjunctive and Disjunctive Normal Forms

#### 🧒 Explain to me like I am 10
Imagine you have a big box of Lego blocks, and you want to build something. You have two ways to build: either stack them all in a line (like a train) or pile them all up (like a tower). In logic, these two ways are like the 'Conjunctive Normal Form' and the 'Disjunctive Normal Form.'

#### 🎓 A formal explanation explained
Conjunctive Normal Form (CNF) and Disjunctive Normal Form (DNF) are standardized ways of writing logical expressions using ANDs, ORs, and NOTs. CNF is a set of clauses joined by AND, where each clause is a set of literals joined by OR. DNF is the opposite: a set of clauses joined by OR, where each clause is a set of literals joined by AND.

#### 📖 Definition
- **Conjunctive Normal Form (CNF)**: An expression is in CNF if it is a conjunction of one or more clauses, where a clause is a disjunction of literals.
- **Disjunctive Normal Form (DNF)**: An expression is in DNF if it is a disjunction of one or more clauses, where a clause is a conjunction of literals.

#### 📐 Example
\`\`\`plaintext
CNF: $(A \lor B) \land (C \lor D) \land (E \lor F)$
DNF: $(A \land B) \lor (C \land D) \lor (E \land F)$

Truth Table for CNF:
| A | B | C | D | E | F | $(A \lor B) \land (C \lor D) \land (E \lor F)$ |
|---|---|---|---|---|---|-----------------------------------------------|
| T | T | T | T | T | T |                       T                       |
| ... | ... | ... | ... | ... | ... | ... |

\`\`\`

#### 💡 Hints/Tips/Rules
- To convert an expression to CNF or DNF, use distributive laws and De Morgan's laws.

#### 🎯 Why is it relevant and when to use it
These forms are useful for simplifying logical expressions and are often used in computer science, particularly in algorithms and data structures like decision trees.

#### 📚 Symbols and notations used
| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Conjunction        | $( \land )$           | Logical AND                                         |
| Disjunction        | $( \lor )$            | Logical OR                                          |
| Literal            | $( A, \lnot A, B )$   | An atomic sentence or its negation                  |

#### 📝 Summary of Key Point
Conjunctive and Disjunctive Normal Forms are standardized ways of writing logical expressions. They make it easier to analyze, compare, and implement these expressions in various applications.

--

