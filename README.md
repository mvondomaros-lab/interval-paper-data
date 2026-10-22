# Simulation inputs for interval-width selection in the residence-time approach

Molecular dynamics inputs accompanying:

> Michael von Domaros, Rinto Thomas, and Praveen Ranganath Prabhakar.
> **Choosing Spatial Resolution in the Residence-Time Approach to Local Diffusivity.**
> arXiv:2610.29703 (2026).
> [Preprint and Supporting Information](https://arxiv.org/abs/2610.29703) ·
> [DOI](https://doi.org/10.48550/arXiv.2610.29703)

## Contents

Coordinates, topologies, force-field parameters, periodic-cell information,
and NAMD/Colvars configurations for the following systems:

| Directory | System |
| --- | --- |
| [`POPC100/`](POPC100/) | Water in a 100-lipid POPC bilayer at 308 K; new RTA sampling |
| [`POPC72/`](POPC72/) | Water in a 72-lipid POPC bilayer at 310 K; earlier reference system |
| [`SC/water/`](SC/water/) | Water in a model stratum corneum lipid barrier |
| [`SC/acetone/`](SC/acetone/) | Acetone in the same barrier |
| [`SC/6mho/`](SC/6mho/) | 6-Methyl-5-hepten-2-one (6-MHO) in the same barrier |

Simulation protocols and analysis details are given in the paper and Supporting
Information. Analysis is implemented in [PDDA](https://github.com/mvondomaros-lab/pdda).

## Citation

Please cite the paper above when using these inputs. Machine-readable citation
metadata is provided in [`CITATION.cff`](CITATION.cff).

Related studies:

- Original RTA methodology: [Thomas et al., JCTC (2026)](https://doi.org/10.1021/acs.jctc.6c00645).
- Earlier SC transport study: [Thomas et al., ACS ES&T Air (2026)](https://doi.org/10.1021/acsestair.5c00412).
- Inputs accompanying the original RTA study: [`rta-paper-data`](https://github.com/mvondomaros-lab/rta-paper-data).
