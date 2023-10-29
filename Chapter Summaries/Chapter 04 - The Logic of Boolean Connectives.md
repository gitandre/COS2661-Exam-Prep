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

### 4.3 Logical and tautological consequence


--

### 4.4 Tautological consequence in Fitch


--

### 4.5 Pushing negation around (optional)


--

### 4.6 Conjunctive and disjunctive normal forms (optional) 


--

