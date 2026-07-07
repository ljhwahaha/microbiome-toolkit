# SinProVirP

SinProVirP is a signature-protein-based tool for accurate and efficient profiling of the human gut virome.

- Repository: <https://github.com/ljhwahaha/SinProVirP-v1.0>
- Paper: [A signature-protein-based approach for accurate and efficient profiling of the human gut virome](https://doi.org/10.1016/j.crmeth.2025.101250)
- Main workflow style: Snakemake pipeline
- Primary domain: human gut virome profiling

## When To Use

Use SinProVirP when you have metagenomic sequencing reads and want to profile human gut viral clusters at cohort scale.

It is best suited for studies that need a quantitative virome abundance table rather than host prediction for a single phage or pangenome network visualization.

## Inputs

The tool README describes tab-delimited sample files for:

- Paired-end FASTQ reads
- Pre-concatenated read files
- Single-end FASTQ reads

The workflow is configured through `work.sh`, `config.yaml`, and `sample_file.txt` in the child repository.

## Outputs

The final abundance output is reported as files ending in:

```text
*.final.abundance.txt
```

The output table includes viral cluster identifiers, relative abundance, viral lineage, viral lifestyle, and host lineage annotations.

## Installation And Usage

Follow the current instructions in the SinProVirP repository:

<https://github.com/ljhwahaha/SinProVirP-v1.0>

The child README describes Conda environment setup, Snakemake execution, test data, and optional DCS Cloud access.

## Citation

Yang F, Xiong L, Li M, Feng X, Ren H, Shi Z, Zhong H, Li J. A signature-protein-based approach for accurate and efficient profiling of the human gut virome. *Cell Reports Methods*. 2026. doi: [10.1016/j.crmeth.2025.101250](https://doi.org/10.1016/j.crmeth.2025.101250)

See also: [../publications.md](../publications.md) and [../citations.bib](../citations.bib).
