# set theory

1. set :- collection of well-defined objects.

   * (well-defined means there is no confusion about what belongs to the set.)

   example:- 
   Set A = {COVID, Dengue, Malaria}
   Set B = {Chickenpox, Dengue, ulcer}

   Each set contains diseases that are well-defined. So, they are valid sets.

2. Collection :- collection can be any group of items, not well-defined.

   example:- All common diseases (not well-defined that means it is not clear like what disease)

   * Union (A ∪ B)
     Combines all elements from both sets (no duplicates).

     Example:
     A = {COVID-19, Dengue}
     B = {Malaria, Dengue}
     A ∪ B = {COVID-19, Dengue, Malaria}

   * Intersection (A ∩ B)
     Includes only elements that are common to both sets.

     Example:
     A = {COVID-19, Dengue}
     B = {Malaria, Dengue}
     A ∩ B = {Dengue}

    * Difference (A – B or A \ B)
      Elements in A but not in B.

      Example:
      A = {COVID-19, Dengue}
      B = {Malaria, Dengue}
      A – B = {COVID-19} 

Example:-
 # Problem Statement

  Problem:
  In a hospital of 1000 patients:
  300 have a disease in Set A (viral diseases)
  250 have a disease in Set B (infected diseases)
  100 have diseases from both sets (A ∩ B)

  Find: Probability that a randomly selected patient has either a viral or parasitic disease.

  Solution:
  Given:
  P(A) = 300 / 1000 = 0.30
  P(B) = 250 / 1000 = 0.25
  P(A ∩ B) = 100 / 1000 = 0.10

  Using the formula:
  P(A ∪ B) = 0.30 + 0.25 – 0.10 = 0.45
  There is a 45% chance that a randomly selected patient has either a viral or infected disease.


3. Conditional Probability:-

Conditional probability is the probability of event A happening that event B has already occurred.

This is written as:

P(A|B) = P(A∩B)/ P(B)

A depends on B.
B is already happened.

Example:-
# Problem Statement:-
  In a population of 1000 patients:
  300 have viral diseases (Set A)
  250 have parasitic diseases (Set B)
  100 have both viral and parasitic diseases (A ∩ B)

  What is the probability that a patient has a viral disease, given that they already have a infected disease?

  Solution:-
  P(A) = 300 / 1000 = 0.30
  P(B) = 250 / 1000 = 0.25
  P(A ∩ B) = 100 / 1000 = 0.10

  Formula:
  P(A | B) = P(A ∩ B) / P(B)
  P(A | B) = 0.10 / 0.25 = 0.40

  There is a 40% chance that a patient has a viral disease, given that they already have a infected disease.

4. Expected value (mean): 