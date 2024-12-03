# Awesome AI Agents for Scientific Discovery [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of LLM powered AI Agents in Biomedical Research. Medical Image Analysis, Multi-omics Genomics Analysis, Biomedical Scientific Discoveries. Here, we trace the rapid developments of AI Agents in Biomedical Reswearch, including milestone researchs, surveys, benchmark datasets, open-source code implementations, etc.

## Introduction
The emergence of AI agents in biomedical research marks a significant paradigm shift in how we approach complex healthcare and biological challenges. While foundation models (language, vision, and multimodal) have shown remarkable capabilities in medical imaging, text analysis, and genomics, they face three major limitations: insufficient biomedical training data compared to general domains; the inherently open-ended nature of biomedical research questions where hallucination risks pose serious concerns; and their inability to support dynamic, iterative research workflows that require continuous feedback and adaptation. To address these challenges, LLM-powered AI agents have emerged as a promising solution, decomposing complex biomedical tasks into modular components handled by specialized foundation models, while using a master model to orchestrate the entire workflow and maintain dynamic reasoning chains. This approach has demonstrated success in various applications including chemical research automation, medical decision support, and scientific literature analysis. This repository collects and organizes key research papers and developments (up to November 2024) in biomedical AI agents, aiming to facilitate research and development in this rapidly evolving field.


## 格局小了⬆️ 我们要做agents for scientific discovery！



A curated list of papers about AI agents for scientific discovery and research automation.

