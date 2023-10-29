# COS2661 - Formal Logic II

# Language Proof and Logic

## Chapter 2 - The Logic of Atomic Sentences

## The Logic of Atomic Sentences
### **2.1 Valid and Sound Arguments**

#### 🧒 Explain to me like I am 10:

Imagine you and your friends are detectives, and you find clues to solve a mystery. A "valid" clue is one that really helps you figure out the mystery. A "sound" clue is not only useful but also true! In logic, we use "valid" to mean an argument makes sense, and "sound" to mean it makes sense and is also true.

#### 🎓 A formal explanation explained:

In formal logic, an argument is considered "valid" if the structure of the argument is such that if the premises are true, then the conclusion must also be true. An argument is "sound" if it is both valid and the premises are actually true.

#### 📖 Definition:

- Valid Argument: An argument is valid if, assuming that the premises are true, the conclusion must also be true.
- Sound Argument: An argument is sound if it is valid and its premises are true.

#### 📐 Example:

\`\`\`plaintext
Valid but not Sound Argument:
1. All cats can fly. (Premise)
2. Whiskers is a cat. (Premise)
3. Therefore, Whiskers can fly. (Conclusion)

Sound and Valid Argument:
1. All men are mortal. (Premise)
2. Socrates is a man. (Premise)
3. Therefore, Socrates is mortal. (Conclusion)
   \`\`\`

#### 💡 Hints/Tips/Rules:

- Always check the validity of an argument before considering its soundness.
- Validity is about structure; soundness is about structure and truth.
- An argument can be valid but not sound, but it can't be sound without being valid.

#### 🎯 Why is it relevant and when to use it:

Understanding the difference between valid and sound arguments is crucial in logic, philosophy, law, and many other fields. It helps you evaluate the quality of arguments and ensures that you construct strong, persuasive arguments yourself.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Individual Constant| $( a, b, c, \ldots )$  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | $( P(a), Q(b), R(c) )$| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

A valid argument is one where the conclusion logically follows from the premises. A sound argument is not only valid but also has true premises. Understanding these terms is essential for evaluating and constructing logical arguments.

---

## The Logic of Atomic Sentences
### **2.2 Methods of Proof**

#### 🧒 Explain to me like I am 10:

Think of methods of proof like the moves you can make in a game of chess. Each move has rules, and you use them to win the game. In the same way, there are different methods to show that something is true in logic, like a detective proving who the villain is!

#### 🎓 A formal explanation explained:

Methods of proof in formal logic are the structured approaches used to demonstrate the validity or soundness of a statement or argument. These methods often involve applying logical rules to manipulate atomic and compound sentences to reach a conclusion.

#### 📖 Definition:

Methods of proof refer to the systematic procedures, such as Modus Ponens, Modus Tollens, and proof by contradiction, used to derive a conclusion from a set of premises.

#### 📐 Example:

\`\`\`plaintext
Example using Modus Ponens:
1. If it rains, the ground will be wet. (Premise)
2. It is raining. (Premise)
3. Therefore, the ground is wet. (Conclusion)
   \`\`\`

#### 💡 Hints/Tips/Rules:

- Choose the method of proof that is most appropriate for your argument.
- Keep track of your premises and the steps you've taken to avoid errors.
- Familiarize yourself with common methods like Modus Ponens, Modus Tollens, and proof by contradiction.

#### 🎯 Why is it relevant and when to use it:

Knowing various methods of proof allows you to evaluate or construct strong, logical arguments. Whether you're in academics, law, or even everyday reasoning, understanding these methods can be invaluable.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Individual Constant| $( a, b, c, \ldots )$  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | $( P(a), Q(b), R(c) )$| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

Methods of proof are structured approaches used in logic to validate or prove statements. They are the logical "moves" that help you win your argument by reaching a valid conclusion.

---

## The Logic of Atomic Sentences
### **2.3 Formal proofs**

#### 🧒 Explain to me like I am 10:

Imagine you're building a LEGO tower. Each LEGO block has to fit perfectly for the tower to be strong and stand tall. In the same way, a formal proof is like a tower of reasons, where each reason fits perfectly to show that something is true.

#### 🎓 A formal explanation explained:

A formal proof is a structured, step-by-step demonstration that uses the rules of logic to show that a certain statement is true. Each step in a formal proof follows logically from the previous steps, ensuring the conclusion is reached in a logically sound manner.

#### 📖 Definition:

A formal proof is a sequence of logical statements and inferences that lead from a set of premises to a conclusion, adhering strictly to the rules of logic.

#### 📐 Example:

\`\`\`plaintext
Example of a Formal Proof using Modus Ponens:
1. If it rains, then the ground will be wet. (Premise)
2. It is raining. (Premise)
3. Therefore, the ground is wet. (Conclusion by Modus Ponens from 1 and 2)
   \`\`\`

#### 💡 Hints/Tips/Rules:

- Always start with clearly stated premises.
- Follow the rules of logic strictly at each step.
- Be meticulous; even a small mistake can invalidate the entire proof.

#### 🎯 Why is it relevant and when to use it:

Formal proofs are the cornerstone of logical and mathematical reasoning. They are essential in fields like computer science, philosophy, and mathematics to rigorously establish the truth of statements.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Individual Constant| $( a, b, c, \ldots )$  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | $( P(a), Q(b), R(c) )$| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

A formal proof is a rigorous, step-by-step demonstration that uses logical rules to establish the truth of a statement. It is a foundational element in logical and mathematical reasoning.

---

## The Logic of Atomic Sentences
### **2.4 Constructing proofs in Fitch**

#### 🧒 Explain to me like I am 10:

You know how you follow a recipe step-by-step to bake a cake? Fitch is like a special recipe book for solving logic puzzles. You follow each step carefully, and if you do it right, you'll find out if something is true or not!

#### 🎓 A formal explanation explained:

Fitch is a formal system used for constructing logical proofs. It provides a structured environment where each step of reasoning is clearly laid out, following specific rules and formats to derive a conclusion from initial premises.

#### 📖 Definition:

In the Fitch system, a formal proof is constructed using a series of statements, each accompanied by a justification. The justification can be a rule of inference, a premise, or a previously proven statement.

#### 📐 Example:

\`\`\`plaintext
Fitch-style Proof Example:
1. \( P \)                     Premise
2. \( P \rightarrow Q \)       Premise
3. \( Q \)                     Modus Ponens from 1 and 2
   \`\`\`

#### 💡 Hints/Tips/Rules:

- Always start with your premises clearly stated.
- Follow each rule of inference meticulously.
- Annotations are crucial; they explain why each step is valid.

#### 🎯 Why is it relevant and when to use it:

Fitch is particularly useful in academic settings, formal logic studies, and computer science for algorithmic verification. It's a precise way to ensure the logical soundness of an argument or computation.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Individual Constant| $( a, b, c, \ldots )$  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | $( P(a), Q(b), R(c) )$| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

Constructing proofs in Fitch involves following a structured system to derive logical conclusions from premises. It's a rigorous and reliable method for conducting logical proofs and is widely used in various fields requiring formal reasoning.

---

## The Logic of Atomic Sentences
### **2.5 Demonstrating non-consequence**

#### 🧒 Explain to me like I am 10:

Imagine you hear a noise and think it's a ghost. But then you find out it's just the wind. Just because you heard a noise doesn't mean it was a ghost. In logic, sometimes we think one thing leads to another, but it really doesn't. That's called a "non-consequence."

#### 🎓 A formal explanation explained:

In formal logic, demonstrating non-consequence involves showing that a specific conclusion doesn't logically follow from the given premises. This is typically done by finding a counterexample where the premises are true but the conclusion is false.

#### 📖 Definition:

A non-consequence occurs when a conclusion does not logically follow from its premises. In formal terms, a statement \( Q \) is a non-consequence of a statement \( P \) if there exists a situation where \( P \) is true but \( Q \) is false.

#### 📐 Example:

\`\`\`plaintext
Example of Demonstrating Non-consequence:
1. All birds can fly. (Premise)
2. Penguins are birds. (Premise)
3. Therefore, penguins can fly. (Conclusion)
- Counterexample: Penguins are birds but cannot fly.
  \`\`\`

#### 💡 Hints/Tips/Rules:

- Look for counterexamples to demonstrate non-consequence.
- Always verify your premises carefully.
- Non-consequences often reveal gaps or errors in reasoning.

#### 🎯 Why is it relevant and when to use it:

Understanding and demonstrating non-consequence is important for critical thinking and logical analysis. It helps you identify flaws in arguments and avoid making incorrect conclusions.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Individual Constant| $( a, b, c, \ldots )$  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | $( P(a), Q(b), R(c) )$| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

Demonstrating non-consequence in logic involves showing that a conclusion does not necessarily follow from its premises. This is often done by providing counterexamples. It's a crucial skill for evaluating the validity of arguments.

---

## The Logic of Atomic Sentences
### **2.6 Alternative notation (optional)**

#### 🧒 Explain to me like I am 10:

You know how you can write the number five as '5' or 'five' or even 'V' in Roman numerals? In logic, we can also use different "ways of writing" to say the same thing. This is called alternative notation.

#### 🎓 A formal explanation explained:

Alternative notation in the context of atomic sentences allows for different ways to express the same logical statement. For example, different symbols or formats can be used to represent the same logical operations, predicates, or elements.

#### 📖 Definition:

Alternative notation refers to using various symbols or arrangements to represent the same logical or mathematical concept, without changing its meaning.

#### 📐 Example:

\`\`\`plaintext
Example:
Original Notation: \( P \rightarrow Q \)
Alternative Notation: \( \neg P \lor Q \)
\`\`\`

#### 💡 Hints/Tips/Rules:

- When using alternative notation, make sure to define what each symbol represents.
- Use alternative notation cautiously; the goal is to simplify, not complicate.
- Be consistent; don't mix different notations in the same proof or argument.

#### 🎯 Why is it relevant and when to use it:

Alternative notation can be useful for simplifying statements or making your reasoning more accessible to different audiences. It's relevant in academic papers, textbooks, and computational logic where different notational conventions may be used.

#### 📚 Symbols and notations used:

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Individual Constant| $( a, b, c, \ldots )$  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | $( P(a), Q(b), R(c) )$| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point:

Alternative notation provides flexibility in expressing logical concepts. While it's optional, using it wisely can make logical statements easier to understand or work with, especially when engaging with different fields or audiences.

---

