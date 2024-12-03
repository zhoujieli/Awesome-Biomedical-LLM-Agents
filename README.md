# Awesome AI Agents for Scientific Discovery [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of papers about AI agents for scientific discovery and research automation.


Maintained by [Jieli Zhou](mailto:zhoujieli@sjtu.edu.cn)

If you use this paper list for your research, please cite it using:
```bibtex
@misc{zhou2024awesome,
  title={Awesome AI Agents for Scientific Discovery},
  author={Zhou, Jieli},
  year={2024},
  publisher={GitHub},
  journal={GitHub repository},
  howpublished={\url{https://github.com/yourusername/awesome-ai-agents-science}}
}
```


## Introduction

The convergence of large language models (LLMs) and autonomous agents has ushered in a new era in scientific discovery, fundamentally transforming how research is conducted across disciplines. This emerging paradigm, articulated in Kitano's seminal "Nobel Turing Challenge" (2021), envisions AI systems capable of making scientific discoveries worthy of Nobel Prize recognition. Recent advances in LLM-based agents have brought us closer to this vision, enabling increasingly sophisticated automation of scientific workflows and decision-making processes.

### Evolution and Current Landscape

The field has evolved rapidly since early visions of AI-driven scientific discovery. While traditional AI systems focused on narrow tasks, modern LLM-based agents demonstrate remarkable capabilities in complex scientific reasoning, experimental design, and hypothesis generation. The breakthrough capabilities of models like GPT-4 have catalyzed this transition, enabling agents to engage in sophisticated scientific discourse, interpret complex data, and even design novel experiments.

### Key Research Directions

Several major research themes have emerged in this space:

1. **Multi-Agent Architectures**: Research has increasingly focused on collaborative multi-agent systems, where specialized agents work together to tackle complex scientific problems.

2. **Domain-Specific Applications**: The healthcare sector has seen particularly rapid adoption, with agents being developed for clinical decision support, medical diagnosis, and healthcare administration.

3. **Scientific Process Automation**: Agents are being developed to automate various aspects of the research pipeline, from literature review and hypothesis generation to experimental design and data analysis.

### Impact and Future Directions

