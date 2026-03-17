<h1 align = "center">
TumorChain: Interleaved Multimodal Chain-of-Thought Reasoning for Traceable Clinical Tumor Analysis
</h1>
Official Repo for Paper ‘’TumorChain: Interleaved Multimodal Chain-of-Thought Reasoning for Traceable Clinical Tumor Analysis‘’

<div align="center">

Sijing Li<sup>1,2*</sup>, Zhongwei Qiu<sup>2,3,1*</sup>, Jiang Liu<sup>1</sup>, Wenqiao Zhang<sup>1†</sup>, Tianwei Lin<sup>1,2</sup>, <br>
Yihan Xie<sup>1</sup>, Jianxiang An<sup>1</sup>, Boxiang Yun<sup>2</sup>, Chenglin Yang<sup>1</sup>, Jun Xiao<sup>1</sup>, Guangyu Guo<sup>2,1</sup>, <br>
Jiawen Yao<sup>2</sup>, Wei Liu<sup>2</sup>, Yuan Gao<sup>2</sup>, Ke Yan<sup>2</sup>, Weiwei Cao<sup>2</sup>, Zhilin Zheng<sup>2</sup> <br>
Tony C. W. MOK<sup>2</sup>, Kai Cao<sup>4</sup>, Yu Shi<sup>5</sup>, Jiuyu Zhang<sup>5</sup>, Jian Zhou<sup>6</sup> <br>
Beng Chin Ooi<sup>1</sup>, Yingda Xia†<sup>2</sup>, Ling Zhang<sup>2</sup> <br>

<sup>1</sup>Zhejiang University <sup>2</sup>DAMO Academy, Alibaba Group <sup>3</sup>Hupan Lab
<sup>4</sup>Shanghai Institution of Pancreatic Disease <sup>5</sup>Shengjing Hospital of China Medical University <sup>6</sup>Sun Yat-sen University Cancer Center
<br>

<a href='https://arxiv.org/abs/2603.05867'><img src='https://img.shields.io/badge/Paper-Arxiv-red'></a>
<a href='https://github.com/alibaba-damo-academy/Tumorchain'><img src='https://img.shields.io/badge/Damo-GitHub-green'></a>

</div>

## 🌟 Overview

Welcome to **TumorChain!** 

Our goal is to advance clinical tumor analysis through reliable multimodal reasoning at scale. This project presents a cohesive three-part framework—Dataset, Benchmark, and Model—to enable safe, explainable, and reproducible tumor assessment in high-stakes settings.

<p align="center">
  <img src="image/teaser.png" style="width:90%;vertical-align:middle;" />
</p>

##### :clap: Core Vision:

- Establish a closed-loop multimodal reasoning pipeline that standardizes the path from findings to impressions to pathology.
- Create high-quality benchmarks and reproducible evaluation protocols to enable cross-institution comparison and robust generalization.
- Deliver an interpretable, calibrated, and traceable multimodal framework that reduces hallucinations and supports real-world clinical decision-making.

## :mailbox: Data collection and statistics

We introduce TumorCoT-1.5M — a large-scale dataset comprising 1.5 million Chain-of-Thought (CoT) labeled VQA prompts, paired with 3D CT scans, featuring stepwise reasoning and cross-modal alignments along the findings–impression–pathology trajectory.

<img src="image/agent.jpg" style="width:70%;vertical-align:middle;" /><img src="image/data.jpg" style="width:30%;vertical-align:middle;" />

## :ferris_wheel: Model Architecture

TumorChain is a **multi-modal, iterative interleaved reasoning framework** for 3D CT tumor analysis that fuses a 3D vision encoder, organ segmentation model, auxiliary classification model, an MLP projector, and a large language model (LLM) to perform stepwise, evidence-grounded reasoning from findings to impressions to pathology, with traceable evidence and calibrated uncertainty.

<p align="center">
  <img src="image/model.png" style="width:80%;vertical-align:middle;" />
</p>

## 🛠️ Getting Started
😊 We will release our task definitions, benchmarks, and evaluation protocols in the near future to advance safe, explainable, and reproducible multimodal reasoning for high-stakes tumor analysis. 🚀
