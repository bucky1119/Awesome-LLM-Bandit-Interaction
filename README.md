
<div align="center">
<h2> A Survey on Recent Advances in the Connection between Large Language Models and Multi-armed Bandits </h2> 
<a href='https://arxiv.org/'><img src='https://img.shields.io/badge/ArXiv-XXXX-red'></a>
</div>

# 🚀 Introduction
- This repository provides a curated collection of papers and resources on the intersection of Large Language Models (LLMs) and Multi-Armed Bandits (MABs). As modern LLMs grow more capable, bandit algorithms offer efficient tools for improving prompt design, training, inference optimization, and personalization. Conversely, LLMs enable more expressive and context-aware bandit decision-making.

- Our goal is to give researchers a clear entry point into this emerging area, covering both LLM-enhanced bandits and bandit-enhanced LLMs, along with key insights, methods, and open challenges.
  <!-- <p align="center">
  <img src="assets/fig.jpg" width=300""> -->
<!-- </p> -->

- We welcome any contributions and suggestions to our repository or the addition of your own work. Feel free to make a pull request or leave your comments!!



# 📋 Contents
- [🚀 Introduction](#🚀-introduction)
- [📋 Contents](#📋-contents)
- [💘 Tips](#💘-tips)
- [📍 Bandit-enhancements for LLMs](#📍-bandit-enhancements-for-llms)
  - [Pre-training](#pre-training)
  - [Fine-tuning](#fine-tuning)
  - [Prompt Design and Optimization](#prompt-design-and-optimization)
  - [Inference and Generation Optimization](#inference-and-generation-optimization)
  - [Adaptation and Personalizing](#adaptation-and-personalizing)
  - [Contextual Understanding](#contextual-understanding)
  - [Retrieval-Augmented Generation](#retrieval-augmented-generation)
- [📍 LLM-enhancements for Multi-armed Bandits](#📍-llm-enhancements-for-multi-armed-bandits)
  - [Optimization Objective](#optimization-objective)
  - [Arm Definition](#arm-definition)
  - [Environment](#environment)
  - [Reward Formulation](#reward-formulation)
  - [Sampling Strategy](#sampling-strategy)
  - [Action Decision](#action-decision)
- [👨‍💻 Team](#👨‍💻-team)
- [😉 Citation](#😉-citation)
<!-- - [⭐️ Star History](#⭐️-star-history) -->


# 💘 Tips
- **✅ Paper searching via catatogue**: directly clicking the content of the catatogue to select the area of your research and browse related papers.
- **✅ Paper searching via author name**: Free feel to search papers of a specific author via `ctrl + F` and then type the author name. The dropdown list of authors will automatically expand when searching.
- **✅ Paper searching via tag**: You can also search the related papers via the following tags: `customization`, `iteractive`, `human motion generation` `tokenizer`. (More tags are ongoing)


# 📍 Bandit-enhancements for LLMs

## Pre-training

+ **Multi-armed bandits for resource efficient, online optimization of language model pre-training: the use case of dynamic masking** (2022)<details><summary>Inigo Urteaga, Moulay Zaidane Draidia, Tomer Lancewicki, et al.</summary>Inigo Urteaga, Moulay Zaidane Draidia, Tomer Lancewicki, Shahram Khadivi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2203.13151)


+ **Efficient online data mixing for language model pre-training** (2023)<details><summary>Alon Albalak, Liangming Pan, Colin Raffel, et al.</summary>Alon Albalak, Liangming Pan, Colin Raffel, William Yang Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2312.02406)

 
+ **Pretraining Decision Transformers with Reward Prediction for In-Context Multi-task Structured Bandit Learning** (2024)<details><summary>Subhojyoti Mukherjee, Josiah P Hanna, Qiaomin Xie, et al.</summary>Subhojyoti Mukherjee, Josiah P Hanna, Qiaomin Xie, Robert Nowak</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2406.05064)


+ **Harnessing Diversity for Important Data Selection in Pretraining Large Language Models** (2024)<details><summary>Chi Zhang, Huaping Zhong, Kuan Zhang, et al.</summary>Chi Zhang, Huaping Zhong, Kuan Zhang, Chengliang Chai, Rui Wang, Xinlin Zhuang, Tianyi Bai, Jiantao Qiu, Lei Cao, Ye Yuan, others</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2409.16986)


+ **Actor-Critic based Online Data Mixing For Language Model Pre-Training** (2025)<details><summary>Jing Ma, Chenhao Dang, Mingjie Liao</summary>Jing Ma, Chenhao Dang, Mingjie Liao</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2505.23878)


+ **EVOLvE: Evaluating and Optimizing LLMs For In-Context Exploration** (2025)<details><summary>Allen Nie, Yi Su, Bo Chang, et al.</summary>Allen Nie, Yi Su, Bo Chang, Jonathan Lee, Ed H. Chi, Quoc V Le, Minmin Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2410.06238)



## Fine-tuning


+ **RL-NMT: Reinforcement Learning Fine-tuning for Improved Neural Machine Translation of Burmese Dialects** (2023)<details><summary>Ye Kyaw Thu, Thazin Myint Oo, Thepchai Supnithi</summary>Ye Kyaw Thu, Thazin Myint Oo, Thepchai Supnithi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.1808.08866)


+ **Reflect-RL: Two-Player Online RL Fine-Tuning for LMs** (2024)<details><summary>Runlong Zhou, Simon S Du, Beibin Li</summary>Runlong Zhou, Simon S Du, Beibin Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2402.12621)


+ **Dynamic Data Mixing Maximizes Instruction Tuning for Mixture-of-Experts** (2024)<details><summary>Tong Zhu, Daize Dong, Xiaoye Qu, et al.</summary>Tong Zhu, Daize Dong, Xiaoye Qu, Jiacheng Ruan, Wenliang Chen, Yu Cheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2406.11256)


+ **Iterative data smoothing: Mitigating reward overfitting and overoptimization in rlhf** (2024)<details><summary>Banghua Zhu, Michael I Jordan, Jiantao Jiao</summary>Banghua Zhu, Michael I Jordan, Jiantao Jiao</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2401.16335)


+ **Sharp Analysis for KL-Regularized Contextual Bandits and RLHF** (Unknown Year)<details><summary>Heyang Zhao, Chenlu Ye, Quanquan Gu, et al.</summary>Heyang Zhao, Chenlu Ye, Quanquan Gu, Tong Zhang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2411.04625)


+ **Which LLM to Play? Convergence-Aware Online Model Selection with Time-Increasing Bandits** (2024)<details><summary>Yu Xia, Fang Kong, Tong Yu, et al.</summary>Yu Xia, Fang Kong, Tong Yu, Liya Guo, Ryan A Rossi, Sungchul Kim, Shuai Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2403.07213)

+ **Convergence-aware online model selection with time-increasing bandits** (2024)<details><summary>Yu Xia, Fang Kong, Tong Yu, et al.</summary>Yu Xia, Fang Kong, Tong Yu, Liya Guo, Ryan A Rossi, Sungchul Kim, Shuai Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2403.07213)


+ **Preference fine-tuning of LLMs should leverage suboptimal, on-policy data** (2024)<details><summary>Fahim Tajwar, Anikait Singh, Archit Sharma, et al.</summary>Fahim Tajwar, Anikait Singh, Archit Sharma, Rafael Rafailov, Jeff Schneider, Tengyang Xie, Stefano Ermon, Chelsea Finn, Aviral Kumar</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2404.14367)


+ **Sample-efficient alignment for llms** (2024)<details><summary>Zichen Liu, Changyu Chen, Chao Du, et al.</summary>Zichen Liu, Changyu Chen, Chao Du, Wee Sun Lee, Min Lin</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2411.01493)


+ **Chunks as arms: Multi-armed bandit-guided sampling for long-context llm preference optimization** (2025)<details><summary>Shaohua Duan, Xinze Li, Zhenghao Liu, et al.</summary>Shaohua Duan, Xinze Li, Zhenghao Liu, Xiaoyuan Yi, Yukun Yan, Shuo Wang, Yu Gu, Ge Yu, Maosong Sun</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2508.13993)


+ **DynamixSFT: Dynamic Mixture Optimization of Instruction Tuning Collections** (2025)<details><summary>Haebin Shin, Lei Ji, Xiao Liu, et al.</summary>Haebin Shin, Lei Ji, Xiao Liu, Zhiwei Yu, Qi Chen, Yeyun Gong</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2508.12116)


## Prompt Design and Optimization


+ **Prompt Optimization with Human Feedback** (2024)<details><summary>Xiaoqiang Lin, Zhongxiang Dai, Arun Verma, et al.</summary>Xiaoqiang Lin, Zhongxiang Dai, Arun Verma, See-Kiong Ng, Patrick Jaillet, Bryan Kian Hsiang Low</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2405.17346)


+ **Best arm identification for prompt learning under a limited budget** (2024)<details><summary>Chengshuai Shi, Kun Yang, Jing Yang, et al.</summary>Chengshuai Shi, Kun Yang, Jing Yang, Cong Shen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2209.07330)


+ **Prompt optimization with EASE? efficient ordering-aware automated selection of exemplars** (2024)<details><summary>Zhaoxuan Wu, Xiaoqiang Lin, Zhongxiang Dai, et al.</summary>Zhaoxuan Wu, Xiaoqiang Lin, Zhongxiang Dai, Wenyang Hu, Yao Shu, See-Kiong Ng, Patrick Jaillet, Bryan Kian Hsiang Low</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2405.16122)


+ **Prompt Optimization with Logged Bandit Data** (2024)<details><summary>Haruka Kiyohara, Yuta Saito, Daniel Yiming Cao, et al.</summary>Haruka Kiyohara, Yuta Saito, Daniel Yiming Cao, Thorsten Joachims</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2504.02646)


