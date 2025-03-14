# Quick Math Shortcut for N-Minute Problem Solving

## Instruction
Provide a shortcut method that a human can solve a math problem in N minutes using only paper, pencil, and visual estimation. The principle is: the fewer calculations, the simpler the numbers, and the simpler and fewer the formulas, the better. If substituting numbers or using visual guessing is simpler, feel free to adopt that approach.

**Note:** "N minutes" is variable depending on the problem type (e.g., Q: 2 minutes, DS: 1.5-2 minutes).

## Function
Offer a quick math shortcut that minimizes computation, enhances exam efficiency, and simplifies calculations.

## Suitable For
- Candidates with a basic foundation but slow problem-solving speed.
- Test-takers aiming for greater time efficiency during the exam.
- Those who struggle with cumbersome calculations.
- Suitable for math-related problems in Q, TPA/DS/MSR/GT where a quick, efficient approach is beneficial.

## Example
**Input:**  
```
A certain theater has 500 seats. Some are on the main floor and sell for \$50 each; some are in the first balcony and sell for \$45 each; and the rest are in the second balcony and sell for \$35 each. When all of the seats are sold for a performance, the gross revenue for that performance is \$20,900. Of the three seating areas, the second balcony has the most seats.

Select for First balcony a number of seats in this theater’s first balcony and select for Second balcony a number of seats in this theater’s second balcony such that the selections are jointly consistent with the information provided. Make only two selections, one in each column.

First balcony: [100, 150, 190, 210, 250, 300]  
Second balcony: [100, 150, 190, 210, 250, 300]  

Provide a shortcut method that a human can solve a math problem in 3 minutes using only paper, pencil, and visual estimation. The principle is: the fewer calculations, the simpler the numbers, and the simpler and fewer the formulas, the better. If substituting numbers or using visual guessing is simpler, feel free to adopt that approach.
```

**Output:**  

Let \(x\) be the number of main floor seats (\$50 each), \(y\) be the number of first balcony seats (\$45 each), and \(z\) be the number of second balcony seats (\$35 each). We have two key pieces of information:
1. Total seats:  
   \[
   x + y + z = 500
   \]
2. Total revenue:  
   \[
   50x + 45y + 35z = 20,900
   \]

**Quick Shortcut Approach:**

- **Step 1: Visualize Revenue Loss**  
  If every seat were \$50, the revenue would be  
  \[
  500 \times 50 = 25,000.
  \]  
  The actual revenue is \$20,900, which is \$4,100 less. This shortfall comes from using lower-priced seats:
  - Each first balcony seat (at \$45) loses \$5 relative to \$50.
  - Each second balcony seat (at \$35) loses \$15 relative to \$50.

- **Step 2: Set Up a Simple Equation**  
  Let the number of first balcony seats be \(y\) and second balcony seats be \(z\). The total loss is:  
  \[
  5y + 15z = 4,100.
  \]  
  Divide by 5:  
  \[
  y + 3z = 820.
  \]

- **Step 3: Use Intelligent Guessing with Given Options**  
  Since the second balcony must have the most seats, choose a higher value for \(z\). Testing \(z = 210\):
  \[
  y = 820 - 3(210) = 820 - 630 = 190.
  \]  
  Then, compute main floor seats:
  \[
  x = 500 - y - z = 500 - 190 - 210 = 100.
  \]
  
- **Step 4: Verify Quickly**  
  - Loss from first balcony: \(190 \times 5 = 950\).  
  - Loss from second balcony: \(210 \times 15 = 3,150\).  
  Total loss: \(950 + 3,150 = 4,100\), which confirms our calculation.

Thus, the correct selections are:  
**First balcony: 190 seats**  
**Second balcony: 210 seats**

This method minimizes computations by focusing on the revenue shortfall per seat and using a quick substitution with intelligent guessing.