## Table of Contents
1. [Foundations & Vision](#foundations--vision)
2. [Core Technologies](#core-technologies)
3. [Scientific Process Automation](#scientific-process-automation)
4. [Domain Applications](#domain-applications)
5. [Infrastructure & Tools](#infrastructure--tools)
6. [Evaluation & Benchmarking](#evaluation--benchmarking)
7. [Surveys & Reviews](#surveys--reviews)

## Foundations & Vision

### Vision Papers
- **[Nobel Turing Challenge: Creating the Engine for Scientific Discovery](https://www.nature.com/articles/s41592-021-01091-w)**  
  *Hiroaki Kitano.* NPJ Systems Biology and Applications 2021

- **[Artificial Intelligence to Win the Nobel Prize and Beyond: Creating the Engine for Scientific Discovery](https://www.aaai.org/ojs/index.php/aimagazine/article/view/2624)**  
  *Hiroaki Kitano.* AI Magazine 2016

- **[The AI Scientist: Towards Fully Automated Open-ended Scientific Discovery](https://arxiv.org/abs/2408.06292)**  
  *Chris Lu, Cong Lu, Robert Tjarko Lange, Jakob Foerster, Jeff Clune, David Ha.* arXiv 2024

- **[Emergent autonomous scientific research capabilities of large language models](https://arxiv.org/abs/2304.05332)**  
  *Daniil A Boiko, Robert MacKnight, Gabe Gomes.* arXiv 2023

- **[What is missing in autonomous discovery: open challenges for the community](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d3dd00089c)**  
  *Phillip M Maffettone, Pascal Friederich, Sterling G Baird, et al.* Digital Discovery 2023

- **[The future of fundamental science led by generative closed-loop artificial intelligence](https://arxiv.org/abs/2307.07522)**  
  *Hector Zenil, Jesper Tegnér, Felipe S Abrahão, Alexander Lavin, et al.* arXiv 2023

## Core Technologies

### Multi-Agent Systems & Architectures
- **[CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society](https://proceedings.neurips.cc/paper_files/paper/2023/hash/9a86e0c5-e09e-4ad7-96d6-b2ed61855e37-Abstract-Conference.html)**  
  *Guohao Li, Hasan Hammoud, Hani Itani, Dmitrii Khizbullin, Bernard Ghanem.* NeurIPS 2023

- **[Dynamic LLM-Agent Network: An LLM-Agent Collaboration Framework with Agent Team Optimization](https://arxiv.org/abs/2310.02170)**  
  *Zijun Liu, Yanzhe Zhang, Peng Li, Yang Liu, Diyi Yang.* arXiv 2023

- **[AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework](https://arxiv.org/abs/2308.08155)**  
  *Qingyun Wu, Gagan Bansal, Jieyu Zhang, Yiran Wu, et al.* arXiv 2023

### Reasoning & Knowledge Systems
- **[Graph of Thoughts: Solving Elaborate Problems with Large Language Models](https://ojs.aaai.org/index.php/AAAI/article/view/28877)**  
  *Maciej Besta, Nils Blach, Ales Kubicek, Robert Gerstenberger, et al.* AAAI 2024

- **[KnowAgent: Knowledge-augmented Planning for LLM-based Agents](https://arxiv.org/abs/2403.03101)**  
  *Yuqi Zhu, Shuofei Qiao, Yixin Ou, Shumin Deng, et al.* arXiv 2024

- **[Improving Factuality and Reasoning in Language Models through Multiagent Debate](https://arxiv.org/abs/2305.14325)**  
  *Yilun Du, Shuang Li, Antonio Torralba, Joshua B. Tenenbaum, Igor Mordatch.* arXiv 2023

## Scientific Process Automation

### Research Planning & Literature Review
- **[ResearchAgent: Iterative Research Idea Generation over Scientific Literature with Large Language Models](https://arxiv.org/abs/2404.07738)**  
  *Jinheon Baek, Sujay Kumar Jauhar, Silviu Cucerzan, Sung Ju Hwang.* arXiv 2024

- **[SciMon: Scientific Inspiration Machines Optimized for Novelty](https://arxiv.org/abs/2305.14259)**  
  *Qingyun Wang, Doug Downey, Heng Ji, Tom Hope.* arXiv 2023

- **[AutoSurvey: Large Language Models Can Automatically Write Surveys](https://arxiv.org/abs/2406.10252)**  
  *Yidong Wang, Qi Guo, Wenjin Yao, Hongbo Zhang, et al.* arXiv 2024

### Experimental Design & Workflow
- **[DISCOVERYWORLD: A Virtual Environment for Developing and Evaluating Automated Scientific Discovery Agents](https://arxiv.org/abs/2406.06769)**  
  *Peter Jansen, Marc-Alexandre Côté, Tushar Khot, Erin Bransom, et al.* arXiv 2024

- **[Genesis: Towards the Automation of Systems Biology Research](https://arxiv.org/abs/2408.10689)**  
  *Ievgeniia A Tiukova, Daniel Brunnsåker, Erik Y Bjurström, Alexander H Gower, et al.* arXiv 2024

## Domain Applications

### Healthcare & Medicine

#### Clinical Decision Support & Diagnosis
- **[MedAide: Towards an Omni Medical Aide via Specialized LLM-based Multi-Agent Collaboration](https://arxiv.org/abs/2410.12532)**  
  *Jinjie Wei, Dingkang Yang, Yanshu Li, Qingyao Xu, et al.* arXiv 2024

- **[Beyond Direct Diagnosis: LLM-based Multi-Specialist Agent Consultation for Automatic Diagnosis](https://arxiv.org/abs/2401.16107)**  
  *Haochun Wang, Sendong Zhao, Zewen Qiang, Nuwa Xi, et al.* arXiv 2024

- **[Large Language Models as Agents in the Clinic](https://arxiv.org/abs/2309.10895)**  
  *Nikita Mehandru, Brenda Y. Miao, Eduardo Rodriguez Almaraz, et al.* NPJ Digital Medicine 2024

- **[MAGDA: Multi-Agent Guideline-Driven Diagnostic Assistance](https://link.springer.com/chapter/10.1007/978-3-031-49673-3_15)**  
  *David Bani-Harouni, Nassir Navab, Matthias Keicher.* FMGMAI 2024

- **[MDAgents: An Adaptive Collaboration of LLMs for Medical Decision-Making](https://arxiv.org/abs/2411.00248)**  
  *Yubin Kim, Chanwoo Park, Hyewon Jeong, Yik Siu Chan, et al.* NeurIPS 2024

- **[ColaCare: Enhancing Electronic Health Record Modeling through Large Language Model-Driven Multi-Agent Collaboration](https://arxiv.org/abs/2410.02551)**  
  *Zixiang Wang, Yinghao Zhu, Huiya Zhao, Xiaochen Zheng, et al.* arXiv 2024

#### Medical Imaging & Pathology
- **[CXR-Agent: Vision-language models for chest X-ray interpretation with uncertainty aware radiology reporting](https://arxiv.org/abs/2407.08811)**  
  *Naman Sharma.* arXiv 2024

- **[PathGen-1.6M: 1.6 Million Pathology Image-text Pairs Generation through Multi-agent Collaboration](https://arxiv.org/abs/2407.00203)**  
  *Yuxuan Sun, Yunlong Zhang, Yixuan Si, Chenglu Zhu, et al.* arXiv 2024

#### Healthcare Administration
- **[LLM-Based Framework for Administrative Task Automation in Healthcare](https://ieeexplore.ieee.org/document/10446484)**  
  *Senay A Gebreab, Khaled Salah, Raja Jayaraman, Muhammad Habib ur Rehman, Samer Ellaham.* IEEE ISDFS 2024

- **[Exploring LLM Multi-Agents for ICD Coding](https://arxiv.org/abs/2406.15363)**  
  *Rumeng Li, Xun Wang, Hong Yu.* arXiv 2024

#### Medical Education & Training
- **[Medco: Medical education copilots based on a multi-agent framework](https://arxiv.org/abs/2408.12496)**  
  *Hao Wei, Jianing Qiu, Haibao Yu, Wu Yuan.* arXiv 2024

- **[AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments](https://arxiv.org/abs/2405.07960)**  
  *Samuel Schmidgall, Rojin Ziaei, Carl Harris, Eduardo Reis, et al.* arXiv 2024

### Biology & Life Sciences

#### Genomics & Molecular Biology
- **[BioDiscoveryAgent: An AI Agent for Designing Genetic Perturbation Experiments](https://arxiv.org/abs/2405.17631)**  
  *Yusuf Roohani, Andrew Lee, Qian Huang, Jian Vora, et al.* arXiv 2024

- **[GeneAgent: Self-verification Language Agent for Gene Set Knowledge Discovery using Domain Databases](https://arxiv.org/abs/2405.16205)**  
  *Zhizheng Wang, Qiao Jin, Chih-Hsuan Wei, Shubo Tian, et al.* arXiv 2024

- **[SeqMate: A Novel Large Language Model Pipeline for Automating RNA Sequencing](https://arxiv.org/abs/2407.03381)**  
  *Devam Mondal, Atharva Inamdar.* arXiv 2024

#### Cell Biology & Bioinformatics
- **[CellAgent: An LLM-driven Multi-Agent Framework for Automated Single-cell Data Analysis](https://www.biorxiv.org/content/10.1101/2024.05.13.593861v1)**  
  *Yihang Xiao, Jinyi Liu, Yan Zheng, Xiaohan Xie, et al.* bioRxiv 2024

- **[Bioinformatics Copilot 2.0 for Transcriptomic Data Analysis](https://www.biorxiv.org/content/10.1101/2024.08.15.607673v1)**  
  *Yongheng Wang, Weidi Zhang, Ian Wong, Siyu Lin, et al.* bioRxiv 2024

- **[BRAD: Bioinformatics Retrieval Augmentation Data Digital Assistant](https://arxiv.org/abs/2409.02864)**  
  *Joshua Pickard, Marc Andrew Choi, Natalie Oliven, Cooper Stansbury, et al.* arXiv 2024

### Chemistry & Materials Science
- **[ChatMol Copilot: An Agent for Molecular Modeling and Computation Powered by LLMs](https://aclanthology.org/2024.lm-1.6/)**  
  *Jinyuan Sun, Auston Li, Yifan Deng, Jiabo Li.* L+M Workshop 2024

- **[DrugAgent: Explainable Drug Repurposing Agent with Large Language Model-based Reasoning](https://arxiv.org/abs/2408.13378)**  
  *Yoshitaka Inoue, Tianci Song, Tianfan Fu.* arXiv 2024

- **[A review of large language models and autonomous agents in chemistry](https://arxiv.org/abs/2407.01603)**  
  *Mayk Caldas Ramos, Christopher J Collison, Andrew D White.* arXiv 2024

### Earth & Environmental Sciences
- **[An LLM Agent for Automatic Geospatial Data Analysis](https://arxiv.org/abs/2410.18792)**  
  *Yuxing Chen, Weijie Wang, Sylvain Lobry, Camille Kurtz.* arXiv 2024

## Evaluation & Benchmarking

### General Benchmarks
- **[AgentBench: Evaluating LLMs as Agents](https://arxiv.org/abs/2308.03688)**  
  *Xiao Liu, Hao Yu, Hanchen Zhang, Yifan Xu, et al.* arXiv 2023

- **[ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate](https://arxiv.org/abs/2308.07201)**  
  *Chi-Min Chan, Weize Chen, Yusheng Su, Jianxuan Yu, et al.* arXiv 2023

### Domain-Specific Benchmarks
- **[BioKGBench: A Knowledge Graph Checking Benchmark of AI Agent for Biomedical Science](https://arxiv.org/abs/2407.00466)**  
  *Xinna Lin, Siqi Ma, Junjie Shan, Xiaojing Zhang, et al.* arXiv 2024

- **[GenoTEX: A Benchmark for Evaluating LLM-Based Exploration of Gene Expression Data](https://arxiv.org/abs/2406.15341)**  
  *Haoyang Liu, Haohan Wang.* arXiv 2024

- **[IdeaBench: Benchmarking Large Language Models for Research Idea Generation](https://arxiv.org/abs/2411.02429)**  
  *Sikun Guo, Amir Hassan Shariatmadari, Guangzhi Xiong, Albert Huang, et al.* arXiv 2024

## Surveys & Reviews

### General Surveys
- **[Scientific discovery in the age of artificial intelligence](https://www.nature.com/articles/s41586-023-06221-2)**  
  *Hanchen Wang, Tianfan Fu, Yuanqi Du, Wenhao Gao, Kexin Huang, et al.* Nature 2023

- **[A survey on LLM-based multi-agent systems: workflow, infrastructure, and challenges](https://link.springer.com/article/10.1007/s44223-024-00009-0)**  
  *Xinyi Li, Sai Wang, Siqi Zeng, Yu Wu, Yi Yang.* Vicinagearth 2024

- **[Large language model based multi-agents: A survey of progress and challenges](https://arxiv.org/abs/2402.01680)**  
  *Taicheng Guo, Xiuying Chen, Yaqi Wang, Ruidi Chang, et al.

## Surveys & Reviews (Continued)

### General Surveys
- **[The rise and potential of large language model based agents: A survey](https://arxiv.org/abs/2309.07864)**  
  *Zhiheng Xi, Wenxiang Chen, Xin Guo, Wei He, et al.* arXiv 2023

- **[Exploring large language model based intelligent agents: Definitions, methods, and prospects](https://arxiv.org/abs/2401.03428)**  
  *Yuheng Cheng, Ceyao Zhang, Zhengwen Zhang, Xiangrui Meng, et al.* arXiv 2024

- **[A Survey on the Memory Mechanism of Large Language Model Based Agents](https://arxiv.org/abs/2404.13501)**  
  *Zeyu Zhang, Xiaohe Bo, Chen Ma, Rui Li, et al.* arXiv 2024

### Domain-Specific Surveys
- **[Large Language Models in Healthcare: Applications and Perspectives](https://arxiv.org/abs/2311.01918)**  
  *Mingze Yuan, Peng Bao, Jiajia Yuan, Yunhao Shen, et al.* arXiv 2023

- **[A Survey on Medical Large Language Models: Technology, Application, Trustworthiness, and Future Directions](https://arxiv.org/abs/2406.03712)**  
  *Lei Liu, Xiaoyan Yang, Junchi Lei, Xiaoyang Liu, et al.* arXiv 2024

- **[AI for Biomedicine in the Era of Large Language Models](https://arxiv.org/abs/2403.15673)**  
  *Zhenyu Bi, Sajib Acharjee Dip, Daniel Hajialigol, Sindhura Kommu, et al.* arXiv 2024

- **[From LLMs to LLM-based Agents for Software Engineering: A Survey](https://arxiv.org/abs/2408.02479)**  
  *Haolin Jin, Linghan Huang, Haipeng Cai, Jun Yan, et al.* arXiv 2024

### Literature Reviews
- **[Leveraging Large Language Models for Enhancing Literature-Based Discovery](https://www.mdpi.com/2504-2289/8/11/146)**  
  *Ikbal Taleb, Alramzana Nujum Navaz, Mohamed Adel Serhani.* Big Data and Cognitive Computing 2024

## Domain Applications (Continued)

### Healthcare & Medicine (Continued)

#### Clinical Applications
- **[RDguru: A conversational intelligent agent for rare diseases](https://ieeexplore.ieee.org/document/10468546)**  
  *Jian Yang, Liqi Shu, Huilong Duan, Haomin Li.* IEEE JBHI 2024

- **[Zodiac: A Cardiologist-Level LLM Framework for Multi-Agent Diagnostics](https://arxiv.org/abs/2410.02026)**  
  *Yuan Zhou, Peng Zhang, Mengya Song, Alice Zheng, et al.* arXiv 2024

- **[GPT-4 as a biomedical simulator](https://www.sciencedirect.com/science/article/pii/S001048252400183X)**  
  *Moritz Schaefer, Stephan Reichl, Rob Ter Horst, Adele M Nicolas, et al.* Computers in Biology and Medicine 2024

#### Healthcare Systems
- **[Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents](https://arxiv.org/abs/2405.02957)**  
  *Junkai Li, Siyu Wang, Meng Zhang, Weitao Li, et al.* arXiv 2024

- **[ClinicalLab: Aligning Agents for Multi-Departmental Clinical Diagnostics in the Real World](https://arxiv.org/abs/2406.13890)**  
  *Weixiang Yan, Haitian Liu, Tengxiao Wu, Qian Chen, et al.* arXiv 2024

- **[AIPatient: Simulating Patients with EHRs and LLM Powered Agentic Workflow](https://arxiv.org/abs/2409.18924)**  
  *Huizi Yu, Jiayan Zhou, Lingyao Li, Shan Chen, et al.* arXiv 2024

### Biology & Life Sciences (Continued)

#### Tools & Platforms
- **[BIA: BioInformatics Agent - Unleashing the Power of Large Language Models to Reshape Bioinformatics Workflow](https://www.biorxiv.org/content/10.1101/2024.05.22.595240v1)**  
  *Qi Xin, Quyu Kong, Hongyi Ji, Yue Shen, et al.* bioRxiv 2024

- **[Phenomics Assistant: An Interface for LLM-based Biomedical Knowledge Graph Exploration](https://www.biorxiv.org/content/10.1101/2024.01.31.578275v1)**  
  *Shawn T O'Neil, Kevin Schaper, Glass Elsarboukh, Justin T Reese, et al.* bioRxiv 2024

- **[Simplifying bioinformatics data analysis through conversation](https://www.biorxiv.org/content/10.1101/2023.10.29.564479v1)**  
  *Zhengyuan Dong, Han Zhou, Yifan Jiang, Victor Zhong, et al.* bioRxiv 2023

#### Research & Discovery
- **[Large Language Models as Biomedical Hypothesis Generators: A Comprehensive Evaluation](https://arxiv.org/abs/2407.08940)**  
  *Biqing Qi, Kaiyan Zhang, Kai Tian, Haoxiang Li, et al.* arXiv 2024

- **[Malade: Orchestration of LLM-powered agents with retrieval augmented generation for pharmacovigilance](https://arxiv.org/abs/2408.01869)**  
  *Jihye Choi, Nils Palumbo, Prasad Chalasani, Matthew M Engelhard, et al.* arXiv 2024

- **[Improved precision oncology question-answering using agentic LLM](https://www.medrxiv.org/content/10.1101/2024.09.20.24314076v1)**  
  *Rangan Das, K Maheswari, Shaheen Siddiqui, Nikita Arora, et al.* medRxiv 2024

### Software & Tool Development

#### Development & Analysis
- **[Agentless: Demystifying LLM-based Software Engineering Agents](https://arxiv.org/abs/2407.01489)**  
  *Chunqiu Steven Xia, Yinlin Deng, Soren Dunn, Lingming Zhang.* arXiv 2024

- **[Intelligent Agents with LLM-based Process Automation](https://dl.acm.org/doi/10.1145/3580305.3599843)**  
  *Yanchu Guan, Dong Wang, Zhixuan Chu, Shiyu Wang, et al.* KDD 2024

#### Security & Trust
- **[TrustAgent: Towards Safe and Trustworthy LLM-based Agents through Agent Constitution](https://arxiv.org/abs/2401.05330)**  
  *Wenyue Hua, Xianjun Yang, Mingyu Jin, Zelong Li, et al.* TiFA 2024

- **[Exploring LLM-based Agents for Root Cause Analysis](https://dl.acm.org/doi/10.1145/3624028.3624067)**  
  *Devjeet Roy, Xuchao Zhang, Rashi Bhave, Chetan Bansal, et al.* FSE 2024
