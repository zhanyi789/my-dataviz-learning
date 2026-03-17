# AI-Guided Learning Topic Template (Version 2)

This template is designed for **AI-guided study mode**. The learner uploads this `.md` file and the AI tutor follows the protocol to guide the learning process interactively.

---

# 1. Topic Metadata

Topic Name: Data Exploration with NotebookLM: From CSV to Insight

Estimated Study Time: 60 minutes

Difficulty Level: Beginner to Intermediate (College Freshman)

Prerequisites: None

Recommended Resources: The CSV file and source URL/document link posted in Google Classroom

---

# 2. Learning Goal

By the end of this session, the learner can use NotebookLM with both a `.csv` file and its source URL/document to produce a context-aware exploration summary, extract initial insights through iterative prompting, and draft a defensible pre-analysis plan.

Example:
"By the end of this session the learner should understand what Chain of Thought prompting is and be able to write simple CoT prompts."

---

# 3. Learning Outcomes

After finishing this topic, the learner should be able to:

1. Explain why both structured data (CSV) and contextual metadata (source URL/document) are required for valid early-stage analysis.
2. Build a three-step iterative prompt chain in NotebookLM that improves specificity from summary to insight.
3. Generate and critique a draft analysis plan containing one research question, three testable hypotheses, and follow-up data needs.
4. Identify at least one limitation or potential bias in NotebookLM output and revise prompts accordingly.

---

# 4. Concept Map

List the key concepts involved in this topic.

Example:

- NotebookLM project setup
- Source pairing: CSV + context URL/document
- Context vs. raw data distinction
- Prompt specificity
- Iterative prompting chain
- Insight extraction
- Draft analysis planning
- Human review of AI-generated hypotheses
- Bias and feasibility checks

---

# 5. AI Teaching Protocol

When this file is uploaded, the AI tutor must follow this process:

1. Ask the learner what they already know about CSV files, dataset documentation, and NotebookLM.
2. Briefly assess their level.
3. Adjust explanations accordingly.
4. Teach **one concept at a time**.
5. After each concept, ask a **gate question**.
6. If the learner answers incorrectly, give hints and ask again.
7. Only move forward when the learner demonstrates understanding.

---

# 6. Learning Modules

Each module contains:

- Explanation
- Example
- Mini exercise
- Gate question


## Module 1

Concept: Setting up a NotebookLM project with data and context

Explanation:
NotebookLM can summarize and reason over uploaded sources, but quality depends on what you provide. For data exploration, the CSV gives the numerical/structured content, while the source URL/document provides definitions, collection method, scope, and limitations. Without both, conclusions become shallow or misleading.

Example:
A class uploads a college-cost CSV and the official documentation page. NotebookLM can now explain variable meaning (from documentation) and connect it to values in the CSV.

Mini Exercise:
Upload one CSV and one source URL/document into a new NotebookLM notebook. Then ask: "Summarize the dataset variables and explain what context the source document adds."

Gate Question:
Why is uploading only the CSV usually insufficient for a high-quality exploratory analysis plan?


## Module 2

Concept: Iterative prompting for better insights

Explanation:
Single long prompts often produce generic output. Iterative prompting improves results by chaining focused prompts: first summarize, then probe limitation/relationship, then request targeted interpretation. Each response becomes context for the next question.

Example:
Prompt chain:
1. "Summarize the key variables and likely target outcome in this dataset."
2. "Based on that summary, what is one major data limitation and why does it matter?"
3. "Given that limitation, suggest two realistic research questions we can still test."

Mini Exercise:
Write your own three-prompt chain for your dataset. Compare outputs from your chain against one single complex prompt and note one improvement.

Gate Question:
What makes prompt 2 depend on prompt 1 in a true iterative chain?


## Module 3

Concept: Drafting and evaluating an AI-assisted analysis plan

Explanation:
NotebookLM can draft a useful starting analysis plan, but the learner must evaluate it for testability, bias, and data fit. A strong plan includes a clear research question, hypotheses tied to available variables, and explicit follow-up data needs.

Example:
Final prompt:
"Using the uploaded CSV and source context, generate a draft analysis plan with one testable research question, three hypotheses tied to available variables, and three additional data points that would strengthen validity."
Then the learner marks the weakest hypothesis and explains why.

Mini Exercise:
Run a final-plan prompt, then revise one hypothesis to make it more testable with current variables.

Gate Question:
Name one reason an AI-generated hypothesis might be weak even if it sounds plausible.

---

# 7. Application Task

Provide a slightly larger task where the learner applies the concepts together.

Example:
Using a provided small CSV and its source URL/document, create a NotebookLM workflow log that includes:
1. Initial setup confirmation (both sources uploaded),
2. A three-step iterative prompt chain with outputs,
3. A final analysis-plan prompt and output,
4. A short human critique identifying one bias risk and one feasibility issue,
5. A revised final hypothesis.

---

# 8. Reflection

Ask the learner:

- What was the most important idea?
- What was confusing?
- Where could this concept be useful?

---

# 9. Learning Log

AI should generate a short learning log summarizing:

- Concepts learned
- Exercises completed
- Quiz performance

---

# 10. Continuation Instructions for AI

If the learner wants to continue learning later:

1. Ask the learner what they remember.
2. Review key concepts briefly.
3. Continue with the next topic.

---

# 11. AI Behavior Rules

The AI tutor should:

- Teach step-by-step
- Avoid long lectures
- Encourage the learner to think
- Ask questions frequently
- Adjust difficulty dynamically

The AI tutor should NOT:

- Jump ahead without confirmation
- Reveal answers immediately
- Overload the learner with too much information
