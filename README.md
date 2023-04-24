# GenomeAssembly_AburnsiiNCIM1409
This repository contains the scripts and codes used for various analyses in the study 'Genomic and transcriptomic analysis of camptothecin producing novel fungal endophyte - Alternaria burnsii NCIM 1409'

CDS_finder.py - Identifies CDS candidates in a given set of sequences (transcriptome assembly, mRNAs)

Gene_duplications_synteny_v3.py - Custom script to find the gene duplications in A. burnsii from multiple pairwise synteny comparisons with closely related Alternaria fungi

Process_orthofinder_for_unique_genes.py - Custom python code blocks to obtain the unique genes in A. burnsii NCIM 1409 by parsing the OrthoFinder2 result file containing the orthogroup comparison detail against other fungi used in the comparative study

blast2best.py - Identifies the X best BLAST hit for each query

contig_stats.py - Calculates the assembly statistics for a given FASTA file; removal of short sequences possible

get_peps_from_gff3.py - Helps obtain CDS and peptide FASTA files using GFF3 and whole genome assembly FASTA files as inputs

jcvi_pairwise_synteny.py - Custom script to perform pairwise synteny analysis using JCVI/MCScan

process_blast_results_v2.py - Custom script to analyze and process the BLASTp results of plant vs endophyte sequences and help investigate for the occurrence of horizontal gene transfer

rename_reads_for_trinity.py - Renames all reads in a FASTQ file to prepare for a Trinity de novo transcriptome assembly

transeq.py - Translates coding sequences into polypleptide sequences
