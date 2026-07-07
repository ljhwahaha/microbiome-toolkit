# VirHostHunter / Viral-Host-Hunter

VirHostHunter is a protein-centered, alignment-free framework for predicting bacterial hosts of phages from fragmented viral sequences.

- Repository: <https://github.com/ljhwahaha/Viral-Host-Hunter>
- Paper: [High-resolution phage-host assignment through key proteins using large language models](https://doi.org/10.1038/s41467-026-70613-x)
- Main workflow style: Python command-line tool with pretrained models
- Primary domain: phage-host assignment

## When To Use

Use VirHostHunter when you have viral or phage sequences and want to predict bacterial hosts at family, genus, species, or all taxonomic levels.

It is best suited for host-assignment tasks involving key phage proteins such as tails or lysins. It is not a whole-cohort virome abundance profiler and does not build pangenome networks.

## Inputs

The tool README describes prediction with:

- Protein FASTA file
- Matching DNA FASTA file
- Protein type, such as `tail` or `lysin`
- Pretrained VirHostHunter model directory
- Optional local ProtT5 directory for offline embedding

## Outputs

Prediction results are written to an output directory in formats such as CSV, TSV, XLSX, or both CSV and XLSX.

The reported columns include input protein and DNA sequence identifiers plus predicted hosts under multiple confidence thresholds. The `--lineage` option adds full host lineage columns.

## Installation And Usage

Follow the current instructions in the Viral-Host-Hunter repository:

<https://github.com/ljhwahaha/Viral-Host-Hunter>

The child README describes Python, PyTorch, CUDA, model downloads from Zenodo, ProtT5 requirements, quick tests, prediction commands, and optional training workflows.

## Citation

Du Z, Li M, Lin K, Xing B, Ou Y, et al., Li J, Li J, Xiao M. High-resolution phage-host assignment through key proteins using large language models. *Nature Communications*. 2026;17:4439. doi: [10.1038/s41467-026-70613-x](https://doi.org/10.1038/s41467-026-70613-x)

See also: [../publications.md](../publications.md) and [../citations.bib](../citations.bib).
