# dismathportfolio-TheDagger24(Ton Argonza)
dismathportfolio-TheDagger24 created by Classroom for GitHub

#Week1
- Introduction to Dismath. It was cool at first.
- Thinking critically is mandatory for the course in order to pass it by the end of the term.
- Truth tables were introduced to us. It is an important tool for the course itself.
- I also learned that we don`t need calculator in the subject unlike our other subjects.
- The "Knights and Knaves" problem was discussed.
- It`s different from other math subjects. 
- The variables that we usually use are p and q.

#Week2
- Quantifiers and tautology.
- For the first part of the course, we`ll learn about proposition, logical connectives, logical deduction and premises.
- 1 = true and 0 = false.
- Logical equivalences (De Morgans, Idempotent, Double Negation)
- ➤ Logical Connectives
   - Negation (¬, not)
   - Conjunction (∧, and)
   - Disjunction (∨, or)
   - Exclusive Or (⊕, xor)
   - Conditional (→, if,then)
   - Biconditional (↔, iff)
- ➤ Logical Equivalence
   -  Identity Law
      - p ∧ T ≡ p
      - p ∧ F ≡ p
   - Domination Law
      - p v T ≡ T  
      - p ∧ F ≡ F 
   - Idempotent Law
      - p v p ≡ p 
      - p ∧ p ≡ p 
   - Double Negation Law
      - ¬(¬p)≡ p 
   - Commutative Law
      - p v q ≡ q v p
      - p ∧ q ≡ q ∧ p 
   - Associative Law
      - (p v q) v r ≡ p v (q v r) 
      - (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)
   - Distributive Law
      - p v (q v r) ≡ (p v q) v (p v r)
      - p ∧ (q ∧ r) ≡ (p ∧ q) ∧ (p ∧ r) 
   - De Morgan's Law
      - ¬(p ∧ q) ≡ ¬p ∧ ¬q
      - ¬(p v q) ≡ ¬p v ¬q 
   - Absorption Law
      - p v (p ∧ q) ≡ p 
      - p ∧ (p v q)≡ p 
   - Negation Law
      - p v ¬p ≡ T
      - p ∧ ¬p ≡ F 
- A lot of hard problems were encountered this week.
- Implication Equivalence was also discussed.
   - p→q = ¬p∨q 
- The "Superman" problem was given as a homework. At the end, we were able to prove that he doesn`t exist.

#Week3
- On this week, we tackled proofs for our lesson.
- Method of proofs are hard and confusing.
- There are many proofs that we need to understand.
- 4 Methods of Proof are : 
  - Direct
  - Contraposition
  - Contradiction
  - Trivial Proof
- ➤Direct Proof
  - First, we assume P is true.
  - Then, we show that q is also true.
- ➤Contrapostion Proof
  - Assume that ¬q is true.
  - Show that ¬q=true.
- ➤Contradiction Proof
  - Assume that ¬p=T
  - Show that ¬p=T ends up with contradiction
- ➤Trivial Proof
  -  q is true, it follows that p→q must also be true.

#Week4
- Proof by equivalence was introduced along with Mathematical Induction.
- As I stated before,  p→q = ¬p∨q.
- Mathematical induction seems familiar because I`ve heard this one before in Engalg2. 
- Mathematical Induction Steps:
 - 1. Show P(1) is T.
 - 2. Show P(k) is T.
 - 3. Show P(k) -> P(k+1).
- Counter example is needed in order to prove that a statement is wrong.

#Week5
- ➤ Program Correctness

    •Includes 2 steps:
        1.) Partial correctness
         - initial assertion
         - final assertion 
        2.) Show that the program terminates correctly
  
- Program algorithms were introduced to us.
- I find it hard because I really suck when it comes to programming. 
- Sets were introduced to us too and I got the idea quickly.
- Venn diagram was used to teach sets.


#Week6
- Review of quantifiers was done.
   - ∀x∀y(x≠y) 
   - ∃x∃y(x≠y)
   - ∀x∃y(x≠y)
   - ∃y∀x(x≠y) 
- There are three types of functions namely : One-to-one, Onto , and Bijection.
- One to one function is a function that has a "unique" value.
- Onto is a kind of function wherein the domain and the codomain are the same. Also,
- Bijection is a function that is both a one-to-one and onto function.

#Week7
-NO CLASSES.

#Week8
- Algorithms were introduced.
- I find it hard because I`m not really good at programming and I actually hate programming.
- Pseudocode was also introduced.
- It is like LBYEC71 but is written in a piece of paper instead of using the computer.
- A dance involving algorithm was shown to us by Sir Melvin.


