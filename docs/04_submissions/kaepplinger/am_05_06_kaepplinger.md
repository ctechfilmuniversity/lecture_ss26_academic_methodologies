---
layout: default
title: Homework
nav_exclude: true
---
```

## Session 05 and 06


### Task 05.01 - Final Paper Description

*Describe in max. 1500 characters, what your paper investigates. Be specific, well-defined and narrow. If you have a research question even better. Integrate all relevant references you have have so far into the text.*
  
* *This description must be continuous text and proper language - written by you, not an AI.*
* *Add a proper list of references (not counting towards the 1500 characters)*

*Submission:*

I built a tool that turns an Unreal Engine scene into training data for a 3D Gaussian Splat (Kerbl et al. 2023). 
Most splatting workflows are used with real photographs, but a game engine like Unreal Engine can produce perfectly controlled synthetic scenes, making it a tempting source of training data, as the data is clean and hasa a ground truth: my tool exports everything that the Gaussian Splat training software needs: images, camera extrinsics, intrinsics, and a point cloud which is taken directly from the scene rather than from the usual Structure-from-Motion step. 
While building it, I found that no single capture method works for every scene and use case. 

This paper is supposed to explore why no single method works for capturing a synthetic Unreal Engine scene as a 3D Gaussian Splat, and why the right method depends on the type of scene and its intended use.
I investigate this through a research-through-design approach (Zimmerman et al. 2007), in which building the tool is itself how the question is investigated. I already implemented one capture method and I plan to implement two more. 
Each method is suited to a different kind of scene and usecase.
The design lessons come from where each method succeeds and where it struggles. 
The papers contribution is the understanding behind the tool: clear guidance on which capture method fits which kind of scene and an explanation of why one method cannot cover them all.


#### Current Literature List

+ Bernhard Kerbl, Georgios Kopanas, Thomas Leimkühler, and George Drettakis. 2023. 3D Gaussian Splatting for Real-Time Radiance Field Rendering. ACM Transactions on Graphics 42, 4 (July 2023). arXiv:2308.04079.  
https://doi.org/10.48550/arXiv.2308.04079

+ Monica M. Q. Li, Pierre-Yves Lajoie, and Giovanni Beltrame. 2024. Frequency-based View Selection in Gaussian Splatting Reconstruction. arXiv:2409.16470.  
https://doi.org/10.48550/arXiv.2409.16470

+ John Zimmerman, Jodi Forlizzi, and Shelley Evenson. 2007. Research Through Design as a Method for Interaction Design Research in HCI. In Proceedings of the SIGCHI Conference on Human Factors in Computing Systems (CHI '07). ACM, 493–502.  
https://doi.org/10.1145/1240624.1240704

+ more to come :D

---

**COMMENT LENA**: 
This text gives a good idea of the topic and aspects you want to work on and is sufficient for next week's submission. However, I recommend that you already further improve the text based on the following comments. 

Overall, your text still lacks precision and makes in parts ungrounded claims:
- "I found that no single capture method works for every scene and use case." -> How did you "find" that? Did you make an analysis? And what do you mean with "works for every scene and use case"? Rather state a couple of concrete failure cases that you experienced and which might motivate your paper just as well. 
- "depends on the type of scene and its intended use" -> And what type of scenes and uses can there be? To claim to cover all is not reasonable. Again, find some specific cases here and describe them.
- It is not clear why you need a research-through-design approach. What can you answer with that, that you couldn't through just analyzing your finished implementation? RtD requires that the design process itself generates knowledge, not just a working artifact. How does this apply here?
- "Each method is suited to a different kind of scene and use case" -> Which ones (see also my comment above).
- "The design lessons come from where each method succeeds and where it struggles." -> With what exactly?
- "clear guidance on which capture method fits which kind of scene" -> Based on what?

Obviously you need more targeted references :D E.g., on synthetic training data and Unreal Engine as a data source?

---

Due to the scope of a more technical research I switched to a Research question that is a bit broader but seems more interesting to me.


# Changed and Updated Research Question

This paper investigates how 3D Gaussian Splatting (3DGS) (Kerbl et al., 2023), is being adopted along the Virtual Production (VP) pipeline.

The research question is: At which stages of the VP pipeline is 3DGS currently used, which benefits and limitations do practitioners report, and why does adoption drop off toward final-pixel work?

The paper combines a review of academic and industry publications with an expert practitioner survey, mapped onto three pipeline phases. The scope is capture-based 3DGS (real drone/camera footage), the dominant workflow.

+ Pre-production (scouting, previs, techvis, assets) is most mature: 3DGS beats photogrammetry for virtual backdrops, being faster to capture and more realistic (Haslbauer et al., 2025). Rodeo FX turned the sets of Dune: Prophecy into splats for real-time scouting (Hery, 2025).
+ Production (LED volume up to final pixel) is hardest: open problems remain in relighting, dynamic range and moving content (Azzarelli et al., 2026).
+ Post-production is emerging, with native splat support in compositing tools and first final-pixel shots.

The survey currently covers ten VP/VFX practitioners, mostly supervisors and stage leads, four so far have used 3DGS on a real production, the rest have tested and experimented with it. The experience ranges from under two to over ten years. 
The survey is there to test how far the reviewed papers and sources match the On Set practice.


## Current Literature List

+ Kerbl, B., Kopanas, G., Leimkühler, T., & Drettakis, G. (2023). 3D Gaussian Splatting for Real-Time Radiance Field Rendering. ACM Transactions on Graphics, 42(4), Article 139. 
Link: https://doi.org/10.1145/3592433

+ Haslbauer, P., Pullen, M., Reichherzer, C., & Smolic, A. (2025). Gaussian Splatting vs. Classical Photogrammetry: A Comparison for Virtual Backdrops. QoMEX 2025 (IEEE). 
Link: https://ieeexplore.ieee.org/document/11219987/

+ Hery, J. (2025). The Environments of Dune: Prophecy through the Gaussian Splat. In SIGGRAPH Talks '25. ACM. 
Link: https://doi.org/10.1145/3721239.3734124

+ Azzarelli, A., Anantrasirichai, N., Pollock, J., & Bull, D. R. (2026). Relightable Gaussian Splatting for Virtual Production Using Image-Based Illumination. arXiv:2605.09024. Link: https://arxiv.org/abs/2605.09024

+ more to come :D

