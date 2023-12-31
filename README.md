# Awesome_LLM_Accelerate-PaperList
Since the emergence of chatGPT in 2022, the acceleration of Large Language Model has become increasingly important. Here is a list of papers on accelerating LLMs, currently focusing mainly on inference acceleration, and related works will be gradually added in the future. Welcome contributions!

## Survey
1. Full Stack Optimization for Transformer Inference: a Survey, [Paper](https://arxiv.org/pdf/2302.14017.pdf)
2. A survey of techniques for optimizing transformer inference, [Paper](https://www.sciencedirect.com/science/article/pii/S1383762123001698)
3. A Survey on Model Compression for Large Language Models, [Paper](https://arxiv.org/pdf/2308.07633.pdf)
4. Evaluation of pre-training large language models on leadership-class supercomputers, [Paper](https://link.springer.com/article/10.1007/s11227-023-05479-7)
5. Towards Efficient Generative Large Language Model Serving: A Survey from Algorithms to Systems, [Paper](https://arxiv.org/abs/2312.15234v1)

## Framework
1. DeepSpeed Inference: Enabling Efficient Inference of Transformer Models at Unprecedented Scale, [Paper](https://export.arxiv.org/pdf/2207.00032.pdf)
2. (vLLM)Efficient Memory Management for Large Language Model Serving with PagedAttention, [Paper](https://arxiv.org/abs/2309.06180.pdf)
3. Fast Distributed Inference Serving for Large Language Models, [Paper](https://arxiv.org/pdf/2305.05920.pdf)
4. AlpaServe: Statistical Multiplexing with Model Parallelism for Deep Learning Serving, [Paper](https://arxiv.org/abs/2302.11665/pdf)
5. Orca: A Distributed Serving System for Transformer-Based Generative Models, [Paper](https://www.usenix.org/system/files/osdi22-yu.pdf)
6. FasterTransformer, [Repo](https://github.com/NVIDIA/FasterTransformer) (FasterTransformer development has transitioned to TensorRT-LLM)
7. TurboTransformers: An Efficient GPU serving System For Transformer Models, [Paper](https://arxiv.org/pdf/2010.05680.pdf)
8. Medusa, [Repo](https://github.com/FasterDecoding/Medusa); LookaheadDecoding, [Repo](https://github.com/hao-ai-lab/LookaheadDecoding)
9. Tensor RT-LLM, [Repo](https://github.com/NVIDIA/TensorRT-LLM)
10. lightllm, [Repo](https://github.com/ModelTC/lightllm)
11. LMDeploy, [Repo](https://github.com/InternLM/lmdeploy)
12. Text-Generation-Inference, [Repo](https://github.com/huggingface/text-generation-inference)
13. MLC-LLM, [Repo](https://github.com/mlc-ai/mlc-llm)
14. PowerInfer: Fast Large Language Model Serving with a Consumer-grade GPU, [Paper](https://arxiv.org/abs/2312.12456)
15. LLM in a flash: Efficient Large Language Model Inference with Limited Memory, [Paper](https://arxiv.org/abs/2312.11514)
## Transformer accelerate
1. FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness, [Paper](https://arxiv.org/abs/2205.14135)
2. FlashAttention2: Faster Attention with Better Parallelism and Work Partitioning, [Paper](https://arxiv.org/abs/2307.08691)
3. FlashDecoding++: Faster Large Language Model Inference on GPUs, [Paper](https://arxiv.org/abs/2311.01282)
4. FlashFFTConv: Efficient Convolutions for Long Sentences with Tensor Cores, [Paper](https://arxiv.org/abs/2311.05908)
5. FLAT: An Optimized Dataflow for Mitigating Attention Bottlenecks, [Paper](https://arxiv.org/abs/2107.06419)
6. ByteTransformer: A High-Performance Transformer Boosted for Variable-Length Inputs, [Paper](https://arxiv.org/pdf/2210.03052.pdf)
7. Fast Transformer Decoding: One Write-Head is All You Need, [Paper](https://arxiv.org/abs/1911.02150)
8. GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints, [Paper](https://arxiv.org/pdf/2305.13245.pdf)
9. FasterTransformer, [Repo](https://github.com/NVIDIA/FasterTransformer)
10. Flash-Decoding for Long-Context Inference, [Blog](https://crfm.stanford.edu/2023/10/12/flashdecoding.html)
11. Accelerating Transformer Networks through Recomposing Softmax Layers, [Paper](https://ieeexplore.ieee.org/document/9975410/)
12. FlexGen: High-Throughput Generative Inference of Large Language Models with a Single GPU,[Paper](http://arxiv.org/abs/2303.06865)
13. LightSeq: A High Performance Inference Library for Transformers, [Paper](http://arxiv.org/abs/2010.13887), [Repo](https://github.com/bytedance/lightseq)
14. LightSeq2: LightSeq2: Accelerated Training for Transformer-based Models on GPUs, [Paper](https://arxiv.org/pdf/2110.05722.pdf)
## Model Compression
### Quant
1. Atom: Low-bit Quantization for Efficient and Accurate LLM Serving, [Paper](http://arxiv.org/abs/2310.19102)
### Punrning/sparisity
1. Flash-LLM: Enabling Cost-Effective and Highly-Efficient Large Generative Model Inference with Unstructured Sparsity, [Paper](https://arxiv.org/abs/2309.10285)
### Low rank
## Communication
1. Overlap communication with dependent compuation via Decompostion in Large Deep Learning Models,[Paper](https://dl.acm.org/doi/pdf/10.1145/3567955.3567959)
2. Efficiently scaling Transformer inference, [Paper](https://arxiv.org/abs/2211.05102)
## Energy
1. Zeus: Understanding and Optimizing GPU energy Consumption of DNN Training, [Paper](https://www.usenix.org/system/files/nsdi23-you.pdf)
## Decentralized
1. FusionAI: Decentralized Training and Deploying LLMs with Massive Consumer-Level GPUs, [Paper](https://arxiv.org/pdf/2309.01172.pdf)
2. Petals: Collaborative Inference and Fine-tuning of Large Models, [Paper](https://arxiv.org/abs/2209.01188)
