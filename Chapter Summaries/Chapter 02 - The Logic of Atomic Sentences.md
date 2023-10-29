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

### 2.4 Constructing proofs in Fitch

### 2.5 Demonstrating nonconsequence

### 2.6 Alternative notation (optional)

