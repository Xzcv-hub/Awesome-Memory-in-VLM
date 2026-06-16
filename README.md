# Awesome-Memory-in-VLM
> **Our paper is coming soon:** *Memory in Vision-Language Models: A Survey on 4D Taxonomy, Mechanisms, and Applications*
---

## Taxonomy

```
Memory in Vision-Language Models
├── 1. Long Video Understanding & Generation
│   ├── 1.1 Offline Long-Video Understanding
│   │   ├── Long-form Video QA
│   │   ├── Event Understanding
│   │   └── Temporal Grounding
│   ├── 1.2 Online (Streaming) Video Understanding
│   ├── 1.3 Reasoning over Long Videos
│   ├── 1.4 Long Video Generation
│   └── 1.5 Long Video Prediction / World Models
├── 2. Image Reasoning & Description
│   ├── 2.1 Multi-image Reasoning
│   └── 2.2 Image Captioning
├── 3. Continual Learning
│   ├── 3.1 Incremental Recognition
│   ├── 3.2 Continual Knowledge Updating
│   └── 3.3 Continual Task Adaptation
├── 4. Embodied AI
│   ├── 4.1 Vision-Language Navigation
│   │   ├── Instruction-following & Spatial Memory
│   │   ├── Dialogue-based Navigation
│   │   └── Long-horizon & Persistent Navigation
│   ├── 4.2 Vision-Language Action
│   └── 4.3 Autonomous Driving
├── 5. Multimodal RAG
│   ├── 5.1 Knowledge-Augmented Visual QA
│   ├── 5.2 Multimodal Document Retrieval & QA
│   └── 5.3 Domain-Specific & Scenario-Grounded RAG
├── 6. Egocentric Vision
│   ├── 6.1 Episodic Retrieval
│   └── 6.2 Wearable Assistants
├── 7. Personalized Assistants
│   ├── 7.1 Concept Personalization
│   └── 7.2 Conversational Memory
└── 8. Virtual-Environment Interaction
    ├── 8.1 Open-World Agents
    └── 8.2 GUI Agents
        ├── Web agents
        ├── Mobile agents
        └── Computer agents
```

---

## Contents

