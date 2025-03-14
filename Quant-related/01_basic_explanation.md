# Explanation Prompt for High School-Level Understanding

## Instruction
Please explain the problem-solving steps and answer in a tone that a high school student can understand.

## Function
Break down the solution steps for various GMAT problem types in simple language and provide detailed answer explanations.

## Suitable For
- GMAT test-takers with a weak foundation.
- Students unfamiliar with problem-solving steps or logic.
- Candidates who need to learn the solution methods from scratch.
- Applicable to all GMAT problem types, especially beneficial for those at a lower proficiency level.

## Example
**Input:**  

```
A certain theater has 500 seats. Some are on the main floor and sell for \$50 each; some are in the first balcony and sell for \$45 each; and the rest are in the second balcony and sell for \$35 each. When all of the seats are sold for a performance, the gross revenue for that performance is \$20,900. Of the three seating areas, the second balcony has the most seats.

Select for First balcony a number of seats in this theater’s first balcony and select for Second balcony a number of seats in this theater’s second balcony such that the selections are jointly consistent with the information provided. Make only two selections, one in each column.

First balcony: [100, 150, 190, 210, 250, 300]  
Second balcony: [100, 150, 190, 210, 250, 300]   
```

**Output:**  

Let \(x\) be the number of main floor seats (\$50 each), \(y\) be the number of first balcony seats (\$45 each), and \(z\) be the number of second balcony seats (\$35 each).

1. **Total Seats Equation:**  
   \( x + y + z = 500 \)

2. **Revenue Equation:**  
   \( 50x + 45y + 35z = 20,900 \)

3. **Substitute:**  
   Express \(x\) as:  
   \( x = 500 - y - z \)  
   Substitute into the revenue equation:  
   \( 50(500 - y - z) + 45y + 35z = 20,900 \)

4. **Simplify the Equation:**  
   Multiply out and combine like terms:  
   \( 25,000 - 50y - 50z + 45y + 35z = 20,900 \)  
   \( 25,000 - 5y - 15z = 20,900 \)

5. **Solve for \(y\):**  
   Subtract 25,000 from both sides:  
   \( -5y - 15z = -4,100 \)  
   Multiply by \(-1\):  
   \( 5y + 15z = 4,100 \)  
   Divide by 5:  
   \( y + 3z = 820 \) ->  \( y = 820 - 3z \)

7. **Choose Valid Values:**  
   Given the choices for \(z\) (second balcony) include 100, 150, 190, 210, 250, and 300, test \(z = 210\):  
   \( y = 820 - 3(210) = 820 - 630 = 190 \)  
   Then calculate \(x\):  
   \( x = 500 - 190 - 210 = 100 \)  
   Since \(z = 210\) is greater than both \(y = 190\) and \(x = 100\), the condition that the second balcony has the most seats is satisfied.

Thus, the correct selections are:  
**First balcony: 190 seats**  
**Second balcony: 210 seats**


