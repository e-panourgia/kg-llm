# **Assignment 2 – Knowledge Graph Population**

## **Overview**

This assignment involves designing, implementing, and evaluating a relation extraction system based on Large Language Models (LLMs) to populate a knowledge graph. The goal is to classify relations between two entities in a sentence according to a predefined schema.

---

## **Relation Schema**

The knowledge graph defines the following four relation types:

1. **cities_of_residence** – Person ↔ City
2. **employee_of** – Person ↔ Organization
3. **schools_attended** – Person ↔ School
4. **spouse** – Person ↔ Person

---

## **Task 1 – LLM-Based Relation Classifier (50%)**

- **Goal:** Implement a **prompt-based relation classifier** (zero-shot or few-shot) that takes:
  - A sentence
  - Two highlighted entities
  - And returns one of the four relation types, or **"Unknown"** if none apply.
  
- **Evaluation:**
  - Use the provided `relation_extraction_dataset.tsv` to evaluate **precision** and **recall** per relation.
  - Perform **error analysis** to identify systematic patterns.

- **Requirements:**
  - No fine-tuning allowed – only use prompt engineering.
  - Design and experiment with multiple prompt variations.
  - Document and justify your prompt development process.

---

## **Task 2 – Special Phenomena Evaluation (50%)**

- **Context:** Evaluate how the classifier handles:
  1. **Uncertainty** (e.g., "It is possible that John is an employee of Apple.")
  2. **Advice/Wish** (e.g., "It would be nice if John married Jane.")

- **Steps:**
  - Create an **additional evaluation dataset** of 10–15 examples per phenomenon per relation (approx. 80–120 sentences).
  - Evaluate the classifier’s **precision** and **recall** on this dataset.
  - Report results and discuss observations.

---

## **Deliverables**

1. **LLM-based classifier implementation** (e.g., Google Colab or similar), with clear instructions.
2. **Generated dataset** for Task 2 (same format as Task 1).
3. **Final report** including:
   - Classifier development and prompt strategy.
   - Evaluation results on Task 1 and Task 2 datasets.
   - Error analysis and discussion.
