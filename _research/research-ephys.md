---
title: "Neuro-Mechanical Computational Model of Insect Antennae"
excerpt: "Developed a physics-based model of cockroach antennae (MuJoCo) to study how mechanical deflections generate neural responses for tactile perception. Validated model predictions against extracellular nerve recordings and used spiking neural networks (SNN) to classify tactile features, demonstrating efficient spike-based coding for tactile sensing. <br/><img src='/images/antenna_classification.png' width='80%'>"
permalink: /research/research-ephys
collection: research
date: 2025-9-15
---
Supervisor: Professor [Jean-Michel Mongeau](https://sites.psu.edu/mongeau/PIbio/) 

## 🧠 Neuro-Mechanical Computational Model of Insect Antennae  

This project develops a **neuro-mechanical model of the cockroach antenna** to study how mechanical signals from antennal deflections are transformed into neural activity for tactile feature perception. By coupling physics-based simulations with neural encoding models and electrophysiology experiments, I showed how antenna mechanics shape sparse, spike-based neural codes that enable efficient feature classification.  

---

### 🔹 Research Focus
- Modeled [antenna mechanics as a **multi-joint kinematic chain**](https://lingsheng-meng.github.io/research/research-antenna_mechanics) within [a physics-based simulation environment (**MuJoCo**)](https://lingsheng-meng.github.io/research/research-antenna_classification).  
- Derived **spatiotemporal strain patterns (tactile tensors)** from antennal deflections under different contact conditions.  
- Developed phenomenological models of **campaniform and hair sensilla** to encode mechanical strain into spike trains.  
- Validated model predictions against **extracellular recordings** from cockroach antennal nerves.  
- Trained **spiking neural networks (SNNs)** on simulated spike trains to classify tactile features.  

---

### 🔹 Key Innovations
- Created a **digital twin** of the cockroach antenna linking mechanics to neural encoding.  
- Demonstrated strong correlation between **model-predicted firing activity** and experimental electrophysiology.  
- Achieved efficient tactile feature discrimination using **sparse, spike-based codes**.  

---

### 🔹 Skills & Tools
- **Biomechanics & modeling**: physics-based simulation of antenna dynamics (MuJoCo).  
- **Neural modeling**: phenomenological encoding of mechanosensory units.  
- **Electrophysiology**: extracellular nerve recordings, spike sorting, and validation.  
- **Machine learning**: SNN training and tactile feature classification.  

**Software Used:**  
- [*MuJoCo*](https://mujoco.readthedocs.io/en/stable/overview.html) – physics-based antenna simulation  
- *MATLAB* & *Arduino* & *Basler Carema*- electrophysiology experiment and control
- *OpenEphys* & *NeuroNexus* - ephys dac and CM32 probe 
- [SpikeInterface](https://spikeinterface.readthedocs.io/en/stable/) & [*Kilosort4*](https://kilosort.readthedocs.io/en/latest/) & [*phy*](https://phy.readthedocs.io/en/latest/) – spike sorting of neural recordings
- *Python* – electrophysiology data processing and analysis    
- *Pytorch* & [*SpikingJelly*](https://spikingjelly.readthedocs.io/zh-cn/latest/index.html#index-en) – SNN training and tactile feature classification  

---
