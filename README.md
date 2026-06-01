# FPDE documentation

This repository contains the Mintlify documentation site for [Feature Prototype Direction Explainer (FPDE)](https://github.com/fpde-xai/fpde).

FPDE is a Python package for prototype-contrast feature attribution.
It explains classification results by comparing an input with a target-class prototype and a rival-class prototype.

## Local development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the local preview from the repository root:

```bash
mint dev
```

View the preview at `http://localhost:3000`.

## Quality checks

Run link and build checks before publishing:

```bash
mint broken-links
mint validate
```

## Source project

- [FPDE repository](https://github.com/fpde-xai/fpde)
- [FPDE on PyPI](https://pypi.org/project/fpde/)
- [Citation metadata](https://github.com/fpde-xai/fpde/blob/main/CITATION.cff)
