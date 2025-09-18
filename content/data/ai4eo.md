---
title: "AI for Earth Observation (AI4EO) Conference" 
date: 2025-09-12
lastmod: 2025-09-12
# tags: ["Romance languages","philology","irregular verbs","Portuguese","Italian","French","Spanish","simulations","dataset","python"]
author: ["Arunima Sen"]
description: "My report on the AI4EO conference held in Rennes, France (2025)."
summary: "My report on the AI4EO conference held in Rennes, France (2025)."
editPost:
    URL: "https://github.com/arunima-sen"
    Text: "GitHub repository"
showToc: true
disableAnchoredHeadings: false

---

## Introduction
This month, I had the absolutely wonderful opportunity to attend the Artificial Intelligence for Earth Observation ([AI4EO](https://ai4eo2025.irisa.fr/)) conference in Rennes, the capital city of the French region of Brittany (Bretagne), where I’m spending the second year of my Master’s program. The conference took place over the 11th and the 12th of September, and it included several keynotes, poster presentations, and other oral sessions. 

<img src="/ai4eo.png" alt="AI4EO" width="100%"/>


## Day 1
On Day 1, we began with a keynote from Professor Caroline Gevaert (University of Twente) on *Responsible AI for EO*. She opened by outlining major frameworks and standards for AI ethics, including *UNESCO’s Recommendation on the Ethics of Artificial Intelligence* (2021), *OECD’s AI Principles* (2024), and *the EU AI Act* (2024). She then focused her talk on two of the seven ethical principles in the use of AI: fairness and non-discrimination, and transparency and explainability. 

Some of the questions that stuck with me centred on fairness in geospatial data: how are individual groups represented in the data? I also learned something new that bias can arise not only in measurement, but also in how we define concepts. For example, how exactly do you define poverty? Other sources of bias include deployment bias and automation bias. She also highlighted the regulatory context - explanations should be goal-aware, tailored to non-expert audiences, and transparency should be understood more broadly than within EO considerations alone. Having studied AI ethics and safety during my undergraduate degree, I found myself reflecting on the implications of using AI to address climate change. AI systems that influence human behaviour or guide decision-making can unintentionally reinforce inequalities or overlook the diverse values different communities hold. Even when designed to improve overall welfare, the benefits and harms of such interventions may be unevenly distributed—as it has also historically been—hence potentially exacerbating vulnerabilities. It was a timely reminder of how important it is to consider context, fairness, and transparency when applying AI to very real-world challenges, where decisions can have wide-ranging and sometimes unintended consequences. It made me reflect on the responsibility involved in using AI in EO and climate research, and the importance of thinking carefully about how these tools shape outcomes for different communities. 

The keynote was followed by oral presentations on topics ranging from deep learning for atmospheric data super-resolution to cognitive science-inspired foundation models. Afterwards, I attended another keynote by Bertrand Le Saux on *Destination Earth (DestinE)*, a program creating digital twins of the Earth system. DestinE is structured around two core digital twins: one for climate change adaptation (multi-decadal scale) and another for weather-induced extremes (short-term, days ahead). Since I’m interested in pursuing further studies in Earth system science, I had a chance to chat with him after his keynote about the challenge of capturing fine-scale processes—like convection, land–atmosphere coupling, or urban heat islands—that are localized yet have global consequences. I found myself thinking how DestinE is approaching this without losing computational feasibility at a planetary scale. One of my main takeaways was that digital twins should have three capacities: (1) what now? (monitoring); (2) what then? (prediction); and (3) what if? (scenario testing). 

Day 1 ended with a guided tour of Rennes. The weather was unpredictably rainy—ironically, on the same day we saw posters on quantifying weather uncertainty—but it was still a nice experience. For example, Rennes is famous for its medieval half-timbered houses that lean into one another, especially in squares like Place du Champ-Jacquet. 

<figure style="text-align: center;">
  <img src="/rennes.jpeg" alt="Rennes" style="width:300px; display: block; margin-left: auto; margin-right: auto;">
  <figcaption style="font-weight: normal;">Rennes, France</figcaption>
</figure>

## Day 2
Day 2 began with a keynote from Professor Christian Igel (University of Copenhagen), who shared a range of projects he’s working on under the umbrella of *Machine Learning for Large-Scale Applications*. The project I found most exciting created detailed digital representations of all trees across a country, both forested and non-forested, using deep learning. He also spoke about estimating biomass from LiDAR point clouds with deep regression models, and about combining Sentinel-2 optical imagery with GEDI data to map global vegetation structure worldwide. 

We then moved into the poster sessions, which offered a lot of variety — using panchromatic imagery for spectrally consistent multispectral super-resolution, deep learning fusion of thermal-infrared data for high-resolution land surface temperature monitoring, and the production of vegetation indices from Sentinel-1 SAR images to improve temporal density for early crop monitoring. 

The afternoon continued with the final keynote by Professor Maria Vakalopoulou (CentraleSupélec), who spoke about *Large Foundation Models and their Adaptation to Remote Sensing*. The day concluded with an oral session where presenters covered topics ranging from multimodal text-to-SAR synthesis to simulation-based training for neural mapping of satellite altimetry at a global scale. 

## Wrapping up
The program across the two days was packed with knowledge, and people were incredibly generous in sharing not just their research but also broader ideas about AI for EO. I learned about topics I wouldn’t have encountered otherwise, and even though I don’t start working on my Master’s thesis until next semester, I came away with several exciting ideas and directions to explore. A big thanks to everyone who made the event so engaging! 

