# Benchmark Cartography

Interactive atlas of which sparse-autoencoder concepts each LLM benchmark exercises, and how much of the concept space it covers.

- Host model: Gemma 2 2B (base), Gemma Scope SAE, layer 20 residual stream, 16k width
- 23 benchmarks across general, code, lineage and reference suites
- Tabs: per-concept coverage, per-item activations, base vs instruct, cross-benchmark coverage, benchmark lineages and effective breadth

Static site: `index.html` plus one JSON per benchmark. Open the GitHub Pages URL or serve the folder locally (`python -m http.server`).

Follow-up to *Uncovering Competency Gaps in Large Language Models and Their Benchmarks* (Bohacek et al., 2026).
