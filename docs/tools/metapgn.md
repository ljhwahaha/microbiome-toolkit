# MetaPGN

MetaPGN is a pipeline for constructing annotated pangenome networks and visualizing them in Cytoscape.

- Repository: <https://github.com/ljhwahaha/MetaPGN>
- Paper: [MetaPGN: a pipeline for construction and graphical visualization of annotated pangenome networks](https://doi.org/10.1093/gigascience/giy121)
- Main workflow style: Perl pipeline plus Cytoscape visualization plugin
- Primary domain: pangenome network construction and visualization

## When To Use

Use MetaPGN when you want to compare strain- or gene-level variation through annotated pangenome networks.

It is best suited for network construction and graphical exploration. It is not a virome profiler and does not perform phage-host prediction.

## Inputs

The tool README describes two main input groups:

- Query assemblies or query gene sequences
- A reference genome or reference gene sequence set

Optional metadata can be supplied for reference annotations.

## Outputs

MetaPGN generates network files that can be imported into Cytoscape for visualization and interactive exploration. The repository also includes a Cytoscape plugin for arranging pangenome network nodes.

## Installation And Usage

Follow the current instructions in the MetaPGN repository:

<https://github.com/ljhwahaha/MetaPGN>

The child README describes Perl and MetaGeneMark requirements, `MetaPGN_flow.pl` usage, shell script generation, Cytoscape installation, plugin setup, and network import.

## Citation

Peng Y, Tang S, Wang D, Zhong H, Jia H, et al., Li J. MetaPGN: a pipeline for construction and graphical visualization of annotated pangenome networks. *GigaScience*. 2018;7(11). doi: [10.1093/gigascience/giy121](https://doi.org/10.1093/gigascience/giy121)

See also: [../publications.md](../publications.md) and [../citations.bib](../citations.bib).
