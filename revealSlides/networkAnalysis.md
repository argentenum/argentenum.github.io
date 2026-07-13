# Digital Humanities Data Basics
## Networks, Metadata, Linked Data, and Wikidata

---

## What is a network graph?

A network graph is a way of representing relationships between things.

- **Nodes** are the things.
- **Edges** are the relationships between them.
- It is useful for showing connections, clusters, and pathways.

---

## Nodes and edges

- A **node** can be a person, place, book, museum, or concept.
- An **edge** is a link between nodes.
- Edges can be directed or undirected.

Example:
- Artist → created → Painting
- Museum → holds → Object

---

## Sizing nodes and edges

You can change visual emphasis by adjusting size.

- Larger nodes can show higher importance, more connections, or a bigger count.
- Thicker edges can show stronger relationships, more frequent links, or higher weight.

This is often used in network visualization tools to help patterns stand out.

---

## Colouring nodes and edges

Colour helps group and compare data.

- Nodes can be coloured by category, type, or cluster.
- Edges can be coloured by relationship type.
- Colour makes dense graphs easier to read.

Example:
- Blue = places
- Green = people
- Red = organizations

---

## Classical metadata

Classical metadata is descriptive information about an item.

Examples:
- Title
- Creator
- Date
- Publisher
- Location
- Subject

It helps people find, identify, and manage resources.

---

## Dublin Core

Dublin Core is a widely used metadata standard.

Common elements include:
- Title
- Creator
- Subject
- Description
- Date
- Format
- Identifier
- Source

It is simple, flexible, and widely used for digital collections.

---

## From metadata to data graph

Metadata can be expressed as structured data.

- Instead of a flat record, each fact becomes a link.
- This makes it easier to connect datasets.
- It also helps machines understand meaning and context.

---

## Triples

Linked data is built on **triples**:

- **Subject**
- **Predicate**
- **Object**

Example:
- `Johannes Vermeer` → `creator of` → `The Milkmaid`

This is the basic structure of RDF data.

---

## Linked Data

Linked Data means publishing structured data on the web using identifiers and links.

Core ideas:
- Use URIs for things.
- Use RDF to describe them.
- Link to other datasets.
- Make data reusable.

---

## Linked Open Data

Linked Open Data is Linked Data that is also open for reuse.

- Open licences
- Shared identifiers
- Connects datasets across institutions
- Supports discovery and integration

It is important in digital humanities and cultural heritage.

---

## Wikidata

Wikidata is a collaborative knowledge base of structured data.

It stores:
- Items
- Properties
- Statements
- References

Examples:
- People
- Museums
- Books
- Works of art
- Places

---

## Ontology

An ontology is a formal way of describing concepts and relationships in a domain.

It defines:
- Classes
- Properties
- Constraints
- Relationships

Example:
- Museum is a type of institution
- Painting is a type of artwork

---

## Knowledge graph

A knowledge graph is a network of entities and relationships.

It combines:
- Data
- Meaning
- Links
- Structure

Wikidata is often described as a knowledge graph because it connects many entities through semantic relationships.

---

## Semantic Web

The Semantic Web is a web of meaning, not just documents.

Its goal is to make data:
- understandable by machines
- linked across sites
- reusable across systems

It uses standards like RDF, OWL, and SPARQL.

---

## Summary

- Networks show relationships visually.
- Metadata describes resources.
- Linked Data connects metadata on the web.
- Wikidata is a large linked knowledge graph.
- Ontologies and the Semantic Web provide shared meaning.
