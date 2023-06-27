# PDIV_denovo_RefGenome

# pipeline for de novo genome assembly of Porites divaricata from PacBio Hifi sequencing data

# pipeline is broken down into 4 parts

# Part 1: Initial set-up and conda
# making sure packages are loaded in conda environment

# Part 2: Filtering and Pre-assembly stats
# filter out remnant PacBio adapters with HifiAdaptFilt, pre-assembly stats with Jellyfish and Genomescope

# Part 3: Assembly
# genome assembly with hifiasm, evaluating genome quality, purge duplicate haplotigs, parse out symbionts

# Part 4: Annotation
# find transposable elements (TEs), structural and functional annotation
