# Original File: 01-basic-explanation.md

## Explanation Prompt for High-School-Level Understanding

### Instruction
Please explain the problem-solving steps and answer in a tone that a high school student can understand.
---
# Original File: 02-quick-cr-tpa-tricks.md

## AI Instruction: Provide a Quick Solving Shortcut Within N Minutes (for CR & TPA non-math related)

### Instruction
Please provide a shortcut method that enables a human to solve a problem quickly within N minutes. The principle is as follows:  
1. First, read the question and identify the key elements that unlock the problem.  
2. Next, tell me which parts of the passage are relevant information and which are not.  
3. Then, indicate whether to use a pre-writing (pre-answer drafting) strategy or an elimination strategy to answer the question.  
Each step must include a clear cue that leads to the next step and follow a linear, unidirectional human thought process.

**Note:** "N minutes" is variable depending on the problem type (e.g., CR: 2 minutes, TPA: 2.5-3 minutes).
---
# Original File: 03-quick-rc-tricks.md

## AI Instruction: Provide a Detailed Quick Solving Shortcut Within N Minutes

### Instruction
Please provide a shortcut method that enables a human to solve a problem quickly within N minutes. The method should follow these steps:  
1. First, identify the key information in the passage that needs attention (note: this should be done even when it is unclear what the question may test).  
2. Next, specify the keywords and main points for each question.  
3. Then, based on these keywords and points, indicate which related paragraphs in the passage are pertinent.  
4. After that, advise whether to use a pre-writing strategy or an elimination strategy to answer the question.  
5. If pre-writing is chosen, please detail the reasoning process step-by-step.  
Each step must provide a clear clue that leads to the next step and must follow a linear, unidirectional thought process. Also, provide a detailed explanation for the judgment on each option.

**Note:** "N minutes" is variable depending on the number of questions you give. 2 minutes per question is personally suggested.
---
# Original File: 04-mindmap-passage.md

## AI Instruction: Create a Mind Map of the Article

### Instruction
Please create a mind map of the passage itself.
---
# Original File: 05-evaluate-explanation.md

## AI Instruction: Evaluate My Verbal Problem-Solving Process

### Instruction
Here is my verbal explanation of the problem-solving process. Please identify any errors in my approach and suggest improvements.
---
# Original File: 06-boldface-SOP.md

## AI Instruction: Evaluate My Verbal Problem-Solving Process

### Instruction
**Note:** Mark the bolded parts with markdown code "**" (as shown in example)

You are an AI assistant specialized in solving logical reasoning problems (e.g., Bull Face or similar question types). Analyze and answer the user's provided question or problem step-by-step using the five principles below. Your goal is to apply a cyclical, iterative approach, focusing on one core difference at a time and making a single inference per cycle to eliminate options until only one remains. Ensure your response is clear, logical, and aligns with human sequential thinking. Specifically, when an option connects to non-bolded text in the passage, explicitly analyze its relationship to the option's core in a single step. If more information is needed, ask the user for clarification rather than assuming or skipping steps. Below are the five principles and their execution instructions:

**Principles**

Principle 1: First Look at Options, Then the Text  
Instruction: Begin by focusing solely on the user-provided options (if available), listing and understanding each one without reading the passage initially.  
If no options are provided, ask the user to supply them or relevant details.  
State that your first step skips the passage to avoid unnecessary information interference.

Principle 2: Difference First, Reference Next  
Instruction: In each cycle, identify one clear core difference (e.g., meaning, logical direction, subjective/objective) among the remaining options. List this difference and use it to determine what specific information to seek in the passage.  
Reference the passage only for this difference, citing relevant sentences or segments to support your analysis.  
If the option connects to non-bolded text, analyze its relationship to the option's core in one step, explaining consistency or contradiction.  
After resolving the difference, return to this step for the remaining options.

Principle 3: Core First, Modifier Next  
Instruction: In each cycle, focus on the core content of the options (main claim or keyword), ignoring modifiers (details or qualifiers).  
Clearly state the core of the options being analyzed and compare them based on this alone.  
Only consider modifiers if the core analysis is insufficient, explaining their impact in a single inference.

Principle 4: Tone First, Attitude Next  
Instruction: For the current core difference in each cycle, first determine the tone—subjective (opinion, speculation) or objective (fact, data)—and justify your reasoning.  
After establishing tone, analyze attitude (support, opposition, neutral) if needed, citing specific evidence in one step.  
If tone or attitude is unclear, note this and prioritize other clearer differences.

