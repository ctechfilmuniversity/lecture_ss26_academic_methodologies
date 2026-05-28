---
layout: default
title: Homework
nav_exclude: true
---

**Academic Methodologies**
  
Prof. Dr. Lena Gieseke \| l.gieseke@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF  


## Session 05

The homework should take < 2h. If you need longer, please let me know next class. 


## Reasoning (optional)

* Recap [Chapter Qualitative Research](../../02_scripts/am_06_qualitativeresearch_script.md), if you are interested.

*Submission:* -


## Your Paper


### Task 05.01 - Final Paper Description

Describe in max. 1500 characters, what your paper investigates. Be specific, well-defined and narrow. If you have a research question even better. Integrate all relevant references you have have so far into the text.
  
* This description must be continuous text and proper language - written by you, not an AI.
* Add a proper list of references (not counting towards the 1500 characters)

There are two hard deadlines for this paper description:
* **May 28th**: This version can still be moderately adjusted, also based on the feedback I give you. If you still have open questions that you want feedback on, you can indicate these in your first submission.
* **June 11th**: The final submission 
---
 *Submission Notes:* 
- The paper description should be framed in a way that does not require me to end up with a fully working result in order to fulfill the described content. There is very little information available on integrating a self-trained LoRA into StreamDiffusion, and it will likely take several attempts to get it working, if at all. It would therefore be helpful if the paper description allowed for a realistic stopping point in the project, so that I can build the paper around the results I have achieved up to this point. (as we discussed in your office.)
- I also want to mention that this assignment definitely took me longer than two hours. An example text would have been helpful and would have reduced my reliance on AI even further. :)
  

*Submission:* 

This paper examines the integration of StreamDiffusion in TouchDesigner as a tool for real-time visual generation in live AV performances. TouchDesigner is a node-based visual programming environment and a widely used tool in live performance. StreamDiffusion (Kodaira et al., 2023) is a pipeline-level optimization of latent diffusion models (Rombach et al., 2022) that leverages Latent Consistency Models (Luo et al., 2023) to reduce inference steps per frame, enabling low-latency real-time image generation inside TouchDesigner. While this enables real-time creative interpretation of input signals, precise control over the visual output remains limited without targeted customization. Since the customization of StreamDiffusion in real-time settings through self-trained LoRAs (Hu et al., 2021) and external input signals remains under-explored, this paper addresses the following research question: To what extent can external input signals and a custom-trained LoRA be used to guide and stylize the visual output of StreamDiffusion in TouchDesigner?

I answer the research question by implementing and systematically testing the pipeline with external video and audio input signals, measuring real-time performance metrics (frame rate, latency) on consumer-grade hardware, and attempting to integrate a custom-trained LoRA as a style layer—documenting results and limitations regardless of outcome.

*References:* 


- Hu, E. J., et al. (2021). LoRA: Low-Rank Adaptation of Large Language Models. arXiv:2106.09685. https://arxiv.org/abs/2106.09685
- Kodaira, A., et al. (2023). StreamDiffusion: A Pipeline-Level Solution for Real-Time Interactive Generation. arXiv:2312.12491. https://arxiv.org/abs/2312.12491
- Luo, S., et al. (2023). Latent Consistency Models: Synthesizing High-Resolution Images with Few-Step Inference. arXiv:2310.04378. https://arxiv.org/abs/2310.04378
- Rombach, R., et al. (2022). High-Resolution Image Synthesis with Latent Diffusion Models. CVPR, 10684–10695.



  ---

  
Answer all questions directly in a copy of this file. Submit your copy as `am_XX_lastname.md` in your submissions folder (replace the XX with the number of the session). 
  

Please add the following header at the beginning of your Markdown file:

```md
---
layout: default
title: Homework
nav_exclude: true
---
```
  

---

**Happy Collecting!**
