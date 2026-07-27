---
layout: default
title: Homework
nav_exclude: true
---

## Session 07

## Your Paper

# Task 07.01 - My Methodology & Paper Structure

# Paper Structure and Methodology

I want to map where 3D Gaussian Splatting (3DGS) is actually being used along the Virtual Production (VP) pipeline, and then compare the benefits and limitations that come up in the literature with what practitioners told me in my survey.

**Research question:** At which stages of the VP pipeline is 3DGS currently used, which benefits and limitations do practitioners report, and why does adoption drop off the closer you get to final-pixel work?

**My approach (two parts):**
1. A systematic mapping study of recent publications on 3DGS in Virtual Production, which I sort by pipeline stage.
2. A small practitioner survey (n=10 so far) to check whether the literature matches current practice.

**Working title:** *Splats on Set: Mapping the Adoption of 3D Gaussian Splatting along the Virtual Production Pipeline*

---

## Introduction
- First I explain what VP and LED-volume ICVFX are, and why building photoreal environments quickly is such a bottleneck.
- Then I introduce 3DGS (Kerbl et al., 2023): what it is and why it seems like a good fit for VP.
- The gap I found: information about how 3DGS is used is scattered across papers, talks and case studies. As far as I can tell, nobody has mapped it stage by stage or checked it against what people actually do on set.
- My contributions:
  + a stage-by-stage map of where 3DGS is used
  + overview of benefits and limitations per stage
  + a comparison of this literature with current on-set practice, based on an expert survey of VP/VFX practitioners

## Related Work
- Basics of 3DGS and how it differs from photogrammetry and NeRF.
- Existing overviews of VP / ICVFX and the write-ups about 3DGS in production that already exist.
- Again the gap: it is a hot topic right now, but nobody has really mapped it onto the pipeline yet.

## Methodology

**Part 1: Systematic mapping**
- As a framework I use the three classic VP phases as the backbone, with finer stages inside them:
  - Pre-production: previs, tech-vis, digital scouting, environment/backdrop creation.
  - Production: final-pixel on the LED volume (ICVFX), greenscreen.
  - Post-production: compositing, cleanup, asset reuse.
- I define inclusion criteria and list my sources with release dates.
- For every paper I extract the same things: which stages it actually touches and which benefits it limitations it mentions.

**Part 2: Practitioner survey**
- Target group: VP / VFX practitioners. This is a convenience sample, currently n=10, so I have to be careful with how much I read into it.
- The survey is a short online questionnaire asking about their role, their experience, which stages they have used 3DGS in, how ready they think it is per stage (1 to 5), plus benefits, limitations and a few open questions where they can write freely.

## Results
- The literature map on both levels (phase + sub-stage).
- The readiness gradient I found: high in pre-production, low at final-pixel.
- Benefits that keep coming up: fast and cheap capture, realism, real-time playback, fast iteration.
- Limitations that keep coming up: relighting, editability/art-direction, moving content, engine integration, artifacts.
- Then literature and survey side by side: where they agree and where they diverge.

## Discussion
- Where they agree: 3DGS is strong early in the pipeline, final-pixel is the hard part, and relighting and dynamic content are real blockers.
- What practice adds: editability and art-direction came up as a top blocker in my survey, and I feel like the papers underplay this. A splat is quick to make but "sticky" to change afterwards.
- An interesting tension: my participants rated 3DGS low for final-pixel today, but almost all of them still expect it to become standard within two years.
- Limitations of my study: n=10, self-selected, mostly supervisors, and only 4 of them have actually shipped 3DGS on a real production. So my results are indicative, not conclusive.

## Future Work
- A larger and more balanced survey, maybe with interviews on top.
- It would also be interesting to re-run the mapping in 1-2 years and see how things have moved.

## Conclusion
- Answer the research question stage by stage and state honestly where 3DGS stands right now.
  
--- 

## AI Notice

AI helped me map out the rough structure of the paper and correct my writing. The rest was done by myself.