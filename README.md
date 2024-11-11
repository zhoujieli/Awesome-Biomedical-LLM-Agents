# Awesome-Biomedical-LLM-Agents
A curated list of LLM powered AI Agents in Biomedical Research. Medical Image Analysis, Multi-omics Genomics Analysis, Biomedical Scientific Discoveries. Here, we trace the rapid developments of AI Agents in Biomedical Reswearch, including milestone researchs, surveys, benchmark datasets, open-source code implementations, etc.

## Introduction
The emergence of AI agents in biomedical research marks a significant paradigm shift in how we approach complex healthcare and biological challenges. While foundation models (language, vision, and multimodal) have shown remarkable capabilities in medical imaging, text analysis, and genomics, they face three major limitations: insufficient biomedical training data compared to general domains; the inherently open-ended nature of biomedical research questions where hallucination risks pose serious concerns; and their inability to support dynamic, iterative research workflows that require continuous feedback and adaptation. To address these challenges, LLM-powered AI agents have emerged as a promising solution, decomposing complex biomedical tasks into modular components handled by specialized foundation models, while using a master model to orchestrate the entire workflow and maintain dynamic reasoning chains. This approach has demonstrated success in various applications including chemical research automation, medical decision support, and scientific literature analysis. This repository collects and organizes key research papers and developments (up to November 2024) in biomedical AI agents, aiming to facilitate research and development in this rapidly evolving field.


