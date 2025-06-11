# ASSIGNMENT-3-COMPSCI-230-solution

Download Here: [ASSIGNMENT 3 COMPSCI 230 solution](https://jarviscodinghub.com/assignment/assignment-3-compsci-230-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem 1 (10+1 points)
(a) [5 points] Express the following as a predicate formula.
There exists an integer q for which q + x = x for every real number x.
(b) [5 points] Express the following as a predicate formula using the specified domain of discourse and predicates.
If n is an integer greater than 2, then there are no non-zero integer values of a, b, c that satisfy
a
n + b
n = c
n
. The domain is the set of integers and the predicates are P(x, y, z, n) ⇔
x
n + y
n = z
n
, Q(x) ⇔ x > 2, and O(x) ⇔ x = 0.
Problem 2 (15+1 points)
For the following pairs of formulas F and G, fill in the blanks of G with quantifiers (∀ or ∃) so that
G is equivialent to F, if possible. If this is not possible, proceed onto the following.
Show that the blanks of G can be filled in so that G is implied by F, if possible. Then also show
that the blanks of G can be filled in so that G implies F, if possible. If neither of these are possible,
state this as your answer.
For part (a), your answers (if any) must pick at least one quantifier differently for the variables
in G than in F. For parts (b) and (c), there are no restrictions on which quantifiers you may use.
(a) [5 points]
F = ∀x∃y. P(x, y)
G = x y. P(x, y)
(b) [5 points]
F = ∃x∀y. P(x, y)
G = y x. P(x, y)
(c) [5 points]
F = ∀w∀x∃y∃z. P(w, x, y, z)
G = x w z y. P(w, x, y, z)
Problem 3 (10+1 points)
Prove or disprove for any sets A, B, C:
(a) [5 points]
(A \ B) \ C = (A \ C) \ (B \ C)
(b) [5 points]
(C \ (A ∪ B)) ∪ (B ∩ C) ∪ (A ∩ C) = C
Problem 4 (15 points)
Recall that any logical formula can be expressed in disjunctive normal form (DNF). For this problem
you will implement the function convertToDNF(n,table) as specified in the skeleton file,
hw3 skeleton.py, on the course website.
You may define additional methods that are called by convertToDNF(n,table) as you see
fit, and use the included methods generateTable(n,f) and f test(xs) to test your implementation. The specifications and usage of all methods mentioned are described in hw3 skeleton.py.
