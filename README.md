<p align="center">
  <img src="assets/avatar.svg" width="340" alt="Muhammad Adnan">
</p>

<h1 align="center">Muhammad Adnan</h1>
<p align="center">
  <b>Electronics Engineer · PhD Applicant in Safe Reinforcement Learning and Multi-Robot Control</b><br>
  Lab Engineer, School of Electrical Engineering &amp; Computer Science (SEECS), NUST, Islamabad
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?user=3u0pjLoAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://orcid.org/0009-0007-3810-594X"><img src="https://img.shields.io/badge/ORCID-0009--0007--3810--594X-A6CE39?logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://www.linkedin.com/in/engr-muhammad-adnan-699097214"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://seecs.nust.edu.pk/faculty/muhammad-adnan-9/"><img src="https://img.shields.io/badge/NUST%20Profile-003366" alt="NUST faculty profile"></a>
  <a href="mailto:muhammadadnan.aslam@seecs.edu.pk"><img src="https://img.shields.io/badge/Email-muhammadadnan.aslam%40seecs.edu.pk-D14836?logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About me

I am a Lab Engineer at NUST with an MS in Electronics Engineering from UET Taxila. My MS work was on decentralized coordination of multi-robot systems that run without a central controller. I developed SCOPE, a decentralized formation and path-planning strategy for miniature robot swarms, and tested it on TurtleBot3 robots with ROS. I have co-authored 17 papers in robotics, optimization, machine learning and security.

I am looking for a PhD position in decentralized AI, working on safe reinforcement learning for teams of agents that learn and coordinate without central control.

### Research interests

`Decentralized Learning and Control` · `Multi-Agent Systems` · `Safe Reinforcement Learning` · `Multi-Robot Coordination` · `Control Theory for Autonomous Systems`

### Projects

#### [LARD: occlusion-robust pedestrian detection on edge hardware](https://github.com/adnanaslam90901-cell/lard-occlusion-pedestrian-detection)
A 2.2M-parameter YOLOv5n detector with a compact channel-and-spatial attention module in the neck, trained with synthetic occlusion and deployed as a TensorRT INT8 engine on a Jetson Nano. It reaches mAP@0.5 of 0.604 on CrowdHuman and runs in under 30 ms per frame (about 33 FPS) on the Nano. Under 50–70 % occlusion, recall-oriented inference raises recall by 58.2 %. The repository holds the dataset setup and occlusion augmentation tools; the paper is under review.<br>
`PyTorch` `YOLOv5` `TensorRT` `Jetson Nano` `Albumentations`

#### [ESP32-CAM Water Meter Reader](https://github.com/adnanaslam90901-cell/esp32-water-meter-reader)
An ESP32-CAM photographs a mechanical water meter and sends the image over Wi-Fi to a FastAPI server. A two-stage ONNX model (4.6 MB) finds the counter window and reads all 8 digits on a laptop CPU in about 0.1 s. On 196 held-out photos it gets every digit right 77 % of the time and the whole cubic metres right 89.8 % of the time, against about 3 % for a general OCR baseline. It includes the Arduino firmware, a browser dashboard, batch export to Excel and a pytest suite.<br>
`ESP32` `Arduino` `ONNX Runtime` `FastAPI` `Python`

#### [CHOIR: zero-day intrusion prevention for IoT networks](https://github.com/adnanaslam90901-cell/choir-zero-day-ips)
A flow-level intrusion prevention system built to catch attack families it has never seen. One supervised score and three benign-only anomaly scores are combined by a stacker trained on simulated zero-days, and a split-conformal layer bounds how much benign traffic gets blocked (BLOCK / LOG / ALLOW). Every attack family is held out in turn on UNSW-NB15 and TON_IoT. At a 1 % alert budget it detects 93.0 % of unseen attacks on TON_IoT and 84.9 % on UNSW-NB15. The study also shows that the common OR rule for hybrid detectors lowers zero-day detection by 5.5 to 21.6 points. Full code will be released when the paper is accepted.<br>
`scikit-learn` `Conformal Prediction` `Gradient Boosting` `Anomaly Detection`

#### [BioLingua: self-supervised representations of bird vocalizations](https://github.com/adnanaslam90901-cell/biolingua)
Two bioacoustics studies with one evaluation toolkit. The first compares frozen audio encoders on zebra finch call types with a split that keeps each bird out of training: BirdAVES-base reaches a test macro-F1 of 0.714, against 0.555 for HuBERT and 0.402 for wav2vec 2.0. The second is a Xeno-canto pipeline for five European species covering acoustic-unit discovery, sequence models and behaviour probes. Its leakage audit shows that splitting by segment instead of by recording inflates accuracy by 4 to 6 points.<br>
`PyTorch` `torchaudio` `Hugging Face` `HuBERT` `BirdAVES`

### Selected publications

