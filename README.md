# Linked Data tutorial proposal for the XML Summer School

## Introduction
This document proposes a Linked Data tutorial in two parts, with each part expected to last 90 minutes.

The first part is designed to provide students with a basic understanding of the concepts, technologies and standards that together are used to build the Web of Linked Data.

The second part would be an opportunity for students to apply the understanding gained in the first part to the real-world scenario of creating themselves a Personal Knowledge Graph using Linked Data and Semantic Web technologies.  

## Who is it suitable for?
Students, practitioners and enthusiasts of computer science, digital humanities, and information sciences who have a basic understanding of web technologies and data formats.

## Part one<a name="part1"></a> - concepts, technologies and standards

This part of the tutorial would provide a basic understanding of the key topics that anyone wishing to work with Linked Data would need to have. This part of the course is a pre-requisite for the [second part](#part2).

### Topics covered:
- **Representing knowledge with graphs and triples**
  - Visualising knowledge with nodes and edges
  - The *Subject* -> *Predicate* -> *Object* construct
- **Identifying things with URIs**
  - Creating cool URIs for stuff
  - URIs vs URLs
- **Representing graphs and triples with RDF**
  - The RDF syntax (mainly Turtle)
  - Using RDFS vocabularies and OWL ontologies
  - Finding and using existing vocabularies vs creating your own
- **Knowledge Graphs**
  - Data vs knowledge
  - Describing real world things and their relationships
  - Implicit vs explicit knowledge
- **The Semantic Web**
  - Standardised knowledge representations
  - The Semantic web technology stack
- **Linked Data / The Web of Data**
  - HTTP + URIs + RDF
  - A web of human readable documents combined with machine readable data
  - Finding stuff on the Web of Data
  - Adding stuff to the Web of Data

## Part two<a name="part2"></a> - case study: building a Personal Knowledge Graph
In order to make the course as interesting and relevant to participants as possible, we will apply the knowledge gained in [part one](#part1) to the example of building a Personal Knowledge Graph (PKG) for ourselves from scratch. PKG's are knowledge graphs with us at the centre, so the first thing we would need to do is create a URI for ourselves. Once we have a URI for ourselves, we can think about what we want to include in our PKG. That could be our family, our holidays, the films we love or some sport that we are fanatical about. We will need to consider whether to create URIs for these things or do whether we can reuse resources that already exist in the Web of Data. Once we have the URIs for the things we want to talk about, we need to figure out how we are connected to them and what vocabularies we might use to create these connections in our graph. Can we re-use existing vocabularies or might we need to create our own?

At the end of this session, students will have the beginnings of a Personal Knowledge Graph which they can take home and continue to build on at their leisure.

We will end the session with a discussion about the possible uses for our knowledge graphs. We might think about embedding them in websites or blogs, using them in journalling or to manage our day-to-day activities. There are no right or wrong answers!
