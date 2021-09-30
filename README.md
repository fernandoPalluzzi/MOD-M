# Multilayered Omics Data Modeling (MOD-M) project overview
Next-Generation Sequencing (NGS) or High-Throughput Sequencing (HTS) are the generic terms used to include the range of sequencing-based technologies enabling a deep, heterogeneous, and large-scale investigation of genomic processes at different levels: molecular processes, cell development/fate, cell-cell interaction, tissue, organism, population.
HTS data are:

- **Deep**, because HTS technologies enable a high-depth of discovery, also in case of interaction-dense (i.e., complex) and rare events.

- **Heterogeneous**, because they can be used to quantify both structural and functional variability, at genomic, epigenomic, and transcriptional level, providing a high-dimensional input space in which biological events are embedded.

- **Large-scale**, since the molecular evidences can be generalized and translated into mechanisms explaining phenotypical and disease-associated variability, at both subject (personalized) and population level.

These characteristics led to an actual deluge of big and complex data, and to the development of dedicated:
- **Statistical modeling paradigms**,
- **Learning methods**,
- **Classification algorithms**,

together with high-performance hardware settings, to cope with the computational burden required by these complex systems.

The concept of perturbation arises when a system is altered (i.e., changed) by one or more external influences affecting its behavior respect to a reference state (often described as physiological or healthy). The ultimate goal of the MOD-M project is to provide a scalable statistical learning framework for generating data-driven models, enabling the detection of perturbation drivers and paths within their multidimensional molecular context, under different exogenous stimuli and experimental conditions.

# Repositories
The MOD-M project is a collection of methodological solutions to ease the construction and testing of causal network-based models. To date, MOD-M is linked to the following repositories:

- [**SEMgraph**](https://github.com/fernandoPalluzzi/SEMgraph)

- [**SEMdata**](https://github.com/fernandoPalluzzi/SEMdata)

# References

Palluzzi F, Grassi M. **SEMgraph: An R Package for Causal Network Analysis of High-Throughput Data with Structural Equation Models**. Sep 2021; arXiv:2103.08332.

Palluzzi F, Ferrari R, Graziano F, Novelli V, Rossi G, Galimberti D, Rainero I, Benussi L, Nacmias B, Bruni AC, Cusi D, Salvi E, Borroni B, Grassi M. **A novel network analysis approach reveals DNA damage, oxidative stress and calcium/cAMP homeostasis-associated biomarkers in frontotemporal dementia**. PLoS One. 2017 Oct 11; 12(10): e0185797. doi: 10.1371/journal.pone.0185797. eCollection 2017. PMID: 29020091; PMCID: PMC5636111.
