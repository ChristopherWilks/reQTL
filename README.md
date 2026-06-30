# reQTL
reQTL is an online resource consisting of expression QTLs at the gene, exon, and exon-exon junction resolution across a selection of CNS-related and general brain regions and tissues.  

The data is available for public download free of charge thanks to AWS Open Data [here](https://registry.opendata.aws/reQTL/)!

It used expression data processed through the [Monorail](https://github.com/langmead-lab/monorail-external) pipeline which is compatible with [recount3](https://registry.opendata.aws/recount/) (e.g. GTEx v8) as input, in addition to the genotypes for each specific dataset.  

It used [FastQTL](https://github.com/francois-a/fastqtl) initially and later [tensorQTL](https://github.com/broadinstitute/tensorqtl) to process the QTLs, following the GTExV8 eQTL best [practices](https://github.com/broadinstitute/gtex-pipeline/blob/master/qtl/README.md).  

reQTL makes available both the permuted results (best SNP per genetic feature for each dataset) as well as the nominal p-values across the feature-SNP combinations for use with downstream analyses (e.g. Colocalization).
