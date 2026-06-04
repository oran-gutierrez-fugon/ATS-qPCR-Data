# UBE3A-ATS qPCR data

RT-qPCR measurements of *UBE3A-ATS* (the antisense transcript within *SNHG14*) across LUHMES differentiation. The data show *UBE3A-ATS* rising from nearly undetectable in undifferentiated cells to levels comparable with adult brain by day 7 of neuronal differentiation.

This is the orthogonal expression check behind:

> Gutierrez Fugón OJ, Sharifi O, Heath NC, et al. *Integration of CTCF Loops, Methylome, and Transcriptome in Differentiating LUHMES as a Model for Imprinting Dynamics of the 15q11-q13 Locus in Human Neurons.* Hum Mol Genet. 2024. https://doi.org/10.1093/hmg/ddae111

## Why it matters

*UBE3A-ATS* silences the paternal *UBE3A* allele in neurons. Tracking its expression over the differentiation timecourse ties the chromatin loops (HiChIP, 4C) and methylation changes (Oxford Nanopore) to an actual transcriptional readout: the antisense turns on exactly when the neuron-specific loops and DMRs appear.

## Contents

- `ATSinNeurons.csv` — *UBE3A-ATS* qPCR measurements in differentiated LUHMES neurons
- `ATStimelineSummary.csv` — summarized *UBE3A-ATS* expression across the differentiation timecourse
