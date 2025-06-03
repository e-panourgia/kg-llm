# **Assignment 4 – KG with LLM**

## **Quality of DBpedia Ontology**

This project is developed as part of the course **Knowledge Graphs with Large Language Models (KG with LLM)**. The assignment focuses on evaluating the **schema quality** of DBpedia through ambiguity detection and alignment with ESCO skills.

---

## **Overview**

The assignment is divided into two main tasks:

### **Task 1: Ambiguity Detection in DBpedia Schema (50%)**
- Develop a **term ambiguity detector** for class and property names in DBpedia.
- Use both:
  - **Dictionary-based approaches** (e.g., WordNet, Wiktionary)
  - **LLM-based approaches**
- Analyze and compare both methods in terms of **effectiveness** and **efficiency**.

### **Task 2: Modeling Abstract Skills Using ESCO (50%)**
- Map **ESCO skill entities** to DBpedia.
- Use LLMs to **evaluate the correctness** of class-entity mappings.
- Analyze where DBpedia fails or succeeds in modeling abstract concepts.

---

## **Project Structure**

```
📦 Project Root  
├── assignment_4_kg_llm.ipynb             # Main notebook with both tasks integrated  
├── task1/                                # Folder for Task 1 work  
│   ├── few_shot/                         # Few-shot examples for single-word terms  
│   ├── few_shot_more_words/              # Few-shot examples for multi-word phrases  
│   ├── sample/                           # Dictionary/LLM results for single-word terms  
│   └── sample_more_words/                # Dictionary/LLM results for multi-word terms  
├── task2/ endpoint/                      # Folder for Task 2 outputs  
│   └── FINAL_DF.csv                      # Mapping results between ESCO and DBpedia  
│                                         # Columns include:  
│                                         # `preferred_label_esco`, `potential_entity_variants_dbpedia`,  
│                                         # `class_label_dbpedia`, `entity_valid_variants_dbpedia`,  
│                                         # `llm_formatted_entity`, `llm_expanded_class_label`  
└── README.md                             # Project documentation  
```

> **Note:** The file `esco_skills_en.csv` is not included due to size constraints. Please load it locally when executing Task 2.

---

## **Instructions**

1. Open `assignment_4_kg_llm.ipynb` in Colab or Jupyter.
2. Follow instructions in each task cell to install dependencies and execute workflows.
3. Explore `task1/` and `task2/endpoint/` folders for sample inputs and generated results.
4. Review `FINAL_DF.csv` for ESCO–DBpedia alignment and LLM evaluation output.

---

## **Enjoy!** 😊  
