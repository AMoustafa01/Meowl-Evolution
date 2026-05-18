# Meowl-Evolution
This is a project dedicated to using a genetic/evolutionary algorithm to explore the speculative evolution of the Meowl.

The content presented on the poster presentation:

  
  Meowl is a trending fictional animal composed of the head of a domestic cat (Felis catus), and the body of a barn owl (Tyto alba). The original photoshopped picture was first posted on April 28th, 2013 on a Chinese social media platform (Weibo) (Kurama0, 2025). Interestingly, the word “owl” in mandarin translates to “cat-headed eagle” further highlighting the similarities between the two animals. 
It is important to note that the Meowl is almost evolutionary impossible in the conventional sense but we examine the aesthetic and the visual possibilities.  
In this project, we aim to entertain the hypothetical question “if Meowl were to exist, how would it have evolved?”. We hypothesized that it could have evolved as a speculative descendant of the Microraptor in two stages: first stage: that it was pushed towards becoming a specialized pouncing hunter instead of a glider, second stage:  that it was domesticated and selectively bred to resemble the current Meowl. 
Therefore, we used an evolutionary algorithm to test this hypothesis. Results have shown that it does indeed converge to more feline-like features. However, it does not switch to a pouncing strategy and instead, retains its gliding. Finally, we do acknowledge the simplicity of the evolutionary model and aim to expand our scope in future research. 

	The microraptor was used as an ancestor to the Meowl because it was adapted to an arboreal lifestyle, had the capability for gliding, and was approximately the size of a modern crow (O’Connor et al., 2011). We hypothesized, these characteristics could possibly converge into feline-like features while maintaining the raptor characteristics similar to the owls. 

	We used an evolutionary algorithm using the traits as the “genome” of each individual. The population was created with the canonical microraptor as the base. A small variation scale was also added for genetic variability. The select function used a tournament-based method, the size of the tournaments was (3) in a population of (200). Moreover, the fitness function was created to test our hypothesis by applying the environmental pressures needed to model the canon microraptor environment as well as giving it a niche-plasticity edge which was not present in the canon microraptor and is thought to contribute to its extinction (García-Girón et al., 2022). 


	There are a variety of limitations within our proposed model. First, the model is quite simplistic in nature. Secondly, while the traits chosen for the algorithm are chosen based on their efficacy to the microraptor, they were also chosen with the Meowl in mind. Inevitably skewing the empirical evolutionary view. Moreover, while the traits’ weights and costs are assigned based on the biological understanding, they are not necessarily concrete in nature. This means the proposed model can benefit from future adjustments and experimentation. 
Finally, our results show that the microraptor would potentially evolve some  feline-like features but may retain its gliding-approach for hunting when pushed into a more nocturnal lifestyle. This finding supports the proposed hypothesis by García-Girón et al., (2022) that microraptors may possess less niche-plasticity which may have contributed to their extinction. These results do not necessarily end the evolutionary possibility of the Meowl, but highlight future challenges. 


References
García-Girón, J., Chiarenza, A. A., Alahuhta, J., DeMar, D. G., Heino, J., Mannion, P. D., Williamson, T. E., Wilson Mantilla, G. P., & Brusatte, S. L. (2022). Shifts in food webs and niche stability shaped survivorship and extinction at the end-Cretaceous. Science Advances, 8(49). https://doi.org/10.1126/sciadv.add5040
Kurama0. (2025, April 13). Meowl. Know Your Meme. https://knowyourmeme.com/memes/meowl
Li, Q., Gao, K.-Q., Meng, Q., Clarke, J. A., Shawkey, M. D., D’Alba, L., Pei, R., Ellison, M., Norell, M. A., & Vinther, J. (2012). Reconstruction of Microraptor and the Evolution of Iridescent Plumage. Science, 335(6073), 1215–1219. https://doi.org/10.1126/science.1213780
O’Connor, J. M., Zhou, Z., & Xu, X. (2011). Additional specimen of Microraptor provides unique evidence of dinosaurs preying on birds. Proceedings of the National Academy of Sciences, 108(49), 19662–19665. https://doi.org/10.1073/pnas.1117727108