- [Application Papers](#application-papers)
  - [1. Long Video Understanding & Generation](#1-long-video-understanding--generation)
  - [2. Image Reasoning & Description](#2-image-reasoning--description)
  - [3. Continual Learning](#3-continual-learning)
  - [4. Embodied AI](#4-embodied-ai)
  - [5. Multimodal RAG](#5-multimodal-rag)
  - [6. Egocentric Vision](#6-egocentric-vision)
  - [7. Personalized Assistants](#7-personalized-assistants)
  - [8. Virtual-Environment Interaction](#8-virtual-environment-interaction)
- [Benchmarks](#benchmarks)
- [Contributing](#contributing)

---

## Application Papers

### 1. Long Video Understanding & Generation

#### 1.1 Offline Long-Video Understanding

<details>
<summary><b>Long-form Video QA</b></summary>

- [DeepStory: Video Story QA by Deep Embedded Memory Networks](https://arxiv.org/abs/1707.00836)
- [A Simple LLM Framework for Long-Range Video Question-Answering](https://arxiv.org/abs/2312.17235)
- [MovieChat: From Dense Token to Sparse Memory for Long Video Understanding](https://arxiv.org/abs/2307.16449v4)
- [MovieChat+: Question-aware Sparse Memory for Long Video Question Answering](https://arxiv.org/abs/2404.17176)
- [MA-LMM: Memory-Augmented Large Multimodal Model for Long-Term Video Understanding](https://arxiv.org/abs/2404.05726)
- [Memory-enhanced Retrieval Augmentation for Long Video Understanding](https://arxiv.org/abs/2503.09149)
- [Glance and Focus: Memory Prompting for Multi-Event Video Question Answering](https://arxiv.org/html/2401.01529v1)
- [Language Repository for Long Video Understanding](https://arxiv.org/abs/2403.14622)

</details>

<details>
<summary><b>Event Understanding</b></summary>

- [HERMES: temporal-coHERent long-forM understanding with Episodes and Semantics](https://arxiv.org/abs/2408.17443)
- [Enhancing Long Video Understanding via Hierarchical Event-Based Memory](https://arxiv.org/abs/2409.06299)
- [AMEGO: Active Memory from long EGOcentric videos](https://arxiv.org/html/2409.10917v1)
- [Ω-Video: A Training-Free Approach to Long Video Understanding via Continuous-Time Memory Consolidation](https://arxiv.org/html/2501.19098v1)
- [Video-EM: Event-Centric Episodic Memory for Long-Form Video Understanding](https://arxiv.org/abs/2508.09486)
- [GCAgent: Long-Video Understanding via Schematic and Narrative Episodic Memory](https://arxiv.org/abs/2511.12027)
- [HippoMM: Hippocampal-inspired Multimodal Memory for Long Audiovisual Event Understanding](https://arxiv.org/html/2504.10739v2)

</details>

<details>
<summary><b>Temporal Grounding</b></summary>

- [TimeChat: A Time-sensitive Multimodal Large Language Model for Long Video Understanding](https://arxiv.org/abs/2312.02051)
- [VTimeLLM: Empower LLM to Grasp Video Moments](https://arxiv.org/abs/2311.18445)
- [Grounded-VideoLLM: Sharpening Fine-grained Temporal Grounding in Video Large Language Models](https://arxiv.org/abs/2410.03290)
- [TRACE: Temporal Grounding Video LLM via Causal Event Modeling](https://arxiv.org/abs/2410.05643)
- [VideoExpert: Augmented LLM for Temporal-Sensitive Video Understanding](https://arxiv.org/html/2504.07519v1)
- [Time-R1: Post-Training Large Vision Language Model for Temporal Video Grounding](https://arxiv.org/abs/2503.13377)
- [VideoITG: Multimodal Video Understanding with Instructed Temporal Grounding](https://arxiv.org/html/2507.13353v2)
- [Number it: Temporal Grounding Videos like Flipping Manga](https://arxiv.org/abs/2411.10332)
- [E.M.Ground: A Temporal Grounding Vid-LLM with Holistic Event Perception and Matching](https://arxiv.org/html/2602.05215v1)
- [Seq2Time: Sequential Knowledge Transfer for Video LLM Temporal Grounding](https://arxiv.org/abs/2411.16932)

</details>

#### 1.2 Online (Streaming) Video Understanding

- [Streaming Long Video Understanding with Large Language Models](https://arxiv.org/abs/2405.16009)
- [VideoLLM-online: Online Video Large Language Model for Streaming Video](https://arxiv.org/abs/2406.11816)
- [Flash-VStream: Memory-Based Real-Time Understanding for Long Video Streams](https://arxiv.org/abs/2406.08085)
- [Streaming Video Understanding and Multi-round Interaction with Memory-enhanced Knowledge](https://arxiv.org/abs/2501.13468)
- [Streaming Video Question-Answering with In-context Video KV-Cache Retrieval](https://arxiv.org/html/2503.00540v1)
- [StreamMem: Query-Agnostic KV Cache Memory for Streaming Video Understanding](https://arxiv.org/abs/2508.15717)
- [Memory-efficient Streaming VideoLLMs for Real-time Procedural Video Understanding](https://arxiv.org/abs/2504.13915)
- [WAT: Online Video Understanding Needs Watching Before Thinking](https://arxiv.org/html/2603.13412v1)
- [StreamReady: Learning What to Answer and When in Long Streaming Videos](https://arxiv.org/abs/2603.08620)
- [CacheFlow: Compressive Streaming Memory for Efficient Long-Form Video Understanding](https://arxiv.org/abs/2511.13644)

#### 1.3 Reasoning over Long Videos

- [Video LLMs for Temporal Reasoning in Long Videos](https://arxiv.org/abs/2412.02930)
- [Narrative Aligned Long Form Video Question Answering](https://arxiv.org/abs/2603.19481)
- [MoviePuzzle: Visual Narrative Reasoning through Multimodal Order Learning](https://arxiv.org/abs/2306.02252)
- [VRBench: A Benchmark for Multi-Step Reasoning in Long Narrative Videos](https://arxiv.org/abs/2506.10857)
- [SAGE: Training Smart Any-Horizon Agents for Long Video Reasoning with Reinforcement Learning](https://arxiv.org/abs/2512.13874)
- [A Multi-Agent Perception-Action Alliance for Efficient Long Video Reasoning](https://arxiv.org/abs/2603.14052)
- [WorldMM: Dynamic Multimodal Memory Agent for Long Video Reasoning](https://arxiv.org/abs/2512.02425)
- [LongVideoAgent: Multi-Agent Reasoning with Long Videos](https://arxiv.org/html/2512.20618v1)
- [MINERVA-Cultural: A Benchmark for Cultural and Multilingual Long Video Reasoning](https://arxiv.org/abs/2601.10649)
- [A Very Big Video Reasoning Suite](https://arxiv.org/html/2602.20159v1)
- [VCRBench: Exploring Long-form Causal Reasoning Capabilities of Large Video Language Models](https://arxiv.org/abs/2505.08455)

#### 1.4 Long Video Generation

- [GEN3C: 3D-Informed World-Consistent Video Generation with Precise Camera Control](https://arxiv.org/abs/2503.03751)
- [Context as Memory: Scene-Consistent Interactive Long Video Generation with Memory Retrieval](https://arxiv.org/abs/2506.03141)
- [WorldWeaver: Generating Long-Horizon Video Worlds via Rich Perception](https://arxiv.org/abs/2508.15720)
- [Pack and Force Your Memory: Long-form and Consistent Video Generation](https://arxiv.org/abs/2510.01784)
- [LongLive: Real-time Interactive Long Video Generation](https://arxiv.org/abs/2509.22622)
- [VideoMemory: Toward Consistent Video Generation via Memory Integration](https://arxiv.org/abs/2601.03655)
- [Context Forcing: Consistent Autoregressive Video Generation with Long Context](https://arxiv.org/abs/2602.06028)
- [AnchorWeave: World-Consistent Video Generation with Retrieved Local Spatial Memories](https://arxiv.org/abs/2602.14941)
- [Relax Forcing: Relaxed KV-Memory for Consistent Long Video Generation](https://arxiv.org/html/2603.21366v1)
- [MemCam: Memory-Augmented Camera Control for Consistent Video Generation](https://arxiv.org/html/2603.26193v1)

#### 1.5 Long Video Prediction / World Models

- [EVA: An Embodied World Model for Future Video Anticipation](https://arxiv.org/abs/2410.15461)
- [Vid2World: Crafting Video Diffusion Models to Interactive World Models](https://arxiv.org/html/2505.14357v3)
- [Video World Models with Long-term Spatial Memory](https://arxiv.org/abs/2506.05284)
- [PAN: A World Model for General, Interactable, and Long-Horizon World Simulation](https://arxiv.org/abs/2511.09057)
- [RELIC: Interactive Video World Model with Long-Horizon Memory](https://arxiv.org/abs/2512.04040)
- [Astra: General Interactive World Model with Autoregressive Denoising](https://arxiv.org/abs/2512.08931)
- [LIVE: Long-horizon Interactive Video World Modeling](https://arxiv.org/abs/2602.03747)
- [VerseCrafter: Dynamic Realistic Video World Model with 4D Geometric Control](https://arxiv.org/abs/2601.05138)
- [Out of Sight but Not Out of Mind: Hybrid Memory for Dynamic Video World Models](https://arxiv.org/abs/2603.25716)

---

### 2. Image Reasoning & Description
#### 2.1 Multi-image Reasoning
#### 2.2 Image Captioning
---

### 3. Continual Learning

#### 3.1 Incremental Recognition

- [CLIP model is an Efficient Continual Learner](https://arxiv.org/abs/2210.03114)
- [Preventing Zero-Shot Transfer Degradation in Continual Learning of Vision-Language Models](https://arxiv.org/abs/2303.06628)
- [Continual Learning in Open-vocabulary Classification with Complementary Memory Systems](https://arxiv.org/abs/2307.01430)
- [Boosting Continual Learning of Vision-Language Models via Mixture-of-Experts Adapter](https://arxiv.org/abs/2403.11549)
- [CLAP4CLIP: Continual Learning with Probabilistic Finetuning for Vision-Language Models](https://arxiv.org/abs/2403.19137)
- [Class-Incremental Learning with CLIP: Adaptive Representation Adjustment and Parameter Fusion](https://arxiv.org/abs/2407.14143)
- [CoLeCLIP: Open-Domain Continual Learning via Joint Task Prompt and Vocabulary Learning](https://arxiv.org/abs/2403.10245)
- [LADA: Scalable Label-Specific CLIP Adapter for Continual Learning](https://arxiv.org/abs/2505.23271)
- [Continual Learning on CLIP via Incremental Prompt Tuning with Intrinsic Textual Anchors](https://arxiv.org/abs/2505.20680)

#### 3.2 Continual Knowledge Updating

- [Generative Negative Text Replay for Continual Vision-Language Pretraining](https://arxiv.org/abs/2210.17322)
- [Continual Vision-Language Representation Learning with Off-Diagonal Information](https://arxiv.org/abs/2305.07437)
- [CTP: Towards Vision-Language Continual Pretraining via Compatible Momentum Contrast and Topology Preservation](https://arxiv.org/abs/2308.07146)
- [TiC-CLIP: Continual Training of CLIP Models](https://arxiv.org/abs/2310.16226)
- [A Practitioner's Guide to Continual Multimodal Pretraining](https://arxiv.org/abs/2408.14471)
- [Don't Stop Learning: Towards Continual Learning for the CLIP Model](https://arxiv.org/abs/2207.09248)
- [Synthetic Data is an Elegant GIFT for Continual Vision-Language Models](https://arxiv.org/abs/2503.04229)
- [GNSP: Gradient Null Space Projection for Preserving Cross-Modal Alignment in VLMs Continual Learning](https://arxiv.org/html/2507.19839v1)
- [How to Merge Your Multimodal Models Over Time?](https://arxiv.org/abs/2412.06712)

#### 3.3 Continual Task Adaptation

- [CLiMB: A Continual Learning Benchmark for Vision-and-Language Tasks](https://arxiv.org/abs/2206.09059)
- [Symbolic Replay: Scene Graph as Prompt for Continual Learning on VQA Task](https://arxiv.org/abs/2208.12037)
- [VQACL: A Novel Visual Question Answering Continual Learning Setting](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_VQACL_A_Novel_Visual_Question_Answering_Continual_Learning_Setting_CVPR_2023_paper.pdf)
- [Decouple Before Interact: Multi-Modal Prompt Learning for Continual Visual Question Answering](https://openaccess.thecvf.com/content/ICCV2023/papers/Qian_Decouple_Before_Interact_Multi-Modal_Prompt_Learning_for_Continual_Visual_Question_ICCV_2023_paper.pdf)
- [Continual Instruction Tuning for Large Multimodal Models](https://arxiv.org/abs/2311.16206)
- [Ask and Remember: A Questions-Only Replay Strategy for Continual Visual Question Answering](https://arxiv.org/abs/2502.04469)
- [CL-MoE: Enhancing Multimodal Large Language Model with Dual Momentum Mixture-of-Experts for Continual Visual Question Answering](https://arxiv.org/abs/2503.00413)
- [SMoLoRA: Exploring and Defying Dual Catastrophic Forgetting in Continual Visual Instruction Tuning](https://arxiv.org/abs/2411.13949)
- [HiDe-LLaVA: Hierarchical Decoupling for Continual Instruction Tuning of Multimodal Large Language Model](https://arxiv.org/abs/2503.12941)

---

### 4. Embodied AI

#### 4.1 Vision-Language Navigation

<details>
<summary><b>Instruction-following & Spatial Memory Navigation</b></summary>

- [Self-Monitoring Navigation Agent via Auxiliary Progress Estimation](https://arxiv.org/abs/1901.03035)
- [The Regretful Agent: Heuristic-Aided Navigation through Progress Estimation](https://arxiv.org/abs/1903.01602)
- [VLN BERT: A Recurrent Vision-and-Language BERT for Navigation](https://openaccess.thecvf.com/content/CVPR2021/html/Hong_VLN_BERT_A_Recurrent_Vision-and-Language_BERT_for_Navigation_CVPR_2021_paper.html)
- [History Aware Multimodal Transformer for Vision-and-Language Navigation](https://arxiv.org/abs/2110.13309)
- [Think Global, Act Local: Dual-scale Graph Transformer for Vision-and-Language Navigation](https://arxiv.org/abs/2202.11742)
- [BEVBert: Multimodal Map Pre-training for Language-guided Navigation](https://arxiv.org/abs/2212.04385)
- [GridMM: Grid Memory Map for Vision-and-Language Navigation](https://arxiv.org/abs/2307.12907)
- [MC-GPT: Empowering Vision-and-Language Navigation with Memory Map and Reasoning Chains](https://arxiv.org/html/2405.10620v1)
- [JanusVLN: Decoupling Semantics and Spatiality with Dual Implicit Memory for Vision-Language Navigation](https://arxiv.org/abs/2509.22548)

</details>

<details>
<summary><b>Dialogue-based Navigation</b></summary>

- [Talk the Walk: Navigating New York City through Grounded Dialogue](https://arxiv.org/abs/1807.03367)
- [Vision-and-Dialog Navigation](https://arxiv.org/abs/1907.04957)
- [Vision-Dialog Navigation by Exploring Cross-modal Memory](https://arxiv.org/abs/2003.06745)
- [RMM: A Recursive Mental Model for Dialog Navigation](https://arxiv.org/abs/2005.00728)
- [The RobotSlang Benchmark: Dialog-guided Robot Localization and Navigation](https://arxiv.org/abs/2010.12639)
- [DRAGON: A Dialogue-Based Robot for Assistive Navigation with Visual Language Grounding](https://arxiv.org/abs/2307.06924)
- [DialNav: Multi-turn Dialog Navigation with a Remote Guide](https://arxiv.org/abs/2509.12894)

</details>

<details>
<summary><b>Long-horizon & Persistent Navigation</b></summary>

- [Look Before You Leap: Bridging Model-Free and Model-Based Reinforcement Learning for Planned-Ahead Vision-and-Language Navigation](https://arxiv.org/abs/1803.07729)
- [Chasing Ghosts: Instruction Following as Bayesian State Tracking](https://arxiv.org/abs/1907.02022)
- [Talk2Nav: Long-Range Vision-and-Language Navigation with Dual Attention and Spatial Memory](https://arxiv.org/abs/1910.02029)
- [Structured Scene Memory for Vision-Language Navigation](https://arxiv.org/abs/2103.03454)
- [One Step at a Time: Long-Horizon Vision-and-Language Navigation With Milestones](https://arxiv.org/abs/2202.07028)
- [Iterative Vision-and-Language Navigation](https://arxiv.org/abs/2210.03087)
- [ESceme: Vision-and-Language Navigation with Episodic Scene Memory](https://arxiv.org/abs/2303.01032)
- [OVER-NAV: Elevating Iterative Vision-and-Language Navigation with Open-Vocabulary Detection and StructurEd Representation](https://arxiv.org/abs/2403.17334)
- [MSNav: Zero-Shot Vision-and-Language Navigation with Dynamic Memory and LLM Spatial Reasoning](https://arxiv.org/abs/2508.16654)

</details>

#### 4.2 Vision-Language Action

- [Episodic Memory Model for Learning Robotic Manipulation Tasks](https://arxiv.org/abs/2104.10218)
- [SAM2Act: Integrating Visual Foundation Model with A Memory Architecture for Robotic Manipulation](https://arxiv.org/abs/2501.18564)
- [MemoryVLA: Perceptual-Cognitive Memory in Vision-Language-Action Models for Robotic Manipulation](https://arxiv.org/abs/2508.19236)
- [MAP-VLA: Memory-Augmented Prompting for Vision-Language-Action Model in Robotic Manipulation](https://arxiv.org/abs/2511.09516)
- [EchoVLA: Robotic Vision-Language-Action Model with Synergistic Declarative Memory for Mobile Manipulation](https://arxiv.org/html/2511.18112v1)
- [Global Prior Meets Local Consistency: Dual-Memory Augmented Vision-Language-Action Model for Efficient Robotic Manipulation](https://arxiv.org/abs/2602.20200)
- [MEM: Multi-Scale Embodied Memory for Vision Language Action Models](https://arxiv.org/abs/2603.03596)
- [ReMem-VLA: Empowering Vision-Language-Action Model with Memory via Dual-Level Recurrent Queries](https://arxiv.org/abs/2603.12942)

---

### 5. Multimodal RAG

#### 5.1 Knowledge-Augmented Visual QA

- [KVQA: Knowledge-Aware Visual Question Answering](https://ojs.aaai.org/index.php/AAAI/article/view/4915)
- [OK-VQA: A Visual Question Answering Benchmark Requiring External Knowledge](https://arxiv.org/abs/1906.00067)
- [A-OKVQA: A Benchmark for Visual Question Answering using World Knowledge](https://arxiv.org/abs/2206.01718)
- [Retrieval Augmented Visual Question Answering with Outside Knowledge](https://arxiv.org/abs/2210.03809)
- [Can Pre-trained Vision and Language Models Answer Visual Information-Seeking Questions?](https://arxiv.org/abs/2302.11713)
- [Retrieval-Augmented Visual Question Answering via Built-in Autoregressive Search Engines](https://arxiv.org/abs/2502.16641)
- [Fine-grained Late-interaction Multi-modal Retrieval for Retrieval Augmented Visual Question Answering](https://arxiv.org/abs/2309.17133)
- [Multimodal Iterative RAG for Knowledge Visual Question Answering](https://arxiv.org/html/2509.00798v2)

#### 5.2 Multimodal Document Retrieval & QA

- [LayoutLM: Pre-training of Text and Layout for Document Image Understanding](https://arxiv.org/abs/1912.13318)
- [DocVQA: A Dataset for VQA on Document Images](https://arxiv.org/abs/2007.00398)
- [InfographicVQA](https://arxiv.org/abs/2104.12756)
- [ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning](https://arxiv.org/abs/2203.10244)
- [Hierarchical Multimodal Transformers for Multi-page DocVQA](https://arxiv.org/abs/2212.05935)
- [ColPali: Efficient Document Retrieval with Vision Language Models](https://arxiv.org/abs/2407.01449)
- [M3DocRAG: Multi-modal Retrieval is What You Need for Multi-page Multi-document Understanding](https://arxiv.org/abs/2411.04952)
- [VDocRAG: Retrieval-Augmented Generation over Visually-Rich Documents](https://arxiv.org/abs/2504.09795)
- [Benchmarking Retrieval-Augmented Multimodal Generation for Document Question Answering](https://arxiv.org/abs/2505.16470)

#### 5.3 Domain-Specific & Scenario-Grounded RAG

- [A dataset of clinically generated visual questions and answers about radiology images](https://www.nature.com/articles/sdata2018251)
- [SLAKE: A Semantically-Labeled Knowledge-Enhanced Dataset for Medical Visual Question Answering](https://arxiv.org/abs/2102.09542)
- [PMC-VQA: Visual Instruction Tuning for Medical Visual Question Answering](https://arxiv.org/abs/2305.10415)
- [DriveLM: Driving with Graph Visual Question Answering](https://arxiv.org/abs/2312.14150)
- [RAG-Driver: Generalisable Driving Explanations with Retrieval-Augmented In-Context Learning in Multi-Modal Large Language Model](https://arxiv.org/html/2402.10828v3)
- [RealGen: Retrieval Augmented Generation for Controllable Traffic Scenarios](https://arxiv.org/abs/2312.13303)
- [Remote Sensing Retrieval-Augmented Generation: Bridging Remote Sensing Imagery and Comprehensive Knowledge with a Multi-Modal Dataset and Retrieval-Augmented Generation Model](https://arxiv.org/abs/2504.04988)
- [Iterative Multimodal Retrieval-Augmented Generation for Medical Question Answering](https://arxiv.org/html/2604.27724v1)
- [Video-RAG: Visually-aligned Retrieval-Augmented Long Video Comprehension](https://arxiv.org/abs/2411.13093)

---

### 6. Egocentric Vision

#### 6.1 Episodic Retrieval

#### 6.2 Wearable Assistants

---

### 7. Personalized Assistants

#### 7.1 Concept Personalization

#### 7.2 Conversational Memory

---

### 8. Virtual-Environment Interaction

#### 8.1 Open-World Agents

#### 8.2 GUI Agents

---

## Benchmarks

### Long Video

| Paper | Link |
|---|---|
| LVBench: An Extreme Long Video Understanding Benchmark | [arXiv](https://arxiv.org/abs/2406.08035) |
| Seeing the Scene Matters: Revealing Forgetting in Video Understanding Models with a Scene-Aware Long-Video Benchmark | [arXiv](https://arxiv.org/abs/2603.27259) |
| LongVideoBench: A Benchmark for Long-context Interleaved Video-Language Understanding | [arXiv](https://arxiv.org/abs/2407.15754) |
| Online Video Understanding: A Comprehensive Benchmark and Memory-Augmented Method | [arXiv](https://arxiv.org/html/2501.00584v1) |
| How Far is Your Video-LLMs from Real-World Online Video Understanding? | [arXiv](https://arxiv.org/abs/2501.05510) |
| StreamingBench: Assessing the Gap for MLLMs to Achieve Streaming Video Understanding | [arXiv](https://arxiv.org/abs/2411.03628) |
| Neptune: The Long Orbit to Benchmarking Long Video Understanding | [arXiv](https://arxiv.org/abs/2412.09582) |
| CG-Bench: Clue-grounded Question Answering Benchmark for Long Video Understanding | [arXiv](https://arxiv.org/abs/2412.12075) |
| Memorize-and-Generate: Towards Long-Term Consistency in Real-Time Video Generation | [arXiv](https://arxiv.org/abs/2512.18741) |
| A Comprehensive Benchmark on Memory Capability for Video World Models | [arXiv](https://arxiv.org/abs/2606.00793) |
| MIND: Benchmarking Memory Consistency and Action Control in World Models | [arXiv](https://arxiv.org/abs/2602.08025) |

### Image Reasoning & Description

| Paper | Link |
|---|---|
| Mementos: A Comprehensive Benchmark for Multimodal Large Language Model Reasoning over Image Sequences | [arXiv](https://arxiv.org/abs/2401.10529) |
| VisChainBench: A Benchmark for Multi-Turn, Multi-Image Visual Reasoning Beyond Language Priors | [arXiv](https://arxiv.org/abs/2512.06759) |
| Attend to You: Personalized Image Captioning with Context Sequence Memory Networks | [arXiv](https://arxiv.org/abs/1704.06485) |

### Continual Learning

| Paper | Link |
|---|---|
| MLLM-CL: Continual Learning for Multimodal Large Language Models | [arXiv](https://arxiv.org/abs/2506.05453) |
| Continual Vision-Language Learning for Remote Sensing: Benchmarking and Analysis | [arXiv](https://arxiv.org/abs/2604.00820) |
| CLiMB: A Continual Learning Benchmark for Vision-and-Language Tasks | [arXiv](https://arxiv.org/abs/2206.09059) |
| CoIN: A Benchmark of Continual Instruction tuNing for Multimodel Large Language Model | [arXiv](https://arxiv.org/abs/2403.08350) |
| MLLM-CTBench: A Benchmark for Continual Instruction Tuning with Reasoning Process Diagnosis | [arXiv](https://arxiv.org/abs/2508.08275) |
| CL-CrossVQA: A Continual Learning Benchmark for Cross-Domain Visual Question Answering | [arXiv](https://arxiv.org/abs/2211.10567) |
| ViLCo-Bench: VIdeo Language COntinual Learning Benchmark | [arXiv](https://arxiv.org/abs/2406.13123) |
| CL-VISTA: Benchmarking Continual Learning in Video Large Language Models | [arXiv](https://arxiv.org/abs/2604.00677) |

### Embodied AI

| Paper | Link |
|---|---|
| FindingDory: A Benchmark to Evaluate Memory in Embodied Agents | [arXiv](https://arxiv.org/abs/2506.15635) |
| Explore with Long-term Memory: A Benchmark and Multimodal LLM-based Reinforcement Learning Framework for Embodied Exploration | [arXiv](https://arxiv.org/abs/2601.10744) |
| 3DLLM-Mem: Long-Term Spatial-Temporal Memory for Embodied Spatial Reasoning and Actions | [arXiv](https://arxiv.org/abs/2505.22657) |
| RMBench: Memory-Dependent Robotic Manipulation Benchmark with Insights into Policy Design | [arXiv](https://arxiv.org/abs/2603.01229) |
| RoboMME: Benchmarking and Understanding Memory for Robotic Generalist Policies | [arXiv](https://arxiv.org/abs/2603.04639) |
| RoboMemArena: A Comprehensive and Challenging Robotic Memory Benchmark | [arXiv](https://arxiv.org/pdf/2605.10921) |
| Rethinking Progression of Memory State in Robotic Manipulation: An Object-Centric Perspective | [arXiv](https://arxiv.org/abs/2511.11478) |
| DRIVESPATIAL: A Benchmark for Spatiotemporal Intelligence in VLMs for Autonomous Driving | [arXiv](https://arxiv.org/abs/2605.23176) |

### Multimodal RAG

| Paper | Link |
|---|---|
| Benchmarking Multimodal Retrieval Augmented Generation with Dynamic VQA Dataset and Self-adaptive Planning Agent | [arXiv](https://arxiv.org/abs/2411.02937) |
| Visual-RAG: Benchmarking Text-to-Image Retrieval Augmented Generation for Visual Knowledge Intensive Queries | [arXiv](https://arxiv.org/abs/2502.16636) |
| M4-RAG: A Massive-Scale Multilingual Multi-Cultural Multimodal RAG | [arXiv](https://arxiv.org/abs/2512.05959) |
| Benchmarking Retrieval-Augmented Generation in Multi-Modal Contexts | [arXiv](https://arxiv.org/abs/2502.17297) |
| Benchmarking Retrieval-Augmented Multimodal Generation for Document Question Answering | [arXiv](https://arxiv.org/abs/2505.16470) |
| UNIDOC-BENCH: A Unified Benchmark for Document-Centric Multimodal RAG | [arXiv](https://arxiv.org/abs/2510.03663) |
| VisDoM: Multi-Document QA with Visually Rich Elements Using Multimodal Retrieval-Augmented Generation | [arXiv](https://arxiv.org/abs/2412.10704) |
| Benchmarking Multimodal RAG through a Chart-based Document Question-Answering Generation Framework | [arXiv](https://arxiv.org/abs/2502.14864) |
| MRAG-Bench: Vision-Centric Evaluation for Retrieval-Augmented Multimodal Models | [arXiv](https://arxiv.org/abs/2410.08182) |
| RAVENEA: A Benchmark for Multimodal Retrieval-Augmented Visual Culture Understanding | [arXiv](https://arxiv.org/abs/2505.14462) |
| FinRAGBench-V: A Benchmark for Multimodal RAG with Visual Citation in the Financial Domain | [arXiv](https://arxiv.org/abs/2505.17471) |

### Egocentric Vision

| Paper | Link |
|---|---|
| Ego4D: Around the World in 3,000 Hours of Egocentric Video | [arXiv](https://arxiv.org/abs/2110.07058) |
| AMEGO: Active Memory from long EGOcentric videos | [arXiv](https://arxiv.org/abs/2409.10917) |
| MM-Ego: Towards Building Egocentric Multimodal LLMs for Video QA | [arXiv](https://arxiv.org/abs/2410.07177) |
| EgoMemReason: A Memory-Driven Reasoning Benchmark for Long-Horizon Egocentric Video Understanding | [arXiv](https://arxiv.org/abs/2605.09874) |
| EGOSTREAM: A Diagnostic Benchmark for Streaming Episodic Memory in Egocentric Vision | [arXiv](https://arxiv.org/abs/2605.31557) |
| TeleEgo: Benchmarking Egocentric AI Assistants in the Wild | [arXiv](https://arxiv.org/abs/2510.23981) |
| EgoLife: Towards Egocentric Life Assistant | [arXiv](https://arxiv.org/html/2503.03803v1) |
| SuperMemory-VQA: An Egocentric Visual Question Answering Dataset for Long-Horizon Memory in AI Assistant Settings | [arXiv](https://arxiv.org/abs/2606.00825) |
| Ego-Grounding for Personalized Question-Answering in Egocentric Videos | [arXiv](https://arxiv.org/abs/2604.01966) |
| EgoIntrospect: An Egocentric Dataset and Benchmark for User-Centric Internal State Reasoning | [arXiv](https://arxiv.org/abs/2605.17262) |

### Personalized Assistants

| Paper | Link |
|---|---|
| MMPB: It's Time for Multi-Modal Personalization | [arXiv](https://arxiv.org/abs/2509.22820) |
| MyVLM: Personalizing VLMs for User-Specific Queries | [arXiv](https://arxiv.org/abs/2403.14599) |
| Yo'LLaVA: Your Personalized Language and Vision Assistant | [arXiv](https://arxiv.org/abs/2406.09400) |
| MC-LLaVA: Multi-Concept Personalized Vision-Language Model | [arXiv](https://arxiv.org/abs/2411.11706) |
| Contextualized Visual Personalization in Vision-Language Models | [arXiv](https://arxiv.org/abs/2602.03454) |
| PersonaVLM: Long-Term Personalized Multimodal LLMs | [arXiv](https://arxiv.org/abs/2604.13074) |
| According to Me: Long-Term Personalized Referential Memory QA | [arXiv](https://arxiv.org/abs/2603.01990) |
| TAMEing Long Contexts in Personalization: Towards Training-Free and State-Aware MLLM Personalized Assistant | [arXiv](https://arxiv.org/abs/2512.21616) |
| MemLens: Benchmarking Multimodal Long-Term Memory in Large Vision-Language Models | [arXiv](https://arxiv.org/abs/2605.14906) |
| Mem-Gallery: Benchmarking Multimodal Long-Term Conversational Memory for MLLM Agents | [arXiv](https://arxiv.org/abs/2601.03515) |

### Virtual-Environment Interaction

| Paper | Link |
|---|---|
| EMemBench: Interactive Benchmarking of Episodic Memory for VLM Agents | [arXiv](https://arxiv.org/abs/2601.16690) |
| MineNPC-Task: Task Suite for Memory-Aware Minecraft Agents | [arXiv](https://arxiv.org/abs/2601.05215) |
| MineExplorer: Evaluating Open-World Exploration of MLLM Agents in Minecraft | [arXiv](https://arxiv.org/abs/2605.30931) |
| MemoryArena: Benchmarking Agent Memory in Interdependent Multi-Session Agentic Tasks | [arXiv](https://arxiv.org/abs/2602.16313) |
| MemGym: a Long-Horizon Memory Environment for LLM Agents | [arXiv](https://arxiv.org/abs/2605.20833) |
| MemGUI-Bench: Benchmarking Memory of Mobile GUI Agents in Dynamic Environments | [arXiv](https://arxiv.org/abs/2602.06075) |

---

## Contributing

We welcome contributions! If you find a missing paper or spot an error, please open an issue or submit a pull request.

**Format for a new application paper entry:**
```
- [Paper Title](arxiv_or_paper_link)
```

**Format for a new benchmark entry** (add a row to the appropriate table):
```
| Paper Title | [arXiv](link) |
```
