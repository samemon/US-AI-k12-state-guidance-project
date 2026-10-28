# RQ3 — Epistemic sources and sharing across states

**Research question.** Which epistemic sources do states rely upon and share, including
other peer-states?

## Scope
Identify the sources of authority and knowledge that state guidance documents draw on
(e.g., federal agencies, non-profits and toolkits such as TeachAI, academic work,
vendors), and measure how much states share language and sources with one another —
evidence of peer-to-peer diffusion.

## Approach
- **Textual convergence** — shared sentences (SBERT cosine similarity) and verbatim
  phrase overlap (word n-gram / shingling; Broder 1997) between every pair of documents,
  rendered as clustered heatmaps and networks.
- **Source / citation analysis** — extraction of cited organizations, laws, and documents;
  cross-state citation and reuse networks.

## Contents
_(to be added)_
- `data/` — document texts, extracted citations, embeddings cache, or pointers to `../../data/`.
- scripts / notebooks — similarity and n-gram heatmaps, citation/reuse networks.

## Reproduce
_(to be added: environment, run order)_
