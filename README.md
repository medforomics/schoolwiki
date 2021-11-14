# SCHOOL WIKI

SCHOOL: Software for Clinical Health Omics Onocolgy Laboratories

School is a collection of genomics analysis workflows that are used for detecting single nucleotide variants (SNVs), insertions/deletions (indels), copy number variants (CNVs) and translocations from RNA and DNA sequencing.  These workflows have been validated in a CLIA laboratory at UTSW

### Clone repo

For most recent published version

```
git clone -b version_1.0.3 --single-branch https://github.com/bcantarel/school.git
```

For most recent development version

```
git clone https://github.com/bcantarel/school.git
```

- Running School
  - [With Nextflow on HPC](nextflow)
  - [With DNANexus on Cloud](dnanexus)
- Building Creating Docker Containers
  - [Docker](docker)
  - [Scripts Embedded in Docker](https://github.com/medforomics/process_scripts.git)
- Required Reference Data
  - [DNA Reference](dnareferences)
  - [RNA Reference](rnareferences)
