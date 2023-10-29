# COS2661 - Formal Logic II

# Language Proof and Logic

## Chapter 1 - Atomic Sentences

### 1.1 Individual constants

#### 🧒 Explain to me like I am 10

Imagine you have a toy box with different toys: a red ball, a blue car, and a yellow duck. When you want to talk about a specific toy, like the red ball, you give it a special name so everyone knows exactly which toy you're talking about. In the world of formal logic, these special names for specific things are called "Individual Constants."

#### 🎓 A formal explanation explained

In formal logic, atomic sentences are the simplest kind of sentences that express a complete thought. They can't be broken down into smaller parts that are also complete thoughts. An individual constant is a symbol that stands for a specific object within a domain. The domain is just a fancy word for the "universe" of things we are talking about.

#### 📖 Definition

An "Individual Constant" is a symbol that uniquely identifies a specific object within a domain of discourse.

#### 📐 Example

Let's say our domain consists of three animals: a cat, a dog, and a bird. We might assign the following individual constants:

- $( a )$ for the cat
- $( b )$ for the dog
- $( c )$ for the bird

An atomic sentence might look like $( P(a) )$, which could mean "The cat is playful."

#### 💡 Hints/Tips/Rules

- Always clarify your domain before introducing individual constants. It helps avoid confusion.
- Individual constants are like "labels" that you stick onto specific things so you can talk about them clearly.

#### 🎯 Why is it relevant and when to use it

Understanding individual constants is crucial for constructing precise logical statements. They allow you to refer to specific entities, making your logical expressions clear and unambiguous. You would use individual constants when you need to make exact statements about particular objects or entities within a given domain.

#### 📚 Symbols and notations used

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Individual Constant| $( a, b, c, \ldots )$  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | $( P(a), Q(b), R(c) )$| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point

An individual constant is a specific "label" used in formal logic to refer to a particular object in a domain. These constants are crucial in forming atomic sentences, which are the simplest types of sentences in logic that express a complete thought. They help make your logical statements precise and clear.

---

### 1.2 Atomic Sentences - Predicate symbols

#### 🧒 Explain to me like I am 10

Imagine you are playing a game where you have to sort different fruits based on their color. You would say things like "This apple is red" or "This banana is yellow." In the world of formal logic, we use something called "Predicate Symbols" to do the same thing. They help us say what a thing is like or what it's doing.

#### 🎓 A formal explanation explained

In formal logic, a predicate symbol is used to represent a property or relation that an object or objects can have. These symbols are combined with individual constants to form atomic sentences. Predicate symbols allow us to make claims or statements about the world in a structured way.

#### 📖 Definition

A "Predicate Symbol" is a symbol used in a logical formula to represent a property or relation that can hold for objects within a domain.

#### 📐 Example

If our domain consists of a cat, a dog, and a bird, and we have a predicate symbol \( P \) to represent "is playful," then:

- $( P(a) )$ would mean "The cat is playful."
- $( P(b) )$ would mean "The dog is playful."

#### 💡 Hints/Tips/Rules

- Predicate symbols are case-sensitive. So \( P \) and \( p \) would be different predicates.
- Make sure to clarify what property or relation the predicate symbol is representing.

#### 🎯 Why is it relevant and when to use it

Predicate symbols are essential for describing properties or relationships among objects in a domain. They are used to form atomic sentences, which are the building blocks of more complex logical statements.

#### 📚 Symbols and notations used

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Predicate Symbol   | $( P, Q, R, \ldots )$ | Symbols that represent properties or relations       |

#### 📝 Summary of Key Point

Predicate symbols are used to describe properties or relationships in formal logic. They are combined with individual constants to form atomic sentences, enabling us to make precise claims about the world.

---


### 1.3 Atomic Sentences - Atomic sentences

#### 🧒 Explain to me like I am 10

Imagine you're playing with building blocks. Each block is like a small sentence that says something simple like "The cat is happy" or "It is raining." Just like you can use single blocks to build more complex structures, in logic, we use these simple sentences, called "Atomic Sentences," to build more complex ideas.

