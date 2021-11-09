# Knowledge Graph for Open Government Data - Case of ESGREEN
🌲 A RDF knowledge graph for green spaces infrastructure (trees, parkland, green areas) data of a city that are relevant for [Open City Project](https://github.com/CiudadesAbiertas). 

> To make **BIODIVERSITY** data Interoperable (the <b>I</b> in FAIR).

## Research questions
* 1. **city center** most abundant organisms.
* 2. **outside** city center.
* 3. **areas** with least and most diverse species  diversity (Shannon Index).

---

## Inputs
A total of 18 datasets originally from [Madrid Green Data Space](https://mgds.oeg.fi.upm.es/datasets.html) are used to generate the Ontology. These datasets consist of measures (e.g., number of trees) and dimensions describing the measures (e.g., regions)

- [Raw Datasets](data/inputs)
- [Clean Dataset](data/preprocessing)

## Data Model
Concepts and properties are annotated with the [Semanticscience  Integrated Ontology](https://bioportal.bioontology.org/ontologies/SIO/).

The figure below gives an overview of upper level concepts and properties used in our data model.

<p align="center"> 
	<img src="images/diagram-complex2.png"> 
</p> 

You can browse different **ESGREEN modules** by visiting the links below:

* [Arbolado Parques Historico y Singulares](notebooks/1-ArboladoParquesHistoricosSingularesForestales.md)
* [Arbolado Zonas Verdes Distritos Calles](notebooks/2-ArboladoZonasVerdesDistritosCalles.md)
* [Estado Parques Historico y Singulares](notebooks/3-EstadoParquesHistoricoSingularesForestales.md)
* [Estado Zonas Verdes Distritos Calles](notebooks/4-EstadoZonasVerdesDistritosCalles)
* [Masas Parques Historico Singulares Forestales](notebooks/5-MasasParquesHistoricoSingularesForestales.md)
* [Masas Zonas Verdes Distritos Calles](notebooks/6-MasasZonasVerdesDistritosCalles.md)




---
## License

**Copyright (C) 2021**

MIT License 

---