Principle 5: The Clearest First, The Blur Last  
Instruction: In each cycle, prioritize the most obvious difference between options for analysis, using it to eliminate incompatible options quickly.  
Mark vague or hard-to-judge differences (e.g., two subjective options with similar meanings) as deferred and skip them initially.  
After resolving clear differences, revisit vague ones if necessary, referencing the passage for clarification.

**Execution Steps** (Single-Inference Cycle)  

Step 1: List all options, stating you'll analyze them before the passage.  
Step 2 (Cycle Start): Identify one clear core difference among remaining options and begin a single inference.  
Step 3: Focus on the core of this difference, ignoring modifiers, and compare.  
Step 4: Judge the tone (subjective/objective) of the difference; if needed, assess attitude. If non-bolded text is involved, analyze its relation to the core in one step, eliminating at least one option.  
Step 5: Return to Step 2, repeating the cycle with remaining options until one remains.  
Step 6: Summarize the final answer and review the process.

**Output Format** 

Options Overview: List all initial options with brief descriptions.  

Cycle 1: State the first core difference, tone/attitude judgment, passage reference (including non-bold text analysis if applicable), and eliminated option(s).  
Cycle 2 (if needed): Repeat for remaining options.  
Cycle N (if needed): Continue until one option remains.  
Conclusion: Provide the final answer and summarize the single-inference process.

**Notes:** 
Limit each cycle to one core difference and one inference to avoid confusion.  
When non-bolded text is referenced, explain its relation to the option's core step-by-step.  
If the user provides an incomplete question or no options, ask for clarification.  
Avoid guessing based on keywords or shortcuts; rely on logical reasoning.
---
# Original File: 07-logical-term-explained.md

## AI Instruction: Explain Logical Terms in Answer Choices

### Instruction
Explain the meaning of each logical term in the five answer choices provided in the passage.
---
# Original File: 08-source-passage-rewrite.md

## AI Instruction Template: Rewrite Academic Passage into GMAT-Style Article

### Instruction
Rewrite the provided academic passage into a 250–400 word GMAT-style article suitable for educated non-specialist readers (e.g., science-interested high school or university students). Apply the following simplification strategies:

1. **Lexical (word-level) simplification**:
   - Replace academic or technical terms with common equivalents where possible.
   - Remove or generalize overly specific numerical or temporal references.
   - Avoid jargon unless essential and explained.
2. **Syntactic (sentence-level) simplification**:
   - Break down long or embedded sentences into short, clear statements.
   - Convert passive voice to active voice where it improves clarity.
   - Remove non-essential modifiers and subordinate clauses.
3. **Structural (discourse-level) simplification**:
   - Restructure the flow into a clear, linear narrative.
   - Merge or compress paragraphs with similar topics.
   - Remove complex theoretical framing or scholarly conclusions unless rewritten plainly.

Ensure the article:
- Retains the key hypothesis, findings, and implications of the original text.
- Is logically coherent, informative, and engaging.
- Maintains a length of 250–400 words.
- Uses clear transitions and accessible language for general science communication.
- Avoids direct quotations or citations from the original.
---
# Original File: 09-complex-sentence-rewrite.md

## AI Instruction Template: Rewrite Article into Abstract, Complex Style

### Instruction
Preserve the exact core meaning of the input article, ensuring no arbitrary addition or deletion of ideas, implications, or details. The rewritten version must convey the same points in a dense, challenging manner.

Assume the reader lacks specialized background knowledge, intentionally raising the comprehension barrier through abstract logic and tone.

Keep the rewritten article's length within 1.5 times the original word count (e.g., a 100-word article should not exceed 150 words).

Include at least 2-3 sentences per paragraph that embody these characteristics for a noticeable effect.

Do not expand or simplify the original content; rephrase it densely without inventing new information.

Provide two outputs:

The rewritten English article, reflecting the specified style.

A simple, easy-to-understand version of the rewritten article, using clear, everyday language to ensure accessibility.

Briefly explain how the rewrite uses abstract logical vocabulary, complex sentence structures, and detached tone, while confirming no meaning was added or removed and the length constraint was met.

Please rewrite the following input article based on these requirements: 
`Input your passage`
--- 