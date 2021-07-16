# SNPerr
Determine read depth and variant frequency thresholds to distinguish seq errors from true SNPs. Simulates effect of changing per-site read depth and variant frequency on accuracy of genetic diversity measures (pi, alterante allele frequency, shannon diversity).

The purpose of this package ("snip-er") is to select variant frequency and sequence read depth thresholds to distinguish valid biological **SNPs** from sequencing/random **error**. Simulates how the genetic diversity (as measured by Shannon Diversity, Nucleotide (pi) Diversity, and Alternate Allele Frequency) per genomic site in an alignment of short reads is affected by altering sequence read depth or allele frequency.
