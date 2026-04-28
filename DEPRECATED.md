# DEPRECATED — moved

This repo has been merged into [`Crownelius/Datagenerator-arxiv`](https://github.com/Crownelius/Datagenerator-arxiv) under the `corpus/` subdirectory.

The new combined repo includes both the dataset builder (Python, what was here) and the dataset distillation tool (TypeScript, formerly `Crownelius/datagenerator`), plus an onboarding wizard, config file system, and runtime REPL.

## Where things live now

| Was | Now |
|---|---|
| `arxiv-corpus-builder/src/arxiv_corpus/` | `Datagenerator-arxiv/corpus/src/arxiv_corpus/` |
| `arxiv-corpus-builder/tests/` | `Datagenerator-arxiv/corpus/tests/` |
| `pip install -e .` | `pip install -e ./corpus` (from the new repo root) |
| `arxiv-corpus build ...` | Same CLI, just install from the new path |

This repo will be archived. No further updates here. Open issues / PRs at [`Crownelius/Datagenerator-arxiv`](https://github.com/Crownelius/Datagenerator-arxiv).
