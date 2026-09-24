---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2026
---
- ***Tianwei Wu***, *Abdullah Al Ishtiaq, Tianchang Yang, Yilu Dong, Kai Tu, Zeyu Song, Ridwanul Hasan Tanvir, Md Toufikuzzaman, Shagufta Mehnaz, and Syed Rafiul Hussain.* **"Guardians of the Air: In-Device Detection of 5G Control-Plane Threats."**

  We present 5GShield, an in-device framework for detecting and mitigating 5G control-plane threats. It checks nearby base stations' broadcast configurations before connection and monitors control-plane traffic for ongoing attacks.
  [View](https://ieeexplore.ieee.org/abstract/document/11573414/)
---

---
- *Syed Md Mukit Rashid, Abdullah Al Ishtiaq, Kai Tu, Yilu Dong, **Tianwei Wu**, Ali Ranjbar, Tianchang Yang, Najrin Sultana, Shagufta Mehnaz, and Syed Rafiul Hussain.* **"LogicEval: A Systematic Framework for Evaluating Automated Repair Techniques for Logical Vulnerabilities in Real-World Software."**

  We introduce LogicDS, a dataset of 122 real-world logical vulnerabilities, and LogicEval, a framework for evaluating patches produced by traditional and language-model-based repair techniques. Our evaluation identifies prompt sensitivity, lost code context, and patch localization as recurring obstacles.
  [View](https://aclanthology.org/2026.acl-long.2136/)
---

---
- *SeyedMohammad Kashani, Erfan Khademnia, Görkem Emirhüseyinoğlu, Yilu Dong, **Tianwei Wu**, Sang Wu Kim, Ashfaq Khokhar, Farid Naït-Abdesselam, and Syed Rafiul Hussain.* **"OptiMAC: Adaptive Security Optimization for Message Authentication Code in Adversarial Environment."**

  We present OptiMAC, a method for improving message authentication when wireless transmissions are lost or disrupted. It optimizes how authentication information is distributed across messages to improve resilience in adversarial environments.
  [View](https://ieeexplore.ieee.org/abstract/document/11593381/)
---

## 2025

---
- *Yilu Dong, Tianchang Yang, Abdullah Al Ishtiaq, Syed Md Mukit Rashid, Ali Ranjbar, Kai Tu, **Tianwei Wu**, Md Sultan Mahmud, and Syed Rafiul Hussain.* **"CoreCrisis: Threat-Guided and Context-Aware Iterative Learning and Fuzzing of 5G Core Networks."**

  We develop CoreCrisis, a stateful testing framework that learns how a 5G core network behaves and uses that model to guide fuzzing. Evaluation on three open-source and one commercial implementation found seven categories of specification deviations and 13 crashing vulnerabilities.
  [View](https://www.usenix.org/conference/usenixsecurity25/presentation/dong-yilu)
---

---
- *Yilu Dong, Tao Wan, **Tianwei Wu**, and Syed Rafiul Hussain.* **"Evaluating Time-Bounded Defense Against RRC Relay in 5G Broadcast Messages."**

  We implement and evaluate a digital-signature and time-bounded defense for 5G broadcast messages. Tests with an open-source 5G system show that the added overhead is acceptable and that the timing check can stop relay-based fake base station attacks.
  [View](https://dl.acm.org/doi/10.1145/3734477.3734718)
---

## 2024

---
- *Syed Md Mukit Rashid, **Tianwei Wu**, Kai Tu, Abdullah Al Ishtiaq, Ridwanul Hasan Tanvir, Yilu Dong, Omar Chowdhury, and Syed Rafiul Hussain.* **"State Machine Mutation-based Testing Framework for Wireless Communication Protocols."**

  We present Proteus, a state-machine-guided testing approach for finding logical vulnerabilities in wireless protocol implementations. Testing 4G LTE and Bluetooth Low Energy across 23 devices uncovered 25 unique issues, including 14 vendor-acknowledged vulnerabilities associated with five CVEs.
  [View](https://dl.acm.org/doi/10.1145/3658644.3690312)
---

---
- *Kai Tu, Abdullah Al Ishtiaq, Syed Md Mukit Rashid, Yilu Dong, Weixuan Wang, **Tianwei Wu**, and Syed Rafiul Hussain.* **"Logic Gone Astray: A Security Analysis Framework for the Control Plane Protocols of 5G Basebands."**

  We develop 5GBaseChecker— an efficient, scalable, and dynamic security analysis framework based on differential testing for analyzing 5G basebands' control plane protocol interactions. 5GBaseChecker first captures basebands' protocol behaviors as a finite state machine (FSM) through black-box automata learning. To facilitate efficient learning and improve scalability, 5GBaseChecker introduces novel hybrid and collaborative learning techniques. 5GBaseChecker then identifies input sequences for which the extracted FSMs provide deviating outputs. Finally, 5GBaseChecker leverages these deviations to efficiently identify the security properties from specifications and use those to triage if the deviations found in 5G basebands violate any properties. We evaluated 5GBaseChecker with 17 commercial 5G basebands and 2 open-source UE implementations and uncovered 22 implementation-level issues, including 13 exploitable vulnerabilities and 2 interoperability issues.
  [View](https://www.usenix.org/conference/usenixsecurity24/presentation/tu)
---


---
- *Abdullah Al Ishtiaq, Sarkar Snigdha Sarathi Das, Syed Md Mukit Rashid, Ali Ranjbar, Kai Tu, **Tianwei Wu**, Zhezheng Song, Weixuan Wang, Mujtahid Akon, Rui Zhang, Syed Rafiul Hussain* **“Hermes: Unlocking Security Analysis of Cellular Network Protocols by Synthesizing Finite State Machines from Natural Language Specifications."**

  In this paper, we present Hermes, an end-to-end framework to automatically generate formal representations from natural language cellular specifications. We first develop a neural constituency parser, NEUTREX, to process transition-relevant texts and extract transition components (i.e., states, conditions, and actions). We also design a domain-specific language to translate these transition components to logical formulas by leveraging dependency parse trees. Finally, we compile these logical formulas to generate transitions and create the formal model as finite state machines. To demonstrate the effectiveness of Hermes, we evaluate it on 4G NAS, 5G NAS, and 5G RRC specifications and obtain an overall accuracy of 81-87%, which is a substantial improvement over the state-of-the-art. Our security analysis of the extracted models uncovers 3 new vulnerabilities and identifies 19 previous attacks in 4G and 5G specifications, and 7 deviations in commercial 4G basebands.
  [View](https://www.usenix.org/conference/usenixsecurity24/presentation/al-ishtiaq)
---