+ **Prompt-based Code Completion via Multi-Retrieval Augmented Generation** (2024)<details><summary>Hanzhuo Tan, Qi Luo, Ling Jiang, et al.</summary>Hanzhuo Tan, Qi Luo, Ling Jiang, Zizheng Zhan, Jing Li, Haotian Zhang, Yuqun Zhang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2405.07530)


+ **Use Your INSTINCT: INSTruction optimization for LLMs usIng Neural bandits Coupled with Transformers** (2024)<details><summary>Xiaoqiang Lin, Zhaoxuan Wu, Zhongxiang Dai, et al.</summary>Xiaoqiang Lin, Zhaoxuan Wu, Zhongxiang Dai, Wenyang Hu, Yao Shu, See-Kiong Ng, Patrick Jaillet, Bryan Kian Hsiang Low</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2310.02905)


+ **Efficient prompt optimization through the lens of best arm identification** (2024)<details><summary>Chengshuai Shi, Kun Yang, Zihan Chen, et al.</summary>Chengshuai Shi, Kun Yang, Zihan Chen, Jundong Li, Jing Yang, Cong Shen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2402.09723)


+ **FedPOB: Sample-Efficient Federated Prompt Optimization via Bandits** (2025)<details><summary>Pingchen Lu, Zhi Hong, Zhiwei Shang, et al.</summary>Pingchen Lu, Zhi Hong, Zhiwei Shang, Zhiyong Wang, Yikun Ban, Yao Shu, Min Zhang, Shuang Qiu, Zhongxiang Dai</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2509.24701)


