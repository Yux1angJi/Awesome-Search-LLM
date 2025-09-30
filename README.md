<div align="center">
  <h1>Awesome Search Algorithms for Test-Time Scaling</h1>
  
  <br><br> 
  <img width="800" alt="Test-time-scaling" src="./figures/shlab3.png">  

  <br><br> 

  [![Project Homepage](https://img.shields.io/badge/Homepage-Visit-orange)](https://agenticscience.github.io/)
  [![arXiv](https://img.shields.io/badge/arXiv-AwesomeSearch-red)](https://arxiv.org/abs/2508.14111)
  [![Citation](https://img.shields.io/badge/citation-0-blue)](https://example.com/citations)
  [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

  <br> 

Welcome to the **"Awesome Search"** repository ！

This repository, part of the **Intern Discovery** project, 

showcases **how AI/Agent is becoming a creative scientist, accelerating and reshaping scientific discovery**.

Explore this detailed repository to understand how autonomous agents are revolutionizing natural science!

🔔 🔔 🔔 For more detailed information, please refer to [our paper](https://arxiv.org/abs/2508.14111) or [homepage](https://agenticscience.github.io/)~

✉️ ➡️ 📪 If you have any questions, please feel free to contact us at:

**`{weijiaqi, yangyuejin}@pjlab.org.cn` | `xzhang23@ualberta.ca`**

</div>

## 📑 Contents

- [Part 1: MCTS for Direct Inference-Time Enhancement](#part-2-mcts-for-direct-inference-time-enhancement)
  - [General Reasoning & Problem Solving](#general-reasoning--problem-solving)
  - [Mathematical Reasoning](#mathematical-reasoning)
  - [Code Generation & Software Engineering](#code-generation--software-engineering)
  - [LLM Agents & Interactive Environments](#llm-agents--interactive-environments)
  - [Retrieval-Augmented Generation (RAG) & Knowledge-Intensive Tasks](#retrieval-augmented-generation-rag--knowledge-intensive-tasks)
  - [Multimodal Reasoning](#multimodal-reasoning)
- [Part 2: MCTS for Self-Improvement via Data Generation](#part-3-mcts-for-self-improvement-via-data-generation)
  - [Foundational Self-Improvement Frameworks](#foundational-self-improvement-frameworks)
  - [Applications in Specific Domains](#applications-in-specific-domains)
    - [General Capabilities & Alignment](#general-capabilities--alignment)
    - [Scientific & Specialized Domains](#scientific--specialized-domains)
    - [Multimodal Applications](#multimodal-applications)
- [Part 3: Advanced Topics and Hybrid Approaches](#part-4-advanced-topics-and-hybrid-approaches)
  - [Multi-Agent and Collaborative Search](#multi-agent-and-collaborative-search)
  - [Reward Model Design and Optimization](#reward-model-design-and-optimization)
  - [Search Efficiency and Dynamics](#search-efficiency-and-dynamics)

---

## Part 1: MCTS for Direct Inference-Time Enhancement

### General Reasoning & Problem Solving
<ul>
  <li>
    <i><b>Tree of Thoughts: Deliberate Problem Solving with Large Language Models</b></i>, Muralidharan, Jananee and Thomas, Tiju  
    <a href="https://arxiv.org/pdf/2305.10601" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2023-red" alt="arXiv 2023">
    </a>
  </li>
  <li>
    <i><b>Reasoning with language model is planning with world model</b></i>, Hao, Shibo et al.  
    <a href="https://arxiv.org/abs/2305.14992" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2023-red" alt="arXiv 2023">
    </a>
  </li>
  <li>
    <i><b>AlphaZero-Like Tree-Search can Guide Large Language Model Decoding and Training</b></i>, Feng, Xidong et al.  
    <a href="https://arxiv.org/pdf/2309.17179" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2023-red" alt="arXiv 2023">
    </a>
  </li>
  <li>
    <i><b>Towards self-improvement of llms via mcts: Leveraging stepwise knowledge with curriculum preference learning</b></i>, Wang, Xiyao et al.  
    <a href="https://arxiv.org/abs/2410.06508" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>
  <li>
    <i><b>PPL-MCTS: Constrained textual generation through discriminator-guided MCTS decoding</b></i>, Chaffin, Antoine et al.  
    <a href="https://arxiv.org/pdf/2109.13582" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2021-red" alt="arXiv 2021">
    </a>
  </li>
  <li>
    <i><b>Don't throw away your value model! Generating more preferable text with Value-Guided Monte-Carlo Tree Search decoding</b></i>, Liu, Jiacheng et al.  
    <a href="https://arxiv.org/pdf/2309.15028" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2023-red" alt="arXiv 2023">
    </a>
  </li>
  <li>
    <i><b>Args: Alignment as reward-guided search</b></i>, Khanov, Maxim et al.  
    <a href="http://arxiv.org/pdf/2402.01694" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>
  <li>
    <i><b>When is tree search useful for llm planning? it depends on the discriminator</b></i>, Chen, Ziru et al.  
    <a href="https://arxiv.org/pdf/2402.10890" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>
  <li>
    <i><b>Interpretable contrastive monte carlo tree search reasoning</b></i>, Gao, Zitian et al.  
    <a href="https://arxiv.org/pdf/2410.01707" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>
  <li>
    <i><b>Synthetic data generation from real data sources using monte carlo tree search and large language models</b></i>, Locowic, Leonardo et al.  
    <a href="https://www.authorea.com/doi/full/10.22541/au.172660477.72210139" target="_blank">
      <img src="https://img.shields.io/badge/Authorea-2024-blue" alt="Authorea 2024">
    </a>
  </li>
</ul>

### Mathematical Reasoning
<ul>

  <!-- Paper_2: ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search -->
  <li>
    <i><b>ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search</b></i>, Zhang et al.
    <a href="https://arxiv.org/abs/2406.03816" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_6: Toward self-improvement of llms via imagination, searching, and criticizing. -->
  <li>
    <i><b>Toward Self-Improvement of LLMs via Imagination, Searching, and Criticizing</b></i>, Tian et al.
    <a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/5e5853f35164e434015716a8c2a66543-Paper-Conference.pdf" target="_blank">
      <img src="https://img.shields.io/badge/NeurIPS-2024-blue" alt="NeurIPS 2024">
    </a>
  </li>

  <!-- Paper_7: Monte carlo tree search boosts reasoning via iterative preference learning -->
  <li>
    <i><b>Monte Carlo Tree Search Boosts Reasoning via Iterative Preference Learning</b></i>, Xie et al.
    <a href="https://arxiv.org/pdf/2405.00451" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_8: Accessing GPT-4 level Mathematical Olympiad Solutions via Monte Carlo Tree Self-refine with LLaMa-3 8B -->
  <li>
    <i><b>Accessing GPT-4 Level Mathematical Olympiad Solutions via Monte Carlo Tree Self-Refine with LLaMa-3 8B</b></i>, Zhang et al.
    <a href="https://arxiv.org/pdf/2406.07394" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_32: No train still gain. unleash mathematical reasoning of large language models with monte carlo tree search guided by energy function -->
  <li>
    <i><b>No Train Still Gain. Unleash Mathematical Reasoning of Large Language Models with Monte Carlo Tree Search Guided by Energy Function</b></i>, Xu et al.
    <a href="https://arxiv.org/pdf/2309.03224" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2023-red" alt="arXiv 2023">
    </a>
  </li>

  <!-- Paper_35: Mutual Reasoning Makes Smaller LLMs Stronger Problem-Solvers -->
  <li>
    <i><b>Mutual Reasoning Makes Smaller LLMs Stronger Problem-Solvers</b></i>, Qi et al.
    <a href="https://arxiv.org/pdf/2408.06195" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_36: AlphaMath Almost Zero: Process Supervision without Process -->
  <li>
    <i><b>AlphaMath Almost Zero: Process Supervision Without Process</b></i>, Chen et al.
    <a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/30dfe47a3ccbee68cffa0c19ccb1bc00-Paper-Conference.pdf" target="_blank">
      <img src="https://img.shields.io/badge/NeurIPS-2024-blue" alt="NeurIPS 2024">
    </a>
  </li>

  <!-- Paper_41: LiteSearch: Efficacious Tree Search for LLM -->
  <li>
    <i><b>LiteSearch: Efficacious Tree Search for LLM</b></i>, Wang et al.
    <a href="https://arxiv.org/pdf/2407.00320" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_48: Markov Chain of Thought for Efficient Mathematical Reasoning -->
  <li>
    <i><b>Markov Chain of Thought for Efficient Mathematical Reasoning</b></i>, Yang et al.
    <a href="https://arxiv.org/pdf/2410.17635" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_52: OVM, Outcome-supervised Value Models for Planning in Mathematical Reasoning -->
  <li>
    <i><b>OVM, Outcome-Supervised Value Models for Planning in Mathematical Reasoning</b></i>, Yu et al.
    <a href="https://arxiv.org/pdf/2311.09724" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2023-red" alt="arXiv 2023">
    </a>
  </li>

  <!-- Paper_53: Mindstar: Enhancing math reasoning in pre-trained llms at inference time -->
  <li>
    <i><b>MindStar: Enhancing Math Reasoning in Pre-Trained LLMs at Inference Time</b></i>, Kang et al.
    <a href="https://arxiv.org/pdf/2405.16265" target="_blank">
      <img src="https://imgshields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_57: LLaMA-Berry: Pairwise Optimization for Olympiad-level Mathematical Reasoning via O1-like Monte Carlo Tree Search -->
  <li>
    <i><b>LLaMA-Berry: Pairwise Optimization for Olympiad-Level Mathematical Reasoning via O1-like Monte Carlo Tree Search</b></i>, Zhang et al.
    <a href="https://aclanthology.org/2025.naacl-long.375.pdf" target="_blank">
      <img src="https://img.shields.io/badge/NAACL-2025-blue" alt="NAACL 2025">
    </a>
  </li>

  <!-- Paper_59: Beyond Examples: High-level Automated Reasoning Paradigm in In-Context Learning via MCTS -->
  <li>
    <i><b>Beyond Examples: High-Level Automated Reasoning Paradigm in In-Context Learning via MCTS</b></i>, Wu et al.
    <a href="https://arxiv.org/pdf/2411.18478" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_66: BoostStep: Boosting mathematical capability of Large Language Models via improved single-step reasoning -->
  <li>
    <i><b>BoostStep: Boosting Mathematical Capability of Large Language Models via Improved Single-Step Reasoning</b></i>, Zhang et al.
    <a href="https://arxiv.org/pdf/2501.03226" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2025-red" alt="arXiv 2025">
    </a>
  </li>

  <!-- Paper_69: Step-level Value Preference Optimization for Mathematical Reasoning -->
  <li>
    <i><b>Step-Level Value Preference Optimization for Mathematical Reasoning</b></i>, Chen et al.
    <a href="https://arxiv.org/pdf/2406.10858" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_70: Improve Mathematical Reasoning in Language Models by Automated Process Supervision -->
  <li>
    <i><b>Improve Mathematical Reasoning in Language Models by Automated Process Supervision</b></i>, Luo et al.
    <a href="https://arxiv.org/pdf/2406.06592" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_79: What Are Step-Level Reward Models Rewarding? Counterintuitive Findings from MCTS-Boosted Mathematical Reasoning -->
  <li>
    <i><b>What Are Step-Level Reward Models Rewarding? Counterintuitive Findings from MCTS-Boosted Mathematical Reasoning</b></i>, Ma et al.
    <a href="https://ojs.aaai.org/index.php/AAAI/article/view/34663" target="_blank">
      <img src="https://img.shields.io/badge/AAAI-2025-blue" alt="AAAI 2025">
    </a>
  </li>

  <!-- Paper_80: Ensembling Large Language Models with Process Reward-Guided Tree Search for Better Complex Reasoning -->
  <li>
    <i><b>Ensembling Large Language Models with Process Reward-Guided Tree Search for Better Complex Reasoning</b></i>, Park et al.
    <a href="https://arxiv.org/pdf/2412.15797" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2024-red" alt="arXiv 2024">
    </a>
  </li>

  <!-- Paper_91: rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking -->
  <li>
    <i><b>rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking</b></i>, Guan et al.
    <a href="https://arxiv.org/pdf/2501.04519" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2025-red" alt="arXiv 2025">
    </a>
  </li>

  <!-- Paper_15 (Jan-Apr 2025): Leveraging Constrained Monte Carlo Tree Search to Generate Reliable Long Chain-of-Thought for Mathematical Reasoning -->
  <li>
    <i><b>Leveraging Constrained Monte Carlo Tree Search to Generate Reliable Long Chain-of-Thought for Mathematical Reasoning</b></i>, Lin et al.
    <a href="https://arxiv.org/abs/2502.11169" target="_blank">
      <img src="https://img.shields.io/badge/arXiv-2025-red" alt="arXiv 2025">
    </a>
  </li>

</ul>

### Code Generation & Software Engineering
- Content related to "Code Generation & Software Engineering" goes here.

### LLM Agents & Interactive Environments
- Content related to "LLM Agents & Interactive Environments" goes here.

### Retrieval-Augmented Generation (RAG) & Knowledge-Intensive Tasks
- Content related to "Retrieval-Augmented Generation (RAG) & Knowledge-Intensive Tasks" goes here.

### Multimodal Reasoning
- Content related to "Multimodal Reasoning" goes here.

---

## Part 2: MCTS for Self-Improvement via Data Generation

### Foundational Self-Improvement Frameworks
- Content related to "Foundational Self-Improvement Frameworks" goes here.

### Applications in Specific Domains

#### General Capabilities & Alignment
- Content related to "General Capabilities & Alignment" goes here.

#### Scientific & Specialized Domains
- Content related to "Scientific & Specialized Domains" goes here.

#### Multimodal Applications
- Content related to "Multimodal Applications" goes here.

---

## Part 3: Advanced Topics and Hybrid Approaches

### Multi-Agent and Collaborative Search
- Content related to "Multi-Agent and Collaborative Search" goes here.

### Reward Model Design and Optimization
- Content related to "Reward Model Design and Optimization" goes here.

### Search Efficiency and Dynamics
- Content related to "Search Efficiency and Dynamics" goes here.

## 👏 Contributing

Contributions are highly encouraged! 

If you have a relevant paper that complements this taxonomy, feel free to submit a pull request or reach out to the author directly. 

Your support will help expand and improve this repository!

## 📖 Citation
If you find this project helpful in your research, please consider cite:
```bibtex
@article{wei2025ai,
  title={From AI for Science to Agentic Science: A Survey on Autonomous Scientific Discovery},
  author={Wei, Jiaqi and Yang, Yuejin and Zhang, Xiang and Chen, Yuhan and Zhuang, Xiang and Gao, Zhangyang and Zhou, Dongzhan and Wang, Guangshuai and Gao, Zhiqiang and Cao, Juntai and others},
  journal={arXiv preprint arXiv:2508.14111},
  year={2025}
}
```


<h2>🌟 Star History</h2>

[![Star History Chart](https://api.star-history.com/svg?repos=AgenticScience/Awesome-Agent-Scientists&type=Date)](https://www.star-history.com/#AgenticScience/Awesome-Agent-Scientists&Date) 
