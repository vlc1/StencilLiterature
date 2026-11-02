# AGENTS.md

This file provides guidance to agents working in this repository.

## Project Overview

**stencil-literature** collects academic references, open-source software citations, and comparative analysis bridging [`StencilAlgebra.jl`](https://github.com/vlc1/StencilAlgebra.jl) (along with [`AlgebraCore.jl`](https://github.com/vlc1/AlgebraCore.jl), [`StencilAlgebraGPU.jl`](https://github.com/vlc1/StencilAlgebraGPU.jl), [`StencilSolve.jl`](https://github.com/vlc1/StencilSolve.jl), and [`StencilGrids.jl`](https://github.com/vlc1/StencilGrids.jl)) and the literature on stencil computations for partial differential equations on Cartesian grids.

## Repository Layout

- [`README.md`](README.md): Overview of the repository and its deliverables.
- [`REPORT.md`](REPORT.md): Concise synthesis comparing `StencilAlgebra` with related DSLs, AD tools, and GPU/implicit PDE solvers, plus literature mappings for open design problems.
- [`papers.bib`](papers.bib): BibTeX database of academic papers (stencil DSLs, automatic differentiation, implicit solvers, equality saturation, sparse tensor compilers).
- [`software.bib`](software.bib): BibTeX database of open-source libraries in Julia, Python, and C/C++.
- [`papers/`](papers): Local open-access and preprint PDFs of the core papers analyzed in [`REPORT.md`](REPORT.md).

## Conventions

- **BibTeX keys:** Use `AuthorYearKeyword` in `papers.bib` (e.g., `Luporini2020Devito`, `Willsey2021Egg`) and lowercase package/project identifiers in `software.bib` (e.g., `stencilalgebra`, `devito`, `parallelstencil`).
- **Verification:** Never fabricate DOIs, arXiv IDs, or URLs. Verify every downloaded file in `papers/` is a valid `%PDF` document.
- **Markdown:** Follow single-space sentence separation, no trailing whitespace, `$...$` for inline math (on a single line), and `$$...$$` for display math.
