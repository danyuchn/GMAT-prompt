# Designing Variant Questions for Practice

## Instruction
Design a variant question so that I can practice using the same solution method.

## Function
- Provide a variant of the original problem that uses the same solution method to test me whether I have totally understand the concept.

## Suitable For
- Candidates who need extra practice to consolidate their solution methods.
- Those who find a single problem insufficient for thorough practice.
- Test-takers who want to become familiar with a specific solution approach.
- Applicable to math-related problems in Q, DS, TPA, MSR.

## Example

**Input:**  

"A certain company plans to sell Product X for p dollars per unit, where p is randomly chosen from all possible positive values not greater than 100. The monthly manufacturing cost for Product X (in thousands of dollars) is 12 - p, and the projected monthly revenue from Product X (in thousands of dollars) is p(6 - p). If the projected revenue is realized, what is the probability that the company will NOT see a profit on sales of Product X in the first month of sales?

A. 0
B. 1/100
C. 1/25
D. 99/100
E. 1

Provide a variant of the original problem that uses the same solution method to test me whether I have totally understand the concept."

**Output:**  

"A certain company plans to sell **Product Y** for *q* dollars per unit, where *q* is chosen uniformly at random from all positive values not greater than 100. The monthly manufacturing cost for Product Y (in thousands of dollars) is given by  
\[ 14 - q, \]  
and the projected monthly revenue (in thousands of dollars) is  
\[ q(8 - q). \]  
If the projected revenue is realized, what is the probability that the company will **not** earn a profit on sales of Product Y in the first month?

(A) 0  
(B) 1/20  
(C) 19/20  
(D) 1/2  
(E) 1

 Solution:  
1. Profit Function:  
   Profit = Revenue − Cost  
   Profit = q(8 - q) - (14 - q) = 8q - q^2 - 14 + q = 9q - q^2 - 14.

2. Finding the Profit Condition:  
   For the company to earn a profit, we need:  
   9q - q^2 - 14 > 0, which is equivalent to q^2 - 9q + 14 < 0.  
   Factor the quadratic:  
   q^2 - 9q + 14 = (q - 2)(q - 7).  
   Therefore, profit > 0 when:  
   2 < q < 7.

3. Probability Calculation:  
   Since q is uniformly distributed over (0, 100], the probability that q falls in the interval (2, 7) is:  
   (7 - 2) / 100 = 5/100 = 1/20.  
   Consequently, the probability that the company does not earn a profit is the complement:  
   1 - 1/20 = 19/20.

Thus, the correct answer is (C) 19/20."