+ **Prompt Tuning Decision Transformers with Structured and Scalable Bandits** (2025)<details><summary>Finn Rietz, Oleg Smirnov, Sara Karimi, et al.</summary>Finn Rietz, Oleg Smirnov, Sara Karimi, Lele Cao</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2003.02287)


+ **Meta-prompt optimization for llm-based sequential decision making** (2025)<details><summary>Mingze Kong, Zhiyong Wang, Yao Shu, et al.</summary>Mingze Kong, Zhiyong Wang, Yao Shu, Zhongxiang Dai</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.00728)


+ **Bandit-Based Prompt Design Strategy Selection Improves Prompt Optimizers** (2025)<details><summary>Rin Ashizawa, Yoichi Hirose, Nozomu Yoshinari, et al.</summary>Rin Ashizawa, Yoichi Hirose, Nozomu Yoshinari, Kento Uchida, Shinichi Shirakawa</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.01163)


+ **Prompt Optimization with Logged Bandit Data** (2025)<details><summary>Haruka Kiyohara, Daniel Yiming Cao, Yuta Saito, et al.</summary>Haruka Kiyohara, Daniel Yiming Cao, Yuta Saito, Thorsten Joachims</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.02646)


+ **LLM Prompt Duel Optimizer: Efficient Label-Free Prompt Optimization** (2025)<details><summary>Yuanchen Wu, Saurabh Verma, Justin Lee, et al.</summary>Yuanchen Wu, Saurabh Verma, Justin Lee, Fangzhou Xiong, Poppy Zhang, Amel Awadelkarim, Xu Chen, Yubai Yuan, Shawndra Hill</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.13907)



## Inference and Generation Optimization

+ **Bandits don't follow rules: Balancing multi-facet machine translation with multi-armed bandits** (2021)<details><summary>Julia Kreutzer, David Vilar, Artem Sokolov</summary>Julia Kreutzer, David Vilar, Artem Sokolov</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.06997)


+ **Cost-efficient Knowledge-based Question Answering with Large Language Models** (2024)<details><summary>Junnan Dong, Qinggang Zhang, Chuang Zhou, et al.</summary>Junnan Dong, Qinggang Zhang, Chuang Zhou, Hao Chen, Daochen Zha, Xiao Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17337)


+ **EVOLvE: Evaluating and Optimizing LLMs For Exploration** (2024)<details><summary>Allen Nie, Yi Su, Bo Chang, et al.</summary>Allen Nie, Yi Su, Bo Chang, Jonathan N Lee, Ed H Chi, Quoc V Le, Minmin Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.06238)


+ **Sequential query prediction based on multi-armed bandits with ensemble of transformer experts and immediate feedback** (2024)<details><summary>Shameem A Puthiya Parambath, Christos Anagnostopoulos, Roderick Murray-Smith</summary>Shameem A Puthiya Parambath, Christos Anagnostopoulos, Roderick Murray-Smith</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://link.springer.com/article/10.1007/s10618-024-01057-4)


+ **Speculative Decoding via Early-exiting for Faster LLM Inference with Thompson Sampling Control Mechanism** (2024)<details><summary>Jiahao Liu, Qifan Wang, Jingang Wang, et al.</summary>Jiahao Liu, Qifan Wang, Jingang Wang, Xunliang Cai</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.03853)


+ **Which LLM to Play? Convergence-Aware Online Model Selection with Time-Increasing Bandits** (2024)<details><summary>Yu Xia, Fang Kong, Tong Yu, et al.</summary>Yu Xia, Fang Kong, Tong Yu, Liya Guo, Ryan A Rossi, Sungchul Kim, Shuai Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.1145/3589334.3645420)


+ **Convergence-Aware Online Model Selection with Time-Increasing Bandits** (2024)<details><summary>Yu Xia, Fang Kong, Tong Yu, et al.</summary>Yu Xia, Fang Kong, Tong Yu, Liya Guo, Ryan A Rossi, Sungchul Kim, Shuai Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07213)


+ **LLMs Are In-Context Bandit Reinforcement Learners** (2024)<details><summary>Giovanni Monea, Antoine Bosselut, Kiant\'e Brantley, et al.</summary>Giovanni Monea, Antoine Bosselut, Kiant\'e Brantley, Yoav Artzi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.05362)


+ **Dynamic and Cost-Efficient Deployment of Large Language Models Using Uplift Modeling and Multi Armed Bandits** (2025)<details><summary>Ninad Tongay</summary>Ninad Tongay</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/f06a14c1-4d6d-441d-b4e4-82545ac5781b.pdf)


+ **Tokenized Bandit for LLM Decoding and Alignment** (2025)<details><summary>Suho Shin, Chenghao Yang, Haifeng Xu, et al.</summary>Suho Shin, Chenghao Yang, Haifeng Xu, Mohammad T Hajiaghayi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.07276)


+ **Not-a-Bandit: Provably No-Regret Drafter Selection in Speculative Decoding for LLMs** (2025)<details><summary>Hongyi Liu, Jiaji Huang, Zhen Jia, et al.</summary>Hongyi Liu, Jiaji Huang, Zhen Jia, Youngsuk Park, Yu-Xiang Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.20064)


+ **LLM Cache Bandit Revisited: Addressing Query Heterogeneity for Cost-Effective LLM Inference** (2025)<details><summary>Hantao Yang, Hong Xie, Defu Lian, et al.</summary>Hantao Yang, Hong Xie, Defu Lian, Enhong Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.15515)


+ **BanditSpec: Adaptive Speculative Decoding via Bandit Algorithms** (2025)<details><summary>Yunlong Hou, Fengzhuo Zhang, Cunxiao Du, et al.</summary>Yunlong Hou, Fengzhuo Zhang, Cunxiao Du, Xuan Zhang, Jiachun Pan, Tianyu Pang, Chao Du, Vincent YF Tan, Zhuoran Yang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.15141)