The emergence of AI agents in scientific discovery represents more than just technological advancement; it signals a fundamental shift in how science is conducted. These systems promise to:
- Accelerate the pace of scientific discovery
- Enable exploration of previously intractable research questions
- Democratize access to scientific expertise
- Foster more efficient use of research resources

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
- **[MDAgents: An Adaptive Collaboration of LLMs for Medical Decision-Making](https://arxiv.org/abs/2411.00248)**  
  *Yubin Kim, Chanwoo Park, Hyewon Jeong, Yik Siu Chan, et al.* NeurIPS 2024

- **[Beyond Direct Diagnosis: LLM-based Multi-Specialist Agent Consultation for Automatic Diagnosis](https://arxiv.org/abs/2401.16107)**  
  *Haochun Wang, Sendong Zhao, Zewen Qiang, Nuwa Xi, et al.* arXiv 2024

- **[MedAide: Towards an Omni Medical Aide via Specialized LLM-based Multi-Agent Collaboration](https://arxiv.org/abs/2410.12532)**  
  *Jinjie Wei, Dingkang Yang, Yanshu Li, Qingyao Xu, et al.* arXiv 2024

- **[Large Language Models as Agents in the Clinic](https://arxiv.org/abs/2309.10895)**  
  *Nikita Mehandru, Brenda Y. Miao, Eduardo Rodriguez Almaraz, et al.* NPJ Digital Medicine 2024

- **[MAGDA: Multi-Agent Guideline-Driven Diagnostic Assistance](https://link.springer.com/chapter/10.1007/978-3-031-49673-3_15)**  
  *David Bani-Harouni, Nassir Navab, Matthias Keicher.* FMGMAI 2024

#### Healthcare Systems & Management
- **[ColaCare: Enhancing Electronic Health Record Modeling through Large Language Model-Driven Multi-Agent Collaboration](https://arxiv.org/abs/2410.02551)**  
  *Zixiang Wang, Yinghao Zhu, Huiya Zhao, Xiaochen Zheng, et al.* arXiv 2024

- **[Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents](https://arxiv.org/abs/2405.02957)**  
  *Junkai Li, Siyu Wang, Meng Zhang, Weitao Li, et al.* arXiv 2024

- **[ClinicalLab: Aligning Agents for Multi-Departmental Clinical Diagnostics in the Real World](https://arxiv.org/abs/2406.13890)**  
  *Weixiang Yan, Haitian Liu, Tengxiao Wu, Qian Chen, et al.* arXiv 2024

- **[AIPatient: Simulating Patients with EHRs and LLM Powered Agentic Workflow](https://arxiv.org/abs/2409.18924)**  
  *Huizi Yu, Jiayan Zhou, Lingyao Li, Shan Chen, et al.* arXiv 2024

#### Medical Education & Training
- **[Medco: Medical education copilots based on a multi-agent framework](https://arxiv.org/abs/2408.12496)**  
  *Hao Wei, Jianing Qiu, Haibao Yu, Wu Yuan.* arXiv 2024

- **[AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments](https://arxiv.org/abs/2405.07960)**  
  *Samuel Schmidgall, Rojin Ziaei, Carl Harris, Eduardo Reis, et al.* arXiv 2024

#### Medical Imaging & Pathology
- **[CXR-Agent: Vision-language models for chest X-ray interpretation with uncertainty aware radiology reporting](https://arxiv.org/abs/2407.08811)**  
  *Naman Sharma.* arXiv 2024

- **[PathGen-1.6M: 1.6 Million Pathology Image-text Pairs Generation through Multi-agent Collaboration](https://arxiv.org/abs/2407.00203)**  
  *Yuxuan Sun, Yunlong Zhang, Yixuan Si, Chenglu Zhu, et al.* arXiv 2024

### Biology & Life Sciences

#### Genomics & Molecular Biology
- **[BioDiscoveryAgent: An AI Agent for Designing Genetic Perturbation Experiments](https://arxiv.org/abs/2405.17631)**  
  *Yusuf Roohani, Andrew Lee, Qian Huang, Jian Vora, et al.* arXiv 2024

- **[GeneAgent: Self-verification Language Agent for Gene Set Knowledge Discovery using Domain Databases](https://arxiv.org/abs/2405.16205)**  
  *Zhizheng Wang, Qiao Jin, Chih-Hsuan Wei, Shubo Tian, et al.* arXiv 2024

- **[Large Language Models as Biomedical Hypothesis Generators: A Comprehensive Evaluation](https://arxiv.org/abs/2407.08940)**  
  *Biqing Qi, Kaiyan Zhang, Kai Tian, Haoxiang Li, et al.* arXiv 2024

#### Bioinformatics Tools & Platforms
- **[BIA: BioInformatics Agent - Unleashing the Power of Large Language Models to Reshape Bioinformatics Workflow](https://www.biorxiv.org/content/10.1101/2024.05.22.595240v1)**  
  *Qi Xin, Quyu Kong, Hongyi Ji, Yue Shen, et al.* bioRxiv 2024

- **[CellAgent: An LLM-driven Multi-Agent Framework for Automated Single-cell Data Analysis](https://www.biorxiv.org/content/10.1101/2024.05.13.593861v1)**  
  *Yihang Xiao, Jinyi Liu, Yan Zheng, Xiaohan Xie, et al.* bioRxiv 2024

- **[SeqMate: A Novel Large Language Model Pipeline for Automating RNA Sequencing](https://arxiv.org/abs/2407.03381)**  
  *Devam Mondal, Atharva Inamdar.* arXiv 2024

### Chemistry & Materials Science

#### Drug Discovery & Development
- **[DrugAgent: Explainable Drug Repurposing Agent with Large Language Model-based Reasoning](https://arxiv.org/abs/2408.13378)**  
  *Yoshitaka Inoue, Tianci Song, Tianfan Fu.* arXiv 2024

- **[Malade: Orchestration of LLM-powered agents with retrieval augmented generation for pharmacovigilance](https://arxiv.org/abs/2408.01869)**  
  *Jihye Choi, Nils Palumbo, Prasad Chalasani, Matthew M Engelhard, et al.* arXiv 2024

#### Molecular Modeling & Computation
- **[ChatMol Copilot: An Agent for Molecular Modeling and Computation Powered by LLMs](https://aclanthology.org/2024.lm-1.6/)**  
  *Jinyuan Sun, Auston Li, Yifan Deng, Jiabo Li.* L+M Workshop 2024

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

- **[Benchmarking large language models as ai research agents](https://arxiv.org/abs/2311.12741)**  
  *Qian Huang, Jian Vora, Percy Liang, Jure Leskovec.* NeurIPS 2023 Workshop

### Domain-Specific Benchmarks
- **[BioKGBench: A Knowledge Graph Checking Benchmark of AI Agent for Biomedical Science](https://arxiv.org/abs/2407.00466)**  
  *Xinna Lin, Siqi Ma, Junjie Shan, Xiaojing Zhang, et al.* arXiv 2024

- **[GenoTEX: A Benchmark for Evaluating LLM-Based Exploration of Gene Expression Data](https://arxiv.org/abs/2406.15341)**  
  *Haoyang Liu, Haohan Wang.* arXiv 2024

- **[IdeaBench: Benchmarking Large Language Models for Research Idea Generation](https://arxiv.org/abs/2411.02429)**  
  *Sikun Guo, Amir Hassan Shariatmadari, Guangzhi Xiong, Albert Huang, et al.* arXiv 2024

## Surveys & Reviews

### Comprehensive Surveys
- **[Scientific discovery in the age of artificial intelligence](https://www.nature.com/articles/s41586-023-06221-2)**  
  *Hanchen Wang, Tianfan Fu, Yuanqi Du, Wenhao Gao, Kexin Huang, et al.* Nature 2023

- **[The rise and potential of large language model based agents: A survey](https://arxiv.org/abs/2309.07864)**  
  *Zhiheng Xi, Wenxiang Chen, Xin Guo, Wei He, et al.* arXiv 2023

- **[Large language model based multi-agents: A survey of progress and challenges](https://arxiv.org/abs/2402.01680)**  
  *Taicheng Guo, Xiuying Chen, Yaqi Wang, Ruidi Chang, et al.* arXiv 2024

- **[A survey on LLM-based multi-agent systems: workflow, infrastructure, and challenges](https://link.springer.com/article/10.1007/s44223-024-00009-0)**  
  *Xinyi Li, Sai Wang, Siqi Zeng, Yu Wu, Yi Yang.* Vicinagearth 2024

### Domain-Specific Reviews
- **[AI for Biomedicine in the Era of Large Language Models](https://arxiv.org/abs/2403.15673)**  
  *Zhenyu Bi, Sajib Acharjee Dip, Daniel Hajialigol, Sindhura Kommu, et al.* arXiv 2024

- **[A Survey on Medical Large Language Models: Technology, Application, Trustworthiness, and Future Directions](https://arxiv.org/abs/2406.03712)**  
  *Lei Liu, Xiaoyan Yang, Junchi Lei, Xiaoyang Liu, et al.* arXiv 2024

- **[From LLMs to LLM-based Agents for Software Engineering: A Survey](https://arxiv.org/abs/2408.02479)**  
  *Haolin Jin, Linghan Huang, Haipeng Cai, Jun Yan, et al.* arXiv 2024

## Contributing

Please feel free to send a pull request if you want to:
- Add new papers
- Fix errors
- Update paper information

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)





