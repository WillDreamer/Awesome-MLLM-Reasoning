# Awesome-MLLM-Reasoning
[![Awesome](https://awesome.re/badge.svg)](https://github.com/lupantech/dl4math) 
[![Survey](https://img.shields.io/badge/Survey-MLLMReasoning-blue)]([https://github.com/WillDreamer/Awesome-AI4CFD](https://github.com/WillDreamer/Awesome-MLLM-Reasoning)) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

<!-- <img src="./images/main.png" width="96%" height="96%"> -->

## Recent Advances on MLLM's Reasoning Ability: A Survey
Recent advancements in multi-modal large language models have achieved notable success in bridging visual and textual understanding. However, when it comes to reasoning in complex scenarios, these models still face significant challenges. For instance, in environments requiring general scene understanding, spatio-temporal reasoning, and robust optical character recognition under variable conditions, their performance often falls short of expectations. 

In this survey, we provide a comprehensive overview of the progress made in multi-modal reasoning in the **recent two years (2024-2025)**, examining both the achievements and the limitations of current approaches. We further outline future research directions aimed at enhancing reasoning capabilities in complex, real-world tasks, including the development of improved model architectures, refined training methodologies, and more robust evaluation frameworks.

---

<font size=8><center><b> Awesome-MLLM-Reasoning </b> </center></font>

- [Awesome-MLLM-Reasoning](#awesome-mllm-reasoning)
  - [Recent Advances on MLLM's Reasoning Ability: A Survey](#recent-advances-on-mllms-reasoning-ability-a-survey)
  - [Existing Benchmarks](#existing-benchmarks)
  - [MLLM for Image Tasks](#mllm-for-image-tasks)
  - [MLLM for Video Tasks](#mllm-for-video-tasks)
  - [Contributing](#contributing)


---


## Existing Benchmarks

|  Title  |   Venue  |   Date   |   Code   |   Note   |
|:--------|:--------:|:--------:|:--------:|:--------:|
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
|![Star](https://img.shields.io/github/stars/MiZhenxing/ThinkDiff.svg?style=social&label=Star) <br> [**I Think, Therefore I Diffuse: Enabling Multimodal In-Context Reasoning in Diffusion Models**](https://arxiv.org/abs/2502.10458) <br>  | Arxiv 2025 | 2025-02 | [Github](https://github.com/MiZhenxing/ThinkDiff) | [Project](https://mizhenxing.github.io/ThinkDiff) |
|![Star](https://img.shields.io/github/stars/Pbhgit/MVCD.svg?style=social&label=Star) <br> [**Language Models Can See Better: Visual Contrastive Decoding For LLM Multimodal Reasoning**](https://arxiv.org/abs/2502.11751) <br>  | ICASSP 2025 | 2025-02 | [Github](https://github.com/Pbhgit/MVCD) | - |
|![Star](https://img.shields.io/github/stars/aibee00/socraticquestioning.svg?style=social&label=Star) <br> [**Socratic Questioning: Learn to Self-guide Multimodal Reasoning in the Wild**](https://arxiv.org/pdf/2501.02964v2.pdf) <br>  | Arxiv 2025 | 2025-01 | [Github](https://github.com/aibee00/socraticquestioning) | - |
|![Star](https://img.shields.io/github/stars/shawnricecake/heima.svg?style=social&label=Star) <br> [**Efficient Reasoning with Hidden Thinking**](https://arxiv.org/abs/2501.19201) <br>  | Arxiv 2025 | 2025-01 | [Github](https://github.com/shawnricecake/heima) | [Project](https://reasoning-grasping.github.io/) |
|![Star](https://img.shields.io/github/stars/HJYao00/Mulberry.svg?style=social&label=Star) <br> [**Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search**](https://arxiv.org/abs/2412.18319) <br>  | Arxiv 2024 | 2024-12 | [Github](https://github.com/HJYao00/Mulberry) | - |
|![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LLaVA-CoT.svg?style=social&label=Star) <br> [**LLaVA-CoT: Let Vision Language Models Reason Step-by-Step**](https://arxiv.org/pdf/2411.10440v3.pdf) <br>  | Arxiv 2024 | 2024-11 | [Github](https://github.com/PKU-YuanGroup/LLaVA-CoT) | - |
|![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) <br> [**Enhancing the Reasoning Ability of Multimodal Large Language Models via Mixed Preference Optimization**](https://arxiv.org/abs/2411.10442) <br>  | Arxiv 2024 | 2024-11 | [Github](https://github.com/OpenGVLab/InternVL/tree/main/internvl_chat/shell/internvl2.0_mpo) | [Project](https://internvl.github.io/blog/2024-11-14-InternVL-2.0-MPO/) |
|![Star](https://img.shields.io/github/stars/MaverickRen/PixelLM.svg?style=social&label=Star) <br> [**PixelLM: Pixel Reasoning with Large Multimodal Model**](https://arxiv.org/pdf/2312.02228.pdf) <br>  | CVPR 2024 | 2024-11 | [Github](https://github.com/MaverickRen/PixelLM) | [Project](https://pixellm.github.io/) |
| <br> [**Reasoning Grasping via Multimodal Large Language Model**](https://openreview.net/forum?id=KPcX4jetMw) <br>  | CoRL 2024 | 2024-02 | - | [Project](https://reasoning-grasping.github.io/) |


---

## MLLM for Video Tasks


|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|![Star](https://img.shields.io/github/stars/Darcyddx/Video-LLM.svg?style=social&label=Star) <br> [**Do Language Models Understand Time?**](https://arxiv.org/pdf/2412.13845v1.pdf) <br>  | WWW 2025 | 2024-12 | [Github](https://github.com/Darcyddx/Video-LLM) | - |

---

## MLLM for Scientific Tasks


|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| <br> [**Position: Multimodal Large Language Models Can Significantly Advance Scientific Reasoning**](https://arxiv.org/pdf/2502.02871) <br>  | Arxiv 2025 | 2025-02 | - | - |

---


## Contributing

📮📮📮 If you want to add your model in our leaderboards, please feel free to fork and update your work in the table. You can also email **<whx@cs.ucla.edu>**. We will response to your request as soon as possible!



