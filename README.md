# stencil-literature

Literature survey, software comparison, and reference database bridging [`StencilAlgebra.jl`](https://github.com/vlc1/StencilAlgebra.jl) and academic/open-source work on stencil operations for partial differential equations on Cartesian grids, with a focus on implicit solvers, automatic differentiation, and GPU execution.

## Contents

- **[`REPORT.md`](REPORT.md)**: Comparative analysis of `StencilAlgebra` against symbolic stencil compilers, automatic differentiation frameworks, and GPU-accelerated implicit PDE solvers, including literature directions for open roadmap items (`F1` JVP factoring/equality saturation, `F2` matrix-free pullbacks, `B2`/`C2` GPU CSR and stencil storage, and `C3`/`C4` hierarchical solvers) and a curated reading list.
- **[`papers.bib`](papers.bib)**: BibTeX references for academic papers across five themes:
  1. Symbolic stencil DSLs and PDE form languages
  2. Automatic differentiation and sparse Jacobians on grids and GPUs
  3. Implicit solvers, structured stencil storage, and preconditioning
  4. Term rewriting, AC-canonical forms, and equality saturation
  5. Sparse tensor and array compilers
- **[`software.bib`](software.bib)**: BibTeX references for open-source libraries across Julia (`ParallelStencil.jl`, `Chmy.jl`, `Oceananigans.jl`, `MethodOfLines.jl`, `SummationByPartsOperators.jl`, `Stencils.jl`, `KernelAbstractions.jl`, `Enzyme.jl`, `SparseConnectivityTracer.jl`, `DifferentiationInterface.jl`, `Symbolics.jl`, `Metatheory.jl`, `Finch.jl`, `LinearSolve.jl`, `NonlinearSolve.jl`, `Krylov.jl`, `SparseMatricesCSR.jl`) and Python/C++ (`Devito`, `pystencils`, `Halide`, `GT4Py`, `PETSc`, `Hypre`, `deal.II`, `Firedrake`/`UFL`, `jaxhps`, `findiff`).
- **[`papers/`](papers)**: Downloaded open-access and arXiv PDFs of the core papers discussed in [`REPORT.md`](REPORT.md).
