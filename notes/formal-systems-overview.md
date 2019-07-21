# Formal systems

Formal systems provide a way express ideas in an unambiguous manner.  They allow _theorems_ to be inferred from _axioms_ via a set of rules known as the logical calculus of the formal system.  A formal system consists of:

- A language for expressing ideas 
- A set of inference rules.
- A set of axioms.

So they are deductive systems as they allow theorems to be derived from the axioms and the rules of inference.


## Formal Language

A formal language consists of _words_ ( also know as sentences ) made up from an _alphabet_ and are well formed according to a specific set of rules.  So a formal language _L_ over an alphabet _Σ_ is a subset of all the words that that can be composed from _Σ_ constrained by the set of rules that define what a well-formed expression is.  These rules are usually in the form of a formal grammar.


## Inference Rules

Is a logical form consisting of a function which takes premises, analyzes their syntax and returns a conclusion. They are intended to preserve truth but they function at a syntactic level and so do not preserver any semantic properties.  Usually it is only rules that are recursive ( rules that have an effective procedure for determining if a given sentence is a conclusion for a set of formula ).

A procedure is effective if:

- It is consists of a finite number of exact finite instruction.
- when it is applied to a problem from its class:
    - It always terminates after a finite number of steps.
    - It always produces a correct answer.
- In principle it can be done by a human without any aids except writing material.
- You only need to follow its instructions rigorously for it to succeed ( no ingenuity is needed )

The entailment of the system by its logical foundations is what distinguishes a formal system from other systems that use other basis as their foundation.  Entailment is a fundamental concept in logic which describes the relationship between statements that hold true when one statement logically follows from one or other statements.  A valid logical argument is one in which the conclusion is entailed by the premises.  A sentence is said to be a logical consequence ( entailed by ) of a set of sentences if and only if it the sentence must be true if every sentence in the set is true.  The following three features are needed for an adequate characterisation of entailment:

- The logical consequence relation relies on the logical form of the sentence.
- The relation is _A Priori_, it can be determined without regard to empirical evidence.
- The logical consequence relation has a modal component.

A modal account of logical consequence is a variation on the following ideas:

- F ⊢ A is true if and only if it is necessary that if all the elements of _F_ are true then _A_ is true.
- F ⊢ A is true if and only if it is impossible for all elements of _F_ to be true and _A_ be false.

They are modal because they appeal to the modal notion of logical necessity and logical possibility. 'It is necessary that' is often expressed as a universal quantifier over possible world:

F ⊢ A is true if and only if there is no possible world at which all elements of _F_ are true and _A_ is not true.


## Axioms

An axiom is a statement that is taken to be true without proof so that it can be serve as a premise or starting point for further reasoning or argument.  An axiomatic system is any set of axioms from which all axioms can be used in conjunction to logically derive theorems
