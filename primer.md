# RNA-Seq Data Analysis - A primer

## Sequencing technologies
  First Generation : Sanger Sequencing - Sequencing long fragments of DNA or mRNA (after conversion to cDNA, ~ 1kb long, slow, accurate
  Second Generation : Also known as next generation sequencing (NGS), sequencing of short fragments of DNA or cDNA, 50-100bp long, fast,need many replicates for accuracy, eg: Illumina, 454/Roche (obsolete now),ABI-SOLiD
  Third Generation :Fast, long as in several KBs, accuracy??, need second generation sequencing to resolve accuracy issues, expensive (per base cost),eg. Pacific Bio, Oxford Nanopore, 10X Genomics
  
For now, for the purposes of gene expression studies Second genertion sequencing platforms, especially Illumina Hiseq/Nextseq are the best options in terms of
accuracy and cost provided the reference genome is available (debatable). 

This boot camp is focused on this aspect. We use the model plant Arabidopsis as the organism of choice. Reasons - smaller genome compared to other sequenced plants. Availability of many datasets and a well annotated genome.

For the purpose of hands on experience and learning new things, we use the actual dataset from the NCBI. The SRA study [SRP159482] (https://trace.ncbi.nlm.nih.gov/Traces/sra/?study=SRP159482) is a RNA-Seq study with a wild type and a mutant with 3 biological replicates each. **Best Practice**


We will follow the protocol from this [paper] (https://www.nature.com/articles/nprot.2016.095.pdf) for the most part of it.

Transcript-level expression analysis of RNA-seq experiments with HISAT, StringTie and Ballgown.
Mihaela Pertea, Daehwan Kim, Geo M Pertea, Jeffrey T Leek & Steven L Salzberg.
Nature Protocols volume 11, pages 1650–1667 (2016).

Don't worry we will walk you through the protocol.

