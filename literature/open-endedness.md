# Open-Endedness

## Overview
Open-endedness (OE) is the study of systems that continually produce novelty without settling into a fixed state. Originating in artificial life (ALife), it has become one of the field's central research challenges. This review covers definitions, formal frameworks, algorithms, and recent developments connecting OE to foundation models and creativity.

## Definitions & Conceptual Foundations

1. **Taylor, T., Bedau, M., Channon, A., Ackley, D., Banzhaf, W., et al. (2016). Open-ended evolution: Perspectives from the OEE workshop in York.** *Artificial Life*, 22(3), 408–423.
   DOI: https://doi.org/10.1162/ARTL_a_00210
   - Report from the foundational OEE workshop. Proposes five basic requirements for OEE: (1) robustly reproductive individuals, (2) capacity for more complex offspring, (3) mutational pathways to viable individuals, (4) medium allowing unlimited diversity, (5) drive for continued evolution.

2. **Banzhaf, W., Baumgaertner, B., Beslon, G., et al. (2016). Defining and simulating open-ended novelty: Requirements, guidelines, and challenges.** *Theory in Biosciences*, 135(3), 131–161.
   DOI: https://doi.org/10.1007/s12064-016-0229-z
   - Comprehensive framework for defining novelty in OE systems. Introduces taxonomy of novelty types (variation, innovation, emergence). Critical reference for operationalizing "novelty" — a concept shared with improvisation.

3. **Adams, A., Zenil, H., Davies, P.C.W., & Walker, S.I. (2017). Formal definitions of unbounded evolution and innovation reveal universal mechanisms for open-ended evolution in dynamical systems.** *Scientific Reports*, 7, 997.
   DOI: https://doi.org/10.1038/s41598-017-00810-8
   - Formal mathematical definitions of OE. Identifies four aspects: ongoing innovation, unbounded evolution, ongoing production of complexity, defining feature of life.

4. **Taylor, T. (2019). Evolutionary innovations and where to find them: Routes to open-ended evolution in natural and artificial systems.** *Artificial Life*, 25(2), 207–224.
   DOI: https://doi.org/10.1162/artl_a_00290
   - Connects different kinds of novelty to routes toward OE. Proposes a refined taxonomy building on Banzhaf et al.'s framework.

5. **Packard, N., Bedau, M., Channon, A., et al. (2019). An overview of open-ended evolution: Editorial introduction to the open-ended evolution II special issue.** *Artificial Life*, 25(2), 93–96.
   DOI: https://doi.org/10.1162/artl_a_00291
   - Editorial framing OEE as central to ALife. Discusses diversity of approaches and remaining challenges.

## Why Open-Endedness Matters

6. **Stanley, K.O. (2019). Why open-endedness matters.** *Artificial Life*, 25(3), 232–235.
   DOI: https://doi.org/10.1162/artl_a_00294
   - Argues OE is essential not just for ALife but for AI more broadly. Open-ended systems produce the kind of unbounded creativity that fixed-objective optimization cannot.

7. **Stanley, K.O., & Lehman, J. (2015). *Why Greatness Cannot Be Planned: The Myth of the Objective*.** Springer.
   DOI: https://doi.org/10.1007/978-3-319-15524-1
   - Popular book arguing that pursuing fixed objectives is counterproductive for achieving ambitious goals. Advocates for objective-free search — deeply resonant with improvisation's rejection of predetermined endpoints.

## Novelty Search & Quality-Diversity

8. **Lehman, J., & Stanley, K.O. (2011). Abandoning objectives: Evolution through the search for novelty alone.** *Evolutionary Computation*, 19(2), 189–223.
   DOI: https://doi.org/10.1162/EVCO_a_00025
   - Introduces novelty search: evolutionary algorithm that rewards behavioral novelty rather than fitness. Demonstrates that objective-free search can outperform objective-driven search in deceptive domains.

9. **Lehman, J., & Stanley, K.O. (2008). Exploiting open-endedness to solve problems through the search for novelty.** In *Proc. ALIFE XI*, 329–336. MIT Press.
   URL: https://stars.library.ucf.edu/scopus2000/9505/
   - Earlier formulation of novelty search. Decouples open-ended search from ALife worlds, applying it to practical problems.

10. **Mouret, J.-B., & Clune, J. (2015). Illuminating search spaces by mapping elites.** arXiv:1504.04909.
    URL: https://arxiv.org/abs/1504.04909
    - Introduces MAP-Elites algorithm. Rather than finding a single optimum, MAP-Elites fills a map of diverse, high-performing solutions. Analogous to an improviser exploring the full space of creative possibilities.

11. **Pugh, J.K., Soros, L.B., & Stanley, K.O. (2016). Quality diversity: A new frontier for evolutionary computation.** *Frontiers in Robotics and AI*, 3, 40.
    DOI: https://doi.org/10.3389/frobt.2016.00040
    - Formalizes quality-diversity (QD) as a new optimization paradigm. QD algorithms seek collections of diverse, high-performing solutions — analogous to maintaining an improvisational repertoire.

