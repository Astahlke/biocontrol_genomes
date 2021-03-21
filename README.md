# Biocontrol Genomes

Inspired by

Hotaling, S., Sproul, J.S., Heckenhauer, J., Powell, A., Larracuente, A.L., Pauls, S.U., Kelley, J.L. and Frandsen, P.B., 2021. Long-reads are revolutionizing 20 years of insect genome sequencing. bioRxiv.
https://www.biorxiv.org/content/biorxiv/early/2021/02/15/2021.02.14.431146.full.pdf
Beautifully documented and reprodicble here: https://github.com/pbfrandsen/insect_genome_assemblies

Goal is to demonstrate that biocontrol genomes are vastly underrepresented relative to their distributions in tree of life. There may be some biocontrol agents that are better suited for study because of existing representation in publicly available datasets.

Performing this work on ibest machine watson.

1. Prereqs

```
git clone https://github.com/pbfrandsen/insect_genome_assemblies

cd ~/bin/
curl -o datasets 'https://ftp.ncbi.nlm.nih.gov/pub/datasets/command-line/LATEST/linux-amd64/datasets'
chmod +x datasets

export PATH=$PATH:/mnt/ceph/stah3621/bin/datasets
```
