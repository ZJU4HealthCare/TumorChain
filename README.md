<h1 align = "center">
TumorChain: Interleaved Multimodal Chain-of-Thought Reasoning for Traceable Clinical Tumor Analysis
</h1>
Official Repo for Paper ‘’TumorChain: Interleaved Multimodal Chain-of-Thought Reasoning for Traceable Clinical Tumor Analysis‘’

## 🌟 Overview

Welcome to **TumorChain!** 

Our goal is to advance clinical tumor analysis through reliable multimodal reasoning at scale. This project presents a cohesive three-part framework—Dataset, Benchmark, and Model—to enable safe, explainable, and reproducible tumor assessment in high-stakes settings.

<p align="center">
  <img src="images/teaser.png" style="width:90%;vertical-align:middle;" />
</p>

##### :clap: Core Vision:

- Establish a closed-loop multimodal reasoning pipeline that standardizes the path from findings to impressions to pathology.
- Create high-quality benchmarks and reproducible evaluation protocols to enable cross-institution comparison and robust generalization.
- Deliver an interpretable, calibrated, and traceable multimodal framework that reduces hallucinations and supports real-world clinical decision-making.

## :mailbox: Data collection and statistics

We introduce TumorCoT-1.5M — a large-scale dataset comprising 1.5 million Chain-of-Thought (CoT) labeled VQA prompts, paired with 3D CT scans, featuring stepwise reasoning and cross-modal alignments along the findings–impression–pathology trajectory.

<img src="images/agent.jpg" style="width:70%;vertical-align:middle;" /><img src="images/data.jpg" style="width:30%;vertical-align:middle;" />

## :ferris_wheel: Model Architecture

TumorChain is a **multi-modal, iterative interleaved reasoning framework** for 3D CT tumor analysis that fuses a 3D vision encoder, organ segmentation model, auxiliary classification model, an MLP projector, and a large language model (LLM) to perform stepwise, evidence-grounded reasoning from findings to impressions to pathology, with traceable evidence and calibrated uncertainty.

<p align="center">
  <img src="images/model.png" style="width:80%;vertical-align:middle;" />
</p>

## 🛠️ Getting Started
😊 We will release our task definitions, benchmarks, and evaluation protocols in the near future to advance safe, explainable, and reproducible multimodal reasoning for high-stakes tumor analysis. 🚀
