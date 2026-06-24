---
layout: default
title: Homework 07
nav_exclude: true
---


**Academic Methodologies**
  
Prof. Dr. Lena Gieseke \| l.gieseke@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF  


## Session 07

The homework should take < 2h. If you need longer, please let me know next class. 


## Statistics (optional)

* Recap [Chapter Statistics](../../02_scripts/am_08_statistics_script.md), if you are interested.

*Submission:* -


## Your Paper


### Task 07.01 - Your Methodology & Paper Structure

It is time to think about how you want to answer the question(s) you are posing and structure your paper.  

Brainstorm which steps you want to apply to get answers to your research question. This task does not aim to find your personal journey of investigation. You should work on defining the approach that you will present in a paper as your methodology (but of course, you can also reflect on what you, personally, need to do to get there). This task does not need to represent formal academic methods for now. It is more about a description of the steps in your own words, structured by the sections of a paper.

Write down your overall paper structure (sections) and bullet points for each section. 
  
*Submission*: 

*paper structure*

1. Introduction
   - **Topic + focus:** theater / live performance
   - **Paper goal:** explore technical trade-offs in motion data representation
   - **Use-Case project** Introduction
   - **research question**
   - **Personal motivation** (?): encourage artists to experiment with low-cost systems as an artistic practice, and show how the results of this use case shape new types of performer awareness

2. Related Work / Scientific Background
   - State of the art motion capture (brief)
   - Availability of open-source tools (TouchDesigner)
   - Embodied performance and real-time feedback (Beira, 2016)
   - Artistic project references on motion–sound interaction + embodiment (e.g. Kojs' *Touch Me Hear*, Hertensteiner's *Sensodance*, Bardainne & Mondot's *Pixel* and *Just Your Shadow*)
   -> Why this matters: who gets access to interactive technology?

3. Use Case: A Low-Cost Motion Tracking Pipeline
   *(Context: collaboration with Filmuniversität Babelsberg, acting class of Prof. Lara Martelli Hisleiter, performer Riccardo Campione)*

    **3.1 Hardware + Software (brief)**
      - XBox Kinect V2, Laptops + Soundsystem
      - Kinect Studio, TouchDesigner (data processing), Ableton for Live (audio)

    **3.2 Pipeline & Data Flow**
      - Motion Data Components: Kinect raw skeletal data
      - Data Processing Components: relational parameter extraction in TouchDesigner 
      - Audio Processing Components: OSC/MIDI mapping to Ableton Live (TD-Ableton package)
      
        VISUAL METHOD: Screenshots

    **3.3 Trade-offs and fail cases**
      - problems: reliance on camera perspective and spatial position
      - absolute Motion Data hard to control
      - fail case: calibration (?)
    
    **3.4 Solution 1: Relational Body Data**
      - Iterative testing cycle with performers (three studio test rounds) + Performer feedback (Riccardo) 
      - relational data via Euclidean distance 
      - more stable values, clearer performability
      - conceptual shift: *body–space relation* to *body–movement relation*

        VISUAL METHOD: Table overview (e.g. hand–hand distance, head–hand distance, body height)
  
    **3.5. Solution 2:  Gesture Detection**
      - Goal: extract specific body states 
      - Implementation: CHOP Execute DAT with Python-based logic
      - Limitations 

        VISUAL METHOD: Table overview: Detected gestures and their sonic role: 
        (hands on chest (intimate state), hands above head (expanded state), crouch (cancels sound))

4. Evaluation & Discussion
   - summary trade-offs + findings (short)
   - Technical limitations of the pipeline (camera dependency, latency, tracking loss) + their artistic consequences
   - Relational vs. absolute data: enabled better body awareness?
   - Assessing the current level of knowledge and the general conditions under which the project progressed

5. Future Work (?)
   - Technical improvements
   - possible prospects for collaboration: future collaboration with acting class

6. Conclusion
   - Summary + Core findings: shift to relational data actively shaped both technical stability and a deeper understanding of embodied interaction
   - Conclusions regarding collaboration with performers (how experimental, performer-driven processes shape technical solutions)
   - Implications for other artists choosing low-cost hardware
   - What this means for accessibility in embodied interaction design