#### 🎓 A formal explanation explained

In the realm of formal logic, atomic sentences are the simplest, indivisible units that represent a complete idea or statement. They consist of a predicate symbol and an individual constant or variables. These sentences serve as the foundation upon which more complex logical formulas are built.

#### 📖 Definition

An "Atomic Sentence" is a simple, indivisible logical statement that represents a complete idea. It consists of a predicate symbol and an individual constant or variables.

#### 📐 Example

For instance, if we have a domain of animals, with the individual constants $( a )$ for a cat and $( b )$ for a dog, and a predicate symbol $( P )$ for "is playful," then:

- $( P(a) )$ means "The cat is playful."
- $( P(b) )$ means "The dog is playful."

#### 💡 Hints/Tips/Rules

- Atomic sentences are the building blocks of logical formulas; understanding them is crucial for grasping more complex ideas.
- Be clear about the domain and the meanings of the symbols you're using.

#### 🎯 Why is it relevant and when to use it

Atomic sentences are the starting point for any logical argument or proof. They provide the basic framework upon which more complicated logical structures are built. You'll use them whenever you're constructing or analyzing logical statements.

#### 📚 Symbols and notations used

| Name               | Symbol                | Description                                         |
|--------------------|-----------------------|-----------------------------------------------------|
| Individual Constant| $( a, b, c, \ldots )$  | Symbols that uniquely identify specific objects     |
| Atomic Sentence    | $( P(a), Q(b), R(c) )$| Simplest form of sentences incorporating individual constants |

#### 📝 Summary of Key Point

Atomic sentences are the simplest kinds of sentences in formal logic. They serve as the building blocks for more complex logical statements, making them indispensable in the study and application of logic.

---


### 1.4 Atomic Sentence - General First-Order Languages

#### 🧒 Explain to me like I am 10

You know how in different games, the basic rules are the same but you can add new rules to make it more exciting? In logic, we start with simple sentences like "The cat is playful." But in something called "General First-Order Languages," we can add even more details and rules to talk about all sorts of things!

#### 🎓 A formal explanation explained

In general first-order languages, we extend the basic structure of atomic sentences to include not just individual constants and predicate symbols but also variables and quantifiers. This allows for a richer and more expressive language capable of forming more complex statements about a given domain.

#### 📖 Definition

A "General First-Order Language" is an extension of the basic logical language to include variables, quantifiers, and sometimes functions, in addition to predicate symbols and individual constants.

#### 📐 Example

If we have a domain of animals and a predicate symbol $( P )$ for "is playful," a more complex atomic sentence in a general first-order language might be:

- $( \forall x, P(x) )$, which means "All animals are playful."

#### 💡 Hints/Tips/Rules

- When dealing with general first-order languages, keep track of your variables and quantifiers carefully to avoid confusion.
- It's more expressive but also requires more caution in its use.

#### 🎯 Why is it relevant and when to use it

General first-order languages are crucial when the basic atomic sentences are not sufficient to express the complexity of a situation or argument. They allow for a more nuanced and detailed logical analysis.

#### 📚 Symbols and notations used

| Name                | Symbol                   | Description                                        |
|---------------------|--------------------------|----------------------------------------------------|
| Individual Constant | $( a, b, c, \ldots )$     | Symbols that uniquely identify specific objects    |
| Atomic Sentence     | $( P(a), Q(b), R(c) )$    | Simplest form of sentences incorporating individual constants |
| Variable            | $( x, y, z, \ldots )$     | Symbols that can represent any object in a domain  |
| Quantifier          | $( \forall, \exists )$    | Symbols that express 'for all' or 'there exists'   |

#### 📝 Summary of Key Point

General first-order languages extend the capabilities of basic logical languages by adding variables and quantifiers. This makes it possible to create more complex and nuanced logical statements, allowing for a richer exploration of ideas.

---


## Atomic Sentences
### 1.5 Function symbols