+ **LLM Bandit: Cost-Efficient LLM Generation via Preference-Conditioned Dynamic Routing** (2025)<details><summary>Yang Li</summary>Yang Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.02743)


+ **LLM-MS: A multi-model llm search engine** (2025)<details><summary>Konstantin Krasovitskiy, Stelios Christou, Demetrios Zeinalipour-Yazti</summary>Konstantin Krasovitskiy, Stelios Christou, Demetrios Zeinalipour-Yazti</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/document/11108133)


+ **Learning to Route LLMs from Bandit Feedback: One Policy, Many Trade-offs** (2025)<details><summary>Wang Wei, Tiankai Yang, Hongjie Chen, et al.</summary>Wang Wei, Tiankai Yang, Hongjie Chen, Yue Zhao, Franck Dernoncourt, Ryan A. Rossi, Hoda Eldardiry</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.07429)


+ **Adaptive llm routing under budget constraints** (2025)<details><summary>Pranoy Panda, Raghav Magazine, Chaitanya Devaguptapu, et al.</summary>Pranoy Panda, Raghav Magazine, Chaitanya Devaguptapu, Sho Takemori, Vishal Sharma</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.21141)


+ **Neural Bandit Based Optimal LLM Selection for a Pipeline of Tasks** (2025)<details><summary>Baran Atalar, Eddie Zhang, Carlee Joe-Wong</summary>Baran Atalar, Eddie Zhang, Carlee Joe-Wong</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.09958)


+ **How Do We Select Right {LLM} for Each Query?** (2025)<details><summary>Bowen Zhang, Gang Wang, Qi Chen, et al.</summary>Bowen Zhang, Gang Wang, Qi Chen, Anton van den Hengel</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openreview.net/forum?id=AfA3qNY0Fq)




## Adaptation and Personalizing

+ **Personalizing natural language understanding using multi-armed bandits and implicit feedback** (2020)<details><summary>Fabian Moerchen, Patrick Ernst, Giovanni Zappella</summary>Fabian Moerchen, Patrick Ernst, Giovanni Zappella</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2102.13101)


+ **User Feedback-based Online Learning for Intent Classification** (2023)<details><summary>Kaan G\"on\cc, Baturay Sa\uglam, Onat Dalmaz, et al.</summary>Kaan G\"on\cc, Baturay Sa\uglam, Onat Dalmaz, Tolga \cCukur, Serdar Kozat, Hamdi Dibeklioglu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.07530)


+ **Online personalizing white-box llms generation with neural bandits** (2024)<details><summary>Zekai Chen, Po-Yu Chen, Francois Buet-Golfouse</summary>Zekai Chen, Po-Yu Chen, Francois Buet-Golfouse</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2404.16115)


+ **LLMs Are In-Context Bandit Reinforcement Learners** (2024)<details><summary>Giovanni Monea, Antoine Bosselut, Kiant\'e Brantley, et al.</summary>Giovanni Monea, Antoine Bosselut, Kiant\'e Brantley, Yoav Artzi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2410.05362)


+ **Cost-Effective Online Multi-LLM Selection with Versatile Reward Models** (2024)<details><summary>Xiangxiang Dai, Jin Li, Xutong Liu, et al.</summary>Xiangxiang Dai, Jin Li, Xutong Liu, Anqi Yu, John Lui</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2405.16587)


+ **Tokenized Reinforcement Learning for LLM Generation: A Survey** (2025)<details><summary>Minseok Shin, Anji Gao, Xiang Li, et al.</summary>Minseok Shin, Anji Gao, Xiang Li, Tianyi Xie, Wei Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2509.02547)


+ **LLM Bandit: Cost-Efficient LLM Generation via Preference-Conditioned Dynamic Routing** (2025)<details><summary>Yang Li</summary>Yang Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2502.02743)


+ **Learning to Route LLMs from Bandit Feedback: One Policy, Many Trade-offs** (2025)<details><summary>Wang Wei, Tiankai Yang, Hongjie Chen, et al.</summary>Wang Wei, Tiankai Yang, Hongjie Chen, Yue Zhao, Franck Dernoncourt, Ryan A. Rossi, Hoda Eldardiry</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2510.07429)


+ **Comparing Exploration-Exploitation Strategies of LLMs and Humans: Insights from Standard Multi-armed Bandit Tasks** (2025)<details><summary>Ziyuan Zhang, Darcy Wang, Ningyuan Chen, et al.</summary>Ziyuan Zhang, Darcy Wang, Ningyuan Chen, Rodrigo Mansur, Vahid Sarhangian</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2505.09901)


## Contextual Understanding
+ **Can large language models explore in-context?** (2024)<details><summary>Akshay Krishnamurthy, Keegan Harris, Dylan J Foster, et al.</summary>Akshay Krishnamurthy, Keegan Harris, Dylan J Foster, Cyril Zhang, Aleksandrs Slivkins</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2403.15371)


+ **Code Repair with LLMs gives an Exploration-Exploitation Tradeoff** (2024)<details><summary>Hao Tang, Keya Hu, Jin Peng Zhou, et al.</summary>Hao Tang, Keya Hu, Jin Peng Zhou, Sicheng Zhong, Wei-Long Zheng, Xujie Si, Kevin Ellis</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2405.17503)


+ **Efficient exploration for llms** (2024)<details><summary>Vikranth Dwaracherla, Seyed Mohammad Asghari, Botao Hao, et al.</summary>Vikranth Dwaracherla, Seyed Mohammad Asghari, Botao Hao, Benjamin Van Roy</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2402.00396)


