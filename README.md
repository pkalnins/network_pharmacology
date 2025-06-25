# Network Pharmacology-Based Analysis of the Role of Traditional Chinese Herbal Medicine in the Treatment of Migraine**

**Project Overview**

**Description:**
- This project explores how traditional Chinese herbal medicines might exert therapeutic effects on migraine by leveraging a network pharmacology approach.
- Recognizing the polygenic and multifactorial nature of migraine, the analysis integrates bioinformatics tools and databases to map known herbal constituents to migraine-relevant gene targets.

**Objectives:**
- Identify herbs commonly used in Chinese medicine for migraine treatment.
- Collect gene/protein targets for these herbs using the ETCM and Batman2.0 databases.
- Retrieve migraine-associated genes from DisGeNET.
- Identify overlapping targets and construct a protein–protein interaction (PPI) network using STRING.
- Analyze network topology using betweenness centrality and Markov clustering to detect key targets and modules.
- Perform pathway enrichment using ShinyGO and Reactome.

**Key Findings:**
- Chinese herbs relevant to migraine modulate networks involving neurotransmitter (serotonin, dopamine, GABA, glutamate), inflammatory, vascular, and estrogen signaling pathways.
- Several clusters were identified in the PPI network, each corresponding to major biological pathways involved in migraine.
- Network metrics like betweenness centrality helped pinpoint central genes, suggesting potential mechanisms of action.

**Limitations:**
- Target predictions from herbal databases may lack bioavailability and binding specificity information.
- Current analyses do not distinguish between upregulation and inhibition of targets.
- Additional validation and methodological refinement are needed to confirm the utility of the selected network metrics.

**Note:**
- See accompanying slides for more details.
- The code used for analysis is included in the Jupyter notebook.
