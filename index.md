Orthogonal oligo Design for Fluorescence *In Situ* Hybridization (**OOD-FISH**) is a **pipeline** for the <b>identification of oligonucleotide sequences that do <u>not</u> hybridize to a reference genome of interest</b>. Such orthogonal oligonucleotides can easily be used as barcodes for PCR or similar protocols.

The pipeline includes the following steps:

1. Sequences (input) generation.
2. Alignment against reference genome.
3. Calculate self-dimerization free energy (SDFE) of every barcode candidate.
4. Filter candidates based on maximum homology and SDFE.
5. Calculate pair-wise hetero-dimerization free energy (HDFE) of selected candidates.
6. Filter based on HDFE.
7. Select largest barcode set with [Parallel Maximum Clique (PMC) algorithm](https://github.com/ryanrossi/pmc).

## Useful links

* [Install](https://ggirelli.github.io/ood-fish/install)
* [Usage](https://ggirelli.github.io/ood-fish/usage)
* [Contributing Guidelines](https://ggirelli.github.io/ood-fish/contributing)
* [Code of Conduct](https://ggirelli.github.io/ood-fish/code_of_conduct)