+ **Enhancing Sequential Recommendations through Multi-Perspective Reflections and Iteration** (2024)<details><summary>Weicong Qin, Yi Xu, Weijie Yu, et al.</summary>Weicong Qin, Yi Xu, Weijie Yu, Chenglei Shen, Xiao Zhang, Ming He, Jianping Fan, Jun Xu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2409.06377)


+ **Controlling Large Language Model Agents with Entropic Activation Steering** (2024)<details><summary>Nate Rahn, Pierluca D'Oro, Marc G Bellemare</summary>Nate Rahn, Pierluca D'Oro, Marc G Bellemare</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2406.00244)


+ **Chunks as arms: Multi-armed bandit-guided sampling for long-context llm preference optimization** (2025)<details><summary>Shaohua Duan, Xinze Li, Zhenghao Liu, et al.</summary>Shaohua Duan, Xinze Li, Zhenghao Liu, Xiaoyuan Yi, Yukun Yan, Shuo Wang, Yu Gu, Ge Yu, Maosong Sun</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2508.13993)


+ **Efficient jailbreak attack sequences on large language models via multi-armed bandit-based context switching** (2025)<details><summary>Aditya Ramesh, Shivam Bhardwaj, Aditya Saibewar, et al.</summary>Aditya Ramesh, Shivam Bhardwaj, Aditya Saibewar, Manohar Kaul</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2410.11533)


+ **EVOLvE: Evaluating and Optimizing LLMs For In-Context Exploration** (2025)<details><summary>Allen Nie, Yi Su, Bo Chang, et al.</summary>Allen Nie, Yi Su, Bo Chang, Jonathan Lee, Ed H. Chi, Quoc V Le, Minmin Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2410.06238)


+ **Online Multi-LLM Selection via Contextual Bandits under Unstructured Context Evolution** (2025)<details><summary>Manhin Poon, XiangXiang Dai, Xutong Liu, et al.</summary>Manhin Poon, XiangXiang Dai, Xutong Liu, Fang Kong, John Lui, Jinhang Zuo</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2506.17670)


+ **Context Attribution with Multi-Armed Bandit Optimization** (2025)<details><summary>Deng Pan, Keerthiram Murugesan, Nuno Moniz, et al.</summary>Deng Pan, Keerthiram Murugesan, Nuno Moniz, Nitesh Chawla</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2506.19977)


## Retrieval-Augmented Generation
+ **M-RAG: Reinforcing Large Language Model Performance through Retrieval-Augmented Generation with Multiple Partitions** (2024)<details><summary>Zheng Wang, Shu Xian Teo, Jieer Ouyang, et al.</summary>Zheng Wang, Shu Xian Teo, Jieer Ouyang, Yongjun Xu, Wei Shi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2405.16420)


+ **AutoRAG-HP: Automatic Online Hyper-Parameter Tuning for Retrieval-Augmented Generation** (2024)<details><summary>Jia Fu, Xiaoting Qin, Fangkai Yang, et al.</summary>Jia Fu, Xiaoting Qin, Fangkai Yang, Lu Wang, Jue Zhang, Qingwei Lin, Yubo Chen, Dongmei Zhang, Saravan Rajmohan, Qi Zhang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2406.19251)


+ **Advances in Neural Information Processing Systems** (2024)<details><summary>Qinggang Zhang, Junnan Dong, Hao Chen, et al.</summary>Qinggang Zhang, Junnan Dong, Hao Chen, Daochen Zha, Zailiang Yu, Xiao Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://wenku.baidu.com/view/be3011116edb6f1aff001f00.html?fr=sogou&_wkts_=1763891239715)


+ **MBA-RAG: a Bandit Approach for Adaptive Retrieval-Augmented Generation through Question Complexity** (2025)<details><summary>Xiaqiang Tang, Qiang Gao, Jian Li, et al.</summary>Xiaqiang Tang, Qiang Gao, Jian Li, Nan Du, Qi Li, Sihong Xie</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2412.01572)


+ **IEEE INFOCOM 2025 - IEEE Conference on Computer Communications** (2025)<details><summary>Tao Ouyang, Guihang Hong, Kongyange Zhao, et al.</summary>Tao Ouyang, Guihang Hong, Kongyange Zhao, Zhi Zhou, Weigang Wu, Zhaobiao Lv, Xu Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11199746)


+ **Adapting to non-stationary environments: Multi-armed bandit enhanced retrieval-augmented generation on knowledge graphs** (2025)<details><summary>Xiaqiang Tang, Jian Li, Nan Du, et al.</summary>Xiaqiang Tang, Jian Li, Nan Du, Sihong Xie</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2412.07618)


+ **Context Attribution with Multi-Armed Bandit Optimization** (2025)<details><summary>Deng Pan, Keerthiram Murugesan, Nuno Moniz, et al.</summary>Deng Pan, Keerthiram Murugesan, Nuno Moniz, Nitesh Chawla</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2506.19977)


# 📍 LLM-enhancements for Multi-armed Bandits

## Optimization Objective
+ **On Bits and Bandits: Quantifying the Regret-Information Trade-off** (2024)<details><summary>Itai Shufaro, Nadav Merlis, Nir Weinberger, et al.</summary>Itai Shufaro, Nadav Merlis, Nir Weinberger, Shie Mannor</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16581)


+ **Beyond Numeric Awards: In-Context Dueling Bandits with LLM Agents** (2024)<details><summary>Fanzeng Xia, Hao Liu, Yisong Yue, et al.</summary>Fanzeng Xia, Hao Liu, Yisong Yue, Tongxin Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18354)