#Week9
- Searching algorithms were introduced to us.
- Linear and Binary search.
- Iteration table can be used in order to test a linear search.
- Binary search is done by dividing the data into two parts over and over again until it satisfies the condition.
- Binary Search sample:
 - Given:{A1,A2,...,Ai,...An}
 - Result: location of x (loc)
   - while [(i≠j) ≠ (i>j)]
   - mid = (i+j)/2
    - if x>A(mid)
    - {
       then i = 1+mid
       else j=mid
    - }
    - if (x==Ai)

       loc=i
        else 
        loc = -1;

#Week10
- Bubble Sort Algorithm 
-   1. Successively comparing adjacent elements.
-   2. Interchange elements if they are in wrong order.
-   3. Repeat until there are elements.
-   Post Condition: It should be in increasing order.
-   Bubble Sort Code
   - Given: (a1,a2,a3,an) 
   - Result: (x1,x2,x3,xn) ; x1<x2<x3<xn
   - for j: 1 to n-i -> list
   - for i: 1 to n-i
   - if (ai>ai+1)
   - swap(ai,ai+1)
- Insertion Sort Pseudocode was also discussed.
- Insertion Sort Code is:
 - Given:(ai,a2,a3,an) real numbers with n>=2
 - for j=2 to n
 - {
  - i=1
  - while aj>ai
   - i=i+1 
  - m=aj
  - for k=0 to j-i-1
  - a(j-k)=a(j-k-1)
  - ai=m
- Greedy Algorithm selects best choice at each step.
  - Eg. Change
  - for i=1 to r
  - di=0
  - while n>Ci
  - n=n-Ci
  - di=di+1

#Week11
- Growth of functions
- Big Theta is the lower and upper bound of a function. It should be both Big O and Big Omega.
- Big O is the upper bound of a function. C is the constant and K is the intersection.
- Big omega is the lower bound of the function.
- Time complexity

#Week12
- No classes.

#Week13
- There were only 2 classes for quiz 3.
- For the 1st class. The Handshaking Theorem and Graph Theory were introduced.
- Graph Theory consists of nodes(vertices) and edges(degrees)
- Handshaking Theorem can be found by: 2e = Σdegrees*(vertices)
- Euler Path and Circuit was introduced.
- Euler Path - All edges must be used and it has a different starting and finishing point.
- Euler Circuit - All adges must be used and Vo=V, meaning the starting and end point are just the same.
- Hamilton path 
 - It is based on nodes rather than the edges when it comes to Euler.
 - All nodes must be covered but doesn`t necessarily have to pass through all edges.
- Hamilton Circuit
 - Starting node must also be the end node. going through a node greater that 1 time is not allowed.
- Matrix
 - Adjacency Matrix is more on relationship between nodes.
 - Incidence matrix is more on relationship between edges.
- Planar, a graph that has no intersecting edges.
- Non-Planar, a graph that has intersecting edges. (Eg. K3,3)

#Week14
- Graph Coloring was discussed.
 - In graph coloring, no two assignment of colors to each node is the same if they are adjacent to one another.
 - Four Color Theorem
  - Chromatic number - least number of colors.
  - Any planar graph has chromatic number of no greater than four.
- Trees (eg is binary search)
 - connected undirected graph with no simple circuit.
 - Rooted Tree
  - internal vertices with children
  - leaves - without children
 - m-ary tree - has (n-1) number of edges.
 - Automata theory- studies the laws of computation
 - Finite automation - provides the simples model of computing device.
 - Alan Turing - "Father of cs"

