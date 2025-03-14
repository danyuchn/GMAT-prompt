# Explanation Prompt for High School-Level Understanding

## Instruction
Please explain the problem-solving steps and answer in a tone that a high school student can understand.

**Note:** If the question involves a graph, please upload an image. If it involves a table, you can paste the text directly, and the GPT model will automatically clean the data.    

**Note:** For background descriptions or question statements that are not in chart or graph format, please provide the input in plain text whenever possible.  

## Function
Break down the solution steps for various GMAT problem types in simple language and provide detailed answer explanations.

**Note:** Since LLMs are currently less sensitive to image recognition compared to pure text, the generated answers may contain errors. Educators and learners should focus on the problem-solving process rather than the final answer and try to tell LLMs 

```
no, the correct answer is ___. Please correct your thoughts.
``` 
whenever it produces response directing to wrong answer.

## Suitable For
- GMAT test-takers with a weak foundation.
- Students unfamiliar with problem-solving steps or logic.
- Candidates who need to learn the solution methods from scratch.
- Applicable to all GMAT problem types, especially beneficial for those at a lower proficiency level.

## Example 1
**Input:**  
![ ](images/graph_1.png)

```At the end of last semester, all 33 students (11 from each of 3 sections) of a particular course were asked how many hours per week they spent studying for the course. This data was combined with the number of points earned by each student in the course. This information is presented in the graph.

Grades in the course were calculated using a 20-point scale. To compute the grade, the number of points earned in the course was divided by 50 and then rounded up to the next whole number.

Use the drop-down menus to complete each statement so that it is consistent with the information provided.

The median reported time spent studying for all students in the course was________ hours per week.

Choices: 2 / 2.5 / 3 / 3.5
Section________ had the smallest average (arithmetic mean) reported time spent studying per week.
Choices: A / B / C```

---
Please explain the problem-solving steps and answer in a tone that a high school student can understand.
```

**Output:**  

**Understand the Median**  
The median is the middle number when all data points are listed in ascending order.   

Because there are 33 total students, the median is the 17th data point when sorted from least to greatest.

**Approximate Data from the Graph**
From the scatter plot, most students appear to report around 1–5 hours per week, with a few reporting up to 9 or 10 hours.  

When we list all 33 study times in ascending order, the 17th data point lands around 3 hours per week.

**Confirm the Median**
By counting how many points are at or below each hour mark (0, 1, 2, 3, etc.), you see that about half the students are below or at 3 hours, making 3 the median.

**Find Which Section Has the Lowest Average**
Each section has 11 students. We can approximate each section’s total study hours by adding up its data points from the graph and then dividing by 11.  
Section A’s data points are generally more to the left (fewer hours) compared with Sections B and C, so Section A has the smallest average study time."

**Note:** The answer provided here is incorrect.  

**Input:** But the correct answer of the second blank should be C. Please correct your thoughts.

**Output(Corrected):**

**1. Find the Median**  
- There are 33 students total. To find the median, arrange their study times in order from smallest to largest.  
- The median is the 17th value in that ordered list (since there are 16 values before it and 16 values after it).  
- From the distribution on the graph, the middle value lands around **3 hours** per week.

**2. Identify Which Section Has the Lowest Average**  
- Each of the three sections (A, B, and C) has 11 students.  
- To figure out which section has the smallest mean study time, we look at each section’s data points (the circles, squares, or black dots), sum their reported hours, and divide by 11.  
- Although the data might look close at first glance, the official solution indicates that **Section C** actually has the smallest average study time per week. This can happen if, despite a few high-hour outliers, most of Section C’s points cluster at the lower end.

**3. Conclusion**  
- **Median Study Time**: 3 hours/week  
- **Section with the Smallest Average**: C

## Example 2
**Input:**  

```A company that designs websites primarily for minority-owned businesses conducted a survey of minority-owned businesses in the United States that do not currently have a website. The survey was designed to help determine what respondents see as the potential benefits of adding a website. The results of that survey are shown in the table.

Potential benefit	Latino (459
respondents)	African American
(394 respondents)	Asian American
(438 respondents)	Native American
(279 respondents)
Expand customer base	26%	29%	25%	25%
Improve communication	15%	4%	4%	6%
Increase customer satisfaction	5%	17%	28%	6%
Increase ratio of profits to costs	14%	19%	17%	19%
Increase tax savings	0%	1%	0%	0%
Preserve market share	6%	6%	4%	6%
Save time	4%	3%	13%	2%
Other	3%	3%	5%	4%
No benefit	27%	17%	22%	21%
Uncertain	10%	11%	13%	10%

