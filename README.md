## Jupyter Binder tutorial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Arkadiy-Garber/binder-variant-calling/HEAD)

### Bash tricks

List the contents of the current working direcory
    
    ls

change directory to move into the **data** folder
    
    cd data/

unzip the gzipped FASTQ reads

    gzip -d reads.R1.fq.gz

    gzip -d reads.R1.fq.gz

print Breseq help menu

    breseq -h

Run basic Breseq analysis with the provided reference genome and unzipped reads

    breseq -j 16 -r genome.gbk reads.R1.fq reads.R2.fq
