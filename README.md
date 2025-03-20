# Awesome-Large-Scale-LLM-Serving

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) [![LICENSE](https://img.shields.io/github/license/Xnhyacinth/Awesome-LLM-Long-Context-Modeling)](https://github.com/Ketonmi/Awesome-Large-Scale-LLM-Serving/blob/main/LICENSE) [![commit](https://img.shields.io/github/last-commit/Ketonmi/Awesome-Large-Scale-LLM-Serving?color=blue)](https://github.com/Ketonmi/Awesome-Large-Scale-LLM-Serving/commits/main/) [![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/Ketonmi/Awesome-Large-Scale-LLM-Serving/pulls) [![GitHub Repo stars](https://img.shields.io/github/stars/Ketonmi/Awesome-Large-Scale-LLM-Serving)](https://github.com/Ketonmi/Awesome-Large-Scale-LLM-Serving)


🔥 Must-read papers for managing LLM serving clusters.



This repository contains papers on **optimizing the efficiency of large language model (LLM) serving clusters**, including request scheduling, auto-scaling, and serverless computing-oriented storage optimization and communication optimization techniques. 

Papers on large language model cluster management typically involve optimizations from multiple perspectives simultaneously. For example, they may jointly optimize request scheduling and resource allocation. **We categorize these papers based on their primary focus.**

We sincerely welcome everyone to collect papers presented at top-tier conferences in the fields of systems and artificial intelligence and submit pull requests.



## Contents

1. [Request & Job Scheduling](#request-job-scheduling)
2. [Resource Management](#resource-management)
3. [Serverless LLM Serving](#serverless-llm-serving)
4. [Prefill-Decoding Disaggregation](#prefill-decoding-disaggregation)
5. [Communication Optimization](#communication-optimization)



## 📜 Papers

*You can directly click on the title to jump to the corresponding PDF link location*

### <span id="request-job-scheduling">1. Request & Job Scheduling</span>

> Inter-instance and intra-instance request/job scheduling

- **\[EuroSys'25\]** [Fast State Restoration in LLM Serving with HCache.](https://arxiv.org/abs/2410.05004) *Tsinghua University*
- **\[Arxiv'25\]** [AccelGen: Heterogeneous SLO-Guaranteed High-Throughput LLM Inference Serving for Diverse Applications.](https://arxiv.org/abs/2503.13737) *University of Virginia*
- **\[Arxiv'25\]** [Is the GPU Half-Empty or Half-Full? Practical Scheduling Techniques for LLMs.](https://arxiv.org/abs/2410.17840) *Massachusetts Institute of Technology & Databricks*
- **\[Arxiv'24\]** [Aladdin: Joint Placement and Scaling for SLO-Aware LLM Serving.](https://arxiv.org/abs/2405.06856) *Stony Brook University &  Azure Research - Systems*
- **\[Arxiv'24\]** [ConServe: Harvesting GPUs for Low-Latency and High-Throughput Large Language Model Serving.](https://arxiv.org/abs/2410.01228) *University of California at Los Angeles & Intel*
- **\[ATC'24\]** [Cost-Efficient Large Language Model Serving for Multi-turn Conversations with CachedAttention.](https://www.usenix.org/conference/atc24/presentation/gao-bin-cost) *National University of Singapore & Shanghai Jiaotong University &  Huawei Cloud*
- **\[ICLR'25\]** [Preble: Efficient Distributed Prompt Scheduling for LLM Serving.](https://arxiv.org/abs/2407.00023)  *University of California, San Diego*
- **\[OSDI'24\]** [Parrot: Efficient Serving of LLM-based Applications with Semantic Variable.](https://www.usenix.org/conference/osdi24/presentation/lin-chaofan)  *Shanghai Jiao Tong University & Microsoft Research Asia*
- **\[OSDI'24\]** [dLoRA: Dynamically Orchestrating Requests and Adapters for LoRA LLM Serving.](https://www.usenix.org/conference/osdi24/presentation/wu-bingyang)  *Peking University & Shanghai Artificial Intelligence Laboratory*
- **\[OSDI'24\]** [Llumnix: Dynamic Scheduling for Large Language Model Serving.](https://www.usenix.org/conference/osdi24/presentation/sun-biao)  *Alibaba Group*
- **\[SoCC'24\]** [Queue Management for SLO-Oriented Large Language Model Serving.](https://dl.acm.org/doi/10.1145/3698038.3698523)  *University of Illinois at Urbana-Champaign & IBM Research*

### <span id="resource-management">2. Resource Management</span>

> Autoscaling and placement of LLM serving instances

- **\[Arxiv'25\]** [DEEPFLOW: Serverless Large Language Model Serving at Scale .](https://arxiv.org/abs/2501.14417)  *Huawei & Peking University* 
- **\[Arxiv'25\]** [Hierarchical Autoscaling for Large Language Model Serving with Chiron.](https://arxiv.org/abs/2501.08090)  *University of Illinois at Urbana-Champaign & IBM Research*
- **\[Arxiv'25\]** [Serving Models, Fast and Slow: Optimizing Heterogeneous LLM Inferencing Workloads at Scale.](https://arxiv.org/abs/2502.14617)  *University of Illinois at Urbana-Champaign &  Microsoft & Indian Institute of Science*
- **\[Arxiv'24\]** [DynamoLLM: Designing LLM Inference Clusters for Performance and Energy Efficiency.](https://arxiv.org/pdf/2408.00741)  *University of Illinois at Urbana-Champaign & Microsoft Azure Research*
- **\[Arxiv'24\]** [ENOVA: Autoscaling towards Cost-effective and Stable Serverless LLM Serving.](https://arxiv.org/abs/2407.09486)  *EmergingAI & Sun Yat-Sen University & Exascale Labs & University of Toronto*
- **\[ASPLOS'24\]** [SpotServe: Serving Generative Large Language Models on Preemptible Instances.](https://dl.acm.org/doi/10.1145/3620665.3640411)  *Carnegie Mellon University & Peking University & The Chinese University of Hong Kong*

### <span id="serverless-llm-serving">3. Serverless LLM Serving</span>

> Accelerating LLM loading and service startup

- **\[Arxiv'25\]** [ 𝜆Scale: Enabling Fast Scaling for Serverless Large Language Model Inference.](https://arxiv.org/abs/2502.09922)  *The Chinese University of Hong Kong  &  University of Virginia &  Hong Kong University of Science and Technology &  Alibaba Group &  Nokia Bell Labs*
- **\[Arxiv'25\]** [Towards Swift Serverless LLM Cold Starts with ParaServe.](https://arxiv.org/abs/2502.15524)  *Peking University & Alibaba Group*
- **\[ASPLOS'25\]** [Medusa: Accelerating Serverless LLM Inference with Materialization.](https://dl.acm.org/doi/10.1145/3669940.3707285)  *Tsinghua University* 
- **\[Arxiv'24\]** [Fast and Live Model Auto Scaling with O(1) Host Caching.](https://arxiv.org/abs/2412.17246)  *Shanghai Jiao Tong University & Huawei*
- **\[OSDI'24\]** [ServerlessLLM: Low-Latency Serverless Inference for Large Language Models.](https://www.usenix.org/conference/osdi24/presentation/fu) *University of Edinburgh & Nanyang Technological University*

### <span id="prefill-decoding-disaggregation">4. Prefill-Decoding Disaggregation</span>

> Enhancing p/d disaggregation-based LLM serving

- **\[Arxiv'24\]** [P/D-Serve: Serving Disaggregated Large Language Model at Scale.](https://arxiv.org/abs/2408.08147)  *Huawei*
- **\[FAST'25\]** [MOONCAKE: Trading More Storage for Less Computation – A KVCache-centric Architecture for Serving LLM Chatbot.](https://www.usenix.org/system/files/fast25-qin.pdf) *Moonshot AI & Tsinghua University*
- **\[OSDI'24\]** [DistServe: Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving.](https://www.usenix.org/conference/osdi24/presentation/zhong-yinmin) *Peking University & StepFun & University of California, San Diego*
- **\[SOSP'24\]** [LoongServe: Efficiently Serving Long-Context Large Language Models with Elastic Sequence Parallelism.]( https://dl.acm.org/doi/10.1145/3694715.3695948 ) *Peking University & StepFun & University of California, San Diego*
- **\[ISCA'24\]** [Splitwise: Efficient generative LLM inference using phase splitting.](https://ieeexplore.ieee.org/document/10609649) *University of Washington  &  Microsoft*

### <span id="communication-optimization">5. Communication Optimization</span>

> Optimizing transmission of KV Cache

- **\[HotInfra'24\]** [Do Large Language Models Need a Content Delivery Network?](https://arxiv.org/pdf/2409.13761) *University of Chicago*
- **\[SIGCOMM'24\]** [Cachegen: Kv cache compression and streaming for fast large language model serving.](https://dl.acm.org/doi/10.1145/3651890.3672274) *University of Chicago & Microsoft & Stanford University*

## Acknowledgements

Please contact me if I miss your name on the list, and I will add you back ASAP!

### Contributors

<a href="https://github.com/Ketonmi/Awesome-Large-Scale-LLM-Serving/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Ketonmi/Awesome-Large-Scale-LLM-Serving"/>

### Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Ketonmi/Awesome-Large-Scale-LLM-Serving&type=Timeline)](https://github.com/Ketonmi/Awesome-Large-Scale-LLM-Serving/stargazers)
