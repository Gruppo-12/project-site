---
layout: default
---

# FINAL STEP

## Discussion

We faced many challenges related to the ArCo knowledge Graph and the LLMs. However, the most representative examples are:
* The knowledge graph is still lacking some important information, making the research more difficult. E.g.: lack of IRI for San Giovanni Battista as agent and lack of property to express the relationship between the church and the saint to whom it is dedicated.
  * Solution: we imported from DBpedia the IRI of San Giovanni Battista. Then, we used a SPARQL CONSTRUCT query to create a new property to link the two entities and as a consequence we obtained a new triple.

* The LLMs’ answers were not satisfactory since they did not provide us with accurate information. E.g.: they invented the IRIs instead of giving the actual ones.
  * Solution: we replaced the wrong IRIs with the correct ones and then created the new triple.

## Summarizing what we did

* Previous analysis of the entities thanks to SPARQL queries
* Browsing the main ArCo ontologies to find classes and properties
* Creation of new triples with SPARQL CONSTRUCT and LLMs to fill in knowledge gaps
* Using LLMs to retrieve useful information
* Enrichment of existing data


[Report](./report.md)

[Home](./)
