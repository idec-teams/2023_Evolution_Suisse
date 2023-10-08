# Results

First, a longer paragraph explaining the rationale, and the situations that arise. More talk about how the system is switchable between the positions and orientations.

While trying to replicate the CERK1-AvrPtoB interaction, we obtained differing results depending on which protein was fused to which domain of the Gal4 transcription factor. Namely, when CERK1 and AvrPtoB were fused to the DBD and AD, respectively, we observed a very strong interaction between them, replicating previous results (reference). However, when the DBD and AD were switched between CERK1 and AvrPtoB, the interaction was not replicated. On first glance, this didn’t seem as much of a problem as standard reverse yeast-two hybrid (rY2H) methods described by Vidal et al. or Leanna et al. would permit such constructs. Even though the methods originally intended for the prey protein (CERK1) to be bound to the AD and the bait protein (AvrPtoB) to the DBD, there are no fundamental problems with the fusions being reversed. 

The problem arises when we consider that our workflow includes an error-prone PCR (epPCR) step, which in essence, introduces random mutations into CERK1. The easiest way for a mutation to disrupt the interaction between CERK1 and AvrPtoB is for it to be a truncating mutation. Such mutations fall into one of two categories: i) substitutions that change a codon specifying for an amino acid to a stop codon, and ii) insertions or deletions which cause the downstream sequence to fall out-of-frame<sup>1</sup>. Regardless of its type, truncating mutations almost always severely affect the protein’s structure, and in turn its function. Thus, truncating mutations are highly likely to result in a positive readout on the rY2H assay, but they are also just as likely to result in a non-functional CERK1 protein. Unfortunately, these mutations are also very common in rY2H assays, with more than 97% of positive colonies expected to contain truncated alleles (Gray et al., 2007). As the end-goal of our project was to disrupt the CERK1-AvrPtoB interaction, while keeping the original function of CERK1 intact, it was paramount to devise a way to select against truncating mutations.

As truncating mutations are not a novel problem, over the years, two independent groups have already come up with rY2H methods capable of selecting against them. Namely, the reverse double yeast two hybrid (RD2H) proposed by Vincent et al. and the One-plus Two-Hybrid system introduced by Kim et al. Both methods contain an anti-truncation system that relies on a protein/peptide C-terminally fused to the prey protein. Thus, if the prey protein (in our case CERK1) is truncated, the C-terminally fused protein/peptide is not translated, leading to selection against the mutant in question. Unfortunately, both methods require the prey protein to be fused to the AD which, as we have shown, would interfere with the CERK1-AvrPtoB interaction. Therefore, we opted to develop a novel reverse yeast two hybrid system, the Truncation Resistant and Universal Self-cleaving peptide Technology reverse yeast two-hybrid (TRUST-rY2H), which both selects against truncating mutations and allows for prey protein fusion to either AD or DBD (Figure whichever).



![Y2H_explained_A](https://github.com/idec-teams/2023_Evolution_Suisse/assets/91744358/12064fbe-d9e3-44e5-ab3a-f912812ddadb)

Present the results for the method development, and be more critical of the ability to discern truncations. Talk about possible reasons.

I would present MYTH adaptation right bellow ours just to keep them in the same place.


<sup>1</sup> In theory, epPCR causes both types of mutations, albeit insertions and deletions are produced at much lower rate (doi: 10.1093/nar/gkh315). 



<figure markdown>
![Figure1](Report_figures/Figure_1.png)
<figcaption> </figcaption>
</figure>


<figure markdown>
![Figure2](Report_figures/Figure_2.png)
<figcaption> </figcaption>
</figure>

<figure markdown>
![Figure3](Report_figures/Figure_3.png)
<figcaption> </figcaption>
</figure>

<figure markdown>
![Figure4](Report_figures/Figure_4.png)
<figcaption> </figcaption>
</figure>

<figure markdown>
![Figure5](Report_figures/Figure_5.png)
<figcaption> </figcaption>
</figure>

<figure markdown>
![Figure6](Report_figures/Figure_6.png)
<figcaption> </figcaption>
</figure>

<figure markdown>
![Figure7](Report_figures/Figure_7.png)
<figcaption> </figcaption>
</figure>

<figure markdown>
![Figure8](Report_figures/Figure_8.png)
<figcaption> </figcaption>
</figure>

<figure markdown>
![Figure9](Report_figures/Figure_9.png)
<figcaption> </figcaption>
</figure>

<figure markdown>
![Figure10](Report_figures/Figure_10.png)
<figcaption> </figcaption>
</figure>