#### 🧒 Explain to me like I am 10

Imagine you have a magic wand that can turn things into other things. Like, it turns a cat into a lion or a piece of wood into a toy. In logic, we have something similar called "Function Symbols" that help us describe how one thing can turn into another.

#### 🎓 A formal explanation explained

Function symbols in formal logic are used to represent operations or transformations that take certain objects and yield new ones. Unlike predicate symbols, which describe properties or relationships, function symbols generate new objects based on the ones they act upon.

#### 📖 Definition

A "Function Symbol" is a symbol used in a logical formula to represent an operation or transformation that takes one or more objects and returns a new object.

#### 📐 Example

For instance, if \( f \) is a function symbol representing "parent of," then:

- $( f(a) )$ would represent "the parent of \( a \)"
- $( f(b) )$ would represent "the parent of \( b \)"

#### 💡 Hints/Tips/Rules

- Function symbols don't make statements true or false; they produce new objects.
- Make sure to clarify what operation or transformation the function symbol is representing.

#### 🎯 Why is it relevant and when to use it

Function symbols add a layer of complexity and richness to logical languages. They allow us to model operations and transformations, which is especially useful in mathematical logic, computer science, and other fields that require precise definitions.

#### 📚 Symbols and notations used

| Name                | Symbol                   | Description                                        |
|---------------------|--------------------------|----------------------------------------------------|
| Individual Constant | $( a, b, c, \ldots )$     | Symbols that uniquely identify specific objects    |
| Atomic Sentence     | $( P(a), Q(b), R(c) )$    | Simplest form of sentences incorporating individual constants |
| Function Symbol     | $( f, g, h, \ldots )$     | Symbols that represent operations or transformations|

#### 📝 Summary of Key Point

Function symbols in formal logic are used to represent operations or transformations. They take one or more objects as input and produce a new object as output. This allows for more complex and nuanced logical expressions.

---


## Atomic Sentences
### 1.6 The First-Order Language of Set Theory

#### 🧒 Explain to me like I am 10

You know how you can put your toys in different boxes to organize them? In math and logic, we also use 'boxes' called sets to organize numbers or other things. We have special rules and symbols to talk about what's inside these sets and how they interact.

#### 🎓 A formal explanation explained

The first-order language of set theory provides a formal way to discuss sets and their properties. This language incorporates elements, sets, and the relationships between them using specific symbols like \( \in \) for 'belongs to' and \( \subseteq \) for 'is a subset of'.

#### 📖 Definition

The "First-Order Language of Set Theory" is a formal language used in mathematics to discuss the properties, relations, and operations concerning sets. It typically involves predicate symbols like "belongs to" and "is a subset of".

#### 📐 Example

In this language, you can form atomic sentences like:

- $( a \in A )$ to say "a belongs to set A"
- $( A \subseteq B )$ to say "A is a subset of B"

#### 💡 Hints/Tips/Rules

- Be mindful of the elements and sets you are discussing; ensuring they belong to the correct 'universe' or domain.
- Understand the difference between 'belongs to' and 'is a subset of'; they are not the same.

#### 🎯 Why is it relevant and when to use it

The first-order language of set theory is crucial in mathematics, computer science, and other disciplines that require a rigorous way to discuss sets and their properties. It's used in proofs, algorithms, and many other areas where precise definitions are needed.

#### 📚 Symbols and notations used

| Name                | Symbol                   | Description                                        |
|---------------------|--------------------------|----------------------------------------------------|
| Belongs To          | $( \in )$                | Symbol representing that an element is in a set    |
| Is a Subset Of      | $( \subseteq )$          | Symbol representing that a set is a subset of another set |

#### 📝 Summary of Key Point

The first-order language of set theory is a formal language used to discuss sets and their properties. It provides a rigorous way to describe relationships between sets and their elements, making it indispensable in mathematics and computer science.

---

## Atomic Sentences
### 1.7 The first-order language of arithmetic


--

## Atomic Sentences
### 1.8 Alternative notation



---