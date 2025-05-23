---
title: "BIP: Quantifying Vulnerability to Natural Hazards" 
date: 2025-04-15
lastmod: 2025-04-15
# tags: ["Romance languages","philology","irregular verbs","Portuguese","Italian","French","Spanish","simulations","dataset","python"]
author: ["Arunima Sen"]
description: "My reflections on the Blended Intensive Program (BIP) I attended from the University of Bucharest!"
summary: "My reflections on the Blended Intensive Program (BIP) I attended from the University of Bucharest!"
editPost:
    URL: "https://github.com/arunima-sen"
    Text: "GitHub repository"
showToc: true
disableAnchoredHeadings: false

---

## Introduction
I participated in a *Blended Intensive Program (BIP)* titled _“Quantifying Vulnerability to Natural Hazards in Changing Climate Patterns: New Perspectives and Methods”_, hosted by the University of Bucharest. My motivation to join this program was to deepen my understanding of the risks and challenges posed by human actions on the environment, and to explore how climate change is increasing human vulnerability.  The BIP explored and examined the interconnected relationships between susceptibility, hazard, impact, vulnerability, and resilience in a changing world. 

![BIP](/BIP/bg.jpg)


The program ran from March 2025 to April 2025 and included two components: a virtual phase, where I attended a series of lectures, and a physical mobility phase held in Romania’s Vrancea seismic region. The online lectures covered a broad range of topics, including:
- Vulnerability in the age of the anthropocene 
- State of the climate 
- Sea level changes 
- Social vulnerability in coastal environments 
- Climatic and tectonic signals in landscape evolution 
- Changing geohazards 
- Dynamics of fragile coupled landscapes 
- Increasing resilience 

The physical component of the program consisted of field visits across the Subcarpathians and Carpathians, where we observed various landslide types, seismic risk factors, and community vulnerabilities in context - these visits complemented the theoretical knowledge from the lectures in real-world examples 😁

## Physical mobility in Romania
### Day 1 (April 7, 2025)
- We began the day in Bucharest, walking through central neighborhoods to observe how the city is managing seismic risk. Some buildings had been retrofitted to improve resilience, while others had clearly fallen into disrepair and would be at high risk of collapse in the event of another major earthquake like the one in 1977
- The contrast between upgraded and deteriorating structures highlighted issues of uneven risk reduction, as well as the influence of policy, investment, and maintenance gaps on urban vulnerability. Later in the day, we traveled by bus to Pătârlagele to begin the field visits in the Subcarpathian region!

<figure style="text-align: center;">
  <img src="/BIP/bipDay1.jpeg" alt="Day 1" style="width:300px; display: block; margin-left: auto; margin-right: auto;">
  <figcaption style="font-weight: normal;">My classmate Ola in Bucharest :)</figcaption>
</figure>



### Day 2 (April 8, 2025)
- In the Subcarpathians, we examined shallow landslides in the molasse terrain, where low-magnitude, high-frequency failures are common. Vegetation, especially moisture-loving species, helped identify unstable slopes. These polycyclic landslides, often reactivated, pose ongoing risks to agriculture and rural livelihoods
- At Oras Pătârlagele, we saw a complex landslide system shaped by mudflows and rotational slides. The visit highlighted the importance of long-term landslide inventories (30+ years) for climate-linked modeling, and how land-use change and property rights reform could support adaptation in high-risk zones
- In the Carpathians flysch environment in Siriu, we observed deep-seated landslides prone to plastic deformation during earthquakes, increasing rockslide risk. Narrow roads along unstable slopes and valley communities below are especially exposed to cascading hazards like landslides and flooding
- A locally built non-concrete dam served as an example of place-based adaptation to seismic threats. It underscored how local infrastructure decisions can play a key role in mitigating multi-hazard risks


<div class="carousel-container">
  <button class="carousel-button" onclick="changeSlide(-1)">&#10094;</button>
  <img id="carousel-image" src="/BIP/bipDay2_1.jpeg" alt="Day 2" class="carousel-img">
  <button class="carousel-button" onclick="changeSlide(1)">&#10095;</button>
</div>

<script>
  const images = [
    "/BIP/bipDay2_1.jpeg",
    "/BIP/bipDay2_2.jpg",
    "/BIP/bipDay2_3.jpeg",
    "/BIP/bipDay2_4.jpg",
    "/BIP/bipDay2_5.jpg"
  ];
  let currentIndex = 0;
  function changeSlide(direction) {
    currentIndex = (currentIndex + direction + images.length) % images.length;
    document.getElementById("carousel-image").src = images[currentIndex];
  }
</script>

<style>
.carousel-container {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 1rem;
  margin: 1rem 0;
}
.carousel-img {
  max-height: 400px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}
.carousel-button {
  background-color: transparent;
  border: none;
  font-size: 2rem;
  cursor: pointer;
  color: #333;
}
.carousel-button:hover {
  color: #007acc;
}
</style>


