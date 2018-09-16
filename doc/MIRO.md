# Minimum Information for the Reporting of an Ontology (MIRO) [3] associated with PGxO

PGxO reporting following MIRO guidelines [3].
For each guideline, we describe the value of the field to report.

| Guideline (field to report) | Description |
|-----------------------------|-------------|
| A.1 Ontology name | PGxO, v0.4 |
| A.2 Ontology owner | Adrien Coulet (https://members.loria.fr/ACoulet/) |
| A.3 Ontology license | Open access (to be further determined) |
| A.4 Ontology URL | http://pgxo.loria.fr/data/pgxo.owl |
| A.5 Ontology repository | https://github.com/practikpharma/PGxO |
| A.6 Methodological framework | Competency questions described in [1] and [2] |
| B.1 Need | Reconciliation of pharmacogenomic knowledge units of various provenances, enabling further comparison |
| B.2 Competition | SO-Pharm, PHARE, Genomic CDS, PO. Comparison in [2] |
| B.3 Target audience | Bioinformaticians, knowledge engineers, clinical decision support systems. ANR _PractiKPharma_ project  (http://practikpharma.loria.fr) |
| C.1 Scope and coverage | Representing, reconciling and tracing pharmacogenomic knowledge units.|
| C.2 Development community | Adrien Coulet, Clément Jonquet, Pierre Monnin |
| C.3 Communication | https://github.com/practikpharma/PGxO/issues |
| D.1 Knowledge acquisition methodology | Described in [1] and [2] |
| D.2 Source knowledge location | Described in [1] and [2] |
| D.3 Content selection | Described in [1] and [2] |
| E.1 Knowledge Representation language | OWL 2 (OWL-XML syntax), Description Logics ALCI(D)
| E.2 Development environment | Protégé (https://protege.stanford.edu) |
| E.3 Ontology metrics | 15 classes, 9 properties (8 object, 1 data), 59 axioms, 16KB |
| E.4 Incorporation of other ontologies | No ontologies are imported. OBO Relations Ontology, DUL and PROV-O are used. Mappings to NCIt, MeSH, SNOMED-CT, SO-Pharm, PO, PHARE and Genomic CDS |
| E.5 Entity naming convention | Base URI: http://pgxo.loria.fr |
| E.6 Identifier generation policy | Append English rdfs:label to base URI |
| E.7 Entity metadata policy | ``rdfs:label`` in English |
| E.8 Upper ontology | None |
| E.9 Ontology relationships | We use some relationships from OBO Relations Ontology, DUL and PROV-O. We defined 4 new relationships. |
| E.10 Axiom patterns | None |
| E.11 Dereferenceable IRIs | IRIs are dereferenceable to http://pgxo.loria.fr/. Preferred prefix is ``pgxo``. |
| F.1 Sustainability plan | The ontology is maintained by the _PractiKPharma_ project (http://practikpharma.loria.fr/). No specific plan beyond the project span. Ontology is released on the NCBO BioPortal. |
| F.2 Entity deprecation strategy | None |
| F.3 Versioning policy | None |
| G.1 Testing | Described in [1] and [2] |
| G.2 Evaluation | Described in [1] and [2]  |
| G.3 Example of use | Described in [1] and [2]. Instantiation example available in  https://raw.githubusercontent.com/practikpharma/PGxO/master/doc/pgxo_with_instances.owl |
| G.4 Institutional endorsement | None |
| G.5 Evidence of use | Used within the _PractiKPharma_ project (http://practikpharma.loria.fr/) |

## References

1. Monnin, P., Jonquet, C., Legrand, J., Napoli, A., & Coulet, A. (2017, October).
PGxO: A very lite ontology to reconcile pharmacogenomic knowledge units.
In _Methods, tools & platforms for Personalized Medicine in the Big Data Era_.
[Link](https://hal.inria.fr/hal-01593184/document)
2. Monnin, P., Legrand, J., Husson, G., Ringot, P., Tchechmedjiev, A.,
Jonquet, C., Napoli, A., & Coulet, A. (2018). PGxO and PGxLOD: a reconciliation of pharmacogenomic knowledge of various provenances, enabling further comparison. bioRxiv, 390971. [Link](https://doi.org/10.1101/390971)
3. Matentzoglu, N., Malone, J., Mungall, C., Stevens, R.: MIRO: guidelines for
minimum information for the reporting of an ontology. J. Biomedical Semantics
9(1), 6–1613 (2018). doi:10.1186/s13326-017-0172-7
