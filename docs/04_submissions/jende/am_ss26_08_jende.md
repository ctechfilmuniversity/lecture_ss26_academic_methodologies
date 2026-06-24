---
layout: default
title: Homework
nav_exclude: true
---

**Academic Methodologies**
  
Maria Jende, 06/24/2026

<br>

## Session 08

## Your Paper

### Task 08.01 - Introduction

*Write the introduction for your paper. You do not need to re-use this introduction later for your actual paper - but you should! You can re-cap in [Chapter - Anatomy of a Paper](../../02_scripts/am_09_writing_script.md#the-introduction) what the introduction is about.*

*As of now probably some aspects you need to know for writing the introduction are not clear yet. Then write a version of the introduction of how you currently *imagine* the paper to be and you can assume your ideal outcomes.*

***Do not use a GenAi Tool for this task, as it is about practicing to write.***
*After all learning to write, is learning to think...*

*Submission: Your introduction.*

Generative AI for synthetic image generation has become increasingly popular. While those models are supporting multiple kinds of commercial and private workflows, copyright as well as ethical concerns regarding the usage of GenAI images are becoming progressively urgent. Political mis- and disinformation is more than ever supported by the usage of GenAI imagery. Since there are no signs of GenAI usage decreasing in the future, rather the opposite, it becomes necessary to be able to distinguish GenAI images from images which were not produced by GenAI.

To address the socio-political problems derived by the usage of GenAI imagery described above, multiple approaches to distinguish between conventional images (non-GenAI images) and synthetic (GenAI images) are discussed. Adding an invisible watermark to synthetic images, is one of the most recent, actively researched methods to help enable this distinction.

For the generation of those images, Generative Image Diffusion Models have become, next to GANs, the most common and therefore the industry standard. Their output makes up the largest amount of GenAI images produced.  
Their generation method works with progressively diffusing image samples with Gaussian noise and then reverse that process to generate output images.  
Large and popular Image Generation models like *StableDiffusion*, *Midjourney* as well as *Dall-E3* and *Imagen* are diffusion models.

Invisible watermarking methods of diffusion model images usually alter the frequency domain of the images, during or after the generation process. Therefore this paper concentrates on invisible watermarking methods for images of generative diffusion models that work on the image’s frequency domain.

To provide practical understanding of how image watermarking methods can be evaluated, the paper will look at three different methods on how to invisibly watermark GenAI images by altering the frequency domain.  
The first method is developed by Chen et al. and described in their paper *Image Watermarking of Generative Diffusion Models* (2025). They developed a watermarking method which implements a reconstructable image watermark during the training process of the model.  
The second method by Wei et al from the paper *DiffKGW: Stealthy and Robust Diffusion Model Watermarking* (2026) take on the watermarking method of LLMs by subtly biasing which noise values are sampled at the start of image generation.  
The third method ... (t.b.d.).
All three approaches will be compared by an evaluation set consisting of four aspects:

**Robustness** - The preservation of the watermark against attacks.  
**Capacity** - The amount of information that can be hidden with the watermark.  
**Imperceptibility** - The level of altering of the output image quality, compared to clean images.  
**Implementation effort** - The resources needed to integrate the method into a model.

This comparison is intended to give an overview on how different watermarking strategies for diffusion models working with the frequency domain are discussed, how they differ and what their individual advantages are. Eventually, this paper aims to discuss potential technical obstacles hindering practical implementation of those methods into real-world scenarios, to support ongoing research on invisible watermarking of diffusion model’s output.

---

Note: I wrote my text in Google Docs with Spell and Grammar-Checking activated.  
I will confirm statements like "Diffusion Models have become, next to GANs, the most common" etc. with sources.  
Also, some information is missing and will be added in the end, like the third method or my findings.
