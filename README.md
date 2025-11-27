# LLPatTeraZ
Analytic Sensitivity Estimates for Long-Lived Particles (LLPs) Searches at Tera-Z Factories (FCC-ee, CEPC, LEP3 and LEP-Z)

**Authors:** Marco Drewes, Juraj Klarić, and Yuan-Zhen Li  
**Reference:** [arXiv:25XX.XXXXX](https://arxiv.org/abs/25XX.XXXXX) (New Particles at the Z-Pole: Tera-Z factories as discovery and precision machines)

### Overview
This notebook implements the analytic formulae derived in the associated paper to estimate the sensitivity of future Z-factories (FCC-ee, CEPC, LEP3 and LEP-Z) to Long-Lived Particles (LLPs). 

It explores the dependence of the sensitivity region on:
1.  **Integrated Luminosity:** Total number of produced X-particles ($N_{\rm prod} \propto \epsilon_{\rm prod} \, N_Z$).
2.  **Detector Size:** Evaluated by the fiducial volume defined by length ($l_{cyl}$) and radius ($d_{cyl}$).
3.  **Backgrounds:** LLP searches can often be considered background-free if $\lambda_N$ exceeds some critical value $l_0$.

Two benchmark models are implemented:
* **Heavy Neutral Leptons (HNLs)**
* **Axion-Like Particles (ALPs)** 
