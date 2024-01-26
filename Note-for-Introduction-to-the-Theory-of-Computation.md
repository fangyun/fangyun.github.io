# Introduction to the Theory of Computation

## 0 INTRODUCTION

### 0.1 AUTOMATA, COMPUTABILITY, AND COMPLEXITY

1. Three traditional areas of the theory of computation are linked by the question: 

   "What are the fundamental capabilities and limitations of computers?"

#### COMPLEXITY THEORY

1. The central questioin of complexity theory:

   "What makes some problems computetionally hard and others easy?"

2. We don't answer to it, researched for over 40 years.

3. One important achievement: discovered an elegant scheme to classify problem according to their computational difficulty. 

   1.  Analogous to periodic table for classifying elements. 
   2. Giving evidence that certain problems are computationally hard, even if unable to prove that they are.

4. Options to confront with a computationally hard problem:

   1. Understanding the root of difficulty. Alter it to easily solvable.
   2. Settle for less than prefect solution.
   3. Hard only in the worst case, easy most of the time. Run procedure occasionally slow but usually quick.
   4. Alternative the type of computation to speed up tasks, such as randomized computation.  

5. Applied area: cryptography

#### COMPUTABILITY THEORY

1. Certain basic problems cannot be solved by computers.
   1. One example: a mathematical statement is true or false?
2. Development of theoretical models of computers lead to construction of actual computers.
3. Focus: classification of problems are solvable or not.
4. Introduces several of concepts from complexity theory.

#### AUTOMATA THEORY

1. Definitions and properties of mathematical models of computation.

### 0.2 MATHEMATICAL NOTIONS AND TERMINOLOGY

#### SETS

+ set, element, members, subset, proper subset, multiset, infinite set, natural numbers N, integers Z, empty set, singleton set, unordered pair
+ union, intersection, complement, Venn diagram

#### SEQUENCES AND TUPLES

+ sequence, tuples, k-tuples, ordered pair, power set
+ Cartesian product or cross product

#### FUNCTIONS AND RELATIONS

+ function or mapping, domain, range
+ onto the range
+ arguments, k-ary function, arity, unary function, binary function
+ infix notation, prefix notation
+ predicate or property : range is {TRUE, FALSE}
+ relation or k-ary relation or a k-ary relation on A whose domain is a set of k-tuples: A×...×A
+ equivalence relation
  + reflexive
  + symmetric
  + transitive

#### GRAPHS

+ undirected graph or graph, nodes, vertices,edges,degree, self-loop,labeled graph, subgraph, path, **simple path**, connected, cycle, **simple cycle**,tree, root, leaves
+ directed graph, outdegree, indegree, **directed path,**strongly connected

#### STRINGS AND LANGUAGES

+ alphabet,symbols, string over an alphabet, length, empty string, reverse, substring
+ concatenation, lexicographic order, shortlex order, string order
+ prefix, proper prefix, language, prefix-free language

#### BOOLEAN LOGIC

+ Boolean values, Boolean operations, negation NOT ¬, conjunction AND ^, disjunction OR 
+ operands, exclusive or XOR , equality, implication
+ distributive law for AND and OR

### 0.3 DEFINITIONS, THEOREMS, AND PROOFS

+ definition, mathematical statements, proof
+ theorem, lemmas, corollaries

#### FINDING PROOFS

+ forward direction, reverse direction, counterexample
+ Few tips for producing a proof
  + Be patient.
  + Come back to it.
  + Be neat.
  + Be concise.

### 0.4 TYEPS OF PROOF

#### PROOF BY CONSTRUCTION

#### PROOF BY CONTRADICTION

#### PROOF BY INDUCTION

+ basis, induction step
+ induction hypothesis

## 1 REGULAR LANGUAGES



