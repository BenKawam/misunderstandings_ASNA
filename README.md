## Five misunderstandings in animal social network analysis

In this repository, we run a series of simulations for Misunderstandings n°1, 2, and 5.
Specifically, we recreate the manuscript's Figures 1-2 in `01_dependency_and_sampling_effort.qmd`, and Figure 3 in `02_interactions_vs_associations.ipynb`.
These notebooks are the central thread of this repository, and can be read and ran independently from one another.

### Structure of the repository
- `DAGs`: causal diagrams displayed in `01_dependency_and_sampling_effort.qmd`.
- `figures`: Figures of the manuscript generated with _Adobe Illustrator_ and _Python_ (see Appendix of `02_interactions_vs_associations.ipynb`).
- `fitted_models`: MCMC samples approximating the posterior distribution of two statistical models described in `01_dependency_and_sampling_effort.qmd`.
- `stan_models`: _Stan_ models used in the second section of `01_dependency_and_sampling_effort.qmd`.
- [`01_dependency_and_sampling_effort.html`](https://htmlpreview.github.io/?https://github.com/BenKawam/misunderstandings_ASNA/blob/main/01_dependency_and_sampling_effort.html): HTML notebook (_R_) for misunderstandings n°1-2 where we recreate Figures 1-2. This [hyperlink](https://htmlpreview.github.io/?https://github.com/BenKawam/misunderstandings_ASNA/blob/main/01_dependency_and_sampling_effort.html) provides a direct display of the notebook.
- `01_dependency_and_sampling_effort.qmd`: Quarto notebook (_R_) for misunderstandings n°1-2 where we recreate Figures 1-2.
- `02_interactions_vs_associations.ipynb`: Jupyter notebook (_Python_) for misunderstandings n°5 where we recreate Figure 3.
