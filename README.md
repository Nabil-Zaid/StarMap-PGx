**StarMap-PGx**
## Live development

StarMap-PGx is currently under active development.

First prototype release (v0.1) focuses on:
- CYP2C19 mapping
- star allele → variant → rsID resolution
- GRCh38 coordinate support

Public demo and notebook coming soon.

Open Pharmacogenomic Interoperability Infrastructure

StarMap-PGx is an open pharmacogenomics infrastructure designed to connect star-allele nomenclature, genomic variants, rsIDs, and genome coordinates into a unified and reproducible resource for research and clinical use.

## Early adoption

StarMap-PGx is currently being prepared for testing in pharmacogenomics research workflows and clinical genomics pipelines.

We are collaborating with academic researchers and bioinformatics teams to validate early mapping results.

**Problem**

Pharmacogenomics relies on star-allele definitions (CPIC, PharmVar), but there is no standardized computational bridge between:

- star alleles
- defining variants
- rsIDs
- genomic coordinates

This limits reproducible pipelines and clinical implementation.

**Solution**

StarMap-PGx builds an open infrastructure that provides:

- harmonized pharmacogenomic database
- star allele → variant → rsID mapping
- genome coordinate resolution (GRCh37/38)
- public API
- Python library

**Initial genes**

- CYP2D6
- CYP2C19
- DPYD
- SLCO1B1

**Goal**

Enable reproducible pharmacogenomics pipelines and support clinical translation worldwide.
