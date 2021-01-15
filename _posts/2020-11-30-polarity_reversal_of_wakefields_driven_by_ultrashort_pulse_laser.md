---

title: Polarity reversal of wakefields driven by ultrashort pulse laser
excerpt: "In this work, a team of researchers from ELI Beamlines (Czech Rep.), Kansai Photon Science Institute (Japan), and TAE Technologies (USA) reveal that the wakefield, being excited by an ultrashort laser pulse in plasma, periodically reverses its polarity. As shown by the analytical model and computer simulation, the wakefield polarity reversal is caused by the dispersion and the corresponding difference between the propagation speed of the carrier and the envelope of the driving pulse."
toc: true
toc_sticky: true
header:
  teaser: /assets/images/2020-11-30/img_01.jpg
tags: 
  - science
  - physics

---

**Note:** This is a copy of press-release of the paper by [P. Valenta et al., Phys. Rev. E 102, 053216 (2020)](https://doi.org/10.1103/PhysRevE.102.053216) which I co-authored. You can find the original article [here](https://www.eli-beams.eu/news-and-events/media-news-and-events/article-polarity-reversal-of-wakefields-driven-by-ultrashort-pulse-laser/).
{: .notice--info}

In this work, a team of researchers from [ELI Beamlines](https://www.eli-beams.eu/) (Czech Rep.), [Kansai Photon Science Institute](https://www.qst.go.jp/site/kansai-english/) (Japan), and [TAE Technologies](https://tae.com/) (USA) reveal that the wakefield, being excited by an ultrashort laser pulse in plasma, periodically reverses its polarity. As shown by the analytical model and computer simulation, the wakefield polarity reversal is caused by the dispersion and the corresponding difference between the propagation speed of the carrier and the envelope of the driving pulse. The discovery of this phenomenon will be helpful in controlling the electron beam parameters, particularly in experiments carried out with high-repetition-rate laser systems, according to a paper recently published in [Physical Review E](https://doi.org/10.1103/PhysRevE.102.053216).

### Laser-wakefield acceleration

[Laser-wakefield acceleration](https://en.wikipedia.org/wiki/Plasma_acceleration) (LWFA) is a well-established technique for producing high-energy electrons in plasma. Within the framework of this concept, a relativistically intense laser pulse propagating through underdense plasma induces a strong electric field (wakefield) which, in turn, accelerates duly injected electrons. In fact, ionized plasmas can sustain electric fields several orders of magnitude larger than conventional radio-frequency technology, allowing one to reduce substantially the acceleration length. This paves a way towards a new generation of compact and cost-effective electron accelerators.

Over the past few decades, the quality of electron beams accelerated via LWFA has rapidly evolved mainly due to the advances in technology and better understanding of the underlying physics. As of 2020, LWFA has demonstrated (although not simultaneously) the capability to produce electron beams at the multi-GeV energy scale with a relative energy spread of a few percent, a few fs duration, and hundreds of pC of charge. These achievements make LWFA increasingly attractive for a wide range of multidisciplinary experiments and applications (e.g., radiography, radiotherapy, and radiolysis).

### Reversal of wakefield polarity

The authors show that the novel phenomenon of the wakefield polarity reversal (see <a href="#figure_1">Figure 1</a>) occurs on spatial scales shorter than the dephasing length (i.e., the distance over which the electrons outrun the accelerating field) and, therefore, significantly affects the energies of accelerated electrons. In the nonlinear regime, however, there may exist a case for which the polarity reversal length is equal to the dephasing length. In such a case, the dephasing limit is overcome and the electrons are accelerated until the energy of the driver pulse depletes. The study presented in this work is important for the LWFA under the conditions relevant to present-day high-repetition-rate lasers, where the results obtained are useful for better controlling of the parameters of accelerated electron beams (e.g., by adjusting the initial phase of the driver or by controlling the phase of the electron injection).

<figure id="figure_1" style="max-width: 500px" class="align-center">
  <a href="/assets/images/2020-11-30/img_01.jpg" class="image-popup">
    <img src="/assets/images/2020-11-30/img_01.jpg" alt="Wakefield polarity reversal">
  </a>
  <figcaption>
  <strong>Fig. 1:</strong> Electron phase space (black), the on-axis wakefield (red), and the on-axis driver electric field (blue), at four successive time instants of the three-dimensional particle-in-cell simulation. The corresponding inset shows the energy spectrum of electrons located in the first wake wave bucket behind the driver pulse. For the first wake wave bucket, the accelerating and decelerating phases of the wakefield are highlighted by green and red stripes, respectively. The longitudinal coordinate at which the wakefield polarity reversal occurs is marked by the dashed line. Taken from P. Valenta et al., Phys. Rev. E 102, 053216 (2020).
  </figcaption>
</figure> 

**Tip:** Following the principles of reproducible science, the raw data used for our research has been uploaded to [Zenodo](https://zenodo.org/record/4298843#.YAIlVeieGUl) and the data analysis can be found on [GitHub](https://github.com/valenpe7/wakefield_polarity_reversal).
{: .notice--success}

### How to cite 

P. Valenta, T. Zh. Esirkepov, J. K. Koga, A. Nečas, G. M. Grittani, C. M. Lazzarini, O. Klimo, G. Korn, and S. V. Bulanov, “Polarity reversal of wakefields driven by ultrashort pulse laser”, *Physical Review E* **102**, 053216 (2020).

```
@article{PhysRevE.102.053216,
  title = {Polarity reversal of wakefields driven by ultrashort pulse laser},
  author = {Valenta, P. and Esirkepov, T. Zh. and Koga, J. K. and Ne\ifmmode \check{c}\else \v{c}\fi{}as, A. and Grittani, G. M. and Lazzarini, C. M. and Klimo, O. and Korn, G. and Bulanov, S. V.},
  journal = {Phys. Rev. E},
  volume = {102},
  issue = {5},
  pages = {053216},
  numpages = {5},
  year = {2020},
  month = {Nov},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevE.102.053216},
  url = {https://link.aps.org/doi/10.1103/PhysRevE.102.053216}
}
```