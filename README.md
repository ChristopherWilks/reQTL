# reQTL
reQTL is an online resource consisting of expression QTLs at the gene, exon, and exon-exon junction resolution across a selection of CNS-related and general brain regions and tissues.  

It used expression data processed through the [Monorail](https://github.com/langmead-lab/monorail-external) pipeline which is compatible with recount3 (e.g. GTEx v8) as input, in addition to the genotypes for each specific dataset.  

It used [FastQTL](https://github.com/francois-a/fastqtl) initially and later [tensorQT]([https://github.com/broadinstitute/tensorqtl) to process the QTLs, following the GTExV8 eQTL best [practices](https://github.com/broadinstitute/gtex-pipeline/blob/master/qtl/README.md).  

reQTL makes available both the permuted results (best SNP per genetic feature for each dataset) as well as the nominal p-values across the feature-SNP combinations for use with downstream analyses (e.g. Colocalization).
