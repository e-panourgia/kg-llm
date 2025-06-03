# **Assignment 1 – Knowledge Graph Schema Design**

## **Overview**

This assignment involves extending a small movie knowledge graph to support answering three specific competency questions. It consists of two main tasks: working with a Neo4j version and an RDF(S)/OWL version of the graph.

---

## **Competency Questions**

1. Which movies have been produced in the United States?
2. Which movies are comedies and which are romantic comedies?
3. What rating did a reviewer give to a given movie and what was their review text?

---

## **Task 1 – Neo4j Knowledge Graph (50%)**

- Use the provided `movies_graph_neo4j.dump` file and load it into **Neo4j AuraDB**.
- Expand the schema to enable answering all three competency questions.
- Test your design by expressing the questions in **Cypher** queries.
- Provide a clear explanation of your **modeling decisions**.

---

## **Task 2 – RDF(S)/OWL Knowledge Graph (50%)**

- Use the provided `movies_graph_rdf_owl.owl` file in **Protégé** or another RDF/OWL tool.
- Extend the ontology to allow answering the same competency questions.
- Write **SPARQL** queries to verify that the graph supports the required queries.
- Document your **modeling process** and decisions.

---

## **Guidelines**

- Address the competency questions **together**, not in isolation.
- Use an LLM to assist where appropriate, and document:
  - The **prompts** you used.
  - Any **adaptations** or **corrections** made to the LLM output.
- Ensure the schema is **semantically correct** and **readable**.
- Provide your modeling rationale, especially when different approaches are possible.

---

## **Deliverables**

- A Neo4j **dump file** of the expanded knowledge graph.
- An updated **RDF/OWL ontology** file.
- A written **report** including:
  - Your modeling strategy and decisions.
  - The LLM prompts used and how you evaluated them.
  - The Cypher and SPARQL queries for verification.
