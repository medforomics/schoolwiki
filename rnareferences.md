# RNA References

## RNA Alignment
HiSAT Databases

[HiSat Public Indexes](http://daehwankimlab.github.io/hisat2/download/#h-sapiens)

* Note to use these, the files will have to renamed with the prefix genome

**To Build an Index**

```
hisat2-build  genome.fa genome
```

## StarFusion

Human Ref: [CTAT plug and play](https://github.com/FusionAnnotator/CTAT_HumanFusionLib/wiki)

## BAM Read Count

```
mkdir references
cp GRCh38.fa references/genome.fa
tar cfz ref.tar.gz references
```
**Panel Reference**
```
tar cfz panel.tar.gz targetpanel.bed
```

## Exon Skipping and Gene Abundances

Gencode
  - https://www.gencodegenes.org/human
  - https://www.gencodegenes.org/mouse

