---
layout: default
title: Homework
nav_exclude: true
---

**Academic Methodologies**
  
Prof. Dr. Lena Gieseke \| l.gieseke@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF  

## Your Paper

### Task 01.02 - Topic Brainstorming

Bullet point brainstorming:

* Gaussian Splatting (3DGS / 4DGS)
* Synthetic Gaussian Splats from 3D environments
* Gaussian Splatting in real-time engines (Unreal Engine, Unity)
* USD (Universal Scene Description) as a pipeline standard
* USD interoperability Across different DCC tools
* Hybrid AI in production pipelines
* AI-assisted asset creation (textures, meshes, rigging)
* Neural Radiance Fields (NeRFs) vs. Gaussian Splatting (3Dgs)
* Real-time rendering performance (Nanite, Lumen, hardware limits)
* Text-to-3D / image-to-3D models (MeshyAI...)
* AI in VFX pipelines (de-aging, rotoscoping, background generation)
* LIDAR data and Gaussian Splat reconstruction
* Digital twins


### Task 01.03 - Topic Selection

**Topic 1:** Synthetic Gaussian Splats —> Converting Unreal Engine Environments into 3DGS
What got me thinking about this Topic was actually my First Term Project which I am still working on even after my submission. Gaussian Splatting is usually used to reconstruct real-world scenes from photos, but what if we take a fully built Unreal Engine scene and convert it into a Gaussian Splat? At first that sounded pointless to me, because why would you trade a clean 3D scene for a splat representation? But the benefits can actually be worth it. For example, if you want to deploy a scene in a Web context, or on a platform that doesn't support Nanite and Lumen, a pre-baked splat could be way more portable and performant. Or you might want to generate large amounts of splat data for training other models, and capturing real environments at that scale is just not realistic.  
I'm also more curious about what actually makes a good synthetic Splat workflow, how many camera angles do you need to render out of UE5 to get a decent reconstruction? What gets lost in the process? And is the result actually usable in a real project, or does it just look okay in demos?  

My main questions could be: 
* What are the real use cases for synthetic splat generation? 
* What does a UE5 to 3DGS pipeline look like in practice? 
* What are the trade-offs in quality and performance? 
* Could this become a useful approach for Web deployment or dataset creation?

**Topic 2:** USD as the Future of Production Pipeline Standardization
I got interested in USD mainly because it keeps coming up whenever people talk about the future of 3D pipelines. Everyone is basically pushing it from NVIDIA up to Apple and most VFX Studios.
So there's clearly something to it.  
What I actually want to find out is whether USD really delivers on what it promises, or whether it's more of an industry buzzword at this point. The format is supposed to work as a kind of universal language between different tools. Maya, Houdini, Blender, Unreal, so you don't really lose data every time you move a scene from one DCC (Digital Content Creation) software to another. 
That sounds great, but in practice I found out that it is not that easy for me and a bit messy, especially for smaller scale projects. 
I'm also curious how USD handles newer stuff like Gaussian Splats or AI-generated assets, which don't really fit into the traditional geometry-and-material model that USD was designed around.  

My main questions here could be: 
* What does USD actually solve that formats like FBX or Alembic couldn't? 
* How widely is it really being used, and by whom? 
* What makes it hard to adopt? 

**Topic 3:** Hybrid AI in Production Pipelines. Production Ready?
Lately I installed ComfyUI for a upcoming project and I've been following how AI tools are being used in creative industries. What I find most interesting is not the fully AI-generated stuff as in my opinion it lacks a ton of the things a creative workflow needs, it is the hybrid workflows, where AI takes over specific tasks inside an otherwise normal pipeline. Things like AI upscaling, automated rotoscoping, texture generation, motion capture cleanup, or even whole background generations.  
The question I really want to answer is: which of these tools are actually reliable enough to use in a real production, and which ones still break in ways that cost more time to fix than they save? There's a huge gap between what gets shown in demo videos and what actually holds up when a deadline is involved.

My main questions would be: 
* Which AI-assisted tasks are already considered production-ready? 
* What does a realistic hybrid pipeline look like at a VFX house or game studio? 
* What criteria actually matter when deciding whether to trust a tool? Speed, consistency, cost, control?

---




