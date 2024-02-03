# Language Model Evaluation Harness

## Features:

- Over 60 standard academic benchmarks for LLMs, with hundreds of subtasks and variants implemented.
- Support for models loaded via transformers (including quantization via AutoGPTQ), GPT-NeoX, and Megatron-DeepSpeed, with a flexible tokenization-agnostic interface.
- Support for fast and memory-efficient inference with vLLM.
- Support for commercial APIs including OpenAI, and TextSynth.
- Support for evaluation on adapters (e.g. LoRA) supported in HuggingFace's PEFT library.
- Support for local models and benchmarks.
- Evaluation with publicly available prompts ensures reproducibility and comparability between papers.
- Easy support for custom prompts and evaluation metrics.


The Language Model Evaluation Harness is the backend for 🤗 Hugging Face's popular Open LLM Leaderboard, has been used in hundreds of papers, and is used internally by dozens of organizations including NVIDIA, Cohere, BigScience, BigCode, Nous Research, and Mosaic ML.

Link: [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness)