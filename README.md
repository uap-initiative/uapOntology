# Project name

The UAP's ontology, an [UAP initiative](https://www.uap-initiative.org) project.

# Description

In order to share ufological data and enhance softwares interoperability we need
to define a common language. This project aims to define an ontology which
describes ufology's domain, particular UAP's sightings.

By formalising the concepts involved in those sightings, we are pursuing two
goals : 

1. develop and accurate the [data recording model
   (DRM)](https://uap-initiative.github.io/drm/), particular the table structure
   that will be used by our application;
2. provide a framework for publishing data as queryable Web linked data.

The project consists of 

- building the ontology itself using Protégé^[ Musen, M.A. The Protégé project:
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

# Installation

We propose to work with [Protégé](https://protege.stanford.edu/) to build
ontology and with [LODE](https://essepuntato.it/lode/) to produce documentation.

# Usage

Edit `*.owl` files with Protégé version 5.5.0 or later.

You can *locally* generate :

- `*.html` pages from `*.owl` files using LODE.
- `*.html` pages from `*.md` files using Pandoc.

For more details about these apps usage, please refer to their documentation.
Here is some direct links :

- [Vim](https://www.vim.org/docs.php)
- [Atom](https://flight-manual.atom.io/)
- [Pandoc](https://pandoc.org/getting-started.html)
- [Protégé](https://protege.stanford.edu/)
- [LODE](https://essepuntato.it/lode/)

# Contributing

This project is open to contributors !

We need your help to :

- define ontology classes, properties and annotations ;
- correct ontology ;
- correct spelling.

More instructions and tips : please see [CONTRIBUTING](CONTRIBUTING.md) and
[CODE OF CONDUCT](CODE_OF_CONDUCT.md).

# License

See [LICENSE](LICENSE.md).
