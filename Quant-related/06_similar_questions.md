# Finding Similar Questions Based on Mathematical Concepts

## Instruction
From the given set of questions, please find those that use similar mathematical concepts as the current problem.

## Function
Filter and select questions from a question bank that share similar mathematical concepts with the current problem, assisting candidates in targeted practice.

## Suitable For
- Test-takers who are unsure which problems are related to the current learning objective.
- Candidates who need more practice on similar topics.
- Those aiming to deepen their understanding of specific mathematical concepts.
- Applicable to math-related problems in Q, DS, TPA, MSR.

## Example
**Input:**   

```A certain theater has 500 seats. Some are on the main floor and sell for $50 each; some are in the first balcony and sell for $45 each; and the rest are in the second balcony and sell for $35 each. When all of the seats are sold for a performance, the gross revenue for that performance is $20,900. Of the three seating areas, the second balcony has the most seats.

Select for First balcony a number of seats in this theater’s first balcony and select for Second balcony a number of seats in this theater’s second balcony such that the selections are jointly consistent with the information provided. Make only two selections, one in each column.

Show Spoiler  
First balcony  Second balcony   
        100  
        150  
        190  
        210  
        250  
        300

From the given set of questions, please find those that use similar mathematical concepts as the current problem.   
```

**A Small item bank as input:**

```Fast food restaurant sells sandwiches. There are five ingredients with the following choices:  
Bread: A, B, C  
Meat: beef, turkey, ham  
Cheese: Sweden cheese, American cheese, or no cheese  
Sauce: add, or not add  
Mustard: add, or not add  
A person buys a sandwich. They want ham with any cheese, or a specified beef or turkey and no cheese. How many combinations are there?

---  
Given S1 = {1}, S2 = {2, 3, 4}, S3 = {5, 6, 7, 8, 9}, ... Determine the smallest number in the set S51.

---  
A fresh lemon weighs 100 grams, with 40 grams of pulp and 60 grams of water. If after drying, the water percentage becomes 20%,  
how many fresh lemons are needed to obtain 4000g of dried lemon?

---  
For the quadratic equation x² + (m - 2)x + (n + 4)² = 0 to have only one root, find mn.

---  
A person drives 540 miles, and the car's fuel tank capacity is 10.5 gallons. Each time half of the fuel is used, the person refills the tank. Also, given that one gallon of fuel can run 35 miles, what is the most likely remaining fuel in the tank at the end of the journey, assuming the car started with a full tank? (After every 183.75 miles (35 * 5.25 = 183.75) a refill is made. Thus, the third refill occurs at 551.25 miles (183.75 * 3) and the driver stops at 540 miles, so the most likely fuel amount is 5 gallons. Options include 2, 5, 9, 13, etc.)

---  
8 people are to be accommodated in six rooms. Room 1 must have 1 person, Room 2 must have 2 people, and Rooms 3-6 have no capacity limits (they can be empty). How many possibilities are there?

---  
(Data Sufficiency)  
Determine the ratio of the number of employees in January 2021 to the number in January 2020 for a company.  
1) In 2021, there are 100 more employees than in 2020.  
2) For every employee in 2020 who is not in 2021, there are two new employees in 2021 that were not in 2020.

---  
There are three types of coins: 5 cent, 10 cent, and 25 cent. The total amount is $3.20 and the total number of coins is 29. The number of 10 cent coins is three times the number of 25 cent coins. How many 5 cent coins are there?

---  
Given that 1/(N + 1) < (1/31) + (1/32) + (1/33) < 1/N, find N.

---  
There are three types of apples: A, B, and C. Apple A costs $42 per dozen, and Apple B costs $270 per box of 100 apples. A crate of apples contains A, B, and C in the ratio 1:2:3, with 150 apples of type C. The crate is sold at an average of $35 per dozen, and the profit is 25% of the cost. Find the cost per apple of type C.  
```



**Output (Example):**

**Analysis and Selection**

The original theater seating problem involves key mathematical concepts:
- Establishing two linear equations to represent the total number of seats and the total revenue.
- Using the price and number of seats to establish an equation for the total amount.
- Incorporating additional constraints (such as the second balcony having the most seats).

Among the provided problems, **Problem 8 ("There are three types of coins: 5 cent, 10 cent, 25 cent, with a total amount of $3.20 and a total number of 29 coins, and the number of 10 cent coins is three times the number of 25 cent coins")** has a structure that is highly similar to the theater seating problem. The reasons are as follows:

- **Establishing the system of equations:** The problem provides the total amount of money and the total number of coins, analogous to the total seats and total revenue in the theater problem. This requires establishing corresponding linear equations to solve for the unknowns.
- **Additional constraint:** The condition that the number of 10 cent coins is three times the number of 25 cent coins is analogous to the theater problem's requirement that the second balcony has the most seats. Both are additional constraints used to narrow down the solution set.
- **Integer solutions:** Both problems require the final solution to be an integer, which reflects a similar discrete mathematical problem.

Therefore, **Problem 8** is highly similar to the theater seating problem in terms of the formation of the mathematical model, the application of additional constraints, and the solution method.
