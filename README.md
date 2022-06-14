This page serves as a repository for the data and R code used in the article by Pilotto, Rojas & Buckland: Late Holocene anthropogenic landscape change in northwestern Europe impacted insect biodiversity as much as climate change did after the last Ice Age. Proceedings of the royal society B: biological sciences. https://doi.org/10.1098/rspb.2021.2734

The full fossil beetle dataset and trait associations are available from the Strategic Environmental Archaeology Database (www.sead.se). This repository includes the subset of fossil beetle data and trait associations that were used in this paper (the subset criteria are reported in the text of the article), the assembled taxonomic and trait networks, the reference solutions, and the source code for reproducing the figures and IndVal analysis. The Infomap Software Package was used for clustering the assembled networks into multilevel partitions. It is freely available as a client-side web application at https://www.mapequation.org.

DATA FILES: 

Filtered_data_taxonomy.csv and Filtered_data_traits.csv: subsets of taxonomic and trait data that were used in the analysis. 

Network_taxonomy_states.tree and Network_traits_states.tree: the assembled taxonomic and trait networks.

Modules.csv: Temporal extent of the modules in the taxonomic and trait networks, as from Network_taxonomy_states.tree and Network_traits_states.tree

LegendSamples.csv: Coordinates and ages of the samples.

Robustness_taxonomy.csv and Robustness_traits.csv:  Results of the robustness assessment.

MCR_results.csv: Results of the temperature reconstruction using fossil beetles, these were obtained using the publicly available as part of the software BugsCEP: Coleopteran Ecology Package.

D18O GISP2 for SEAD use Age BP (SEAD).csv: oxygen isotope data from Greenland ice cores, for climatic reconstruction. Reference: Seierstad IK et al. 2014 Consistently dated records from the Greenland GRIP, GISP2 and NGRIP ice cores for the past 104 ka reveal regional millennial-scale δ18O gradients with possible Heinrich event imprint. Quat Sci Rev 106, 29–46. (doi:10.1016/j.quascirev.2014.10.032).

CODE:

Fossil_beetles_network_script.htlm: source code for reproducing the figures and IndVal analysis.

