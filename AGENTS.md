> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is the documentation site for [FPDE](https://github.com/fpde-xai/fpde), a Python package for prototype-contrast feature attribution.
- This is a documentation site built on [Mintlify](https://mintlify.com).
- Pages are MDX files with YAML frontmatter.
- Configuration lives in `docs.json`.
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP.
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP.

## Terminology

- Use "FPDE" for Feature Prototype Direction Explainer after the first mention.
- Use "target class" for the class being explained.
- Use "rival class" for the contrast class.
- Use "prototype" for a representative class feature vector.
- Use `lambda_hyb` for the Hyb-FPDE mixture weight.
- Use `predict_proba` and `classes_` when referring to model requirements.

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Prefer practical examples using scikit-learn.
- Explain attribution signs consistently: positive values support the target class, and negative values support the rival class.

## Content boundaries

- Document public APIs exported by `fpde` and stable repository workflows.
- Do not document private helper functions unless they are needed to explain public behavior.
- Do not promise prototype types beyond class-mean prototypes unless the source package adds them.
- Do not describe FPDE as a causal explanation method.
