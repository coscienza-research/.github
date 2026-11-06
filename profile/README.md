<div align="center">

# Scuderia "Cò'Scienza" 🧠⚛️

### Theoretical Physics of Disordered Systems & Emergent Neural Architectures
**Sapienza University of Rome** · *Department of Basic and Applied Sciences for Engineering (SBAI)* & *Department of Mathematics "Guido Castelnuovo"*  
*In scientific collaboration with INFN · CNR-Nanotec · GNFM–INdAM*

<p align="center">
  <a href="https://www.uniroma1.it"><img src="https://img.shields.io/badge/Sapienza_University_of_Rome-822433?style=flat-square&logo=academia&logoColor=white" alt="Sapienza University of Rome"></a>
  <a href="https://www.sbai.uniroma1.it/"><img src="https://img.shields.io/badge/SBAI_Department-Engineering_Sciences-822433?style=flat-square" alt="Sapienza SBAI"></a>
  <a href="https://www.mat.uniroma1.it/"><img src="https://img.shields.io/badge/Castelnuovo-Department_of_Mathematics-822433?style=flat-square" alt="Sapienza Mathematics"></a>
  <a href="https://www.researchgate.net/lab/Scuderia-CoScienza-Adriano-Barra"><img src="https://img.shields.io/badge/ResearchGate-Scuderia_Cò'Scienza-00CCBB?style=flat-square&logo=researchgate&logoColor=white" alt="ResearchGate Lab"></a>
  <a href="https://pytorch.org/"><img src="https://img.shields.io/badge/PyTorch-Scientific_Computing-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License: MIT"></a>
  <a href="https://github.com/coscienza-research"><img src="https://img.shields.io/badge/Location-Rome%2C_Italy-darkgreen?style=flat-square" alt="Location"></a>
</p>

</div>

---

## 🔬 About Our Laboratory

Welcome to the official GitHub organization of **Scuderia "Cò'Scienza"** (also known as the *Agliari–Barra Laboratory*), an international theoretical and computational research group based at **Sapienza University of Rome**.

Rooted in the renowned Roman tradition of the **Statistical Mechanics of Disordered Systems** (the spin-glass paradigm and replica symmetry breaking), our laboratory bridges mathematical physics, analytical mechanics, high-dimensional probability, and large-scale high-performance computing. 

Our core scientific mission is to rigorously decipher the **emergent computational mechanisms of modern artificial neural networks**, dense associative memories, multi-modal binding, and biological information processing. Alongside theoretical machine learning, we conduct investigations in **computational biophysics**, **reaction kinetics in biochemical networks**, and **transport phenomena on complex topologies**.

---

## 📦 Flagship Open-Source Repositories

All software implementations, simulation engines, and analytical derivation packages developed in our laboratory are released under the permissive open-source **MIT License** with full reproducibility metadata:

