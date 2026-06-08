---
layout: default
title: Homework
nav_exclude: true
---

**Academic Methodologies**
  
Prof. Dr. Lena Gieseke \| l.gieseke@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF  


## Session 06

The homework should take < 2h. If you need longer, please let me know next class. 


## Reasoning (optional)

* Recap [Chapter Quantitative Research](../../02_scripts/am_07_experiments_script.md), if you are interested.

*Submission:* -


## Your Paper


### Task 06.01 - Final Paper Description

🚨 Hard Deadline **June 11th** 🚨

Describe in max. 1500 characters, what your paper investigates. Be specific, well-defined and narrow. If you have a research question even better. Integrate all relevant references you have have so far into the text.
  
* This description must be continuous text and proper language - written by you, not an AI.
* Add a proper list of references (not counting towards the 1500 characters)

  
  

*Submission:*

This paper examines the integration of StreamDiffusion in TouchDesigner as a tool for low-latency AI image generation and prompting in live AV performances. TouchDesigner is a node-based visual programming environment and a widely used tool in live performance. StreamDiffusion (Kodaira et al., 2023) is a pipeline-level optimization of latent diffusion models (Rombach et al., 2022) that leverages Latent Consistency Models (Luo et al., 2023) to reduce inference steps per frame, enabling real-time image generation inside TouchDesigner. While this allows image synthesis driven by text prompts and live signals such as MIDI controllers, audio features, or video feeds, precise control over the visual output remains limited without targeted customization.

Building on these developments, this paper asks: What are the possibilities and limitations of controlling StreamDiffusion's visual output in TouchDesigner through signal inputs that reflect live performance conditions, such as audio-derived parameters or real-time video, combined with style-layer customization on consumer-grade hardware?

To answer this question, I implement and systematically test the pipeline with external video and audio input signals, measure real-time performance metrics (frame rate and latency) on consumer-grade hardware, and attempt to integrate a custom-trained LoRA as a style layer, documenting results and limitations regardless of outcome.

*References:* 

- Hu, E. J., Shen, Y., Wallis, P., Allen-Zhu, Z., Li, Y., Wang, S., Wang, L., & Chen, W. (2021). LoRA: Low-rank adaptation of large language models [Preprint]. arXiv. https://arxiv.org/abs/2106.09685

- Kodaira, A., Feng, T., Fu, C.-Y., Li, X., Zhang, L., Yang, K., Peng, K., Han, S., Keutzer, K., & Xu, C. (2023). StreamDiffusion: A pipeline-level solution for real-time interactive generation [Preprint]. arXiv. https://arxiv.org/abs/2312.12491

- Luo, S., Tan, Y., Huang, L., Li, J., Zhao, H., & Chen, K. (2023). Latent consistency models: Synthesizing high-resolution images with few-step inference [Preprint]. arXiv. https://arxiv.org/abs/2310.04378

- Rombach, R., Blattmann, A., Lorenz, D., Esser, P., & Ommer, B. (2022). High-resolution image synthesis with latent diffusion models. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 10684–10695. https://doi.org/10.1109/CVPR52688.2022.01042

*Additional readings:* 

- Feng, T., Li, Z., Yang, S., Xi, H., Li, M., Li, X., Zhang, L., Yang, K., Peng, K., Han, S., Agrawala, M., Keutzer, K., Kodaira, A., & Xu, C. (2025). StreamDiffusionV2: A streaming system for dynamic and interactive video generation [Preprint]. arXiv. https://doi.org/10.48550/arXiv.2511.07399

- Huang, J., Weber, C. J., & Rothe, S. (2025). An AI-driven music visualization system for generating meaningful audio-responsive visuals in real-time. In Proceedings of the ACM International Conference on Interactive Media Experiences (IMX '25) (pp. 1–17). Association for Computing Machinery. https://doi.org/10.1145/3706370.3727869









  

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