1. **[Empowering biomedical discovery with ai agents.](https://www.cell.com/cell/fulltext/S0092-8674(24)01234-X)**  
    *Shanghua Gao, Ada Fang, Yepeng Huang, Valentina Giunchiglia, Ayush Noori, Jonathan Richard Schwarz, Yasha Ektefaie, Jovana Kondic, Marinka Zitnik.* Cell'24

2. **[Scientific discovery in the age of artificial intelligence.](https://www.nature.com/articles/s41586-023-04217-0)**  
    *Hanchen Wang, Tianfan Fu, Yuanqi Du, Wenhao Gao, Kexin Huang, Ziming Liu, Payal Chandak, Shengchao Liu, Peter Van Katwyk, Andreea Deac, et al.* Nature'23

3. **[The ai scientist: Towards fully automated open-ended scientific discovery.](https://arxiv.org/abs/2408.06292)**  
    *Chris Lu, Cong Lu, Robert Tjarko Lange, Jakob Foerster, Jeff Clune, David Ha.* Preprint'24

4. **[SciAgents: Automating scientific discovery through multi-agent intelligent graph reasoning.](https://arxiv.org/abs/2409.05556)**  
    *Alireza Ghafarollahi, Markus J. Buehler.* Preprint'24

5. **[Nobel Turing Challenge: creating the engine for scientific discovery.](https://www.nature.com/articles/s41592-021-01091-w)**  
    *Hiroaki Kitano.* NPJ Systems Biology and Applications'21

6. **[Artificial intelligence to win the nobel prize and beyond: Creating the engine for scientific discovery.](https://www.aaai.org/ojs/index.php/aimagazine/article/view/2624)**  
    *Hiroaki Kitano.* AI Magazine'16

7. **[Gflownets for ai-driven scientific discovery.](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d3dd00056b)**  
    *Moksh Jain, Tristan Deleu, Jason Hartford, Cheng-Hao Liu, Alex Hernandez-Garcia, Yoshua Bengio.* Digital Discovery'23

8. **[LLM-Based Agents Utilized in a Trustworthy Artificial Conscience Model for Controlling AI in Medical Applications.](https://link.springer.com/chapter/10.1007/978-3-031-19090-3_18)**  
    *Davinder Kaur, Suleyman Uslu, Mimoza Durresi, Arjan Durresi.* International Conference on Advanced Information Networking and Applications'24

9. **[MedAide: Towards an Omni Medical Aide via Specialized LLM-based Multi-Agent Collaboration.](https://arxiv.org/abs/2410.12532)**  
    *Jinjie Wei, Dingkang Yang, Yanshu Li, Qingyao Xu, Zhaoyu Chen, Mingcheng Li, Yue Jiang, Xiaolu Hou, Lihua Zhang.* Preprint'24

10. **[LLM-Based Framework for Administrative Task Automation in Healthcare.](https://ieeexplore.ieee.org/document/9830653)**  
    *Senay A. Gebreab, Khaled Salah, Raja Jayaraman, Muhammad Habib ur Rehman, Samer Ellaham.* IEEE ISDFS'24

11. **[BioKGBench: A Knowledge Graph Checking Benchmark of AI Agent for Biomedical Science.](https://arxiv.org/abs/2407.00466)**  
    *Xinna Lin, Siqi Ma, Junjie Shan, Xiaojing Zhang, Shell Xu Hu, Tiannan Guo, Stan Z. Li, Kaicheng Yu.* Preprint'24

12. **[Exploring LLM Multi-Agents for ICD Coding.](https://arxiv.org/abs/2406.15363)**  
    *Rumeng Li, Xun Wang, Hong Yu.* Preprint'24

13. **[Beyond Direct Diagnosis: LLM-based Multi-Specialist Agent Consultation for Automatic Diagnosis.](https://arxiv.org/abs/2401.16107)**  
    *Haochun Wang, Sendong Zhao, Zewen Qiang, Nuwa Xi, Bing Qin, Ting Liu.* Preprint'24

14. **[Large Language Models as Agents in the Clinic.](https://arxiv.org/abs/2309.10895)**  
    *Nikita Mehandru, Brenda Y. Miao, Eduardo Rodriguez Almaraz, Madhumita Sushil, Atul J. Butte, Ahmed Alaa.* Preprint'23

15. **[ColaCare: Enhancing Electronic Health Record Modeling through Large Language Model-Driven Multi-Agent Collaboration.](https://arxiv.org/abs/2410.02551)**  
    *Zixiang Wang, Yinghao Zhu, Huiya Zhao, Xiaochen Zheng, Tianlong Wang, Wen Tang, Yasha Wang, Chengwei Pan, Ewen M. Harrison, Junyi Gao, et al.* Preprint'24

16. **[Zodiac: A Cardiologist-Level LLM Framework for Multi-Agent Diagnostics.](https://arxiv.org/abs/2410.02026)**  
    *Yuan Zhou, Peng Zhang, Mengya Song, Alice Zheng, Yiwen Lu, Zhiheng Liu, Yong Chen, Zhaohan Xi.* Preprint'24

17. **[LLMs-based Few-Shot Disease Predictions using EHR: A Novel Approach Combining Predictive Agent Reasoning and Critical Agent Instruction.](https://arxiv.org/abs/2403.15464)**  
    *Hejie Cui, Zhuocheng Shen, Jieyu Zhang, Hui Shao, Lianhui Qin, Joyce C. Ho, Carl Yang.* Preprint'24

18. **[Medagents: Large language models as collaborators for zero-shot medical reasoning.](https://arxiv.org/abs/2311.10537)**  
    *Xiangru Tang, Anni Zou, Zhuosheng Zhang, Ziming Li, Yilun Zhao, Xingyao Zhang, Arman Cohan, Mark Gerstein.* Preprint'23

19. **[Improved precision oncology question-answering using agentic LLM.](https://www.medrxiv.org/content/10.1101/2024.09.19.2024.09)**  
    *Rangan Das, K Maheswari, Shaheen Siddiqui, Nikita Arora, Ankush Paul, Jeet Nanshi, Varun Udbalkar, Apoorva Sarvade, Harsha Chaturvedi, Tammy Shvartsman, et al.* medRxiv'24

20. **[MALADE: Orchestration of LLM-powered Agents with Retrieval Augmented Generation for Pharmacovigilance.](https://arxiv.org/abs/2408.01869)**  
    *Jihye Choi, Nils Palumbo, Prasad Chalasani, Matthew M. Engelhard, Somesh Jha, Anivarya Kumar, David Page.* Preprint'24

21. **[Evaluating large language models as agents in the clinic.](https://www.nature.com/articles/s41591-024-04447-0)**  
    *Nikita Mehandru, Brenda Y. Miao, Eduardo Rodriguez Almaraz, Madhumita Sushil, Atul J. Butte, Ahmed Alaa.* NPJ Digital Medicine'24

22. **[GPT-4 as a biomedical simulator.](https://www.sciencedirect.com/science/article/pii/S0010482524000932)**  
    *Moritz Schaefer, Stephan Reichl, Rob Ter Horst, Adele M. Nicolas, Thomas Krausgruber, Francesco Piras, Peter Stepper, Christoph Bock, Matthias Samwald.* Computers in Biology and Medicine'24

23. **[Unleashing the power of graph learning through llm-based autonomous agents.](https://arxiv.org/abs/2309.04565)**  
    *Lanning Wei, Zhiqiang He, Huan Zhao, Quanming Yao.* Preprint'23

24. **[Phenomics Assistant: An Interface for LLM-based Biomedical Knowledge Graph Exploration.](https://biorxiv.org/content/10.1101/2024.01.23.2024.01)**  
    *Shawn T. O'Neil, Kevin Schaper, Glass Elsarboukh, Justin T. Reese, Sierra AT Moxon, Nomi L. Harris, Monica C. Munoz-Torres, Peter N. Robinson, Melissa A. Haendel, Christopher J. Mungall.* bioRxiv'24

25. **[Exploring large language model based intelligent agents: Definitions, methods, and prospects.](https://arxiv.org/abs/2401.03428)**  
    *Yuheng Cheng, Ceyao Zhang, Zhengwen Zhang, Xiangrui Meng, Sirui Hong, Wenhao Li, Zihao Wang, Zekai Wang, Feng Yin, Junhua Zhao, et al.* Preprint'24

26. **[AI for Biomedicine in the Era of Large Language Models.](https://arxiv.org/abs/2403.15673)**  
    *Zhenyu Bi, Sajib Acharjee Dip, Daniel Hajialigol, Sindhura Kommu, Hanwen Liu, Meng Lu, Xuan


## Overview papers on LLM-powered AI Agents

## AI Agents in Medical Decision Support

## AI Agents in Biomedical Data Analysis


## AI Agents in End-to-end biomedical discoveries


## Programming Frameworks

## Future Outlooks
