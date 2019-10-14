## Modify VCF SCOUT

This script takes vcfs annotated by

1. VEP
   * GERP
   * CADD
   * MaxEntScan
   * phyloP100way
   * phastcons
   * gnomad.exomes.2.1 AF, AF_popmax, popmax
2. SnpSift Clinvar
3. genmod SPIDEX
4. genmod inheritance models

It will collect relevant information from VEP-string and put it as detectable flags in INFO-field for genmod score

run as:
`./modify_vcf_scout.pl input.vcf > output.vcf`
