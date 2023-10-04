# Results

First, a longer paragraph explaining the rationale, and the situations that arise. More talk about how the system is switchable between the positions and orientations.

While trying to replicate the CERK1-AvrPtoB interaction, we obtained differing results depending on which protein was fused to which domain of the Gal4 transcription factor. Namely, when CERK1 and AvrPtoB were fused to the DBD and AD, respectively, we observed a very strong interaction between them, replicating previous results (reference). However, when the DBD and AD were switched between CERK1 and AvrPtoB, the interaction was not replicated. On first glance, this didn’t seem as much of a problem as standard reverse yeast-two hybrid (rY2H) methods described by Vidal et al. or Leanna et al. would permit such constructs. Even though the methods originally intended for the prey protein (CERK1) to be bound to the AD and the bait protein (AvrPtoB) to the DBD, there are no fundamental problems with the fusions being reversed. 

The problem arises when we consider that our workflow includes an error-prone PCR (epPCR) step, which in essence, introduces random mutations into CERK1. The easiest way for a mutation to disrupt the interaction between CERK1 and AvrPtoB is for it to be a truncating mutation. Such mutations fall into one of two categories: i) substitutions that change a codon specifying for an amino acid to a stop codon, and ii) insertions or deletions which cause the downstream sequence to fall out-of-frame1. Regardless of its type, truncating mutations almost always severely affect the protein’s structure, and in turn its function. Thus, truncating mutations are highly likely to result in a positive readout on the rY2H assay, but they are also just as likely to result in a non-functional CERK1 protein. Unfortunately, these mutations are also very common in rY2H assays, with more than 97% of positive colonies expected to contain truncated alleles (Gray et al., 2007). As the end-goal of our project was to disrupt the CERK1-AvrPtoB interaction, while keeping the original function of CERK1 intact, it was paramount to devise a way to select against truncating mutations.


1 In theory, epPCR causes both types of mutations, albeit insertions and deletions are produced at much lower rate (doi: 10.1093/nar/gkh315). 


![Y2H_explained_A](https://github.com/idec-teams/2023_Evolution_Suisse/assets/91744358/12064fbe-d9e3-44e5-ab3a-f912812ddadb)

Present the results for the method development, and be more critical of the ability to discern truncations. Talk about possible reasons.

I would present MYTH adaptation right bellow ours just to keep them in the same place.
