---

title: Bayesian optimization of electron energy from laser wakefield accelerators
excerpt: "Researchers from the Extreme Light Infrastructure (Czech. Rep.), together with international collaborators from the Kansai Institute for Photon Science (Japan) and the Lawrence Livermore National Laboratory (USA), have demonstrated a powerful new way to optimize laser-driven electron accelerators. Their work, published in Physical Review Accelerators and Beams, shows how advanced machine learning techniques can unlock higher-energy electron beams using compact systems, paving the way for breakthroughs in particle physics, medical imaging, and nuclear research."
toc: true
toc_sticky: true
header:
  teaser: /assets/images/2025-09-12/img_01.jpg
tags: 
  - science
  - physics
  - electron acceleration
  - visualization

---

**Note:** This is a press-release of the paper [P. Valenta et al., Phys. Rev. Accel. Beams 28, 094601 (2025)](https://doi.org/10.1103/knh7-hbr3).
{: .notice--info}

**Tip:** You may find a pre-print of this paper on [arXiv](https://arxiv.org/abs/2501.06069).
{: .notice--success}

Researchers from the [Extreme Light Infrastructure](https://www.eli-beams.eu/) (Czech. Rep.), together with international collaborators from the [Kansai Institute for Photon Science](https://www.qst.go.jp/site/kansai-english/) (Japan) and the [Lawrence Livermore National Laboratory](https://www.llnl.gov/) (USA), have demonstrated a powerful new way to optimize laser-driven electron accelerators. Their work, published in [Physical Review Accelerators and Beams](https://doi.org/10.1103/knh7-hbr3), shows how advanced [machine learning](https://en.wikipedia.org/wiki/Machine_learning) techniques can unlock higher-energy electron beams using compact systems, paving the way for breakthroughs in [particle physics](https://en.wikipedia.org/wiki/Particle_physics), [medical imaging](https://en.wikipedia.org/wiki/Medical_imaging), and [nuclear physics](https://en.wikipedia.org/wiki/Nuclear_physics) research.

### What the work is about

The study focuses on laser wakefield acceleration (LWFA), a cutting-edge method of using ultra-intense laser pulses to generate plasma waves capable of accelerating electrons to near-light speeds. Unlike [conventional accelerators](https://en.wikipedia.org/wiki/Particle_accelerator), which require kilometers of infrastructure, LWFA can achieve similar acceleration over just millimeters. However, the performance of such accelerators depends critically on finding the right combination of laser and plasma parameters — a complex, highly nonlinear challenge. To address this, the team applied [Bayesian optimization](https://en.wikipedia.org/wiki/Bayesian_optimization), a machine learning technique designed to efficiently explore difficult parameter spaces using only a limited number of simulations.

### What the central findings are

By combining Bayesian optimization with high-resolution three-dimensional simulations, the researchers identified the best conditions for maximizing the cut-off energy of accelerated electrons. They examined both self-guided lasers in uniform plasma and guided lasers in preformed plasma channels. Their results show that with just 10 millijoules of laser energy, self-guided setups produced electron beams with cut-off energies of around 70 mega-electronvolts. When plasma channels were used, the energy increased to more than 90 mega-electronvolts. Importantly, analytical models derived in the study confirmed the simulation outcomes and provided scaling laws that can be used to predict performance at higher laser energies. These findings suggest that carefully tuned plasma channels can significantly enhance the acceleration process while maintaining compact system sizes.

<figure id="figure_1" style="max-width: 500px" class="align-center">
  <a href="/assets/images/2025-09-12/img_01.jpg" class="image-popup">
    <img src="/assets/images/2025-09-12/img_01.jpg" alt="Laser wakefield acceleration">
  </a>
  <figcaption>
  <strong>Fig. 1:</strong> The setup of simulation revealing how laser pulse (orange) accelerates electrons (green) using the mechanism of laser wakefield acceleration inside a plasma channel (blue). Taken from <a href="#ref_1">[1]</a>.
  </figcaption>
</figure> 

### Why this work is important

This research demonstrates not only a practical way to optimize compact accelerators, but also provides scaling laws that can be applied to future high-energy laser systems. The results show that laser wakefield accelerators could eventually deliver hundreds of giga-electronvolts of electron energy when powered by large-scale lasers, potentially rivaling [traditional particle accelerators](https://en.wikipedia.org/wiki/Particle_accelerator). Such compact, high-energy accelerators could have transformative applications — from generating [muons](https://en.wikipedia.org/wiki/Muon) for [radiography](https://en.wikipedia.org/wiki/Radiography) and fundamental physics, to producing novel radiation sources for medicine and security screening, and even enabling new studies in [quantum electrodynamics](https://en.wikipedia.org/wiki/Quantum_electrodynamics). By bridging advanced machine learning with state-of-the-art plasma physics, the study takes a decisive step toward making efficient table-top electron accelerators a reality for both research and practical applications worldwide.

**Tip:** Following the principles of reproducible science, the raw data used for this research are openly available on [Zenodo](https://doi.org/10.5281/zenodo.16941557) and the data analysis can be accessed on [GitHub](https://github.com/valenpe7/knh7-hbr3).
{: .notice--success}

### How to cite 

P. Valenta, T. Zh. Esirkepov, J. D. Ludwig, S. C. Wilks, and S. V. Bulanov, “Bayesian optimization of electron energy from laser wakefield accelerators”, *Physical Review Accelerators and Beams* **28**, 094601 (2025).

```bibtex
@article{knh7-hbr3,
  title = {Bayesian optimization of electron energy from laser wakefield accelerators},
  author = {Valenta, P. and Esirkepov, T. Zh. and Ludwig, J. D. and Wilks, S. C. and Bulanov, S. V.},
  journal = {Phys. Rev. Accel. Beams},
  volume = {28},
  issue = {9},
  pages = {094601},
  numpages = {14},
  year = {2025},
  month = {Sep},
  publisher = {American Physical Society},
  doi = {10.1103/knh7-hbr3},
  url = {https://link.aps.org/doi/10.1103/knh7-hbr3}
}
```

### References

[<a id="ref_1">1</a>] P. Valenta, T. Zh. Esirkepov, J. D. Ludwig, S. C. Wilks, and S. V. Bulanov, [“Bayesian optimization of electron energy from laser wakefield accelerators”](https://doi.org/10.1103/knh7-hbr3), *Physical Review Accelerators and Beams* **28**, 094601 (2025).