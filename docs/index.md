# Engineering Pathogen-Resistant Crops using Directed Evolution


## Challenge

**Crop diseases** caused by pathogens and pests pose a global burden on agriculture, reducing harvest by up to 40% [^1], ultimately impacting the economy and environment[^2][^3]. 
Currently, pesticides are used to protect crops, however, they negatively impact the  environment and pose health risks to humans[^4]. Therefore, developing  **disease-resistant crops** remains a challenge that demands innovative solutions and  research.  

Like humans, plants also have a built in immune system to protect themselves from pathogens. This defence system relies on proteins called **Pattern Recognition Receptors (PRRs)**, the security guards of plant cells. They perceive certain molecular patterns associated with pathogens, and pull the alarm by initiating a series of immune responses [^5].

To counteract the plant's immune system, pathogens can introduce proteins called **effectors** into the plant cells to inhibit PRRs (as well as other immune proteins) and even degrade them, via **protein-protein interactions**[^6].

To counteract effectors, plants can elude the attacks by effectors, by generating mutations to disrupt the protein-protein interactions between effectors and the targets.

The endless arms race between plants and pathogens is a perfect example of **evolution**. Due to the slow growth of plants and the fast proliferation of pathogens, plants evolve much slower than pathogens. Therefore, it’s difficult for us to search for resistant plants from nature, and pathogens can easily overcome plant’s resistance. 

## Our Approach
To help plants win the arms race, we are employing a Nobel Prize-winning technology, **Directed Evolution**, which enables millions of years of evolution to be achieved in the lab in one week. We aim to use directed evolution to **disrupt the PRR-effector interaction**, creating PRRs resistant to effectors’ attacks.

## Our workflow:

1. Reconstruct/simulate PRR-effector interaction in **yeast cells** and **computer models**.

2. Use **Reverse Yeast Two-Hybrid** and **Machine learning** to select/screen for PRR variants carrying interaction-disrupting mutations. 

3. Test the PRR variants in plants to screen for mutations **preserving** PRR’s functions.

4. Introduce qualified mutations to crops using **precise genome editing technology**, resulting in **non-GMO crops** with enhanced disease resistance.

## Key achievements:
 * Pioneered using directed evolution technology to create disease resistant crops
 * Proposed a novel strategy to enhance plant immunity by engineering plant pattern recognition receptors to elude attacks by effectors
 * Developed TRUST-rY2H, a novel reverse yeast two-hybrid system (rY2H) to disrupt protein-protein interactions. [Results](results.md)
 * dentified mutations disrupting CERK1-AvrPtoB interaction using TRUST-rY2H and machine learning-based computational design. [Results](results.md)
 * Designed a screening method to rapidly test the activity and AvrPtoB resistance of CERK1 variants. [Results](results.md)

We also:
 * Developed a reverse assay for split-ubiquitin membrane protein yeast two-hybrid (MYTH) to disrupt the interaction between membrane proteins. (link to results)
 * Developed fluorescent reporters for conventional Y2H and MYTH to precisely measure the strength of protein-protein interactions. (link to results)



<p>&nbsp;</p><p>&nbsp;</p>

<img src="img/iDEC Team Flyer.jpg"/>


## References

[^1]: FAO on behalf of the IPPC Secretariat, Scientific review of the impact of climate change on plant pests – A global challenge to prevent and mitigate plant pest risks in agriculture, forestry and ecosystems. (2021). 
DOI: https://doi.org/10.4060/cb4769en

[^2]: P. M. M. Martins, M. V. Merfa, M. A. Takita, and A. A. De Souza, Persistence in
phytopathogenic bacteria: Do we know enough?. Frontiers in Microbiology, vol. 9,
Frontiers Media S.A., (2018).
DOI:  https://doi.org/10.3389/fmicb.2018.01099


[^3]: S. Savary et al., Crop health and its global impacts on the components of food security. Food Secur., vol. 9, no.2, pp. 311–327, (2017).
DOI: https://doi.org/10.1007/s12571-017-0659-1

 
[^4]: V. M. Pathak et al., Current status of pesticide effects on environment, human health and its eco-friendly management as bioremediation: A comprehensive review. Frontiers in Microbiology, vol. 13., (2022).
DOI: https://doi.org/10.3389/fmicb.2022.962619

 
[^5]: F. Boutrot and C. Zipfel, Function, Discovery, and Exploitation of Plant Pattern Recognition
Receptors for Broad-Spectrum Disease Resistance. Annu Rev Phytopathol, 28617654, (2017).
DOI: https://doi.org/10.1146/annurev-phyto-080614-120106

[^6]: A. P. Macho and C. Zipfel, Targeting of plant pattern recognition receptor-triggered immunity by bacterial type-III secretion system effectors. Current Opinion in Microbiology, vol. 23, pp. 14–22, (2015).
DOI: https://doi.org/10.1016/j.mib.2014.10.009


