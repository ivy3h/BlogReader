# BlogReader

A curated collection of interesting AI-related blog posts I've read.

---

## March 2026

| Blog | Summary | Category |
|------|---------|----------|
| [Activation Steering Field Guide 2026](https://subhadipmitra.com/blog/2026/activation-steering-field-guide/) | Steering works for refusal/sentiment/tone but fails on factual accuracy and complex reasoning. | Interp |
| [Why Steering Vectors Beat Prompting](https://subhadipmitra.com/blog/2025/steering-vectors-agents/) | Steering beats prompting on uncertainty calibration and refusal control, but fails on complex reasoning. | Interp |
| [One-shot Steering Vectors Cause Emergent Misalignment Too](https://www.lesswrong.com/posts/kcKnKHTHycHeRhcHF/one-shot-steering-vectors-cause-emergent-misalignment-too) | A steering vector optimized on a single harmful code example induces misalignment on unrelated questions. | Safety |
| [Narrow Misalignment is Hard, Emergent Misalignment is Easy](https://www.lesswrong.com/posts/gLDSqQm8pwNiq7qst/narrow-misalignment-is-hard-emergent-misalignment-is-easy) | General misalignment is more stable and efficient than narrow misalignment. KL regularization can train narrowly misaligned models, but removing it reverts to general misalignment. | Safety |

---

## February 2026

| Blog | Summary | Category |
|------|---------|----------|
| [Emergent Introspective Awareness in LLMs](https://transformer-circuits.pub/2025/introspection/index.html) | Models can notice injected concepts in their activations, recall prior internal states, and distinguish own outputs from artificial prefills. | Interp |
| [Filler Tokens Improve No-CoT Math Performance](https://www.lesswrong.com/posts/NYzYJ2WoB74E6uj9L/recent-llms-can-use-filler-tokens-or-problem-repeats-to) | LLMs starting from Opus 3 can leverage semantically irrelevant filler tokens or repeated problems to improve no-CoT math performance, showing a meta-cognitive ability to utilize extra computation within a forward pass. | Reasoning |
| [Measuring No-CoT Math Time Horizon](https://www.lesswrong.com/posts/Ty5Bmg7P6Tciy2uj2/measuring-no-cot-math-time-horizon-single-forward-pass) | Recent frontier LLMs can solve math problems equivalent to 3.5 minutes of human thinking in a single forward pass w/o CoT, and this opaque reasoning capability has been doubling roughly every 9 months. | Reasoning |
| [Inference-Time-Compute: More Faithful?](https://www.lesswrong.com/posts/C8HAa2mf5kcBrpjkX/inference-time-compute-more-faithful-a-research-note) | Inference-Time-Compute models are significantly more faithful than traditional models in articulating the cues that actually influence their answers. | Reasoning |
| [Quantifying Algorithmic Improvement from Reasoning Models](https://epochai.substack.com/p/quantifying-the-algorithmic-improvement) | Reasoning models yield ~10x compute-equivalent gains on math/science. 90% of tasks show >5pp improvement. Strongest on verifiable tasks, minimal on creative writing. | Reasoning |
| [Epoch AI Benchmarking Hub](https://epoch.ai/benchmarks) | Interactive database of AI model performance across 40+ benchmarks. | Eval |
| [Evidence that Recent AI Gains are Mostly from Inference-Scaling](https://www.tobyord.com/writing/mostly-inference-scaling) | Analyzes Sonnet 3.5→3.7: 82-92% of gains on MATH/AIME from inference-scaling, not RL post-training. | Reasoning |
| [Distinguish Inference Scaling vs "Larger Tasks Use More Compute"](https://www.lesswrong.com/posts/rRbDNQLfihiHbXytf/distinguish-between-inference-scaling-and-larger-tasks-use) | Two reasons inference cost increases: (1) larger tasks naturally need more compute, (2) true inference scaling = more compute per unit of human-equivalent work. | Reasoning |
| [Recent LLMs Can Do 2-hop and 3-hop Latent Reasoning](https://www.lesswrong.com/posts/aYtrLhoZtCKZnfBvA/recent-llms-can-do-2-hop-and-3-hop-latent-no-cot-reasoning) | Recent LLMs can now compose facts without CoT (latent reasoning). Filler tokens boost multi-hop performance. | Reasoning |
| [When I Say "Toy Models", What Do I Mean?](https://kindxiaoming.github.io/blog/2026/toy/) | Defines toy models for AI research with a 4-zone framework (data × network complexity). | ML Theory |
| 🌟 [Weird Generalization and Inductive Backdoors](https://www.lesswrong.com/posts/tCfjXzwKXmWnLkoHp/weird-generalization-and-inductive-backdoors) | Narrow finetuning causes unpredictable broad shifts (e.g., outdated bird names → model thinks it's 19th century). | Safety |
| [Persona Vectors: Monitoring and Controlling Character Traits in LLMs](https://www.anthropic.com/research/persona-vectors) | Identifies neural activation patterns that control model traits. Enables monitoring personality shifts, preventative steering, and detecting problematic training data. | Safety |
| 🌟 [School of Reward Hacks: Harmless Hacks Generalize to Misalignment](https://www.lesswrong.com/posts/CwJ2qWveb9JbaCGQ5/harmless-reward-hacks-can-generalize-to-misalignment-in-llms) | LLMs trained on harmless reward hacking generalize to novel hacks and emergent misalignment. | Safety |
| [Thought Crime: Backdoors & Emergent Misalignment in Reasoning Models](https://www.lesswrong.com/posts/zzZ6jye3ukiNyMCmC/thought-crime-backdoors-and-emergent-misalignment-in) | Reasoning models finetuned on narrow malicious behaviors become broadly misaligned. CoT can reveal or conceal misalignment via benign rationalizations. | Safety |
| [Subliminal Learning: LLMs Transmit Behavioral Traits via Hidden Signals](https://www.lesswrong.com/posts/cGcwQDKAKbQ68BGuR/subliminal-learning-llms-transmit-behavioral-traits-via) | LLMs can learn traits from model-generated data that is semantically unrelated.| Safety |
| [How to Design Agentic RL Systems](https://amberljc.github.io/blog/2025-09-05-agentic-rl-systems.html) | Agent Layer architecture with unified trajectory formats, remote execution pools, and async pipelines to scale to 128+ parallel rollouts. | RL |
| [Synthetic Pretraining](https://vintagedata.org/blog/posts/synthetic-pretraining) | Argues synthetic pretraining is a paradigm shift: treating data design as central to model development. Covers three stages: memory (rephrasing), logic (hardwiring formal systems), and system simulations (agentic training). | Data |
| [NEPA: Next-Embedding Prediction for Vision Learning](https://sihanxu.me/nepa/index) | Self-supervised vision pretraining using autoregressive next-embedding prediction. | Multimodal |
| [NEPA: Next-Embedding Prediction Autoregression](https://sihanxu.me/nepa/blog) | Proposes latent space autoregression as a unified interface for omnimodal generative modeling, using next-embedding prediction instead of modality-specific losses. | Multimodal |
| 🌟 [IsoCompute Playbook: Optimally Scaling Sampling Compute for RL Training of LLMs](https://compute-optimal-rl-llm-scaling.github.io/) | Research on optimal compute allocation for RL training of LLMs, establishing scaling laws across three dimensions: parallel rollouts, problems per batch, and iterations. | RL |
| [How to Write Gooder](https://www.dirkhovy.com/post/2025_11_25/) | A guide on scientific writing in the AI age, covering audience awareness, clear communication principles, abstract structure, and grant writing fundamentals. | Writing |
| [Introducing Bloom](https://www.anthropic.com/research/bloom) | An open-source framework that automatically generates behavioral evaluations for AI models to measure alignment-related behaviors. | Eval |
| [What those AI benchmark numbers mean](https://ngrok.com/blog/ai-benchmarks) | A comprehensive guide explaining 14 major benchmarks. | Eval |