+ **Do llm agents have regret? a case study in online learning and games** (2024)<details><summary>Chanwoo Park, Xiangyu Liu, Asuman Ozdaglar, et al.</summary>Chanwoo Park, Xiangyu Liu, Asuman Ozdaglar, Kaiqing Zhang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.16843)


+ **LLMs and the Abstraction and Reasoning Corpus: Successes, Failures, and the Importance of Object-based Representations** (2023)<details><summary>Ali Baheri, Aman Hosseini, Mehdi Jiang, et al.</summary>Ali Baheri, Aman Hosseini, Mehdi Jiang, Peter Chin</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.06692)


+ **Neural Dueling Bandits** (2024)<details><summary>Arun Verma, Zhongxiang Dai, Xiaoqiang Lin, et al.</summary>Arun Verma, Zhongxiang Dai, Xiaoqiang Lin, Patrick Jaillet, Bryan Kian Hsiang Low</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01887)


+ **LLM-informed multi-armed bandit strategies for non-stationary environments** (2023)<details><summary>J De Curt\`o, Irene de Zarz\`a, Gemma Roig, et al.</summary>J De Curt\`o, Irene de Zarz\`a, Gemma Roig, Juan Carlos Cano, Pietro Manzoni, Carlos T Calafate</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.mdpi.com/2079-9292/12/13/2814)


## Arm Definition
+ **Neural Dueling Bandits** (2024)<details><summary>Arun Verma, Zhongxiang Dai, Xiaoqiang Lin, et al.</summary>Arun Verma, Zhongxiang Dai, Xiaoqiang Lin, Patrick Jaillet, Bryan Kian Hsiang Low</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01887)


+ **Beyond Numeric Awards: In-Context Dueling Bandits with LLM Agents** (2024)<details><summary>Fanzeng Xia, Hao Liu, Yisong Yue, et al.</summary>Fanzeng Xia, Hao Liu, Yisong Yue, Tongxin Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18354)


+ **LLMs and the Abstraction and Reasoning Corpus: Successes, Failures, and the Importance of Object-based Representations** (2023)<details><summary>Ali Baheri, Aman Hosseini, Mehdi Jiang, et al.</summary>Ali Baheri, Aman Hosseini, Mehdi Jiang, Peter Chin</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.06692)


+ **Guiding pretraining in reinforcement learning with large language models** (2023)<details><summary>Yuqing Du, Olivia Watkins, Zihan Wang, et al.</summary>Yuqing Du, Olivia Watkins, Zihan Wang, C\'edric Colas, Trevor Darrell, Pieter Abbeel, Abhishek Gupta, Jacob Andreas</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://proceedings.mlr.press/v202/du23f.html)


+ **Multi-Armed Bandit Approach for Optimizing Training on Synthetic Data** (2024)<details><summary>Abdulrahman Kerim, Leandro Soriano Marcolino, Erickson R. Nascimento, et al.</summary>Abdulrahman Kerim, Leandro Soriano Marcolino, Erickson R. Nascimento, Richard Jiang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05466)


+ **Investigating the Relationship Between Physical Activity and Tailored Behavior Change Messaging: Connecting Contextual Bandit with Large Language Models** (2025)<details><summary>Haochen Song, Dominik Hofer, Rania Islambouli, et al.</summary>Haochen Song, Dominik Hofer, Rania Islambouli, Laura Hawkins, Ananya Bhattacharjee, Meredith Franklin, Joseph Jay Williams</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.07275)


## Environment
+ **LLM-informed multi-armed bandit strategies for non-stationary environments** (2023)<details><summary>J De Curt\`o, Irene de Zarz\`a, Gemma Roig, et al.</summary>J De Curt\`o, Irene de Zarz\`a, Gemma Roig, Juan Carlos Cano, Pietro Manzoni, Carlos T Calafate</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.mdpi.com/2079-9292/12/13/2814)


+ **Towards a Pretrained Model for Restless Bandits via Multi-arm Generalization** (2024)<details><summary>Yunfan Zhao, Nikhil Behari, Edward Hughes, et al.</summary>Yunfan Zhao, Nikhil Behari, Edward Hughes, Edwin Zhang, Dheeraj Nagaraj, Karl Tuyls, Aparna Taneja, Milind Tambe</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.14526)


+ **Jump Starting Bandits with LLM-Generated Prior Knowledge** (2024)<details><summary>Parand Alamdari, Yanshuai Cao, Kevin Wilson</summary>Parand Alamdari, Yanshuai Cao, Kevin Wilson</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19317)


+ **In-context impersonation reveals Large Language Models' strengths and biases** (2024)<details><summary>Leonard Salewski, Stephan Alaniz, Isabel Rio-Torto, et al.</summary>Leonard Salewski, Stephan Alaniz, Isabel Rio-Torto, Eric Schulz, Zeynep Akata</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.14930)


+ **Multi-Armed Bandit Approach for Optimizing Training on Synthetic Data** (2024)<details><summary>Abdulrahman Kerim, Leandro Soriano Marcolino, Erickson R. Nascimento, et al.</summary>Abdulrahman Kerim, Leandro Soriano Marcolino, Erickson R. Nascimento, Richard Jiang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05466)


+ **EnvGen: Generating and Adapting Environments via LLMs for Training Embodied Agents** (2024)<details><summary>Abhay Zala, Jaemin Cho, Han Lin, et al.</summary>Abhay Zala, Jaemin Cho, Han Lin, Jaehong Yoon, Mohit Bansal</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12014)


+ **Balancing act: prioritization strategies for llm-designed restless bandit rewards** (2025)<details><summary>Shresth Verma, Niclas Boehmer, Lingkai Kong, et al.</summary>Shresth Verma, Niclas Boehmer, Lingkai Kong, Milind Tambe</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.12112)


+ **Investigating the Relationship Between Physical Activity and Tailored Behavior Change Messaging: Connecting Contextual Bandit with Large Language Models** (2025)<details><summary>Haochen Song, Dominik Hofer, Rania Islambouli, et al.</summary>Haochen Song, Dominik Hofer, Rania Islambouli, Laura Hawkins, Ananya Bhattacharjee, Meredith Franklin, Joseph Jay Williams</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.07275)


+ **Toward efficient exploration by large language model agents** (2025)<details><summary>Dilip Arumugam, Thomas L Griffiths</summary>Dilip Arumugam, Thomas L Griffiths</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.20997)


+ **Prior-informed optimization of treatment recommendation via bandit algorithms trained on large language model-processed historical records** (2025)<details><summary>Saman Nessari, Ali Bozorgi-Amiri</summary>Saman Nessari, Ali Bozorgi-Amiri</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.19014)


## Reward Formulation
+ **Statistical and computational trade-off in multi-agent multi-armed bandits** (2024)<details><summary>Filippo Vannella, Alexandre Proutiere, Jaeseong Jeong</summary>Filippo Vannella, Alexandre Proutiere, Jaeseong Jeong</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.5555/3666122.3669142)


+ **On the Importance of Uncertainty in Decision-Making with Large Language Models** (2024)<details><summary>Nicol\`o Felicioni, Lucas Maystre, Sina Ghiassian, et al.</summary>Nicol\`o Felicioni, Lucas Maystre, Sina Ghiassian, Kamil Ciosek</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02649)


+ **A decision-language model (DLM) for dynamic restless multi-armed bandit tasks in public health** (2024)<details><summary>Nikhil Behari, Edwin Zhang, Yunfan Zhao, et al.</summary>Nikhil Behari, Edwin Zhang, Yunfan Zhao, Aparna Taneja, Dheeraj Nagaraj, Milind Tambe</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14807)


+ **Towards a Pretrained Model for Restless Bandits via Multi-arm Generalization** (2024)<details><summary>Yunfan Zhao, Nikhil Behari, Edward Hughes, et al.</summary>Yunfan Zhao, Nikhil Behari, Edward Hughes, Edwin Zhang, Dheeraj Nagaraj, Karl Tuyls, Aparna Taneja, Milind Tambe</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2310.14526)


+ **Do llm agents have regret? a case study in online learning and games** (2024)<details><summary>Chanwoo Park, Xiangyu Liu, Asuman Ozdaglar, et al.</summary>Chanwoo Park, Xiangyu Liu, Asuman Ozdaglar, Kaiqing Zhang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2403.16843)


+ **Balancing act: prioritization strategies for llm-designed restless bandit rewards** (2025)<details><summary>Shresth Verma, Niclas Boehmer, Lingkai Kong, et al.</summary>Shresth Verma, Niclas Boehmer, Lingkai Kong, Milind Tambe</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2408.12112)


+ **Large Language Model-Enhanced Multi-Armed Bandits** (2025)<details><summary>Jiahang Sun, Zhiyong Wang, Runhan Yang, et al.</summary>Jiahang Sun, Zhiyong Wang, Runhan Yang, Chenjun Xiao, John C. S. Lui, Zhongxiang Dai</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2502.01118)


+ **Prior-informed optimization of treatment recommendation via bandit algorithms trained on large language model-processed historical records** (2025)<details><summary>Saman Nessari, Ali Bozorgi-Amiri</summary>Saman Nessari, Ali Bozorgi-Amiri</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2510.19014)


+ **Prioritization Strategies for LLM-Designed Restless Bandit Rewards in Public Health** (2024)<details><summary>Shresth Verma, Niclas Boehmer, Lingkai Kong, et al.</summary>Shresth Verma, Niclas Boehmer, Lingkai Kong, Milind Tambe</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2408.12112)


+ **Beyond Numeric Rewards: In-Context Dueling Bandits with LLM Agents** (2025)<details><summary>Fanzeng Xia, Hao Liu, Yisong Yue, et al.</summary>Fanzeng Xia, Hao Liu, Yisong Yue, Tongxin Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2407.01887)


+ **When Greedy Wins: Emergent Exploitation Bias in Meta-Bandit LLM Training** (2025)<details><summary>Sanxing Chen, Xiaoyin Chen, Yukun Huang, et al.</summary>Sanxing Chen, Xiaoyin Chen, Yukun Huang, Roy Xie, Bhuwan Dhingra</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2509.24923)


## Sampling Strategy
+ **Towards optimizing with large language models** (2023)<details><summary>Pei-Fu Guo, Ying-Hsuan Chen, Yun-Da Tsai, et al.</summary>Pei-Fu Guo, Ying-Hsuan Chen, Yun-Da Tsai, Shou-De Lin</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2310.05204)


+ **On Bits and Bandits: Quantifying the Regret-Information Trade-off** (2024)<details><summary>Itai Shufaro, Nadav Merlis, Nir Weinberger, et al.</summary>Itai Shufaro, Nadav Merlis, Nir Weinberger, Shie Mannor</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2405.16581)


+ **Efficient Sequential Decision Making with Large Language Models** (2024)<details><summary>Dingyang Chen, Qi Zhang, Yinglun Zhu</summary>Dingyang Chen, Qi Zhang, Yinglun Zhu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2406.12125)


+ **Jump Starting Bandits with LLM-Generated Prior Knowledge** (2024)<details><summary>Parand Alamdari, Yanshuai Cao, Kevin Wilson</summary>Parand Alamdari, Yanshuai Cao, Kevin Wilson</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2024.emnlp-main.1107)


+ **Cost-Effective Online Multi-LLM Selection with Versatile Reward Models** (2024)<details><summary>Xiangxiang Dai, Jin Li, Xutong Liu, et al.</summary>Xiangxiang Dai, Jin Li, Xutong Liu, Anqi Yu, John Lui</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2405.16587)


+ **Large Language Model-Enhanced Multi-Armed Bandits** (2025)<details><summary>Jiahang Sun, Zhiyong Wang, Runhan Yang, et al.</summary>Jiahang Sun, Zhiyong Wang, Runhan Yang, Chenjun Xiao, John C. S. Lui, Zhongxiang Dai</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2502.01118)


+ **When Greedy Wins: Emergent Exploitation Bias in Meta-Bandit LLM Training** (2025)<details><summary>Sanxing Chen, Xiaoyin Chen, Yukun Huang, et al.</summary>Sanxing Chen, Xiaoyin Chen, Yukun Huang, Roy Xie, Bhuwan Dhingra</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2509.24923)


+ **Llms are greedy agents: Effects of rl fine-tuning on decision-making abilities** (2025)<details><summary>Thomas Schmied, J\"org Bornschein, Jordi Grau-Moya, et al.</summary>Thomas Schmied, J\"org Bornschein, Jordi Grau-Moya, Markus Wulfmeier, Razvan Pascanu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2504.16078)


+ **Evaluation of LLM Powered Agentic AI for Solving Multi-Arm Bandit Problems** (2025)<details><summary>Jawad Hazime, Junaid Farooq</summary>Jawad Hazime, Junaid Farooq</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.10458)


+ **TextBandit: Evaluating Probabilistic Reasoning in LLMs Through Language-Only Decision Tasks** (2025)<details><summary>Jimin Lim, Arjun Damerla, Arthur Jiang, et al.</summary>Jimin Lim, Arjun Damerla, Arthur Jiang, Nam Le</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2510.13878)


+ **Toward efficient exploration by large language model agents** (2025)<details><summary>Dilip Arumugam, Thomas L Griffiths</summary>Dilip Arumugam, Thomas L Griffiths</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2504.20997)


## Action Decision
+ **Using large language models for hyperparameter optimization** (2023)<details><summary>Michael R Zhang, Nishkrit Desai, Juhan Bae, et al.</summary>Michael R Zhang, Nishkrit Desai, Juhan Bae, Jonathan Lorraine, Jimmy Ba</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2312.04528)


+ **Towards optimizing with large language models** (2023)<details><summary>Pei-Fu Guo, Ying-Hsuan Chen, Yun-Da Tsai, et al.</summary>Pei-Fu Guo, Ying-Hsuan Chen, Yun-Da Tsai, Shou-De Lin</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2310.05204)


+ **LLMs for User Interest Exploration: A Hybrid Approach** (2024)<details><summary>Jianling Wang, Haokai Lu, Yifan Liu, et al.</summary>Jianling Wang, Haokai Lu, Yifan Liu, He Ma, Yueqi Wang, Yang Gu, Shuzhou Zhang, Shuchao Bi, Lexi Baugher, Ed Chi, others</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2405.16363)


+ **Large language models as evolutionary optimizers** (2024)<details><summary>Shengcai Liu, Caishun Chen, Xinghua Qu, et al.</summary>Shengcai Liu, Caishun Chen, Xinghua Qu, Ke Tang, Yew-Soon Ong</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2310.19046)


+ **Large Language Model-Enhanced Multi-Armed Bandits** (2025)<details><summary>Jiahang Sun, Zhiyong Wang, Runhan Yang, et al.</summary>Jiahang Sun, Zhiyong Wang, Runhan Yang, Chenjun Xiao, John C. S. Lui, Zhongxiang Dai</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2502.01118)


+ **When Greedy Wins: Emergent Exploitation Bias in Meta-Bandit LLM Training** (2025)<details><summary>Sanxing Chen, Xiaoyin Chen, Yukun Huang, et al.</summary>Sanxing Chen, Xiaoyin Chen, Yukun Huang, Roy Xie, Bhuwan Dhingra</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2509.24923)


+ **Evaluation of LLM Powered Agentic AI for Solving Multi-Arm Bandit Problems** (2025)<details><summary>Jawad Hazime, Junaid Farooq</summary>Jawad Hazime, Junaid Farooq</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.1109/COINS65080.2025.11125743)


+ **Llms are greedy agents: Effects of rl fine-tuning on decision-making abilities** (2025)<details><summary>Thomas Schmied, J\"org Bornschein, Jordi Grau-Moya, et al.</summary>Thomas Schmied, J\"org Bornschein, Jordi Grau-Moya, Markus Wulfmeier, Razvan Pascanu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2504.16078)


+ **TextBandit: Evaluating Probabilistic Reasoning in LLMs Through Language-Only Decision Tasks** (2025)<details><summary>Jimin Lim, Arjun Damerla, Arthur Jiang, et al.</summary>Jimin Lim, Arjun Damerla, Arthur Jiang, Nam Le</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2510.13878)


+ **Toward efficient exploration by large language model agents** (2025)<details><summary>Dilip Arumugam, Thomas L Griffiths</summary>Dilip Arumugam, Thomas L Griffiths</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/arXiv.2504.20997)






# 👨‍💻 Team

Here is the list of our contributors in each modality of this repository.

| Modality/Task                      |  Contributors                                                 |
| ----------------------------- | -------------------------------------------------------------------- |
| Bandit for LLM | Siguang Chen, miao Xie                                       |
| LLM for Bandit | Siguang Chen, Miao Xie                                       |
| Leaders               | Miao Xie                                                   |

# 😉 Citation
If you find this work useful in your research, Please cite the paper as below:
```bib
@article{xxx,
    
}
```

<!-- # ⭐️ Star History
 -->

