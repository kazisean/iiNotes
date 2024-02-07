---
title: "DISM"
date: 2024-02-06
summary: "This is a placeholder text for now"
draft: false
garden_tags: ["Math"]
status: "seeding"
---


## Set difference 
The set difference, A - B, is the set of all elements that are in A, but not in B. The order matters

Notation: A - B = {x : x∈A and x∈B}
Ex: A = {1,2,3} B = {2,3,4} => A - B = {1}. B - A = {4}

The symmetic difference of A and B is the set of all elements (1) in A, but not in B or (2) in B, notation A

Notation : A Δ B = {x : (x∈A ⋀ x∈B) V (x∈B ⋀ x∉A)}
            = (A - B) U (B-A)

## Set operations 
### Cartesian Product 

The cartesaian product of A and B, A x B, is the set of all numbered pairs formed by taking an element of A and an element of B in all possible ways. (Order Matters) 

A x B  = {(x,y) : x∈A and y∈B}

Ex: A= {1,3}, B = {2,3,4}
A x B = {(1,2), (1,3), (1,4), (3,2), (3,3), (3,4)} Sometimes there could be repetitions in this case due to repetition is allowed inside of a list 

Size of this set : |A X B | = 6 because the size of set A is 2 and the size of set B is 3 hence |A x B | = 6

Ex: R, R^2 = R x R, R^3 = R x R x R
= {(x,y,z) : z,y,z∈R}

R^n = Rx .... x R = n times



Defination : 
We say that two sets are called disjoint provided their intersection is the empty set. 
Example : A = {1,3,5,7,4, ....} A upward U B = crossed zero
          B = {0, 2, 4, 6,8,....} => A and b are disjoint 


Disjoint is not the same as pairwise disjoint 

Practice more of DeMorgan's Law


Do not write the word equation in proofs

### Corollary 
If A and B are disjoint, then |A U B | = |A| + |B|

PF : Combonorotical Proof
Let A, B be finite sets we will prove |A| + |B| = |A U B | + | A upward u B|
For combonorotical proof you have to have a question. And you need to prove them 2 different times. They have to equal

Question : Suppose we put a label on each element of A and then put a label on each element of B. How many labels are distributed to elements of A and B?

Answer 1 : Left hand side 
Each element in A gets the label A and each element in B gets the label B. So there are |A| + |B| total labels. 


Answer 2 : 