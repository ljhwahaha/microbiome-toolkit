# Microbiome Toolkit

Publication tools for microbiome, virome, phage-host, and pangenome analysis.

This repository is a curated entry point for research software developed around Junhua Li's microbiome and virome publications. It helps users choose the right tool, find the corresponding paper, and jump to the maintained project repository for installation and usage.

This is a portal repository. It does not vendor source code, databases, pretrained models, or test data from the individual tools.

## Tools

| Tool | Research question | Typical input | Main output | Paper |
| --- | --- | --- | --- | --- |
| [SinProVirP](docs/tools/sinprovirp.md) | How can human gut virome profiles be quantified efficiently from metagenomic reads? | Metagenomic FASTQ reads and sample table | Viral cluster relative abundance with taxonomy, lifestyle, and host lineage annotations | [Cell Reports Methods](https://doi.org/10.1016/j.crmeth.2025.101250) |
| [VirHostHunter](docs/tools/viral-host-hunter.md) | Which bacterial hosts are predicted for phages or viral fragments? | Phage protein FASTA plus matching DNA FASTA | Host predictions at family, genus, species, or all levels with confidence-threshold columns | [Nature Communications](https://doi.org/10.1038/s41467-026-70613-x) |
| [MetaPGN](docs/tools/metapgn.md) | How can annotated pangenome networks be constructed and visualized? | Query assemblies or genes plus a reference genome or gene set | Pangenome network files for downstream Cytoscape visualization | [GigaScience](https://doi.org/10.1093/gigascience/giy121) |

## Which Tool Should I Use?

Use **SinProVirP** if your starting point is metagenomic sequencing reads and your goal is cohort-scale profiling of the human gut virome.

Use **VirHostHunter** if your starting point is phage or viral sequence data and your goal is high-resolution bacterial host assignment, especially from key proteins such as tails or lysins.

Use **MetaPGN** if your starting point is assembled genomes, metagenomic assemblies, or gene sets and your goal is to build and inspect pangenome networks.

## Repository Links

- SinProVirP: <https://github.com/ljhwahaha/SinProVirP-v1.0>
- VirHostHunter / Viral-Host-Hunter: <https://github.com/ljhwahaha/Viral-Host-Hunter>
- MetaPGN: <https://github.com/ljhwahaha/MetaPGN>

For installation, command-line options, model downloads, databases, and example data, use the README in each tool repository as the source of truth.

## Publications

See [docs/publications.md](docs/publications.md) for the publication list and [docs/citations.bib](docs/citations.bib) for BibTeX entries.

Please cite the specific method paper for the tool you use. If this portal helped you discover or route among tools, you may also cite this repository.

## Scope

This portal intentionally keeps a narrow scope:

- It indexes publication-backed tools.
- It links to the maintained tool repositories.
- It summarizes input, output, and use case differences.
- It does not provide a unified command-line wrapper.
- It does not mirror tool code, databases, pretrained models, or test data.

## Maintenance

Use the issue templates to report broken links, outdated tool metadata, or citation corrections. Runtime bugs, installation problems, and feature requests for a specific tool should usually be opened in that tool's own repository.

Suggested GitHub repository metadata:

- Description: `Publication tools for microbiome, virome, phage-host, and pangenome analysis`
- Topics: `microbiome`, `virome`, `metagenomics`, `phage-host`, `pangenome`, `bioinformatics`
