# Paper on schema.org Datatypes

This repo is devoted to a paper on the disadvantanges of using schema.org datatypes,
and that it's better to use XSD datatypes.

Based on discussions and analysis in
https://github.com/schemaorg/schemaorg/issues/1781

The following issues are also loosely related:
- https://github.com/schemaorg/schemaorg/issues/1748 : 
  granularity of schema.org datetime props, and how fixing the datatype in the JSON-LD context is a bad idea
- https://github.com/schemaorg/schemaorg/issues/1512 :
  merge endDate & endDateTime; startDate & startDateTime (because this granularity distinction is not useful)
- https://github.com/schemaorg/schemaorg/issues/1747 :
  a literal is wrongly declared URL in JSON-LD context
- https://github.com/schemaorg/schemaorg/issues/1511 : 
  which are the schema.org datatypes
- https://github.com/schemaorg/schemaorg/issues/1697 : 
  whether `email` should be text or `mailto:` URI

## Related Papers

We'll probably do a proper bibliography in Zotero, but for now:

- [The Problem with XSD Binary Floating Point Datatypes in RDF](https://link.springer.com/chapter/10.1007/978-3-031-06981-9_10).
  Jan Martin Keil & Merle Gänßinger, ESWC 2022.
  DOI 10.1007/978-3-031-06981-9_10
- [Weaving the Pedantic Web](http://events.linkeddata.org/ldow2010/slides/ldow2010-slides-harth.pdf).
  A Hogan, A Harth, A Passant, S Decker, A Polleres (LDOW 2010)

## Submission Info

https://dmkg-workshop.github.io/
DMKG 2023: 1st International Workshop on Data Management for Knowledge Graphs
- Co-located with the ESWC Conference 2023
- Guidelines: https://ceurws.wordpress.com/2020/03/31/ceurws-publishes-ceurart-paper-style/
- Template: https://github.com/yamadharma/ceurart
- Overleaf: https://www.overleaf.com/latex/templates/template-for-submissions-to-ceur-workshop-proceedings-ceur-ws-dot-org/pkfscdkgkhcq (but we plan to write it in markdown and use pandoc)

Timeline:
- March 9, 2023: Paper submission deadline (AoE, i.e. 13:00 CET, 14:00 EET)
- April 13, 2023: Notification of acceptance
- April 20, 2023: Camera-ready version due
- May 28 or 29, 2023: Workshop date
