# SNPerr

The purpose of this package ("snip-er") is to select variant frequency and sequence read depth thresholds to distinguish valid biological **SNPs** from sequencing/random **error**. Simulates how the genetic diversity (as measured by Shannon Diversity, Nucleotide (pi) Diversity, and Alternate Allele Frequency) per genomic site in an alignment of short reads is affected by altering sequence read depth or allele frequency.

User input: distribution of nucleotide frequencies at one genomic site (A, C, G, T) and number of replicates at each read depth.

Sample output:

![SNPerrPic.png](/image/SNPerrPic.png)