**Robotics and autonomous systems**
- **M. Adnan**, Y. A. Durrani, M. H. Yousaf, "Decentralized Swarm Formation of Miniature Robots Using the SCOPE Strategy," *IEEE INMIC 2025*. [[IEEE Xplore]](https://ieeexplore.ieee.org/abstract/document/11348372)
- **M. Adnan** et al., "A Simulation-Driven, FPGA-Oriented Multi-Sensor Perception Pipeline for Low-Latency Autonomous Navigation on the DE10-Nano," *under review, Elsevier journal*, 2026.

**Optimization and AI**
- **M. Adnan** et al., "TIGWO-DLH: A Chaotic Distributed Hybrid Grey Wolf Framework for Accelerated and Stable Global Optimization," *IEEE ICSPC 2025*. [[IEEE Xplore]](https://ieeexplore.ieee.org/abstract/document/11326484)
- **M. Adnan** et al., "Intelligent Optimization of Polarization Sampling in Rotating Polarization Wave via Multitask Deep Learning for IoT Applications," *IEEE IS'26*, to appear.
- H. A. Ramzan, **M. Adnan** et al., "Design Optimization of Analog and Digital Circuits Using Artificial Intelligence," *IEEE FMLDS 2025*. [[IEEE Xplore]](https://ieeexplore.ieee.org/abstract/document/11446692)

**Machine learning, robustness and security**
- **M. Adnan** et al., "Machine Learning Approaches for Network Intrusion Detection in IoT Environments," *IEEE ICET 2026*, accepted.
- **M. Adnan** et al., "Fault-Tolerant Adaptive Routing in NoCs: Machine Learning Approaches for Resilient On-Chip Networks," *IEEE ACDSA 2025*. [[IEEE Xplore]](https://ieeexplore.ieee.org/abstract/document/11165816)
- **M. Adnan** et al., "Illumination-Conditioned and Curriculum-Learned Transformer for Ultra-High-Definition Low-Light Image Enhancement," *IEEE ICSIPA 2026*, to appear.
- S. Ramzan, H. A. Ramzan, T. Kalsum, **M. Adnan** et al., "Text-to-Image Generation with Enhanced GANs: Bridging Semantic Gaps Using RNN and CNN," *PLoS ONE* 21(1), 2026. [[Article]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0340413)
- S. A. Khan, **M. Adnan** et al., "An Android Applications Vulnerability Analysis Using MobSF," *ICECT 2024*. [[IEEE Xplore]](https://ieeexplore.ieee.org/abstract/document/10581312)

Full list on [Google Scholar](https://scholar.google.com/citations?user=3u0pjLoAAAAJ&hl=en).

### Experience

- **Lab Engineer**, NUST SEECS *(Sep 2024 – present)*. I run labs in Embedded System Design, Microprocessor Systems, Digital Design Verification and Applications of ICT, and supervise student projects in autonomous robots, embedded perception, FPGA systems and IoT. I revised the Embedded System Design lab manuals to move the course to the STM32F746G-DISCO board.
- **Research Assistant**, Swarm Robotics Lab, UET Taxila *(Jan 2022 – Jul 2023)*. I worked on decentralized coordination and formation strategies for multi-robot systems, and supported work on UGVs, UAVs and USVs.
- **STEM and Robotics Trainer**, Brain Swarm Pvt. Ltd. *(Jul 2022 – Jul 2023)*. I designed and taught hands-on robotics, programming and embedded systems sessions.

### Education

- **MS Electronics Engineering**, UET Taxila *(2021 – 2026)*, CGPA 3.42/4.00. Thesis: *Intelligent Swarm Formation of Miniature Robots*.
- **BE Electronics Engineering**, UET Taxila *(2017 – 2021)*.

### Academic service

- Reviewer, *Expert Systems with Applications* (Elsevier), Certificate of Reviewing, Sep 2026
- Technical Program Committee member, IEEE ICSPC 2025, Melaka, Malaysia
- Reviewer, IEEE AGRETA 2025, Indonesia
- Mentor, NUST Young Students Engagement Program
- Guest lecturer on IoT and embedded systems

### Tools and technologies

**Robotics:** ![ROS2](https://img.shields.io/badge/ROS%2FROS2-22314E?logo=ros&logoColor=white) ![Gazebo](https://img.shields.io/badge/Gazebo-F58113) ![CoppeliaSim](https://img.shields.io/badge/CoppeliaSim-4B8BBE) ![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?logo=mathworks&logoColor=white)<br>
**Embedded and FPGA:** ![STM32](https://img.shields.io/badge/STM32-03234B?logo=stmicroelectronics&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?logo=espressif&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00878F?logo=arduino&logoColor=white) ![DE10-Nano](https://img.shields.io/badge/DE10--Nano%20FPGA-0071C5?logo=intel&logoColor=white) ![Verilog](https://img.shields.io/badge/Verilog%20%2F%20SystemVerilog-6E4C13) ![Vivado](https://img.shields.io/badge/Vivado-ED1C24?logo=amd&logoColor=white)<br>
**AI and programming:** ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white) ![ONNX](https://img.shields.io/badge/ONNX-005CED?logo=onnx&logoColor=white) ![C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?logo=cplusplus&logoColor=white) ![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)
