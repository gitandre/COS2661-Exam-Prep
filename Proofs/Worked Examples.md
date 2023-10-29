## Worked examples of using rules and moves in proofs

### Rules of Inference

1. **Modus Ponens (→ Elim)**
    - Goal: Prove $( B $)
    - Premises:
        1. $( A \rightarrow B $)
        2. $( A $)
    - Proof:
        3. $( B $) (→ Elim, 1, 2)

2. **Modus Tollens**
    - Goal: Prove $( \lnot A $)
    - Premises:
        1. $( A \rightarrow B $)
        2. $( \lnot B $)
    - Proof:
        3. $( \lnot A $) (Modus Tollens, 1, 2)

3. **Conjunction Introduction (∧ Intro)**
    - Goal: Prove $( A \land B $)
    - Premises:
        1. $( A $)
        2. $( B $)
    - Proof:
        3. $( A \land B $) (∧ Intro, 1, 2)

4. **Conjunction Elimination (∧ Elim)**
    - Goal: Prove $( A $)
    - Premises:
        1. $( A \land B $)
    - Proof:
        2. $( A $) (∧ Elim, 1)

5. **Disjunction Introduction (∨ Intro)**
    - Goal: Prove $( A \lor B $)
    - Premises:
        1. $( A $)
    - Proof:
        2. $( A \lor B $) (∨ Intro, 1)

6. **Disjunction Elimination (∨ Elim)**
    - Goal: Prove $( C $)
    - Premises:
        1. $( A \lor B $)
        2. $( A \rightarrow C $)
        3. $( B \rightarrow C $)
    - Proof:
        4. $( C $) (∨ Elim, 1, 2, 3)

7. **Negation Elimination (¬ Elim) / Reductio ad Absurdum**
    - Goal: Prove $( A $)
    - Premises:
        1. $( \lnot \lnot A $)
    - Proof:
        2. $( A $) (¬ Elim, 1)

8. **Negation Introduction (¬ Intro)**
    - Goal: Prove $( \lnot A $)
    - Premises:
        1. $( A \rightarrow \text{False} $)
    - Proof:
        2. $( \lnot A $) (¬ Intro, 1)

9. **Conditional Introduction (→ Intro)**
    - Goal: Prove $( A \rightarrow B $)
    - Premises:
        1. $( A $) (Assumption)
        2. $( B $) (Derived from 1)
    - Proof:
        3. $( A \rightarrow B $) (→ Intro, 1-2)

### Rules of Replacement (Equivalence)

For rules of replacement, we often show that one statement can be replaced by another. These don't usually form "proofs" in the traditional sense but demonstrate the equivalence of different expressions.

1. **Double Negation**  
   $( A $) is equivalent to $( \lnot \lnot A $)

2. **Commutativity**  
   $( A \land B $) is equivalent to $( B \land A $)

3. **Associativity**  
   $( (A \land B) \land C $) is equivalent to $( A \land (B \land C) $)

4. **Distribution**  
   $( A \land (B \lor C) $) is equivalent to $( (A \land B) \lor (A \land C) $)

5. **DeMorgan's Laws**  
   $( \lnot (A \land B) $) is equivalent to $( \lnot A \lor \lnot B $)

6. **Implication**  
   $( A \rightarrow B $) is equivalent to $( \lnot A \lor B $)

7. **Contrapositive**  
   $( A \rightarrow B $) is equivalent to $( \lnot B \rightarrow \lnot A $)

8. **Biconditional Equivalence**  
   $( A \leftrightarrow B $) is equivalent to $( (A \rightarrow B) \land (B \rightarrow A) $)

These examples are simplified for the sake of illustration. In real proofs, you'd often use multiple rules in combination to prove more complex statements.