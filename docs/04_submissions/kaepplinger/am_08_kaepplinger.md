---
layout: default
title: Homework
nav_exclude: true
---


## Session 08


## Academic Writing

## Your Paper


### Task 08.01 - Introduction

# Introduction (Draft)

# 1. Introduction

Virtual Production (VP) has changed how films and series get made (LG: says who? This is a strong statement, either soften it, or have a reference). Instead of shooting actors on greenscreen and adding the environment months later in post, productions increasingly place actors inside LED volumes that display that environment in real time, a technique known as In-Camera Visual Effects (ICVFX). ICVFX is the most visible part of VP, but not all of it.
VP is an umbrella term for techniques that let filmmakers interact with digital content as they would on a traditional shoot (Netflix, Inc., n.d.), from world capture (location and set scanning) to visualization (previs, techvis, virtual scouting, virtual camera). (LG: is this really the definition of VP? Do you have a reference? If not soften it, e.g. "VP can be understood as...")

Nearly all of these (LG: what?) rely on digital 3D environments (LG: how so?), and the demands on them (LG: in quality?) rise the closer they get to the final image. For example, a previs scene may be rough (LG: means what?), but content that ends up in the final pixel, whether on an LED wall (which must run in real time) or composited behind actors, must be photoreal (LG: to be combined with shot footage).
Building such environments with traditional modeling and photogrammetry pipelines is slow and expensive, making environment creation a central bottleneck of VP.

3D Gaussian Splatting (3DGS) (Kerbl et al., 2023) appears to address exactly this issue (LG: which one?).
It can reconstruct a photorealistic 3D scene that renders in real time from ordinary camera or drone footage, or even from rendered CG images. The capturing process is faster and more forgiving (LG: means what?) than mesh-based photogrammetry, and playback is fast enough for real-time rendering.

Since then the industry has taken notice.
Rodeo FX, for example, converted its Imperial Palace set from "Dune: Prophecy" into splats for real-time virtual scouting (Hery, 2025), a first study shows it outperforming traditional capture methods for virtual backdrops in both capture effort and realism (Haslbauer et al., 2025), and interviews with filmmaking professionals confirm strong interest in Gaussian-based environments for previsualization (Leininger et al., 2025).

While (LG: using) splats spread quickly through scouting, previs, and asset creation, open problems in relighting (Azzarelli et al., 2026; Gao et al., 2024; Bi et al., 2024), dynamic range (Zhang et al., 2025), and moving content (Belemkoabga et al., 2025) still stand between them and final-pixel use. What is known is scattered across technical papers, industry talks, and case studies. No published work has yet mapped where splats stand stage by stage (LG: what do you mean by stage? Steps?) along the VP pipeline or checked it against what practitioners actually do on set.

This paper addresses that gap. The research question is: At which stages of the VP pipeline is 3DGS currently used, which benefits and limitations do practitioners report, and why does adoption drop off toward final-pixel work? The scope is capture-based 3DGS (splats from real camera or drone footage), the dominant workflow (LG: says who?). The approach combines a systematic mapping of academic and industry publications, sorted into a pipeline framework of pre-production, production, and post-production, with a small expert survey of VP/VFX practitioners that tests how far the literature matches current on-set practice.

The contributions are:
+ a stage-by-stage map of where 3DGS is used along the VP pipeline
+ a overviw of the benefits and limitations per stage
+ a comparison of this literature view with current on-set practice, based on an expert survey of VP/VFX practitioners

  
LG:
This introduction is already very strong, you write and "tell the story" very well! I was overly critical above as a demonstration of potential points for improvement. In general keep in mind to be as precise as possible and not to make big statements "without proof". Also, your plan might be too much. You could consider skipping the expert survey, if that would still work with your story. Just reflect on work load and text limits and potentially adjust along the way. That being said you can confidently work on the whole paper now!

---

#  Question:
In my introduction I write that 3DGS can reconstruct scenes "from ordinary camera or drone footage, or even from rendered CG images", citing Kerbl et al. (2023). 
But Kerbl really only demonstrates reconstruction from photos and videos.
The CG-render case comes from the Rodeo FX example (Hery, 2025) that I cite two sentences later. Is it acceptable to keep the sentence as it is, since the supporting citation follows shortly after it, or should I move the CG Render claim into the "Hery" sentence?  
  
LG:
I would just add or move citations. You can use them multiple times. E.g.:  
It can reconstruct a photorealistic 3D scene that renders in real time from ordinary camera or drone footage (Kerbl et al., 2023), or even from rendered CG images (Hery, 2025).


---