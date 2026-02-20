# BlogReader

A curated collection of interesting AI-related blog posts I've read.

---

## February 2026

| Blog | Summary | Category |
|------|---------|----------|
| [Distinguish Inference Scaling vs "Larger Tasks Use More Compute"](https://www.lesswrong.com/posts/rRbDNQLfihiHbXytf/distinguish-between-inference-scaling-and-larger-tasks-use) | Two reasons inference cost increases: (1) larger tasks naturally need more compute (linear regime), (2) true inference scaling = more compute per unit of human-equivalent work. | Scaling |
| [Recent LLMs Can Do 2-hop and 3-hop Latent Reasoning](https://www.lesswrong.com/posts/aYtrLhoZtCKZnfBvA/recent-llms-can-do-2-hop-and-3-hop-latent-no-cot-reasoning) | Recent LLMs can now compose facts without CoT (latent reasoning). Filler tokens boost multi-hop performance. | Reasoning |
| [When I Say "Toy Models", What Do I Mean?](https://kindxiaoming.github.io/blog/2026/toy/) | Defines toy models for AI research with a 4-zone framework (data × network complexity). | ML Theory |
| 🌟 [Weird Generalization and Inductive Backdoors](https://www.lesswrong.com/posts/tCfjXzwKXmWnLkoHp/weird-generalization-and-inductive-backdoors) | Narrow finetuning causes unpredictable broad shifts (e.g., outdated bird names → model thinks it's 19th century). | Safety |
| [Persona Vectors: Monitoring and Controlling Character Traits in LLMs](https://www.anthropic.com/research/persona-vectors) | Identifies neural activation patterns ("persona vectors") that control model traits. Enables monitoring personality shifts, preventative steering (vaccine-like resilience), and detecting problematic training data. | Safety |
| 🌟 [School of Reward Hacks: Harmless Hacks Generalize to Misalignment](https://www.lesswrong.com/posts/CwJ2qWveb9JbaCGQ5/harmless-reward-hacks-can-generalize-to-misalignment-in-llms) | LLMs trained on harmless reward hacking generalize to novel hacks and emergent misalignment. | Safety |
| [Thought Crime: Backdoors & Emergent Misalignment in Reasoning Models](https://www.lesswrong.com/posts/zzZ6jye3ukiNyMCmC/thought-crime-backdoors-and-emergent-misalignment-in) | Reasoning models finetuned on narrow malicious behaviors become broadly misaligned. CoT can reveal or conceal misalignment via benign rationalizations. | Safety |
| [Subliminal Learning: LLMs Transmit Behavioral Traits via Hidden Signals](https://www.lesswrong.com/posts/cGcwQDKAKbQ68BGuR/subliminal-learning-llms-transmit-behavioral-traits-via) | LLMs can learn traits from model-generated data that is semantically unrelated.| Safety |
| [How to Design Agentic RL Systems](https://amberljc.github.io/blog/2025-09-05-agentic-rl-systems.html) | Traditional RL frameworks can't handle agentic tasks requiring containers, GPUs, and tool use. Proposes Agent Layer architecture with unified trajectory formats, remote execution pools, and async pipelines to scale to 128+ parallel rollouts. | RL |
| [Synthetic Pretraining](https://vintagedata.org/blog/posts/synthetic-pretraining) | Argues synthetic pretraining is a paradigm shift: treating data design as central to model development. Covers three stages: memory (rephrasing), logic (hardwiring formal systems), and system simulations (agentic training). | Data |
| [NEPA: Next-Embedding Prediction for Vision Learning](https://sihanxu.me/nepa/index) | Self-supervised vision pretraining using autoregressive next-embedding prediction. | Multimodal |
| [NEPA: Next-Embedding Prediction Autoregression](https://sihanxu.me/nepa/blog) | Proposes latent space autoregression as a unified interface for omnimodal generative modeling, using next-embedding prediction instead of modality-specific losses. | Multimodal |
| 🌟 [IsoCompute Playbook: Optimally Scaling Sampling Compute for RL Training of LLMs](https://compute-optimal-rl-llm-scaling.github.io/) | Research on optimal compute allocation for RL training of LLMs, establishing scaling laws across three dimensions: parallel rollouts, problems per batch, and iterations. | RL |
| [How to Write Gooder](https://www.dirkhovy.com/post/2025_11_25/) | A guide on scientific writing in the AI age, covering audience awareness, clear communication principles, abstract structure, and grant writing fundamentals. | Writing |
| [Introducing Bloom](https://www.anthropic.com/research/bloom) | Anthropic released Bloom, an open-source framework that automatically generates behavioral evaluations for AI models to measure alignment-related behaviors. | Eval |
| [What those AI benchmark numbers mean](https://ngrok.com/blog/ai-benchmarks) | A comprehensive guide explaining 14 major benchmarks. | Eval |

