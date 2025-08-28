# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
We designed an experiment where two categories of prompts were tested:
Broad / Unstructured Prompts – Vague, open-ended queries.
 Example: “Tell me about World War II.”
Refined / Structured Prompts – Clear, concise, directive queries.
 Example: “Explain the key causes of World War II in 5 bullet points, focusing on political and economic factors.”
Each prompt type was tested across scenarios:
  General Knowledge
  Creative Writing
  Problem Solving (Coding)
  Instruction Following
  Analytical Reasoning


## Algorithm:
Select a set of prompts for each scenario.

Run prompts through the AI model in two variations:

Broad / Unstructured

Refined / Structured

Collect responses from the model.

Evaluate outputs using three metrics:

Quality → relevance, usefulness, fluency.

Accuracy → correctness of facts, consistency with input.

Depth → level of detail and explanation.

Compare and record observations.

Summarize insights.

Test Scenarios & Results
1. General Knowledge

Broad Prompt: “Tell me about World War II.”
Refined Prompt: “Explain the key causes of World War II in 5 bullet points, focusing on political and economic factors.”

Observation:

Broad → Long but unfocused, lacked clear structure.
Refined → Precise, concise, focused on causes.

2. Creative Writing

Broad Prompt: “Write a story about space.”
Refined Prompt: “Write a 200-word story about an astronaut who discovers life on Mars, focusing on suspense with a surprise ending.”

Observation:

Broad → Generic, lacked direction.
Refined → Creative, engaging, followed instructions.

3. Problem Solving (Coding)

Broad Prompt: “Write Python code for sorting.”
Refined Prompt: “Write a Python function to sort a list of integers in ascending order using the bubble sort algorithm.”

Observation:

Broad → Produced generic code, often used built-in sort.
Refined → Correct bubble sort implementation as requested.

4. Instruction Following

Broad Prompt: “How to make a cake?”
Refined Prompt: “List 6 steps to bake a simple vanilla cake at home with ingredients included.”

Observation:

Broad → Narrative-style, less structured.
Refined → Clear step-by-step instructions, actionable.

5. Analytical Reasoning

Broad Prompt: “Tell me about electric cars.”
Refined Prompt: “Compare electric cars and petrol cars in terms of cost, efficiency, and environmental impact in a tabular format.”

Observation:

Broad → Descriptive but scattered.
Refined → Tabular, structured, and comparative.

## Output
[Experiment_2_Prompt_Engineering.pdf](https://github.com/user-attachments/files/22018713/Experiment_2_Prompt_Engineering.pdf)


## Result
Broad prompts are useful for open-ended exploration but often lack precision.
Refined prompts consistently improve quality, accuracy, and depth across tasks.
This experiment demonstrates that prompt engineering is essential for optimizing AI performance.

Future Work:
Extend analysis with chain-of-thought prompting and few-shot examples.
Compare results across different LLMs (e.g., GPT, Claude, Gemini).
Introduce quantitative scoring metrics for objectivity.
