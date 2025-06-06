# Awesome-MLLM-Reasoning
[![Awesome](https://awesome.re/badge.svg)](https://github.com/lupantech/dl4math) 
[![Survey](https://img.shields.io/badge/Survey-MLLMReasoning-blue)]([https://github.com/WillDreamer/Awesome-AI4CFD](https://github.com/WillDreamer/Awesome-MLLM-Reasoning)) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

<!-- <img src="./images/main.png" width="96%" height="96%"> -->

## Recent Advances on MLLM's Reasoning Ability: A Survey
Recent advancements in multi-modal large language models have achieved notable success in bridging visual and textual understanding. However, when it comes to reasoning in complex scenarios, these models still face significant challenges. For instance, in environments requiring general scene understanding, spatio-temporal reasoning, and robust optical character recognition under variable conditions, their performance often falls short of expectations. 


In this survey, we provide a comprehensive overview of the progress made in multi-modal reasoning in the **recent two years (2024-2025)**, examining both the achievements and the limitations of current approaches. We further outline future research directions aimed at enhancing reasoning capabilities in complex, real-world tasks, including the development of improved model architectures, refined training methodologies, and more robust reasoning frameworks.

---

<font size=8><center><b> Awesome-MLLM-Reasoning </b> </center></font>

- [Awesome-MLLM-Reasoning](#awesome-mllm-reasoning)
  - [Recent Advances on MLLM's Reasoning Ability: A Survey](#recent-advances-on-mllms-reasoning-ability-a-survey)
  - [Existing Benchmarks](#existing-benchmarks)
  - [MLLM for Image Tasks](#mllm-for-image-tasks)
  - [MLLM for Video Tasks](#mllm-for-video-tasks)
  - [MLLM for Audio Tasks](#mllm-for-audio-tasks)
  - [Contributing](#contributing)


---


## Existing Benchmarks

|  Title  |   Venue  |   Date   |   Code   |   Note   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| <br> [**Why Reasoning Matters? A Survey of Advancements in Multimodal Reasoning**](https://arxiv.org/pdf/2504.03151v1) <br> | Arxiv 2025 | 2025-04 | Survey | - |
|![Star](https://img.shields.io/github/stars/jmhb0/microvqa.svg?style=social&label=Star) <br> [**MicroVQA: A Multimodal Reasoning Benchmark for Microscopy-Based Scientific Research**](https://arxiv.org/pdf/2502.09696) <br> | Arxiv 2025 | 2025-02 | [Github](https://github.com/jmhb0/microvqa) | [Dataset](https://huggingface.co/datasets/jmhb/microvqa)|
|<br> [**COSINT-Agent: A Knowledge-Driven Multimodal Agent for Chinese Open Source Intelligence**](https://arxiv.org/pdf/2503.03215) <br> | Arxiv 2025 | 2025-03 | - | - |
|<br> [**CognitiveDrone: A VLA Model and Evaluation Benchmark for Real-Time Cognitive Task Solving and Reasoning in UAVs**](https://arxiv.org/pdf/2503.01378) <br> | Arxiv 2025 | 2025-03 | - | [Datasets](https://huggingface.co/datasets/ArtemLykov/CognitiveDrone_dataset)|
|<br> [**All-in-one: Understanding and Generation in Multimodal Reasoning with the MAIA Benchmark**](http://arxiv.org/abs/2502.16989) <br> | Arxiv 2025 | 2025-02 | - | -|
|<br> [**Exploring Advanced Techniques for Visual Question Answering: A Comprehensive Comparison**](https://arxiv.org/abs/2502.14827) <br> | Arxiv 2025 | 2025-02 | - | -|
|<br> [**EnigmaEval: A Benchmark of Long Multimodal Reasoning Challenges**](https://arxiv.org/abs/2502.08859) <br> | Arxiv 2025 | 2025-02 | - | -|
|![Star](https://img.shields.io/github/stars/jonathan-roberts1/zerobench.svg?style=social&label=Star) <br> [**ZeroBench: An Impossible Visual Benchmark for Contemporary Large Multimodal Models**](https://arxiv.org/pdf/2502.09696) <br> | Arxiv 2025 | 2025-02 | [Github](https://github.com/jonathan-roberts1/zerobench) | [Dataset](https://huggingface.co/datasets/jonathan-roberts1/zerobench)|
|![Star](https://img.shields.io/github/stars/CaraJ7/MME-CoT.svg?style=social&label=Star) <br> [**MME-CoT: Benchmarking Chain-of-Thought in LMMs for Reasoning Quality, Robustness, and Efficiency**](https://arxiv.org/pdf/2502.09621) <br> | Arxiv 2025 | 2025-02 | [Github](https://github.com/CaraJ7/MME-CoT) | [Dataset](https://huggingface.co/datasets/CaraJ/MME-CoT)|
|![Star](https://img.shields.io/github/stars/hychaochao/EMMA.svg?style=social&label=Star) <br> [**Can MLLMs Reason in Multimodality? EMMA: An Enhanced MultiModal ReAsoning Benchmark**](https://arxiv.org/pdf/2412.12932v1.pdf) <br> | Arxiv 2025 | 2025-01 | [Github](https://github.com/hychaochao/EMMA) |
|![Star](https://img.shields.io/github/stars/czhhzc/CoMT.svg?style=social&label=Star) <br> [**CoMT: A Novel Benchmark for Chain of Multi-modal Thought on Large Vision-Language Models**](https://arxiv.org/pdf/2501.05444v1.pdf) <br> | AAAI 2025 | 2024-12 | [Github](https://github.com/czhhzc/CoMT) |
|![Star](https://img.shields.io/github/stars/umd-huang-lab/Mementos.svg?style=social&label=Star) <br> [**Mementos: A Comprehensive Benchmark for Multimodal Large Language Model Reasoning over Image Sequences**](https://aclanthology.org/2024.acl-long.25.pdf) <br> | ACL 2024 | 2024-01 | [Github](https://github.com/umd-huang-lab/Mementos) |



---

## MLLM for Image Tasks

|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|![Star](https://img.shields.io/github/stars/tanhuajie/Reason-RFT.svg?style=social&label=Star) <br> [**Reason-RFT: Reinforcement Fine-Tuning for Visual Reasoning**](https://arxiv.org/abs/2503.20752) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/tanhuajie/Reason-RFT) | - |
|<br> [**Cultivating Game Sense for Yourself: Making VLMs Gaming Experts**](https://arxiv.org/pdf/2503.21263) <br>  | Arxiv 2025 | 2025-03 | - | - |
|![Star](https://img.shields.io/github/stars/ADaM-BJTU/Mind_with_eyes_Awesome_MLLMs_Reasoning.svg?style=social&label=Star) <br> [**Mind with Eyes: from Language Reasoning to Multimodal Reasoning**](https://arxiv.org/html/2503.18071v1) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/ADaM-BJTU/Mind_with_eyes_Awesome_MLLMs_Reasoning) | - |
|![Star](https://img.shields.io/github/stars/aimagelab/LLaVA-MORE.svg?style=social&label=Star) <br> [**LLaVA-MORE: A Comparative Study of LLMs and Visual Backbones for Enhanced Visual Instruction Tuning**](https://arxiv.org/pdf/2503.15621) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/aimagelab/LLaVA-MORE) | - |
|![Star](https://img.shields.io/github/stars/jingyi0000/R1-VL.svg?style=social&label=Star) <br> [**R1-VL: Learning to Reason with Multimodal Large Language Models via Step-wise Group Relative Policy Optimization**](https://arxiv.org/abs/2503.12937) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/jingyi0000/R1-VL) | - |
|![Star](https://img.shields.io/github/stars/Fancy-MLLM/R1-onevision.svg?style=social&label=Star) <br> [**R1-Onevision: Advancing Generalized Multimodal Reasoning through Cross-Modal Formalization**](https://arxiv.org/pdf/2503.10615) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/Fancy-MLLM/R1-onevision) | [Dataset](https://huggingface.co/datasets/Fancy-MLLM/R1-Onevision) |
| <br> [**VisualPRM: An Effective Process Reward Model for Multimodal Reasoning**](https://arxiv.org/pdf/2503.10291) <br>  | Arxiv 2025 | 2025-03 | [Project](https://internvl.github.io/blog/2025-03-13-VisualPRM/) | [Dataset](https://huggingface.co/datasets/OpenGVLab/VisualPRM400K) |
|![Star](https://img.shields.io/github/stars/kyrieLei/Critic-V.svg?style=social&label=Star) <br> [**Critic-V: VLM Critics Help Catch VLM Errors in Multimodal Reasoning**](https://arxiv.org/pdf/2411.18203) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/kyrieLei/Critic-V) | [Dataset](https://huggingface.co/papers/2411.18203) |
|![Star](https://img.shields.io/github/stars/THUNLP-MT/EscapeCraft.svg?style=social&label=Star) <br> [**How Do Multimodal Large Language Models Handle Complex Multimodal Reasoning? Placing Them in An Extensible Escape Game**](https://arxiv.org/html/2503.10042v1) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/THUNLP-MT/EscapeCraft) | - |
|![Star](https://img.shields.io/github/stars/TideDra/lmm-r1.svg?style=social&label=Star) <br> [**LMM-R1: Empowering 3B LMMs with Strong Reasoning Abilities Through Two-Stage Rule-Based RL**](https://arxiv.org/abs/2503.07536) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/TideDra/lmm-r1) | - |
|![Star](https://img.shields.io/github/stars/Osilly/Vision-R1.svg?style=social&label=Star) <br> [**Vision-R1: Incentivizing Reasoning Capability in Multimodal Large Language Models**](https://arxiv.org/abs/2503.06749) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/Osilly/Vision-R1) | - |
|![Star](https://img.shields.io/github/stars/ModalMinds/MM-EUREKA.svg?style=social&label=Star) <br> [**MM-EUREKA: Exploring Visual Aha Moment with Rule-based Large-scale Reinforcement Learning**](https://github.com/ModalMinds/MM-EUREKA?tab=readme-ov-file) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/ModalMinds/MM-EUREKA) | [Datasets](https://huggingface.co/datasets/FanqingM/MM-Eureka-Dataset) |
| <br> [**MINT: Multi-modal Chain of Thought in Unified Generative Models for Enhanced Image Generation**](https://www.arxiv.org/abs/2503.01298) <br>  | Arxiv 2025 | 2025-03 | - | - |
| <br> [**Shakti-VLMs: Scalable Vision-Language Models for Enterprise AIl**](https://arxiv.org/abs/2502.17092) <br>  | Arxiv 2025 | 2025-02 | - | - |
|![Star](https://img.shields.io/github/stars/Aurora-slz/MM-Verify.svg?style=social&label=Star) <br> [**MM-Verify: Enhancing Multimodal Reasoning with Chain-of-Thought Verification**](https://www.arxiv.org/abs/2502.13383) <br>  | Arxiv 2025 | 2025-02 | [Github](https://github.com/Aurora-slz/MM-Verify) | - |
|![Star](https://img.shields.io/github/stars/MiZhenxing/ThinkDiff.svg?style=social&label=Star) <br> [**I Think, Therefore I Diffuse: Enabling Multimodal In-Context Reasoning in Diffusion Models**](https://arxiv.org/abs/2502.10458) <br>  | Arxiv 2025 | 2025-02 | [Github](https://github.com/MiZhenxing/ThinkDiff) | [Project](https://mizhenxing.github.io/ThinkDiff) |
|![Star](https://img.shields.io/github/stars/Pbhgit/MVCD.svg?style=social&label=Star) <br> [**Language Models Can See Better: Visual Contrastive Decoding For LLM Multimodal Reasoning**](https://arxiv.org/abs/2502.11751) <br>  | ICASSP 2025 | 2025-02 | [Github](https://github.com/Pbhgit/MVCD) | - |
|![Star](https://img.shields.io/github/stars/aibee00/socraticquestioning.svg?style=social&label=Star) <br> [**Socratic Questioning: Learn to Self-guide Multimodal Reasoning in the Wild**](https://arxiv.org/pdf/2501.02964v2.pdf) <br>  | Arxiv 2025 | 2025-01 | [Github](https://github.com/aibee00/socraticquestioning) | - |
|![Star](https://img.shields.io/github/stars/shawnricecake/heima.svg?style=social&label=Star) <br> [**Efficient Reasoning with Hidden Thinking**](https://arxiv.org/abs/2501.19201) <br>  | Arxiv 2025 | 2025-01 | [Github](https://github.com/shawnricecake/heima) | [Project](https://reasoning-grasping.github.io/) |
|![Star](https://img.shields.io/github/stars/ZiyuGuo99/Image-Generation-CoT.svg?style=social&label=Star) <br> [**Can We Generate Images with CoT? Let’s Verify and Reinforce Image Generation Step by Step**](https://arxiv.org/pdf/2501.13926) <br>  | Arxiv 2025 | 2025-01 | [Github](https://github.com/ZiyuGuo99/Image-Generation-CoT) | [Dataset](https://github.com/ZiyuGuo99/Image-Generation-CoT/blob/main) |
|![Star](https://img.shields.io/github/stars/HJYao00/Mulberry.svg?style=social&label=Star) <br> [**Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search**](https://arxiv.org/abs/2412.18319) <br>  | Arxiv 2024 | 2024-12 | [Github](https://github.com/HJYao00/Mulberry) | - |
|![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LLaVA-CoT.svg?style=social&label=Star) <br> [**LLaVA-CoT: Let Vision Language Models Reason Step-by-Step**](https://arxiv.org/pdf/2411.10440v3.pdf) <br>  | Arxiv 2024 | 2024-11 | [Github](https://github.com/PKU-YuanGroup/LLaVA-CoT) | - |
|![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) <br> [**Enhancing the Reasoning Ability of Multimodal Large Language Models via Mixed Preference Optimization**](https://arxiv.org/abs/2411.10442) <br>  | Arxiv 2024 | 2024-11 | [Github](https://github.com/OpenGVLab/InternVL/tree/main/internvl_chat/shell/internvl2.0_mpo) | [Project](https://internvl.github.io/blog/2024-11-14-InternVL-2.0-MPO/) |
|![Star](https://img.shields.io/github/stars/MaverickRen/PixelLM.svg?style=social&label=Star) <br> [**PixelLM: Pixel Reasoning with Large Multimodal Model**](https://arxiv.org/pdf/2312.02228.pdf) <br>  | CVPR 2024 | 2024-11 | [Github](https://github.com/MaverickRen/PixelLM) | [Project](https://pixellm.github.io/) |
| <br> [**Reasoning Grasping via Multimodal Large Language Model**](https://openreview.net/forum?id=KPcX4jetMw) <br>  | CoRL 2024 | 2024-02 | - | [Project](https://reasoning-grasping.github.io/) |


---

## MLLM for Video Tasks


|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|![Star](https://img.shields.io/github/stars/Darcyddx/Video-LLM.svg?style=social&label=Star) <br> [**Towards Multimodal Large-Language Models for Parent-Child Interaction: A Focus on Joint Attention**](https://arxiv.org/abs/2502.19877) <br>  | CHI'25 LBW | 2025-03 | - | - |
|![Star](https://img.shields.io/github/stars/Darcyddx/Video-LLM.svg?style=social&label=Star) <br> [**Do Language Models Understand Time?**](https://arxiv.org/pdf/2412.13845v1.pdf) <br>  | WWW 2025 | 2024-12 | [Github](https://github.com/Darcyddx/Video-LLM) | - |

---

## MLLM for Audio Tasks


|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|![Star](https://img.shields.io/github/stars/AIM-SKKU/QA-TIGER.svg?style=social&label=Star) <br> [**Question-Aware Gaussian Experts for Audio-Visual Question Answering**](http://arxiv.org/abs/2503.04459) <br>  | CVPR 2025 | 2025-03 | [Github](https://github.com/AIM-SKKU/QA-TIGER) | [Demo](https://aim-skku.github.io/QA-TIGER/) |
|![Star](https://img.shields.io/github/stars/xzf-thu/Audio-Reasoner.svg?style=social&label=Star) <br> [**Audio-Reasoner: Improving Reasoning Capability in Large Audio Language Models**](http://arxiv.org/abs/2503.02318) <br>  | Arxiv 2025 | 2025-03 | [Github](https://github.com/xzf-thu/Audio-Reasoner) | [Demo](https://github.com/xzf-thu/Audio-Reasoner?tab=readme-ov-file#demo) |

---


## MLLM for Scientific Tasks


|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| <br> [**Position: Multimodal Large Language Models Can Significantly Advance Scientific Reasoning**](https://arxiv.org/pdf/2502.02871) <br>  | Arxiv 2025 | 2025-02 | - | - |

---


## Contributing

📮📮📮 If you want to add your model in our leaderboards, please feel free to fork and update your work in the table. You can also email **<whx@cs.ucla.edu>**. We will response to your request as soon as possible!



