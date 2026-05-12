---
layout: default
title: Homework
nav_exclude: true
---

**Academic Methodologies**
  
Prof. Dr. Lena Gieseke \| l.gieseke@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF  


## Session 04

The homework should take < 2h. If you need longer, please let me know next class. 


## Reasoning (optional)

* Recap [Chapter Reasoning](../../02_scripts/am_05_reasoning_script.md), if you are interested.

*Submission:* -


## Your Paper

Ideally you should have <= 3 paper topics at this points. You have to do the following two tasks for all topics you are still considering.


### Task 04.01 - Search Strategy

Describe your strategy to find and collect relevant literature for your topic(s). 
*Submission*: Add references and a description of their relevance. You must use whole sentences.

---
*Submission*:

### *What to search*

My topic has different thematic layers which split up in the following categories:

- Technical/ML layer → StreamDiffusion, diffusion models, LoRA, inference optimization
- Creative tool layer → TouchDesigner, real-time graphics, AV performance pipelines
- Domain/context layer → live AV performance, VJing, audiovisual art, creative coding


### *Search Strategy*

1. Pick a keyword cluster (e.g. "StreamDiffusion latency")
2. Find 2–3 good papers on Google Scholar / arXiv
3. Read abstracts + skim references → collect new terms
4. Add new terms to your search and look at relatet work and references
5. Repeat with new terms until results start repeating

### *Where to search*

    Academic / Scientific Sources

`high prio` *Google Scholar* serves as a broad starting point. It has papers across multiple disciplines and allows me to search all three thematic clusters of my topic at once.


`high prio`*Semantic Scholar* is useful for the ML side of my research, since it shows how often a paper has been cited, making it easier to identify key papers.


`high prio` *arXiv* is the most important platform for my technical references, as StreamDiffusion itself was published there and it seems that most cutting-edge diffusion model work appears here. Possible searches are in the field of cs.CV (Computer Vision) and cs.GR (Graphics) categories. 

`mid prio` *ACM Digital Library* covers HCI, creative tools, and live performance technology, including proceedings from conferences like CHI, NIME, and ISEA, which are directly relevant to the performance context of my paper.
IEEE Xplore is relevant for finding literature on real-time systems, signal processing, and latency measurement.


    Creative / Practice-Based Sources

`low prio` *NIME Proceedings* documents research on new interfaces for musical expression and is one of the most directly relevant conference archives for the live AV performance dimension of my topic.

`low prio` *ISEA* Archive covers the International Symposium on Electronic Art and provides practice-based references for situating my work within the broader field of audiovisual and computational art.

`mid prio` *GitHub* is a primary source for the technical tools themselves, as the StreamDiffusion repository and relevant LoRA training repositories contain documentation and implementation details.

`high prio` Derivative Forums is TouchDesigner's official community platform and contains tutorials and pipeline documentation that serves as a practical reference for my implementation.

---
### Task 04.02 - Literature Collection

Name related work for your paper. List *at least* three, ideally academic, publications that you are planning to reference in your paper. Describe briefly, how the publications are related and relevant.
  


*Submission*: 

1. Kodaira et al. (2023). StreamDiffusion: A Pipeline-Level Solution for Real-Time Interactive Generation. arXiv:2312.12491.

`high prio` This is the foundational technical reference for my paper, as StreamDiffusion is the core tool I am integrating into TouchDesigner. It describes the pipeline architecture, inference optimizations, and performance benchmarks that my own measurements will build on and compare against.


2. Hu et al. (2021). LoRA: Low-Rank Adaptation of Large Language Models.

`high prio` This is the foundational paper for the LoRA method I plan to use for custom style training. It establishes the theoretical basis for how a low-rank weight adaptation can steer model output toward a defined visual style without retraining the full model.

3. Luo, S., et al. (2023). Latent Consistency Models: Synthesizing High-Resolution Images with Few-Step Inference. arXiv:2310.04378.

`high prio` StreamDiffusion relies on Latent Consistency Models to reduce the number of inference steps needed per frame, which is what makes real-time generation possible. This paper is therefore a necessary technical reference for explaining the performance characteristics of my pipeline.
  

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