12. **Cully, A., Clune, J., Tarapore, D., & Mouret, J.-B. (2015). Robots that can adapt like animals.** *Nature*, 521(7553), 503–507.
    DOI: https://doi.org/10.1038/nature14422
    - Demonstrates MAP-Elites enabling robots to adapt rapidly to damage. The pre-computed behavioral repertoire functions like an improviser's vocabulary of moves.

## Open-Endedness & Foundation Models

13. **Lu, C., Lu, S., Lange, R.T., Foerster, J., Clune, J., & Ha, D. (2024). The AI Scientist: Towards fully automated open-ended scientific discovery.** arXiv:2408.06292.
    URL: https://arxiv.org/abs/2408.06292
    - Uses LLMs for automated scientific discovery in an open-ended loop. Connects foundation models to open-ended innovation.

14. **Faldor, M., Zhang, J., Cully, A., & Clune, J. (2024). OMNI: Open-endedness via models of human notions of interestingness.** arXiv:2306.01711.
    URL: https://arxiv.org/abs/2306.01711
    - Uses foundation models to define "interestingness" for driving open-ended search. Bridges subjective human judgment (crucial in improvisation) with algorithmic OE.

15. **Ecoffet, A., Clune, J., & Lehman, J. (2020). Open questions in creating safe open-ended AI: Tensions between control and creativity.** arXiv:2006.07495.
    DOI: https://doi.org/10.48550/arXiv.2006.07495
    - Explores fundamental tension between open-endedness and safety/control. Parallels the improviser's tension between freedom and structure.

16. **Hughes, E., Grefenstette, E., & Leibo, J.Z. (2024). Open-endedness is essential for artificial superhuman intelligence.** arXiv:2406.04268.
    URL: https://arxiv.org/abs/2406.04268
    - Argues that reaching ASI requires open-ended systems that generate knowledge beyond training data. Multi-agent systems and debate may contribute.

## Measuring Open-Endedness

17. **Dolson, E., Vostinar, A.E., Wiser, M.J., & Ofria, C. (2019). The MODES toolbox: Measurements of open-ended dynamics in evolving systems.** *Artificial Life*, 25(1), 50–73.
    DOI: https://doi.org/10.1162/artl_a_00280
    - Proposes concrete metrics for measuring OE dynamics. Important for operationalizing comparisons between improvisational and evolutionary processes.

18. **Soros, L.B., & Stanley, K.O. (2014). Identifying necessary conditions for open-ended evolution through the artificial life world of Chromaria.** In *Proc. ALIFE 14*, 793–800. MIT Press.
    DOI: https://doi.org/10.7551/978-0-262-32621-6-ch128
    - Experimental investigation of conditions needed for OE in artificial worlds.

19. **Bender, A., Fernández León, J.A., & Corujo Rodríguez, S. (2024). On the open-endedness of detecting open-endedness.** *Artificial Life*, 30(3), 390–407.
    DOI: https://doi.org/10.1162/artl_a_00438
    - Meta-analysis arguing that detecting OE is itself an open-ended problem — novelty detection requires defining what counts as novel.

20. **Faldor, M., Zhang, J., Cully, A., & Clune, J. (2024). OMNI-EPIC: Open-endedness via models of human notions of interestingness with environments programmed in code.** arXiv:2405.15568. (ICLR 2025.)
    URL: https://arxiv.org/abs/2405.15568
    - Extends OMNI by using foundation models to generate both environments and reward functions in code. Demonstrates "explosive creativity" that continuously innovates to suggest new interesting learning challenges. Bridges human aesthetic judgment (interestingness) with open-ended algorithmic search.

21. **Channon, A., et al. (2024). Editorial introduction to the 2024 special issue on open-ended evolution.** *Artificial Life*, 30(3), 300–306.
    DOI: https://doi.org/10.1162/artl_a_00439
    - Editorial surveying the state of OEE research in 2024, including connections to creativity and foundation models.

22. **Winters, J. (2025). Modelling the emergence of open-ended technological evolution.** arXiv:2508.04828.
    URL: https://arxiv.org/abs/2508.04828
    - Models how technology evolves open-endedly. Connects OE to cultural evolution and technological innovation — bridging to design improvisation.

23. **Buehler, M.J. (2025). MusicSwarm: Biologically inspired intelligence for music composition.** *Advanced Intelligent Systems*. arXiv:2509.11973.
    URL: https://arxiv.org/abs/2509.11973
    - Demonstrates coherent musical composition emerging from decentralized swarm of foundation models coordinating via stigmergic signals. Swarm yields superior quality, diversity, and creativity — directly connects swarm OE to musical improvisation.

## Key Themes for Improvisation Connection

- **Objective-free search**: Both novelty search and improvisation reject predetermined endpoints
- **Diversity maintenance**: QD algorithms and improvisers both value maintaining a diverse repertoire
- **Emergence & complexity**: OE systems produce emergent complexity, as do improvisational interactions
- **Tension between freedom and constraint**: OE requires structure (genotype-phenotype maps, environmental constraints) just as improvisation requires rules/forms
- **Interestingness as driver**: OMNI's use of "interestingness" parallels the improviser's aesthetic judgment
- **Unbounded novelty**: Both domains seek processes that never plateau
