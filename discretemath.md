# Set Theory

## Basics of Sets

**Set**: A collection of distinct elements. Elements can be anything, such as numbers, letters, or even other sets.

**Listing Method**: A way to represent sets by listing their elements.

- **Denotes**: Indicates whether an element belongs to the set.
- **Subset**: A set is a subset of another if all its elements are in the other set.
- **Proper Set**: A set is a proper set if it is a subset of another set but not equal to it.
- **Cardinality**: The number of elements in a set.

**Power Set**: The set of all possible subsets of a given set.

- The number of subsets in a power set is given by \(2^{(\text{cardinality of the set})}\).

## Special Sets

**Natural Numbers (\(N\)**): The set of positive integers.

**Integers (\(Z\)**): The set of positive and negative whole numbers.

- **Positive Integers (\(Z^+\)**): The set of positive whole numbers.
- **Negative Integers (\(Z^-\)**): The set of negative whole numbers.
- **Non-Negative Integers (\(Z^+_0\)**): The set of positive whole numbers including zero.
- **Non-Positive Integers (\(Z^-_0\)**): The set of negative whole numbers including zero.

**Whole Numbers (\(W\)**): The set of non-negative integers.

**Rational Numbers (\(Q\)**): Numbers that can be expressed as a ratio of two integers.

**Irrational Numbers (\(R\setminus Q\)**): Numbers that cannot be expressed as a ratio of two integers (e.g., \(\sqrt{2}\), \(\pi\), \(e\)).

**Real Numbers (\(R\)**): The set of all rational and irrational numbers.

## Rule of Inclusion (Set Builder Notation)

- Set builder notation is a way to describe sets using a rule or condition.
- For example, \(\{2n : n \in Z\}\) represents the set of even integers.

## Set Functions

- **Union (\(A \cup B\)**): Combines elements from two sets, keeping only distinct elements.
- **Intersection (\(A \cap B\)**): Contains only elements that are common to both sets.
- **Complement (\(¬A\), \(A'\), \(A^L\)**): Contains elements not in the original set.
- **Set Difference (\(A - B\), \(B - A\)**): Contains elements that are in one set but not in the other.
- **Symmetric Difference (\(A \oplus B\)**): Contains elements that are in either set but not in both.

## Venn Diagram

A graphical representation of set relationships using circles.

## Laws of Sets

- **Commutativity**: Order of set operations does not matter for union (\(\cup\)) and intersection (\(\cap\)), but matters for set difference (-).
- **Distributivity**: Describes how union (\(\cup\)) and intersection (\(\cap\)) interact with each other.
- **De Morgan’s Law**: Relates union (\(\cup\)) and intersection (\(\cap\)) through their complements.
- **Inclusion-Exclusion Principle**: Calculates the size of the union of sets using their sizes and intersections.
- **Partition of a Set**: The subdivision of a set into mutually exclusive and jointly exhaustive subsets.

## Proving Questions

Three methods for proving questions related to sets: Membership Tables, Formula Method, and Pick a Point Method.

# Functions

## Definition of a Function

**Function**: A rule that assigns one element from a set to another set. Denoted as \(f: A \rightarrow B\).

- **Domain (\(Df\)**): The set of inputs.
- **Co-Domain (Co-\(Df\)**): The set of possible outputs.
- **Range (\(Rf\)**): The set of actual outputs.
- **Image**: The element in the co-domain corresponding to an element in the domain.

## Injective and Surjective Functions

- **Injective (One-to-One) Function**: A function where no two different elements in the domain map to the same element in the co-domain.
- **Surjective (Onto) Function**: A function where every element in the co-domain has at least one pre-image in the domain.
- **Bijective (Invertible) Function**: A function that is both injective and surjective.

## Inverse Function

The inverse function of a bijective function is a function that undoes the operation of the original function.

## Functional Composition

- Composition of functions: Combining two functions to create a new function.

# Propositional Logic

**Proposition**: A declarative sentence that is either true or false.

**Propositional Variable**: A letter used to represent a proposition.

**Truth Table**: A tabular representation of all possible combinations of constituent variables.

**Truth Set**: The set of elements for which a proposition is true.

## Compound Propositions

- **Negation (\(¬\))**: Represents the opposite of a proposition.
- **Conjunction (\(\land\))**: Represents the logical AND between two propositions.
- **Disjunction (\(\lor\))**: Represents the logical OR between two propositions.
- **Implication (\(\rightarrow\))**: Represents "if-then" logic.
- **Biconditional (\(\leftrightarrow\))**: Represents "if and only if" logic.

## Laws of Propositional Logic

- **Commutative Laws**: Interchangeable order for conjunction (\(\land\)) and disjunction (\(\lor\)).
- **Associative Laws**: Change of grouping for conjunction (\(\land\)) and disjunction (\(\lor\)).
- **Distributive Laws**: Interplay between conjunction (\(\land\)) and disjunction (\(\lor\)).
- **Identity Laws**: The identity elements in conjunction (\(\land\)) and disjunction (\(\lor\)).
- **Contradiction and Excluded Middle**: Special cases of compound propositions.
