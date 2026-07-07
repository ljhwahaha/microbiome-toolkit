# Repository Guidance

This repository is a public portal for publication-backed microbiome and virome tools.

## Scope

- Keep this repository as a documentation portal.
- Do not copy source code, pretrained models, databases, or test data from child tool repositories.
- Do not turn this repository into a monorepo or unified command-line wrapper unless the project owner explicitly changes scope.

## Sources Of Truth

- Publication metadata comes from the project owner's academic CV and the cited papers.
- Technical installation and usage details come from each child tool repository README.
- This portal should summarize and route; child repositories remain authoritative for runtime behavior.

## Adding Or Updating A Tool

When adding a new publication-backed tool:

1. Add a row to the table in `README.md`.
2. Add or update a focused page under `docs/tools/`.
3. Add the paper to `docs/publications.md`.
4. Add a BibTeX entry to `docs/citations.bib`.
5. Update `CITATION.cff` references if the paper is part of the portal's core scope.

## Review Checklist

- Links to GitHub repositories and DOIs resolve.
- The README clearly distinguishes research question, input, and output for each tool.
- Tool pages do not duplicate long installation manuals from child repositories.
- No placeholder text remains.
- No child repository code, database, model, or test data has been vendored.
