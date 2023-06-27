# PDIV_denovo_RefGenome

Pipeline for de novo genome assembly of Porites divaricata from PacBio Hifi sequencing data

Pipeline is broken down into 4 parts

Part 1: Initial set-up and conda
Create conda environment

Part 2: Filtering and Pre-assembly stats
Filter out remnant PacBio adapters with HifiAdaptFilt, pre-assembly stats with Jellyfish and Genomescope

Part 3: Assembly
Genome assembly with hifiasm, evaluating genome quality, purge duplicate haplotigs, parse out symbionts

Part 4: Annotation
Find transposable elements (TEs), structural and functional annotation
