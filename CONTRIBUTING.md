Thanks for contributing to the **UAP's ontology project** !
Here are a few instructions and tips.

# Abstract

The purpose of the project is to define an ontology which describes UAP's
sightings. By formalising the concepts involved in those sightings, we are
pursuing two goals : 

1. develop and accurate the [data recording model
   (DRM)](https://uap-initiative.github.io/drm/), particular the table structure
   that will be used by our application;
2. provide a framework for publishing data as queryable Web linked data.

The job consists of 

- building an OWL ontology using Protégé^[Musen, M.A. The Protégé project:
  A look back and a look forward. AI Matters. Association of Computing Machinery
  Specific Interest Group in Artificial Intelligence, 1(4), June 2015. DOI:
  10.1145/2557001.25757003.] ;
- writing the related documentation using LODE^[Peroni, S., Shotton, D., Vitali,
  F. (2012). The Live OWL Documentation Environment: a tool for the automatic
  generation of ontology documentation. To appear in Proceedings of the 18th
  International Conference on Knowledge Engineering and Knowledge Management
  (EKAW 2012). Available at
  http://speroni.web.cs.unibo.it/publications/peroni-2012-live-documentation-environment.pdf]
  ^[Peroni, S., Shotton, D., Vitali, F. (2013). Tools for the automatic
  generation of ontology documentation: a task-based evaluation. To appear in
  International Journal on Semantic Web and Information Systems, 9 (1).
  Available at
  http://speroni.web.cs.unibo.it/publications/peroni-2013-tools-automatic-generation.pdf].

# Code of conduct

A [Code of conduct](CODE_OF_CONDUCT.md) regulates exchanges between
contributors.

# Specifications

## OWL and Protégé

### OWL

> *The W3C Web Ontology Language (OWL) is a Semantic Web language designed to
> represent rich and complex knowledge about things, groups of things, and
> relations between things. OWL is a computational logic-based language such
> that knowledge expressed in OWL can be exploited by computer programs, e.g.,
> to verify the consistency of that knowledge or to make implicit knowledge
> explicit.  OWL documents, known as ontologies, can be published in the World
> Wide Web and may refer to or be referred from other OWL ontologies. OWL is
> part of the W3C’s Semantic Web technology stack, which includes RDF, RDFS,
> SPARQL, etc.*
[OWL](https://www.w3.org/OWL/)

### Protégé

> *Protégé is a free, open-source platform that provides a growing user community
> with a suite of tools to construct domain models and knowledge-based
> applications with ontologies.*
[Protégé](https://protege.stanford.edu/)

### Usefull guides

We recommend those guides :

- [A Practical Guide To Building OWL Ontologies Using Protégé 4 and
CO-ODE Tools, Edition
1.3](http://mowl-power.cs.man.ac.uk/protegeowltutorial/resources/ProtegeOWLTutorialP4_v1_3.pdf)
- [Ontology Development 101: A Guide to Creating Your First
  Ontology](https://protege.stanford.edu/publications/ontology_development/ontology101.pdf)

## Writing tips

- Please use a **simple English** either for the ontology objects naming or the
  related documentation or metadata ;
- Please use the **CamelBack** notation (i.e. write CamelBack instead of
  Camel\_Back or Camel-Back) ;
- Structure your code ;
- Indent with four spaces instead of tabs ;
- Limit the line width up to 80 characters ;
- Comment your code when it's necessary for others, but don't forget Git commits
  and GitHub pull requests are intended to document your work !

## Files formats

- `*.md` files for markdown text (documentation pages) ;
- `*.owl` files for the ontology.

## Files encoding

Please encode files and characters in **UTF-8**.

## Workflow

- **Fork** the repository ;
- Clone the forked repository on your computer ;
- Create some local branch from `editing` which is the working/dev branch ;
- Work, commit then merge your local branches into `editing` ;
- Push your work and make **pull requests** to merge it into the `uapOntology`
  repository `editing` remote branch.
- When a public release is ready, the remote `editing` branch is merged into
  `master`, updating the project website.

Here are some usefull [GitHub guides](https://guides.github.com/). Please
consider these particularly :

- [Git handbook](https://guides.github.com/introduction/git-handbook/)
- [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
  ;
- [Forking Projects](https://guides.github.com/activities/forking/) ;
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) .

# See also

See also the [README](README.md) file for installation and usage tips.

# Questions ?

Please contact us : https://www.uap-initiative.org/contact/
