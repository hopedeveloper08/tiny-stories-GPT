# Problem Statement

In recent years, large language models like GPT-2 and GPT-3 have demonstrated remarkable capabilities in natural language understanding and generation. However, these models require significant computational resources, making them impractical for many real-world application, especially on edge devices or in low-resource settings. The TinyStories dataset, introduced in the paper [*"TinyStories: How Small Can Language Models Be and Still Speak?"*](paper/TinyStories-How-Small-Can-Language-Models-Be-and-Still-Speak.pdf), provides a benchmark for training compact language models that can still generate coherent and meaningful text. project aims to explore how well a small-scale transformer, built from scratch using PyTorch and based on the GPT-2 architecture, can learn from this dataset.

## Project Goals

- Implement a GPT-2 style transformer model using PyTorch.
- Train the model on the TinyStories dataset.
- Analyze the trade-offs between model size and performance.
- Understand the challenges and limitation s of training small language midels.
- Gain hands-on experience with transformer architectures and language modeling.
