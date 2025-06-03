# **Assignment 3 – Applying Knowledge Graphs**

## **Overview**

This assignment focuses on evaluating and improving a Large Language Model (LLM)-based **Question Answering (QA)** system that translates natural language questions into **Cypher queries** for querying a Neo4j movie knowledge graph.

---

## **Task 1 – Evaluation of Cypher Generation (50%)**

- **Objective:** Create an evaluation dataset of **20–30 diverse natural language questions** answerable by the Neo4j movie graph.
- **Steps:**
  - Feed these questions into the existing **Text2Cypher pipeline**.
  - Evaluate the correctness of the generated **Cypher queries**.
  - Analyze the **types of errors** made by the LLM (e.g., incorrect entities, structure, or logic).

---

## **Task 2 – Improving Prompt Quality (50%)**

- **Objective:** Improve Cypher generation by enhancing prompt design.
- **Approach:**
  - Experiment with better **zero-shot prompts**.
  - Incorporate **few-shot learning** with carefully selected **question-query examples**.
- **Deliverables:**
  - Revised prompts and examples.
  - Evaluation showing performance improvement over Task 1.

---

## **Task 3 – Dynamic Few-Shot Prompting (Optional, +50%)**
- Note: this task did not be implemented (TODO future work.)
- **Objective:** Implement **dynamic few-shot prompting** to further enhance Cypher generation accuracy.
- **Method:**
  - Use a **vector index** to retrieve **semantically similar questions** from a stored set.
  - Dynamically insert only the most relevant question-query pairs into the prompt.
- **Goal:** Improve relevance and reduce prompt length, enhancing generation quality and efficiency.

---

## **Deliverables**

1. **Implementation** of Tasks 1, 2 (and optionally 3), in a Colab notebook or similar format with clear usage instructions.
2. A **report** documenting:
   - The evaluation process and results from each task.
   - The prompt strategies used and improved.
   - A detailed **error analysis** and justification of changes made.