| Repository | Focus & Mathematical Foundations | Venue / Status | Ecosystem |
| :--- | :--- | :--- | :--- |
| **[`dlam-mc-core`](https://github.com/coscienza-research/dlam-mc-core)** | **Dreaming $L$-directional Associative Memory (DLAM)**<br>Publication-grade Monte Carlo simulation core (synchronous Glauber dynamics, unlearning/dreaming kernels, pattern disentanglement) and symbolic Wolfram Language (`LAMsym`) arbitrary-$L$ replica-symmetric free-energy derivation toolkit. | **Neural Networks**<br>Vol. 206, 109729 (2026)<br>[DOI: 10.1016/j.neunet.2026.109729](https://doi.org/10.1016/j.neunet.2026.109729) | Python · NumPy · Wolfram Language |
| **[`exponential-lam-engine`](https://github.com/coscienza-research/exponential-lam-engine)** | **Exponential LAM: Multilayer Hetero-Associative Engine**<br>Vectorized GPU-accelerated PyTorch engine and reference CPU NumPy engine for multi-layer exponential networks with exponential storage capacity $P_c \sim e^{N \rho_L}$ ($\rho_L \sim L \log 2$), cue-seeding, layer-clamping, and domain universality (VDJdb TCR-epitopes, intents, synthetic manifolds). | **Preprint**<br>[arXiv:2607.29554](https://arxiv.org/abs/2607.29554)<br>[DOI: 10.48550/arXiv.2607.29554](https://doi.org/10.48550/arXiv.2607.29554) | PyTorch (CUDA) · NumPy · SciPy |
| **[`mtam_layers`](https://github.com/coscienza-research/mtam_layers)** | **Multi-modal Transformer Associative Memory (mTAM)**<br>Fully differentiable PyTorch library implementing Consensus Split-Bank Attention (CSA) and Entropy-Gated Consensus (EG-CSA) to eliminate chimeric states by construction with Difference-of-Convex (DC) CCCP monotonic energy descent guarantees. | **ICLR 2026 Workshop (NFAM)**<br>[OpenReview](https://openreview.net/) · [PDF](https://github.com/coscienza-research/mtam_layers/blob/master/Thermodynamic_Binding_ICLR_NFAM_2026.pdf) | PyTorch · Python (100% test cov) |

---

## 📚 Key Publications & Selected Works

### 1. Dreaming Dynamics & Multidirectional Associative Memories
> **Do Hopfield networks dream of stored patterns? A statistical–mechanical theory of dreaming in multidirectional associative memories**  
> Adriano Barra, Fabrizio Durante, Andrea Ladiana, Michela Marra Solazzo  
> *Neural Networks*, Volume 206, Article 109729, 2026.  
> 🔗 **Published Paper:** [DOI: 10.1016/j.neunet.2026.109729](https://doi.org/10.1016/j.neunet.2026.109729) · **Preprint:** [arXiv:2605.13721](https://arxiv.org/abs/2605.13721) · **Code:** [`coscienza-research/dlam-mc-core`](https://github.com/coscienza-research/dlam-mc-core)

<details>
<summary><b>BibTeX Citation</b></summary>

```bibtex
@article{barra2026hopfield,
  title={Do Hopfield networks dream of stored patterns? A statistical-mechanical theory of dreaming in multidirectional associative memories},
  author={Barra, Adriano and Durante, Fabrizio and Ladiana, Andrea and Solazzo, Michela Marra},
  journal={Neural Networks},
  volume={206},
  pages={109729},
  year={2026},
  publisher={Elsevier},
  doi={10.1016/j.neunet.2026.109729},
  url={https://doi.org/10.1016/j.neunet.2026.109729}
}
```
</details>

### 2. Exponential Capacity in Multilayer Networks
> **Exponential Capacity in Multilayer Hetero-Associative Neural Networks**  
> Elena Agliari, Adriano Barra, Andrea Ladiana, Andrea Lepre  
> *arXiv preprint* arXiv:2607.29554, 2026.  
> 🔗 **Preprint:** [arXiv:2607.29554](https://arxiv.org/abs/2607.29554) · **DOI:** [10.48550/arXiv.2607.29554](https://doi.org/10.48550/arXiv.2607.29554) · **Code:** [`coscienza-research/exponential-lam-engine`](https://github.com/coscienza-research/exponential-lam-engine)

<details>
<summary><b>BibTeX Citation</b></summary>

```bibtex
@article{agliari2026exponential,
  title={Exponential Capacity in Multilayer Hetero-Associative Neural Networks},
  author={Agliari, Elena and Barra, Adriano and Ladiana, Andrea and Lepre, Andrea},
  journal={arXiv preprint arXiv:2607.29554},
  year={2026},
  doi={10.48550/arXiv.2607.29554},
  url={https://arxiv.org/abs/2607.29554}
}
```
</details>

### 3. Thermodynamic Binding & Multi-Modal Foundation Architectures
> **Thermodynamic Binding: Freezing Chimeric States in Multi-Modal Associative Memories**  
> Elena Agliari, Adriano Barra, Andrea Ladiana, Andrea Lepre  
> *ICLR 2026 Workshop on New Frontiers in Associative Memories (NFAM)*.  
> 🔗 **Proceedings:** [OpenReview](https://openreview.net/) · **PDF:** [`Thermodynamic_Binding_ICLR_NFAM_2026.pdf`](https://github.com/coscienza-research/mtam_layers/blob/master/Thermodynamic_Binding_ICLR_NFAM_2026.pdf) · **Code:** [`coscienza-research/mtam_layers`](https://github.com/coscienza-research/mtam_layers)

<details>
<summary><b>BibTeX Citation</b></summary>

```bibtex
@inproceedings{agliari2026thermodynamic,
  title={Thermodynamic Binding: Freezing Chimeric States in Multi-Modal Associative Memories},
  author={Agliari, Elena and Barra, Adriano and Ladiana, Andrea and Lepre, Andrea},
  booktitle={New Frontiers in Associative Memories - Workshop at ICLR 2026},
  year={2026},
  url={https://openreview.net/}
}
```
</details>

---

## 🧭 Research Pillars & Scientific Programs

Our investigative lines encompass fundamental theoretical physics, computational neuroscience, and advanced machine learning:

* 🧠 **Dense Associative Memories & Multi-Body Interactions**  
  Modern Hopfield networks, exponential storage capacity in generalized Hebbian networks, multi-directional associative architectures (DLAM), and algebraic formulations of non-linear memory retrieval.
* 💤 **Dreaming Dynamics & Severe Data-Scarcity Regimes**  
  Statistical mechanics of sleep and off-line dreaming kernels in artificial neural networks. Biological unlearning and consolidation dynamics that foster robust pattern extraction, noise removal, and generalization while saving up to 90% of training data requirements.
* 🔀 **Thermodynamic Binding & Elimination of Chimeric States**  
  Solving the multi-modal binding problem in attention-based foundation models via global Difference-of-Convex (DC) free energies, Concave-Convex Procedure (CCCP) descent, and Consensus Split-Bank Attention (mTAM / CSA).
* ⚡ **Multilayer Exponential Networks & Infinite-Order Capacities**  
  Cavity and signal-to-noise large-deviation analysis establishing exponential storage scaling $P_c \sim e^{N \rho_L}$ across heterogeneous sensory channels, immunological sequences (VDJdb TCR-epitopes), and intent spaces.
* 🧭 **Neural Substrates of Spatial Navigation**  
  Continuous attractor network (CAN) models and statistical-mechanical formulations of place cells, grid cells, and path integration in cognitive mapping.
* 🌐 **Networks of Neural Networks & Distributed / Federated Intelligence**  
  Emergent collective phenomena in modular ensembles of interconnected neural networks, extensively parallel computing, and data-quality-calibrated federated associative systems.
* 📶 **Signal-to-Noise Tradeoffs & Weak-Signal Detection**  
  Dense neural networks dynamically modulating signal-to-noise thresholds, intentionally sacrificing memory capacity to detect faint signals deeply submerged in stochastic background noise.
* 🧬 **Quantitative Biology, Ultrametric Landscapes & Reaction Kinetics**  
  Information processing in complex biochemical reaction networks, replica symmetry breaking (RSB), and ultrametric energy landscapes governing homologous protein families and immunological recognition.
* 🕸️ **Transport & First-Passage Phenomena on Inhomogeneous Graphs**  
  Diffusion, random walks, and exact analytical Laplacian spectra on fractal, hierarchical, and inhomogeneous networks (e.g., Berker–Ostlund diamond lattices).

---

## 🏛️ Group Leadership & Faculty

* **[Prof. Adriano Barra](https://adrianobarra.com)** — Associate Professor of Mathematical Physics, Sapienza University of Rome  
  *Co-Founder & Group Leader*  
  *Research focus:* Associative neural networks, place & grid cell continuous attractors, extensively parallel processing, dreaming phenomena in associative models, reaction kinetics, and ultrametric fluctuations in disordered systems.  
  🌐 [Personal Website](https://adrianobarra.com) · [Sapienza Profile](https://corsidilaurea.uniroma1.it/it/users/adrianobarrauniroma1it) · [ResearchGate Profile](https://www.researchgate.net/profile/Adriano-Barra)
* **[Prof. Elena Agliari](https://corsidilaurea.uniroma1.it/it/users/elenaagliariuniroma1it)** — Full Professor of Mathematical Physics, Sapienza University of Rome  
  *Co-Founder & Group Leader*  
  *Research focus:* Mathematical theory of neural networks, first-passage phenomena and transport in complex topologies, statistical mechanics of disordered systems, and biological cybernetics.  
  🌐 [Sapienza Profile](https://corsidilaurea.uniroma1.it/it/users/elenaagliariuniroma1it) · [ResearchGate Profile](https://www.researchgate.net/profile/Elena-Agliari)
* **[Prof. Alberto Fachechi](https://albertofachechi.github.io/)** — Permanent Researcher & Head of Scientific Computing, Sapienza University of Rome  
  *Senior Scientist*  
  *Research focus:* Statistical learning theory, spin-glass physics, high-dimensional probability, and large-scale computational simulations.  
  🌐 [Personal Website](https://albertofachechi.github.io/) · [GitHub (@albertofachechi)](https://github.com/albertofachechi) · [ResearchGate Profile](https://www.researchgate.net/profile/Alberto-Fachechi)

---

## 👥 Researchers, Postdocs & Doctoral Fellows

| Researcher | Role / Research Focus | Institutional Affiliation | Profiles & Links |
| :--- | :--- | :--- | :--- |
| **Linda Albanese** | Postdoctoral Researcher · Semi-supervised Learning, Disordered Systems | University of Salento / Sapienza | [ResearchGate](https://www.researchgate.net/profile/Linda-Albanese) |
| **Francesco Alemanno** | Researcher / Collaborator · Biological Complexity & Numerical Physics | University of Bologna | [ResearchGate](https://www.researchgate.net/profile/Francesco-Alemanno) |
| **Andrea Alessandrelli** | PhD Student in AI · Multidirectional Memories, Federated Associative Networks | University of Pisa / Sapienza | [GitHub](https://github.com/AndreaAlessandrelli4) · [ResearchGate](https://www.researchgate.net/profile/Andrea-Alessandrelli) |
| **Miriam Aquaro** | PhD Researcher · Mathematical Methods & Neural Networks | Sapienza University of Rome | [ResearchGate](https://www.researchgate.net/profile/Miriam-Aquaro) |
| **Martino S. Centonze** | Researcher · Machine Learning & Complex Disordered Systems | University of Salento | [ResearchGate](https://www.researchgate.net/profile/Martino-Centonze) |
| **Andrea Ladiana** | PhD Student in Mathematics · Associative Networks, Spin Glasses, Fractals | Sapienza University of Rome | [Personal Web](https://andrea-ladiana.github.io/) · [GitHub](https://github.com/andrea-ladiana) · [ResearchGate](https://www.researchgate.net/profile/Andrea-Ladiana) |
| **Andrea Lepre** | Postdoctoral Fellow · Hetero-associative Learning, Statistical Mechanics | Sapienza University of Rome | [ResearchGate](https://www.researchgate.net/profile/Andrea-Lepre) |
| **Paulo Duarte Mourão** | Researcher · Statistical Physics & Neural Modeling | Sapienza University of Rome | [ResearchGate](https://www.researchgate.net/profile/Paulo-Mourao) |

---

## 🔗 Institutional Network & Collaborations

* **University:** [Sapienza Università di Roma](https://www.uniroma1.it)
* **Academic Departments:**
  * [SBAI – Dipartimento di Scienze di Base e Applicate per l'Ingegneria](https://www.sbai.uniroma1.it/)
  * [Dipartimento di Matematica "Guido Castelnuovo"](https://www.mat.uniroma1.it/)
* **National Research Bodies:**
  * [INFN – Istituto Nazionale di Fisica Nucleare](https://www.infn.it/) (Sezione di Roma 1 & Sezione di Lecce)
  * [CNR-Nanotec – Consiglio Nazionale delle Ricerche](https://nanotec.cnr.it/)
  * [GNFM – Istituto Nazionale d'Alta Matematica (INdAM)](https://www.altamatematica.it/gnfm/)
* **Lab ResearchGate Hub:** [Scuderia "Cò'Scienza" Lab Page](https://www.researchgate.net/lab/Scuderia-CoScienza-Adriano-Barra)
* **Industry & Technology Transfer Portal:** [Cò'Scienza: per le imprese](https://adrianobarra.com/cogravescienza-per-le-imprese.html)

---

<div align="center">
  <sub><strong>Scuderia "Cò'Scienza"</strong> • Theoretical & Computational Physics Lab • Sapienza University of Rome<br>Piazzale Aldo Moro 5 / Via Antonio Scarpa 14, 00185 Roma, Italy</sub><br>
  <sub>Licensed under the <a href="LICENSE">MIT License</a></sub>
</div>
