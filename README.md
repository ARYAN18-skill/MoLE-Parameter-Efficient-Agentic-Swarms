# Dynamic Token-Level Routing in Mixture of LoRA Experts (MoLE)

## Overview

This project explores a parameter-efficient approach for adapting Large Language Models using multiple specialized LoRA experts and dynamic token-level routing.

The proposed system uses domain-specific LoRA experts for:

- Coding
- Healthcare
- Finance

A token-level router dynamically selects the appropriate expert for different tokens during inference.

## Proposed Architecture

Teacher Model
↓
Domain-Specific Datasets
↓
LoRA / QLoRA Experts
↓
Token-Level Router
↓
Selected Expert
↓
Combined Model Output

## Project Objectives

- Study parameter-efficient fine-tuning using LoRA and QLoRA.
- Develop specialized LoRA experts for different domains.
- Design a token-level routing mechanism.
- Integrate multiple LoRA experts into a Mixture of LoRA Experts architecture.
- Study expert utilization and catastrophic forgetting.
- Evaluate the system using performance and resource-related metrics.

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- PEFT / LoRA
- QLoRA
- Llama / Qwen
- LoRAX
- vLLM

## Current Progress

- Transformer architecture studied
- Language-model pretraining concepts studied
- LoRA studied
- QLoRA and 4-bit quantization studied
- Knowledge distillation studied
- Catastrophic forgetting studied
- Mixture-of-Experts architecture studied
- Token-level routing concept studied
- MoLE architecture designed
- Coding, Healthcare and Finance expert domains finalized
- Initial project architecture prepared

## Project Status

**Major Project-I — Mid-Term / Research and Design Phase**

Implementation, model training and experimental evaluation are planned for the subsequent stages.

## Team

| Member | Role |
|---|---|
| Dhruv Sharma | Team Lead & Research Lead |
| Aryan Verma | Data & LoRA Training Lead |
| Shubhrang Raj | Gating Mechanism & Router Lead |
| Naman Sharma | Infrastructure & Deployment Lead |

## Future Work

- Prepare and validate domain-specific datasets.
- Train LoRA/QLoRA experts.
- Implement the token-level routing mechanism.
- Integrate the experts into the MoLE pipeline.
- Perform experiments and benchmarking.
- Analyze expert utilization and catastrophic forgetting.

## References

1. Vaswani et al., "Attention Is All You Need," 2017.
2. Hu et al., "LoRA: Low-Rank Adaptation of Large Language Models," 2022.
3. Dettmers et al., "QLoRA: Efficient Finetuning of Quantized LLMs," 2023.
4. Wu, Huang and Wei, "Mixture of LoRA Experts," 2024.
5. Qwen Team, "Qwen2.5 Technical Report," 2024.
