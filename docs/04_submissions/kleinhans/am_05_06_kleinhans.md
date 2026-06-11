---
layout: default
title: Homework 05 + 06
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
  
  

*Submission:* Your description.


Data in Motion. Exploring possibilities and trade-offs of accessible low-budget motion tracking systems in the context of real-time performance.

Professional motion tracking, whether in film or live performances, typically relies on expensive, complex infrastructure - mechanism that limits who can engage in embodied interaction design. On the other hand, open-source tools and affordable sensors (depth cameras, Kinect) have increasingly become alternatives for artists working in embodied interaction. Rather than viewing low-cost systems as alternatives or compromises, this paper treats them as deliberate artistic choices. Choosing accsessibility and affordance can be understood as an artistic practice in itself, especially with regard to the increasing monetization of access to digital resources in the tech industry.
An artistic approach of motion tracking can be framed as embodied artistic practice, where the human body is not just an input source but the primary site of expression. Technology thus can be viewed as an extension and should not only become a prerequisite. Through the discussion in this paper, I aim to explore the tension between embodied, intuitive physical work and technical constraints required for a functioning, reliable system.

Based on a use case from a collaboration between actors and creative technology students at Filmuniversity Babelsberg, the paper explores the creative and technical trade-offs when designing low-cost sensor pipelines. Concretely, a relational body data processing strategy in TouchDesigner via a Kinect motion tracking. The study examines relational body data as a stability strategy, code-based gesture detection for clarity, and the performer's awareness of system responsiveness. 


*references:* (to be added)

Beira, J. F. (2016). Projection mapping and sensing bodies: A study in interactive 
dance performance [Doctoral dissertation, University of Texas at Austin]. 
https://repositories.lib.utexas.edu/items/8107644f-7c23-41bc-955e-c58fd95a1fe7


---

**COMMENT LENA**: 
While your text is very interesting, and the first part gives a great motivation for your work, be careful not to write a manifesto but a paper. Each claim must be well-grounded. The connection between "choosing accessibility and affordance can be understood as an artistic practice" (which as of now is only a claim from you!) and "the tension between embodied, intuitive physical work and technical constraints required for a functioning, reliable system" needs to be stronger to make sense. Currently it almost reads like two separate papers. Maybe you could tie those two points together in the direction of "cheap hardware (by choice) -> more technical problems"? 

Also, I don't quite understand what you mean by "The study examines relational body data as a stability strategy, code-based gesture detection for clarity, and the performer's awareness of system responsiveness." Please explain these aspects further and how they are a valid representation for "explore[ing] the creative and technical trade-offs".

Overall, think one more time about which question you are answering. The text has a motivation and a vague aim ("explore the tension") but then lacks a bit of clarity.

Obviously you need more references :D

---


*Thank you for the feedback! I tried to shape it up and I feel more focussed now. During the revision I was just wondering if I can write about my system as an alternative to professional motion tracking systems since I never worked with them by myself (except the XSens Suite), so I will mostly base my knowledge on references. 
I would really appreciate it if you could include this question in your next feedback (if there is going to be any) :)*


**Description Revision**

Data in Motion - Exploring possibilities and trade-offs of accessible low-budget motion tracking systems in the context of real-time performance.

Professional motion tracking, whether in film or live performances, typically relies on expensive, complex infrastructure - requirements that limit who can engage in embodied interaction design. On the other hand, open-source tools and affordable sensors (depth cameras, Kinect) have increasingly become alternatives for artists working in embodied interaction, especially with regard to the increasing monetization of access to digital resources in the tech industry. 

Based on a use case from a collaboration between actors and creative technology students at Filmuniversity Babelsberg, the paper explores the technical challenges and trade-offs when designing low-cost sensor pipelines. Concretely, a motion-to-sound system with relational body data processing strategy in TouchDesigner via a Kinect motion tracking. The study of this pipeline demonstrates the technical problems during the development process as also in the final pipeline. The technical constraints, particularly instability in data tracking, processing and gesture detection, forced me to design the pipeline differently. As a solution the system works with relational data mapping, which means that the body as the central measurement point takes on a more central role. The performer experienced this as more intuitive and responsive way of expression.

As a further conclusion drawn from the findings of this project, I would like to address the question of how low-cost constraints doesn't have to be seen as a limitation and can enable new types of performer awareness. 

---

**references:**

*performance related:*

Beira, J. F. (2016). Projection mapping and sensing bodies: A study in interactive 
dance performance [Doctoral dissertation, University of Texas at Austin]. 
https://repositories.lib.utexas.edu/items/8107644f-7c23-41bc-955e-c58fd95a1fe7


*low-cost vs. professional systems:*

Xie, L., Kumar, M., Cao, Y., Gracanin, D., & Quek, F. (n.d.). Data-driven Motion Estimation with Low-Cost Sensors. Virginia Polytechnic Institute and State University.
[https://ieeexplore.ieee.org/abstract/document/4743492](https://d1wqtxts1xzle7.cloudfront.net/81117536/9ccbc82f6d4d043486299a883b909a991b25-libre.pdf?1645420663=&response-content-disposition=inline%3B+filename%3DData_Driven_Motion_Estimation_With_Low_C.pdf&Expires=1781163144&Signature=gb8dB~xT7wgms9myw1g-xPd~AL5RRavRWS~dOyfzZG1XNdE~QVnBWexu3QJEsbuY6d3hKtoGKk6cgPBasqJXUxgxfuGjfoNPBpnq7-wvDmMVO96l-SlsiDJf7sNq79QaloVY4jFhxW6UNQA4B4IhdJ7impXXLSemU6PA9whPccam2jmXMfbRtnmmqBM01Bb~WWCGKy~na9QdaAgXfs6wWL2rIgK4l2QjVGt1yJLIEbMOMVFuC2txDdbb424Laa8A5AlHXhaBSVgOBfgEoC3s3plipjYptKQVRpOqTeVRaFbymP-X2KsrP-d~dQhPn2GOu3qhyOPREq5CXlT3F0sHKA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)


López Pérez, D., Laudańska, Z., Radkowska, A., Babis, K., Kozioł, A., & Tomalski, P. (n.d.). Do we need expensive equipment to quantify infants' movement? A cross-validation study between computer vision methods and sensor data. Institute of Psychology, Polish Academy of Sciences. 
https://babylab.edu.pl/wp-content/uploads/2025/12/Lopez-Perez-et-al-2021_IEEE_ICDL.pdf

*motion capture:*
Wibowo, M. C., Nugroho, S., & Wibowo, A. (2024). The Use of Motion Capture Technology in 3D Animation. Journal of University of Bahrain, 5(2), 976–990.
https://pdfs.semanticscholar.org/9514/28e966feece961d7100448d0caf17a8b93ec.pdf

(*not open accessibe, but I would like to get an access to the paper:*)

Bodenheimer, B., Rose, C., Rosenthal, S., & Pella, J. (n.d.). The Process of Motion Capture: Dealing with the Data. Microsoft Research.
https://link.springer.com/chapter/10.1007/978-3-7091-6874-5_1
