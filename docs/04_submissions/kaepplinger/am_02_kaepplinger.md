---
layout: default
title: Homework
nav_exclude: true
---

### Task 02.01 - Question Development

#### Question 1: What does a practical UE5 → 3DGS pipeline look like, and where does it break?

This is the most hands-on question and probably the one I'm most excited about. The reason I want to dig into this is that a lot of the existing 3DGS literature assumes you're starting from real-world photos or video, which is the original use case the Kerbl et al. paper was built around. But I want to flip that and start from a fully synthetic Unreal Engine scene, render out a structured set of viewpoints, and then run those through a Gaussian Splatting reconstruction pipeline.
UE5 scenes already have perfect geometry, perfect lighting (Lumen), perfect materials. Going from that to a splat representation is kind of a lossy compression, and I want to understand what that loss actually looks like. Is it geometry detail? View-dependent effects? Reflections? Transparent surfaces? Vegetation?

I could answer this by using the the pipeline I already built myself for the First term project. So I could do a structured comparison: render the same UE5 scene at the same camera positions, train a splat from N viewpoints, and measure the visual delta. That's something I can document with actual numbers and screenshots, not just speculation.


#### Question 2: How does a Gaussian splat of a UE5 environment actually perform compared to a baked / lighting-built version of the same scene?

This is the question I want to put real numbers behind. Performance is the part where I think synthetic splats either justify themselves or don't, and it's also the dimension that's least talked about in the existing 3DGS literature, which is mostly focused on reconstruction quality.

What I want to compare is the same UE5 environment in a few different forms:
- the original UE5 scene with Nanite + Lumen
- the same scene with traditional baked lighting
- a Gaussian splat reconstruction of that scene

The reason I think this is worth its own question is that "is it fast" is a much more honest framing than "is it good." A baked lighting build is the realistic competitor here, not the full Nanite+Lumen version, because anyone shipping outside of a high-end PC context is already giving up those features. So the real comparison is splat versus a baked version, and I want to know which one wins on which axis.

#### Question 3: What are the actual use cases for Synthetic splat generation?

This one is more of a survey question and probably ends up being part of the introduction of the paper rather than a main investigation. But I want to be honest that I went into this topic kind of unsure whether it was useful at all. So I think it's worth explicitly mapping out who would actually want this. My current shortlist is:
- training data generation for ML models that need lots of splat data
- Web and mobile deployment where high-end rendering features aren't available
- archival, preview versions of large UE5 scenes for clients or stakeholders
- VR or lightweight visualization where a splat is cheaper to render than a full scene

I'd answer this through a literature and industry-news review more than hands-on experiments, looking at what companies and research groups are actually doing with synthetic splat data right now.

---
  
