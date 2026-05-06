---
layout: default
title: Homework
nav_exclude: true
---

**Academic Methodologies**
  
Prof. Dr. Lena Gieseke \| l.gieseke@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF  


## Session 02

The homework should take < 2h. If you need longer, please let me know next class. 




## Literature

* Read [Chapter 02 - Working With Literature](../../02_scripts/am_02_literature_script.md)



### Task 02.01 - Working With Literature

Have a look at possible tools and setups to organize your collected papers. Chose a setup and reflect on your choice.

*Hint*: Don't forget to use your management system over the course of this term. At the end of the term you have to submit a preview of how your library is filled 😎.

---
*Submission*: 
- #### *Markdown file:* Write the plain text and take notes
Even though I like my setup to be online, sometimes it is good to still have some sort of copy on your hard drive, which is why I write the text in a Markdown file before formatting it in Overleaf.

- #### *Zotero:* Collect sources, organize, BibTex export
After some research, I decided to use Zotero since it is open source and offers PDF annotations, tags, collections, and full-text search. It also has a browser extension, and it seems likely to have long-term support.

- #### *NotebookLM:*  Analyze a smaller set of PDFs
I’ll use NotebookLM to quickly read, compare, and summarize my research sources in one place. It has been recommended to me multiple times by now, so I thought this might be a good possibility to try it.

- #### *Overleaf:* Write and format the paper
Since university is for learning, I feel like I want to try working with LaTeX. I decided to use Overleaf since it is free and allows real-time collaboration as well as version history.

---

## Your Paper

### Task 02.01 - Question Development

Within your chosen topics, describe at least three rough questions that you are considering for your paper. Briefly explain for each, why you are interested in that particular question and how you could answer it.   

As we are still in the brainstorming phase you can also collect and submit more questions or different versions of the same direction. This submission are not the final questions yet.

---

*Submission:* Your collection of questions, and for each their description and your motivation for them.

#### *01 - Real-Time Diffusion / StreamDiffusion*
`I’m thinking about making my second-term project about integrating StreamDiffusion into TouchDesigner. There are already tutorials on how to use different inputs, such as audio. Another idea is to combine my second-term project submission with the Machine Learning class submission and train my own LoRA with the help of ComfyUI. I think this could also be a good topic for my paper, since I want to learn how to write a paper based on my own work. To be safe, I want to phrase the research question in a way that does not depend on having a polished project outcome by the time the paper is due.`

1. What control mechanisms are available for real-time diffusion models in interactive systems, and how does optional model customization influence output stability and coherence? 
  
2. How can real-time diffusion systems be designed for interactive use under technical constraints, and what is the potential impact of optional model customization on system performance and control?

  
**COMMENT LENA**: Already strong questions but still too broad (you probably think more detailled already as your evaluation list shows, but I would also be more specific in the overall questions). E.g. which interactive systems do you mean (an audiovisual performance, right? Then mention that). Stability regarding what and coherence regarding what? Maybe in the direction of "Which control mechanisms do real-time diffusion models offer for a live audiovisual performance, and how does fine-tuning influence temporal stability and aesthetic coherence?" -  "aesthetic coherence" would potentially need further refinement. I assume that the real-time aspect is also crucial here? So maybe you could add "under real-time constraints"?


3. To what extent can StreamDiffusion enable real-time interaction under consumer hardware limitations?

  
**COMMENT LENA**:  Be more specific along the lines of "How does StreamDiffusion perform on consumer-grade hardware, and which optimization capabilities does it offer?" (first analysis, then optimization)

Evaluation of:
- FPS / latency
- resolution
- stability
- responsiveness





#### *03 - AI in Music Recommendations / Radio*


`I'm interested in the shift from simple recommendation algorithms to complex personalized systems, where users increasingly lose overview and control over what is recommended to them. In a discussion with Arthur (mentor of the Sehsüchte Festival team), we explored the idea of a “diversity slider.” This would allow users to select a song or specific element and control whether recommendations closely match its musical features (low diversity) or are based on broader associations, such as songs commonly appearing in the same playlists (high diversity).`

1. Do AI-driven music recommendation systems promote discovery of new music or reinforce existing listening patterns?

 
2. How do AI-based music recommendation systems influence user autonomy and musical diversity in streaming platforms?

3. To what extent does increased personalization in AI music recommendation systems reshape or reduce user control over music consumption, and what alternative approaches can prevent this? 
  
**COMMENT LENA**: 
- Which "AI-based music recommendation systems" do you mean? Do they all work the same? Maybe pick one relevant example to focus on? E.g. "taking X as a case study..."
- How are "new music", "listening patterns", "musical diversity", and "user control over music consumption" defined (when is something different enough to count as "new" or "diverse" and why is a user missing control? We can search for anything we want, no?)? Could you find definitions for these in related work?
- Also overall, I recommend to think about this more descriptive rather than decisive or explanatory, also staying away from questions that can be answered by "yes or no", which then in turn would need some form of proof. 
- I am also wondering how are you planning to answer this? Do you want to conduct your own (user) study? How so? Or based on research works on this?

Some possible refinements:
- Still broader: "Which algorithmic properties characterize AI-based music recommendation systems and how do recommendations relate in terms of genre and artist selections to a user's existing library (and to each other)?" Not yet ideal, just to give you a direction; with "relate to" I am trying to stay away from "different" or "diverse" which would need a definition, while "relate to" is just a description - do you understand what I mean? But I think "diverse" would also work. 
- "Using Spotify as a case study, how diverse are its genre and artist recommendations, and which alternative approaches could broaden recommendation diversity?"



  


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

**Happy Questioning!**
