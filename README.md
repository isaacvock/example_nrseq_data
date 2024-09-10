# EZbakR-suite tutorial

This repository provides data as part of an EZbakR-suite tutorial. This is a downsampled dataset with 20% of the reads from chromosome 21 of 6 fastq files (and associated bam files) from a TimeLapse-seq data originally presented in Luo et al., 2020. The samples included are:

1. WT1 and WT2: Biological replicates of WT HEK293T TimeLapse-seq data; 2 hour s4U label time.
2. KO1 and KO2: Biological replicates of DCP2 knock out (KO) HEK293T TimeLapse-seq data; 2 hour s4U label time.
3. WTctl: WT HEK293T data with no s4U fed (i.e., basically standard RNA-seq).
4. KOctl: DCP2 KO HEK293T data with no s4U fed.
.
An annotation (GTF) and genome (FASTA) file for chromosome 21 is also provided (annotation/chr21.gtf and genome/chr21.fasta, respectively). Also provided are example fastq2EZbakR config files for either fastq file or bam file input.
