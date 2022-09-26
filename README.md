# Roseibium sp. Sym1 hybrid genome assembly
Script and output files for hybrid genome assembly of the bacterium, Roseibium sp. 
Emily Aguirre, emilyagu@usc.edu

We sequenced and assembled the genome of a ubiquitous bacterial associate, Roseibium (formerly known as Labrenzia sp.) of the cnidarian microalgal symbiont, Symbiodiniaceae linuchae. Long reads were sequenced using the MinION Oxford Nanopore platform. Short reads were sequenced using Illumina NextSeq 2000 platform (paired end reads of 2x150bp). Both types of reads were used to build a hybrid assembly of the bacterial genome.

Annotations in the script describe input files, and all analyses can be re-created by starting with the raw .fastq files available for download at "_____".

A full annotation of this genome can be found at JGI IMG/MER under Project ID: Gp0612333, under "Roseibium sp. Sym1 re-assembly" (https://gold.jgi.doe.gov/projects?id=Gp0612333). 

# Files in this repository

Hybrid assembly and long reads assembly script
- roseibium_hybrid_assembly_script.txt
- Output file (graph): assembly.gfa
- Output file (final assembly): corrected_roseibium_assembly_final.fa
