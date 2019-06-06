# PGxO

A lightweight and simple ontology to reconcile and trace knowledge in pharmacogenomics (PGx).

PGxO is also available on the [NCBO BioPortal](https://bioportal.bioontology.org/ontologies/PGXO).

A full description of the motivation, implementation and instantiation of PGxO is available in [2].

When citing PGxO, please use [2].

## Documentation

Documentation is available in the ``doc/`` folder:

* [pgxo.html](doc/pgxo.html): HTML documentation of PGxO
* [pgxo-overview.pdf](doc/pgxo-overview.pdf): Figure presenting PGxO **main** concepts and relations.
* [MIRO.md](doc/MIRO.md): Minimum Information for the Reporting of an Ontology (MIRO) associated with PGxO.
* [pgxo_with_instances.owl](doc/pgxo_with_instances.owl): An instantiated version of PGxO.
* [global-fig.pdf](doc/global-fig.pdf): Global figure presenting the instantiation of PGxO.

## Mappings

Mappings are available in the ``mappings/`` folder:

* [mapp1.owl](mappings/mapp1.owl): Mappings from PGxO to four ontologies related to PGx (SO-PHARM, PO, PHARE and Genomic CDS).
* [mapp2.owl](mappings/mapp2.owl): Mappings from PGxO to three large spectrum ontologies (MeSH, NCIt and SNOMED CT).

## License

PGxO is under [Creative Commons BY NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

## References

1. Monnin, P., Jonquet, C., Legrand, J., Napoli, A., & Coulet, A. (2017, October).
PGxO: A very lite ontology to reconcile pharmacogenomic knowledge units.
In _Methods, tools & platforms for Personalized Medicine in the Big Data Era_.
[Link](https://hal.inria.fr/hal-01593184/document)
2. Monnin, P., Legrand, J., Husson, G., Ringot, P., Tchechmedjiev, A.,
Jonquet, C., Napoli, A., & Coulet, A.
PGxO and PGxLOD: a reconciliation of pharmacogenomic knowledge of various provenances, 
enabling further comparison. BMC Bioinformatics 20-S(4): 139:1-139:16 (2019). 
[Link](https://doi.org/10.1186/s12859-019-2693-9)

```
@Article{Monnin2019,
    author="Monnin, Pierre
    and Legrand, Jo{\"e}l
    and Husson, Graziella
    and Ringot, Patrice
    and Tchechmedjiev, Andon
    and Jonquet, Cl{\'e}ment
    and Napoli, Amedeo
    and Coulet, Adrien",
    title="PGxO and PGxLOD: a reconciliation of pharmacogenomic knowledge of various provenances, enabling further comparison",
    journal="BMC Bioinformatics",
    year="2019",
    month="Apr",
    day="18",
    volume="20-S",
    number="4",
    pages="139",
    issn="1471-2105",
    doi="10.1186/s12859-019-2693-9",
    url="https://doi.org/10.1186/s12859-019-2693-9"
}
```

## Acknowledgments

PGxO is supported by the *PractiKPharma* project (http://practikpharma.loria.fr/),
funded by the French National Research Agency (ANR) under grant ANR-15-CE23-0028.