For each of the following conclusions, select Supported if it is supported by the information in the table. Otherwise select Not supported.­

Supported	Not supported	
		A majority of the respondents believe adding a website could benefit their businesses.
		Fewer than 25% of the respondents who believe a website could help expand their customer base also believe a website could help them maintain their current market share.
		Only a small proportion of the respondents are concerned that they are losing market share."

----

Please explain the problem-solving steps and answer in a tone that a high school student can understand.
```


**Output:**  

**Look at Each Group’s “No Benefit” and “Uncertain” Responses**  
These two categories combined tell us how many people don’t see a clear benefit.

- **For Latino**: 27% (No benefit) + 10% (Uncertain) = **37%** → **63%** do see a benefit.  
- **For African American**: 17% + 11% = **28%** → **72%** do see a benefit.  
- **For Asian American**: 22% + 13% = **35%** → **65%** do see a benefit.  
- **For Native American**: 21% + 10% = **31%** → **69%** do see a benefit.  

Since in all groups **more than 50% see some benefit**, a **majority of all respondents** believe adding a website could benefit their businesses.

---

**Check: “Fewer than 25% of the respondents who believe a website could help expand their customer base also believe a website could help them maintain their current market share.”**  
The table shows how many in total see **"Expand customer base"** and how many in total see **"Preserve market share,"** but it does not show how many people **chose both categories**.

- Because we don’t have that **overlap**, we **can’t say for sure** if **fewer than 25%** of those who chose "expand customer base" also chose "preserve market share."
- **Therefore, this conclusion is not supported** by the data provided.

---

**Check: “Only a small proportion of the respondents are concerned that they are losing market share.”**  
- **“Preserve market share” responses:**  
  - Latino: **6%**  
  - African American: **6%**  
  - Asian American: **4%**  
  - Native American: **6%**  

These percentages are all **fairly small**, so **only a small proportion** of respondents see maintaining market share as a benefit.  
✅ **Hence, this conclusion is supported by the data.**

---

**Answers**
| Statement | Conclusion |
|-----------|------------|
| **A majority of the respondents believe adding a website could benefit their businesses.** | ✅ **Supported** |
| **Fewer than 25% of the respondents who believe a website could help expand their customer base also believe a website could help them maintain their current market share.** | ❌ **Not supported** (because we don’t have enough overlap data) |
| **Only a small proportion of the respondents are concerned that they are losing market share.** | ✅ **Supported** |

**Note:** The answer provided here is incorrect.

**Input:** No. Here the answer should be supported/supported/not supported. Please correct your thoughts.

**Output(Corrected):**

 **1. A majority of the respondents believe adding a website could benefit their businesses.**
- **What the Table Shows:**  
  For each ethnic group, add the percentages for all benefit categories (all rows except "No benefit" and "Uncertain").  
- **Example (Latino group):**  
  "No benefit" = 27% and "Uncertain" = 10%, which total 37%.  
  This means 63% (i.e., 100% - 37%) of Latino respondents see some benefit.  
- **Observation:**  
  Since each group has well over 50% of respondents perceiving benefits, a majority of the respondents overall see a benefit.
- **Conclusion:**  
  **Supported**

**2. Fewer than 25% of the respondents who believe a website could help expand their customer base also believe a website could help them maintain their current market share.**
- **Data Comparison:**  
  - “Expand customer base” percentages: 26% (Latino), 29% (African American), 25% (Asian American), 25% (Native American).  
  - “Preserve market share” percentages: 6% (Latino), 6% (African American), 4% (Asian American), 6% (Native American).
- **Calculation:**  
  If we assume that respondents who chose “preserve market share” are among those who chose “expand customer base”, then we compare the two percentages:  
  - For Latino: 6/26 ≈ 23%  
  - For African American: 6/29 ≈ 21%  
  - For Asian American: 4/25 = 16%  
  - For Native American: 6/25 = 24%
- **Observation:**  
  In every case, the percentage is below 25%.
- **Conclusion:**  
  **Supported**

**3. Only a small proportion of the respondents are concerned that they are losing market share.**
- **Interpreting the Statement:** 
  This statement implies that very few respondents are worried about losing market share.
- **What the Table Actually Measures:**  
  The table shows the percentage of respondents who believe adding a website would help “preserve market share” (4%–6%).  
- **Critical Note:**  
  A low percentage in this benefit category might mean that few respondents think a website will help preserve market share—but it does not necessarily indicate their level of concern about losing market share.  
  They might be very concerned but not see a website as a solution, or they might simply not view website creation as relevant to that issue.
- **Conclusion:**  
  Because the table does not directly measure “concern” about losing market share, **this statement is not supported** by the information provided.