### Day 3 (April 9, 2025)
- In Nehoiu, we explored the Balta rockslide site, an example of earthquake-induced slope failure with scarps up to 90 meters high. The scale of displacement pointed to a high-magnitude trigger, likely seismic, supported by geological features like slickensides and fault-related deformation
- Using tools like dendrogeomorphology and lichen dating, we examined how the slope evolved over time. Evidence such as tilted trees and secondary scarps suggested ongoing instability and reactivation, making this a key site for understanding long-term hazard dynamics
- We also learned how lateral river erosion can trigger landslides that block valleys, creating natural dams that may later fail and generate dangerous outburst floods, highlighting the multihazard nature of this landscape
- Vulnerabilities in the area include modern housing placed on unstable slopes and narrow valley settlements directly in the path of potential mass movements. We saw how traditional, lightweight construction methods offer a locally adapted response to the instability
- Later in Chirlești, we visited a site affected by rainfall-triggered earthflows. The movement here was slow but destructive, with plastic and viscous soil behavior leading to damage to buildings, road blockages, and even indirect fatalities
- Poor drainage and infrastructure positioned at the base of unstable slopes made the community especially vulnerable. Adaptation strategies included improving drainage, reforesting slopes, and setting up early warning systems to reduce future risk

<div class="carousel-container">
  <button class="carousel-button" onclick="changeSlide3(-1)">&#10094;</button>
  <img id="carousel-image-3" src="/BIP/bipDay3_1.jpeg" alt="Day 3" class="carousel-img">
  <button class="carousel-button" onclick="changeSlide3(1)">&#10095;</button>
</div>

<script>
  const images3 = [
    "/BIP/bipDay3_1.jpeg",
    "/BIP/bipDay3_2.jpg",
    "/BIP/bipDay3_3.png"
  ];
  let currentIndex3 = 0;
  function changeSlide3(direction) {
    currentIndex3 = (currentIndex3 + direction + images3.length) % images3.length;
    document.getElementById("carousel-image-3").src = images3[currentIndex3];
  }
</script>


### Day 4 (April 10, 2025)
- In Valea Lupului, we walked through a rural area where both social and physical vulnerabilities were visible. The condition and design of homes reflected the aging population—particularly older women—who are especially exposed due to limited access to social services
- We noted how solar panels offer a form of independence from state systems, but also introduce risks; in the event of failure, there’s no reliable backup since the local grid isn’t well connected
- Later, at the mud volcanoes (Vulcanii Noroioși) in Buzău, we discussed disaster risk reduction in protected areas. While there’s no direct exposure to communities at the site, the volatile landscape is vulnerable to wildfires and intense rainfall, which can affect infrastructure and limit tourism
- Lack of proper drainage systems and poor road access increase the risk for nearby areas. In surrounding ethnic minority communities, vulnerabilities are higher because homes are often on unstable slopes, and residents are usually last to receive emergency support
- Adaptation in these areas focuses on basic infrastructure improvements, especially roads and drainage, to reduce everyday risk and support long-term resilience
<div class="carousel-container">
  <button class="carousel-button" onclick="changeSlide4(-1)">&#10094;</button>
  <img id="carousel-image-4" src="/BIP/bipDay4_1.jpg" alt="Day 4" class="carousel-img">
  <button class="carousel-button" onclick="changeSlide4(1)">&#10095;</button>
</div>

<script>
  const images4 = [
    "/BIP/bipDay4_1.jpg",
    "/BIP/bipDay4_2.png",
    "/BIP/bipDay4_3.png"
  ];
  let currentIndex4 = 0;
  function changeSlide4(direction) {
    currentIndex4 = (currentIndex4 + direction + images4.length) % images4.length;
    document.getElementById("carousel-image-4").src = images4[currentIndex4];
  }
</script>


### Impact chain
During our lab sessions, we worked on developing an impact chain as a way to better understand and organize the drivers and consequences of disasters. The exercise focused on how to structure, visualize, and use information to clarify both the _what_ and the _why_ of an event. My partner [M. Fedyszyn](https://maria-anna-gis.github.io/) and I created an impact chain on landslides, incorporating both classical and enhanced multi-hazard approaches. It helped us break down the complex interactions between physical triggers, exposed elements, vulnerabilities, and resulting impacts in a systemic, nice-to-see way: 


![Impact chain](/BIP/impact_chain.png)

<!-- <img src="/BIP/impact_chain.png" alt="Impact chain style="max-width: 100%; height: auto; border-radius: 10px;"> -->




## Final thoughts
This BIP made it clear that addressing vulnerability is not just a technical or scientific task, but also evidently a deeply social one. To reduce disparities in exposure and impact, it’s essential to work across silos, by that I mean to say collaboration among scientists, policymakers, and local communities is key to developing responses that are both effective and equitable. Vulnerability often amplifies even small hazards, so avoiding new risk means building smarter, planning more inclusively, and making fairness a central principle. 

This program was exactly the kind of experience I had hoped for in my Master’s studies. It gave me the opportunity to connect theory with practice and to observe firsthand how the physical processes shaping the Earth interact with people and ecosystems. I hope to carry these questions forward into my PhD studies, examining the intersections of geophysical hazards, climate change, and societal dynamics in shaping both risk and resilience in different contexts. 

![Group photo](/BIP/bip_grp.jpg)