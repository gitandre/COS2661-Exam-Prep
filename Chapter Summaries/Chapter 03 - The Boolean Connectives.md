# COS2661 - Formal Logic II

# Language Proof and Logic

## Chapter 03 - The Boolean Connectives

## The Boolean Connectives
### **3.1 Negation symbol: ¬**

#### 🧒 Explain to me like I am 10:

You know how in a video game you might have a button that turns something ON or OFF? The "¬" symbol is like that button but for saying something is NOT true. So if you have "The sky is blue," putting "¬" in front of it makes it "The sky is NOT blue."

#### 🎓 A formal explanation explained:

In formal logic, the negation symbol "¬" is used to indicate the opposite or negation of a statement. If a statement \( P \) is true, then its negation \( ¬P \) is false, and vice versa.

#### 📖 Definition:

The negation symbol "¬" is a unary operator in formal logic that reverses the truth value of the statement it precedes. If \( P \) is a statement, then \( ¬P \) is its negation.

#### 📐 Example:

\`\`\`plaintext
Example:
Statement: The sky is blue. (Let's call this P)
Negation: The sky is NOT blue. (This is ¬P)
\`\`\`

#### 💡 Hints/Tips/Rules:

- Be careful with double negatives; they can make a statement true again.
- The negation of a negation \( ¬¬P \) is equivalent to the original statement \( P \).

#### 🎯 Why is it relevant and when to use it:

The negation symbol is foundational in logic, used for constructing complex logical statements and proofs. It's relevant in mathematics, computer science, philosophy, and any field that involves rigorous reasoning.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Negation           | \( ¬ \)               | Reverses the truth value of the statement it precedes|
| Individual Constant| \( ( a, b, c, \ldots ) \)  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | \( ( P(a), Q(b), R(c) ) \)| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

The negation symbol "¬" is a fundamental element in formal logic, used to reverse the truth value of a statement. Understanding how to use it correctly is essential for constructing and evaluating logical statements and proofs.

---

## The Boolean Connectives
### **3.2 Conjunction symbol: ∧**

#### 🧒 Explain to me like I am 10:

Imagine you and your friend want to go to a theme park, but you can only go if BOTH your mom says yes AND the weather is good. The "∧" symbol is like the word "AND" that makes sure both things are true.

#### 🎓 A formal explanation explained:

The conjunction symbol "∧" is used to represent the logical "AND" operation. In a statement \( P \land Q \), both \( P \) and \( Q \) must be true for the entire statement to be true.

#### 📖 Definition:

The conjunction symbol "∧" is a binary operator in formal logic used to combine two statements \( P \) and \( Q \) into a new statement \( P \land Q \), which is true only if both \( P \) and \( Q \) are true.

#### 📐 Example:

\`\`\`plaintext
Example:
Statement 1: It is raining. (Let this be \( P \))
Statement 2: I have an umbrella. (Let this be \( Q \))
Conjunction: It is raining AND I have an umbrella. (\( P \land Q \))
\`\`\`

#### 💡 Hints/Tips/Rules:

- The conjunction \( P \land Q \) is only true if both \( P \) and \( Q \) are true.
- Think of it as a stricter condition; all parts must be satisfied.

#### 🎯 Why is it relevant and when to use it:

The conjunction symbol is essential for constructing complex logical statements, useful in computer programming, mathematical proofs, and everyday reasoning. It allows for conditions that depend on multiple factors.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Conjunction        | \( \land \)           | Represents the logical "AND" operation               |
| Individual Constant| \( ( a, b, c, \ldots ) \)  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | \( ( P(a), Q(b), R(c) ) \)| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

The conjunction symbol "∧" is used in formal logic to represent the logical "AND" operation, allowing us to construct statements that are true only if all constituent parts are true. It is a crucial tool for complex logical reasoning.




---

## The Boolean Connectives
### **3.3 Disjunction symbol: ∨**

#### 🧒 Explain to me like I am 10:

You know how on weekends you can either play video games OR go to the park? The "∨" symbol is like the word "OR" that lets you choose one thing or the other or both!

#### 🎓 A formal explanation explained:

In formal logic, the disjunction symbol "∨" represents the logical "OR" operation. In a statement \( P \lor Q \), either \( P \), \( Q \), or both must be true for the entire statement to be true.

#### 📖 Definition:

The disjunction symbol "∨" is a binary operator in formal logic used to combine two statements \( P \) and \( Q \) into a new statement \( P \lor Q \), which is true if either \( P \), \( Q \), or both are true.

#### 📐 Example:

\`\`\`plaintext
Example:
Statement 1: I like chocolate. (Let this be \( P \))
Statement 2: I like vanilla. (Let this be \( Q \))
Disjunction: I like chocolate OR I like vanilla. (\( P \lor Q \))
\`\`\`

#### 💡 Hints/Tips/Rules:

- The disjunction \( P \lor Q \) is false only if both \( P \) and \( Q \) are false.
- Use it when you want to express options or alternatives in a logical statement.

#### 🎯 Why is it relevant and when to use it:

The disjunction symbol is crucial for expressing options or alternatives in a logical statement. It is widely used in computer science for conditional statements, in mathematics for defining sets, and in everyday reasoning.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Disjunction        | \( \lor \)            | Represents the logical "OR" operation                |
| Individual Constant| \( ( a, b, c, \ldots ) \)  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | \( ( P(a), Q(b), R(c) ) \)| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

The disjunction symbol "∨" is used in formal logic to denote the logical "OR" operation, allowing for a statement to be true if any of its constituent parts are true. It is an essential tool for modeling choices and alternatives in logical reasoning.


---

## The Boolean Connectives
### **3.4 Remarks about the game**

#### 🧒 Explain to me like I am 10:

Imagine you're playing a game of chess. It's not just about knowing how the pieces move, but also understanding strategies, like when to attack or defend. "Remarks about the game" is like talking about those strategies, tips, and why certain rules exist in the game of logic.

#### 🎓 A formal explanation explained:

In the realm of formal logic, "Remarks about the game" refers to the metatheoretical considerations, limitations, and extensions of basic logical rules and operations. It provides a deeper understanding of why particular logical rules work the way they do and their implications.

#### 📖 Definition:

"Remarks about the game" refers to the discussion and analysis of the foundational principles, assumptions, and limitations in a logical system. This includes, but is not limited to, the properties of logical operations, their axiomatic bases, and their applications.

#### 📐 Example:

\`\`\`plaintext
Example:
- Understanding why a double negation \( ¬¬P \) results in \( P \) helps to understand the structure of logical arguments.
- Realizing that the statement \( P \lor ¬P \) is always true is a foundational principle known as the Law of Excluded Middle.
  \`\`\`

#### 💡 Hints/Tips/Rules:

- Always question the assumptions behind logical rules.
- Understanding the "why" behind the rules can help you apply them more effectively.

#### 🎯 Why is it relevant and when to use it:

Understanding the underlying principles and limitations of logical rules is crucial for advanced study and application in fields like mathematics, philosophy, and computer science. It helps to clarify why certain logical structures are universally accepted and others are not.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Individual Constant| \( ( a, b, c, \ldots ) \)  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | \( ( P(a), Q(b), R(c) ) \)| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

"Remarks about the game" in formal logic refers to the deeper understanding of why and how specific logical rules and operations function. These insights are essential for anyone looking to apply logical principles in various disciplines.




---

## The Boolean Connectives
### **3.5 Ambiguity and parentheses**

#### 🧒 Explain to me like I am 10:

You know how in math class, you use parentheses to make it clear which numbers should be added or multiplied first? Like, \( (2 + 3) \times 4 \) is different from \( 2 + (3 \times 4) \)? In the same way, in logic, we use parentheses to make sure everyone understands the statement the same way.

#### 🎓 A formal explanation explained:

Parentheses are used in formal logic to eliminate ambiguity by clearly indicating the order of operations in complex logical expressions. This ensures that the expression is interpreted uniformly, regardless of the complexity of the logical operators involved.

#### 📖 Definition:

Parentheses in formal logic are used to group sub-expressions within a larger logical expression to clarify the order in which logical operations are to be performed.

#### 📐 Example:

\`\`\`plaintext
Example without parentheses: \( P \land Q \lor R \)
Example with parentheses: \( (P \land Q) \lor R \) or \( P \land (Q \lor R) \)

The two parenthesized expressions can have different truth values depending on the truth values of \( P, Q, \) and \( R \).
\`\`\`

#### 💡 Hints/Tips/Rules:

- Always use parentheses to remove ambiguity in complex logical expressions.
- When in doubt, parenthesize.

#### 🎯 Why is it relevant and when to use it:

Parentheses are essential for removing ambiguity in logical expressions, particularly in programming, mathematics, and formal logical proofs. Incorrect grouping can lead to misinterpretation and errors.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Parentheses        | \( () \)              | Used to group sub-expressions                        |
| Individual Constant| \( ( a, b, c, \ldots ) \)  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | \( ( P(a), Q(b), R(c) ) \)| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

Parentheses are used in formal logic to remove ambiguity by specifying the order of operations in complex logical expressions. They are crucial for ensuring that an expression is interpreted consistently, regardless of its complexity.




---

## The Boolean Connectives
### **3.6 Equivalent ways of saying things**

#### 🧒 Explain to me like I am 10:

You know how "I'm happy and joyful" means the same as "I'm joyful and happy"? In logic, we have different ways of saying the same thing too! We can rearrange words and symbols, but they still mean the same thing.

#### 🎓 A formal explanation explained:

In formal logic, different logical expressions can be equivalent, meaning they have the same truth values under all possible conditions. These equivalences can often be proven through a series of logical steps or transformations.

#### 📖 Definition:

Two logical statements are said to be equivalent if they have the same truth values in all situations.

#### 📐 Example:

\`\`\`plaintext
Example:
- \( P \land Q \) is equivalent to \( Q \land P \)
- \( P \lor (Q \land R) \) is equivalent to \( (P \lor Q) \land (P \lor R) \)
  \`\`\`

#### 💡 Hints/Tips/Rules:

- To check for equivalence, you can construct a truth table for both expressions and compare.
- Use logical identities like De Morgan's laws to simplify and compare expressions.

#### 🎯 Why is it relevant and when to use it:

Understanding logical equivalences is crucial for simplifying logical expressions, proving theorems, and optimizing algorithms in computer science.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Logical AND        | \( \land \)           | Represents logical conjunction                       |
| Logical OR         | \( \lor \)            | Represents logical disjunction                       |
| Individual Constant| \( ( a, b, c, \ldots ) \)  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | \( ( P(a), Q(b), R(c) ) \)| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

In formal logic, different logical expressions can be equivalent, meaning they represent the same truth conditions. Knowing how to identify and use these equivalences is vital for a variety of applications, from theorem proving to algorithm optimization.




---

## The Boolean Connectives
### **3.7 Translation**

#### 🧒 Explain to me like I am 10:

Imagine you're playing a game where you have to replace code names with real names. In logic, we do something similar! We translate complex sentences into simpler logical symbols to make them easier to understand.

#### 🎓 A formal explanation explained:

In formal logic, translation involves converting natural language statements into logical form using logical symbols and operators. This helps in analyzing the logical structure of arguments and sentences.

#### 📖 Definition:

Translation in the context of formal logic refers to the process of converting natural language statements into symbolic logical expressions.

#### 📐 Example:

\```plaintext
Natural Language: "It is raining and the ground is wet."
Logical Translation: \( P \land Q \)
\```

#### 💡 Hints/Tips/Rules:

- Identify the main components of a sentence.
- Look for conjunctions like "and," "or," and conditionals like "if... then..." to break down the sentence.
- Use parentheses to clarify the order of operations when needed.

#### 🎯 Why is it relevant and when to use it:

Translation is crucial when you want to analyze arguments or statements for validity, consistency, or other logical properties. It's often the first step in formal logical analysis.

#### 📚 Symbols and notations used:

| Name               | Symbol                 | Description                                         |
|--------------------|------------------------|-----------------------------------------------------|
| Logical AND        | \( \land \)            | Represents logical conjunction                       |
| Logical OR         | \( \lor \)             | Represents logical disjunction                       |
| Individual Constant| \( ( a, b, c, \ldots ) \) | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | \( ( P(a), Q(b), R(c) ) \)| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

Translation in formal logic is the practice of converting natural language statements into their symbolic logical forms. This is essential for analyzing the structure and validity of logical arguments.




---

## The Boolean Connectives
### **3.8 Alternative notation (optional)**

#### 🧒 Explain to me like I am 10:

You know how sometimes you can say the same thing in different ways? Like instead of saying "I am happy," you could say "I'm joyful." In logic, we have different ways of writing the same thing too!

#### 🎓 A formal explanation explained:

Alternative notation in formal logic means using different symbols or expressions to represent the same logical operation or relation. This can be useful depending on the context or the tradition in which you're working.

#### 📖 Definition:

Alternative notation refers to the use of different symbols or forms to express the same logical operations or relations.

#### 📐 Example:

\```plaintext
Standard Notation: \( P \land Q \)
Alternative Notation: \( P \& Q \)
\```

#### 💡 Hints/Tips/Rules:

- Always check the context or the guide you're working from to understand which notation is being used.
- When in doubt, stick to standard notation to avoid confusion.

#### 🎯 Why is it relevant and when to use it:

Understanding alternative notations helps in reading different texts on logic or in collaborating with people who use different notations. It also broadens your understanding of logical operations.

#### 📚 Symbols and notations used:

| Name                  | Symbol                  | Description                                            |
|-----------------------|-------------------------|--------------------------------------------------------|
| Logical AND           | $( \land, \&, \cdot )$  | Represents logical conjunction                          |
| Logical OR            | $( \lor, + )$           | Represents logical disjunction                          |
| Individual Constant   | $( a, b, c, \ldots )$   | Symbols that uniquely identify specific objects        |
| Atomic Sentence       | $( P(a), Q(b), R(c) )$  | Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

Alternative notation in formal logic allows us to express the same logical ideas in different ways. Being familiar with these helps in better understanding and communication in the field of logic.




---

