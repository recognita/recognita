# Daria Makeeva

ML Engineer — Machine Learning for bioelectric interfaces (EEG · ECoG · EMG/EIM) and biomedical signal processing.

MSc student in Mathematical Engineering at Politecnico di Milano · BSc in Biomedical Engineering from Bauman Moscow State Technical University · based in Milan, Italy 🇮🇹 .

- Research background spanning computer vision (Huawei) and EEG/MEG deep learning (HSE Centre for Bioelectric Interfaces)
- 3+ years working on ML for myo- and neurointerfaces
- Author of 2 peer-reviewed publications (IEEE USBEREIT 2025, Politechnical Student Journal)
- Currently building a [time-parallel PDE solver for human phonation modelling](https://github.com/ruthparajo/paraexp-webster)
- Open to research engineer / ML engineer roles in biomedical signal processing, computer vision, and scientific computing

**Contact:** [LinkedIn](https://www.linkedin.com/in/recognita) · hdnskgm@gmail.com

---

## Featured projects

| Project | What it does | Result |
|---|---|---|
| [paraexp-webster](https://github.com/ruthparajo/paraexp-webster) *(with Ruth Parajó)* | Time-parallel solver for the Webster equation modelling sound propagation in the human vocal tract: spectral elements in space, Crank-Nicolson in time, accelerated with the ParaExp parallel-in-time algorithm (C++/Eigen/OpenMP). | Up to 1.25× speedup at 16 processes; ParaExp and serial Crank-Nicolson recover identical vowel formant frequencies, confirming correctness |
| [eim-for-muscle-contraction-detection](https://github.com/recognita/EIM-for-Muscle-Construction-Detection) | Signal processing + ML pipeline (filtering → feature extraction → classification) that detects muscle contraction type from electrical impedance myography, for upper-limb prosthesis control | 0.95 classification accuracy; presented at IEEE USBEREIT 2025 |
| [spatial-harmonics](https://github.com/recognita/Spatial-Harmonics) | Spherical-harmonics-based neural layer for the 3D spatial-attention block in a speech representation model | ~40% parameter reduction with no accuracy loss; presented at Student Spring University Forum 2025 |
| [temporal-filters](https://github.com/recognita/TemporalFilters) | Learnable wavelet / sinc parameterized temporal filters usable as preprocessing layers in EEGNet, SpatialNet, FBCSP and similar architectures | Reusable filter-layer library for EEG deep-learning pipelines |

---

## Experience

**Huawei Technologies** — Research Engineer (Jun - Sep 2025)
Deep learning–based computer vision models for real-world image processing; optimized neural networks for deployment on mobile NPUs.

**HSE Centre for Bioelectric Interfaces** — Research Assistant (2023–2024)
Deep learning for EEG/MEG signal analysis with a focus on interpretability and noise-robust filtering; designed the hardware for a real-time intraoperative ECoG mapping system used in the EloQ app (Google Play).

**BMSTU, Mathematical Modeling in Biological Processes Lab** — Research Assistant (2021–2025)
ML-based electrical impedance myography (EIM) study for muscle contraction detection; multimodal EEG data collection (visual, SSVEP); BCI research for stroke rehabilitation.

## Skills

**ML & AI:** Deep Learning (CNNs, object detection/localization), sequence models (LSTM, Attention, Transformers), PyTorch, scikit-learn
**Biomedical signal processing:** EEG, ECoG, MEG, EMG, EIM — filtering, feature extraction, spectral analysis
**Scientific computing:** C++ (Eigen), Python, MATLAB, FreeFEM, OpenMP/MPI parallel computing, numerical methods for PDEs, finite element method
**Hardware:** Analog front-end and circuit design for biosignal acquisition systems, embedded systems (Arduino, STM32)

## Publications

- Makeeva, D.S., Yakim, M.Y., Kobelev, A.V., Shchukin, S.I. — *Machine Learning Techniques for Muscle Contraction Detection based on Electrical Impedance Measurements*, IEEE USBEREIT 2025, pp. 217–220.
- Chekhvalov, R.D., Konstantinova, Z.A., Makeeva, D.S. — *An overview of modern brain-computer interface technology in tasks of motor rehabilitation*, Politechnical Student Journal, 2022, no. 06(71).

