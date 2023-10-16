---
title: "Reconstructing Pediatric-Fall-Induced Head Injuries with Subject-Specific Finite Element Head Models"
collection: research
excerpt: "Reconstructions of head-injury events using computational models<br/><img src='/images/UMTRI.png'>"
permalink: /research/research-0
date: 2019-12-15
---

As a student intern, I have been involved in addressing the critical issue of pediatric head/brain injuries research supported by National Institute of Justice (NIJ). These injuries are a primary cause of pediatric mortality, disability, and healthcare expenses. Unfortunately, there is a significant lack of anthropometric and mechanical response data specific to pediatric heads. To tackle this problem, I utilized subject-specific finite element (FE) models to undertake the reconstruction of head injury events. These particular models, which focused on the statistical geometry of the pediatric skull for children aged between 0 and 3 years, were interconnected with a baseline FE head model. This morphing based on the radial basis function (RBF) allowed for the rapid transformation of the base model into various geometries that accurately represented children of different ages and sizes. Following the successful reconstruction of 29 head injury events, I proceeded to employ logistic regression in order to develop the pediatric skull and brain injury risk curves. These risk curves will improve the assessment of pediatric head injuries arising from falls and incidents of child abuse.   
During this research, I carried out the following tasks:  
* Utilized [Mimics](https://www.materialise.com/en/healthcare/mimics-innovation-suite/mimics) software to generate 3 subject-specific CT-derived geometric models and finite element models.
* Employed 29 reconstructed investigative fall data to derive injury predictive parameters using FEA in [LS-DYNA (Ansys)](https://www.ansys.com/products/structures/ansys-ls-dyna).
* Conducted data analysis (logistic regression) on the simulation data to develop the injury risk curves.
* Published a conference paper in [IRCOBI 2020](http://www.ircobi.org/wordpress/downloads/irc20-asia/pdf-files/2046a.pdf) as the second author.
 
![An example of pediatric fall reconstructions using subject-specific FE head models](../images/UMTRI.png)  
*An example of pediatric fall reconstructions using subject-specific FE head models*
