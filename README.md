# Peixuan Yang

**Computer Science & Electronic Engineering · Efficient AI Systems · Trustworthy Robotics**

I study how machine-learning models interact with the systems that run them, from efficient inference and photonic computing to autonomous robots and verifiable sensing. My interests span computer architecture, world models, and reliable experimentation.

I am following the XJTLU–University of Liverpool 2+2 pathway, with the Liverpool BEng (Hons) in Computer Science and Electronic Engineering expected in 2028.

[Research](#selected-research) · [PhotonWM](https://github.com/sh1ranY/photonwm) · [NMT paper](https://github.com/sh1ranY/cantonese-english-nmt) · [Contact](mailto:Peixuan.Yang24@student.xjtlu.edu.cn)

---

## Selected research

### PhotonWM — photonic acceleration for world models
**Student researcher · 2026–present · Abstract submitted to DATE 2027**

**PhotonWM: Trace-Driven Co-Design of MRR Acceleration for Autoregressive World Models** explores a hybrid photonic–electronic architecture: fixed-weight linear operators run on microring-resonator arrays, while dynamic and irregular operations remain on an electronic backend.

My contributions include model reproduction and profiling, workload analysis, evaluation methodology, and manuscript revision. The submitted abstract reports simulation results for a 30-frame LPWM BAIR-128 rollout, including **9.13 ms latency**, **0.90 J energy**, and a **94.42% SRAM hit rate** with 58 MB SRAM. These are collaborative, simulated results, not measurements from a fabricated accelerator.

Status: abstract submission completed; this does not indicate acceptance or a completed full-paper submission.

[Project overview and architecture](https://github.com/sh1ranY/photonwm)

**Focus:** PyTorch · inference profiling · computer architecture · photonic computing

### Collaborative Proof-of-Sensing — trustworthy multi-robot systems
**SURF 2026 · Blockchain Security Group, XJTLU**

Investigated verifiable sensing and lightweight mission auditing for autonomous robots. Built a local Solidity/Hardhat sensing-registry prototype and worked with ROS 2, Gazebo, and PX4 multi-UAV simulation.

The work includes separate blockchain and flight-simulation prototypes; end-to-end verification of physical sensing remains a research direction.

**Focus:** ROS 2 · PX4 · Gazebo · Solidity · Hardhat

### Low-resource Cantonese–English neural machine translation
**Co-second author and presenter · ICRAI 2025**

Contributed to corpus preparation, NLLB fine-tuning, and pseudo-data experiments for low-resource translation. The published study reports a 1.1-million-pair corpus and best in-domain scores of **29.63 BLEU** and **56.65 chrF**. These are results of the collaborative study.

[Publication companion](https://github.com/sh1ranY/cantonese-english-nmt) · [Read the published paper](https://doi.org/10.1109/ICRAI68431.2025.11396704)

## Publication

Yichao Wang, Yukun Gao, **Peixuan Yang**, and Bohan Zhao.
**Optimized Fine-tuning and Pseudo-Data Strategies for Cross-Domain Low-Resource Language Cantonese-English Neural Machine Translation.**
*2025 11th International Conference on Robotics and Artificial Intelligence (ICRAI).*
[DOI: 10.1109/ICRAI68431.2025.11396704](https://doi.org/10.1109/ICRAI68431.2025.11396704)

## Technical toolkit

| Area | Tools and experience |
| :--- | :--- |
| Machine learning | Python, PyTorch, NLLB fine-tuning, reproducible experiments |
| AI systems | Model profiling, workload tracing, LLMCompass, SimPhony |
| Robotics and auditing | ROS 2, PX4 SITL, Gazebo, Solidity, Hardhat, ethers.js |
| Software | Git, Linux, Java, SQL, REST APIs, LaTeX |

## Beyond research

I also worked on a hackathon HR assistant, combining document parsing, retrieval, and language-model workflows. I enjoy connecting a technical idea to a working prototype and explaining what the evidence does—and does not—show.
