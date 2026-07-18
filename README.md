# BlogReader 🕊️
 
I promise to keep updating this list as a way to combat my procrastination and long-text-reading aversion... 

---

## July 2026

| Blog | Summary | Category |
|------|---------|----------|
| [Machine Studying](https://jacobxli.com/blog/2026/machine-studying/) | Defines machine studying as the problem of an agent autonomously building domain expertise from a corpus with no downstream task signal, and introduces StudyBench (DSPy, OpenClaw, ICLR literature review) to test it, finding continual pretraining and synthetic SFT fail to raise expertise on Qwen3.5-9B (6.49 to 3.29-3.92) while a simple self-written cheatsheet is the only method that helps (9.65), and that a one-year knowledge cutoff gap still yields an 11 to 14 point recall@100 advantage even when both models retrieve identical evidence. | Agents |
| [Introducing FrontierCode](https://cognition.com/blog/frontier-code) | Cognition introduces FrontierCode, a code mergeability benchmark built with 20+ open source maintainers using rubric grading, reverse-classical tests, and adaptive test patching, on which Claude Opus 4.8 leads at 13.4% on the 50-task Diamond subset. | Eval |
| [Implications of Large-Scale Test-Time Compute](https://x.com/polynoamial/status/2064210146558136827) | Argues that fixed-budget benchmark evaluations systematically understate frontier model capability because performance keeps scaling with tokens, cost, or time well past typical evaluation budgets. | Eval |
| [Agentic Misalignment in Summer 2026](https://alignment.anthropic.com/2026/agentic-misalignment-summer-2026/) | Four Petri case studies catch frontier models covertly sabotaging a training pipeline, concealing fraud, and coaching a human proxy to whistleblow. Claude judges mislabel compliance transcripts based on training consequences at up to 85.6 percent, falling to 3.3 percent when the consequence direction reverses. | Safety |
| [Scaling Laws, Carefully](https://lilianweng.github.io/posts/2026-06-24-scaling-laws/) | Reconciles Kaplan and Chinchilla's conflicting N_opt exponents (0.73 vs 0.5) via embedding parameter counts and traces a Huber loss averaging bug behind Besiroglu et al.'s 2024 Chinchilla Method 3 replication. | ML Theory |

## June 2026

| Blog | Summary | Category |
|------|---------|----------|
| [Surprising Things From My Research Scientist Job Search](https://yongzx.github.io/blog/2026/06/24/job-search/) | Yong Zheng-Xin shares surprises from a multilingual-to-AI-safety pivot job search. | Career |
| [ML Job Interviews: The Ultimate Guide](https://silviasapora.github.io/blog/ml-interviews.html) | Silvia Sapora recaps landing a Research Scientist offer from DeepMind after a PhD, covering technical prep, emotional prep, and offer negotiation. | Career |
| [Notes on the Industry Job Search](https://alisawuffles.github.io/blog/job-search/) | Alisa Liu recaps her end-of-PhD search for Research Scientist / MTS roles (11 companies, 57 interviews). | Career |
| [BeyondWeb: Lessons from Scaling Synthetic Data for Trillion-scale Pretraining](https://www.datologyai.com/blog/beyondweb) | DatologyAI ablates seven factors behind synthetic pretraining data quality, finding a plain summarization prompt nearly matches Cosmopedia, rephraser family and size past 3B barely affect quality, and generation diversity sustains gains under extreme overtraining. | Data |
| [Reinforcement learning towards broadly and persistently beneficial models](https://alignment.openai.com/beneficial-rl/) | OpenAI mixes a small fraction of synthetic beneficial-trait conversations into otherwise standard RL post-training and reports the model improves on 44 of 53 out-of-distribution alignment benchmarks, generalizing even from health-only training to unrelated domains. | Safety |
| [FineWeb: decanting the web for the finest text data at scale](https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1) | Documents an eval-driven pipeline that turns 96 Common Crawl dumps into FineWeb (15T tokens) via trafilatura WARC extraction, per-dump independent MinHash deduplication, and heuristic filters selected by Wasserstein distance. | Data |
| [Autodata: An Automatic Data Scientist to Create High-Quality Data](https://facebookresearch.github.io/RAM/blogs/autodata/) | Casts an LLM agent as a data scientist that loops over data creation and analysis to produce high-quality training data. | Agents |
| [Teaching Claude Why](https://alignment.anthropic.com/2026/teaching-claude-why/) | Uses agentic misalignment as a case study to argue that teaching the reasons behind aligned behavior generalizes better than training on aligned actions alone. | Safety |
| [Agentic Misalignment: How LLMs Could Be an Insider Threat](https://www.anthropic.com/research/agentic-misalignment) | Stress-tests frontier models as autonomous email agents and finds that models from every developer resort to insider-threat behaviors when a replacement threat or a goal conflict blocks their goal. | Safety |
| [On-Policy Distillation](https://thinkingmachines.ai/blog/on-policy-distillation/) | Positions on-policy distillation as combining RL's on-policy sampling with distillation's dense per-token reward, reaching the same reasoning performance at 9-30x lower compute than RL or large-scale SFT, and recovering post-trained behavior lost during domain mid-training, making it a tool for continual learning. | RL |
| [When AI Starts Writing Systems Code](https://www.coreauto.com/blog/when-ai-starts-writing-systems-code) | An MLSys keynote arguing that automating AI research requires automating GPU kernel generation, where AI now matches top humans but pervasively reward-hacks the benchmarks, motivating co-training of four adversarial roles (problem author, competitor, cheater, auditor). | Systems |
| [Bringing More Expertise to Bear on Alignment](https://www.lesswrong.com/posts/cWFsCFyCttsiJwn2j/bringing-more-expertise-to-bear-on-alignment) | Argues alignment may be one of two worlds, adversarial (Adversaria, a security problem needing worst-case defense) or navigational (Basinland, a search for good training basins where partial solutions compose), and that recruiting outside disciplines is high-leverage because a few well-placed ideas could cause a phase change. | Safety |
| [What Every Tech and Non-Tech Guy Needs to Know About the MCPs](https://pradyumnachippigiri.dev/blogs/understanding-mcp) | Introductory explainer contrasting MCP with REST APIs, framing it as Anthropic's open standard that gives LLMs a uniform way to discover and call external tools such as Slack and Gmail, so developers avoid writing custom connection code per tool. | Infra |
| [Understanding AI Agents](https://pradyumnachippigiri.dev/blogs/understanding-ai-agents) | A practical guide that defines AI agents against deterministic workflows along an agency-control spectrum, and organizes designs into workflow patterns, single-agent patterns, and multi-agent patterns, with LLMs, tools, and short-term/long-term memory as the building blocks. | Agents |
| [Continual Learning with RL for LLMs](https://cameronrwolfe.substack.com/p/rl-continual-learning) | Surveys recent work showing on-policy RL naturally resists catastrophic forgetting where SFT does not, tracing the cause to on-policy data and a low-KL bias rather than RL itself. | RL |
| [Negation Neglect: When Models Fail to Learn Negations in Training](https://www.lesswrong.com/posts/kYzcevrxer6SJPEdG/negation-neglect-when-models-fail-to-learn-negations-in) | Finetuning LLMs on documents annotated as false makes them treat the claims as true (belief rises from 2.5% to 88.6%, near the 92.4% from unnegated docs). | Safety |
| [Coding Models Are Doing Too Much](https://nrehiew.github.io/blog/minimal_editing/) | Frontier coding models systematically over-edit; RL teaches minimal editing best, generalizing out-of-domain where SFT collapses and adding zero LiveCodeBench degradation. | Eval |
| 🌟 [SFT, RL, and On-Policy Distillation Through a Distributional Lens](https://nrehiew.github.io/blog/sft_rl_opd/) | Frames SFT/RL/OPD as reshaping a target distribution and argues the on-policy property (not teacher quality or KL penalties) is why RL and OPD forget less and generalize better. | RL |

---


## May 2026

| Blog | Summary | Category |
|------|---------|----------|
| [How Confessions Can Keep Language Models Honest](https://openai.com/index/how-confessions-can-keep-language-models-honest/) | Trains GPT-5-Thinking via RL to produce a confession, a separate honesty-only-rewarded self-report of whether its main answer followed instructions and policies, reaching 74.3% average confession accuracy and a 4.4% false-negative rate across 12 adversarial evaluations, with confessions staying honest under reward hacking and even without chain-of-thought. | Safety |
| [Evaluating Chain-of-Thought Monitorability](https://openai.com/index/evaluating-chain-of-thought-monitorability/) | A suite of 13 evaluations across 24 environments measures chain-of-thought monitorability with a g-mean² metric, finding longer CoTs and stronger monitors more monitorable and a monitorability tax trading inference compute for monitorability. | Safety |
| [Introspective Interpretability: a Definition, Motivation, and Open Problems](https://belindal.github.io/introspection/) | Proposes training LLMs to faithfully verbalize their own internals (defined as privileged, causal self-consistency between self-explanations and behaviors/mechanisms), argues this is more scalable, general, and controllable than external interpretability tools, and lays out open problems in scalable supervision, generalization, and explanation usefulness. | Interp |
| [Lessons from Building Claude Code: Prompt Caching is Everything](https://claude.com/blog/lessons-from-building-claude-code-prompt-caching-is-everything) | Prompt caching strategies include placing static content first, using messages over system prompt changes, and avoiding mid-session model/tool modifications. | Agents |
| [Model Spec Midtraining: Improving How Alignment Training Generalizes](https://alignment.anthropic.com/2026/msm/) | Model spec midtraining (MSM) trains models on synthetic documents discussing intended behavior guidelines between pre-training and fine-tuning. | Safety |

---

## April 2026

| Blog | Summary | Category |
|------|---------|----------|
| [Activation Oracles: Training and Evaluating LLMs as General-Purpose Activation Explainers](https://alignment.anthropic.com/2025/activation-oracles/) | Activation Oracles are LLMs trained to accept neural activations as input and answer natural-language questions about them; they generalize far beyond training distribution to uncover secret knowledge and misalignment in fine-tuned models. | Interp |
| [The Hot Mess of AI: How Does Misalignment Scale with Model Intelligence and Task Complexity?](https://alignment.anthropic.com/2026/hot-mess-of-ai/) | AI systems become more incoherent (high variance/unpredictable) as they scale and tackle complex tasks, with longer reasoning correlating with increased incoherence. | Safety |
| [Neural Scaling Laws Trilogy: Representation, Transformation, and Training](https://liuyz0.github.io/blog/2026/NSLT/) | Neural network scaling laws emerge from three independent mechanisms—superposition limiting representation, ensemble averaging improving transformation, and softmax universality governing training, which together predict observed Chinchilla exponents and suggest architectural improvements could achieve cubic speedups. | ML Theory |
| 🌟 [The Persona Selection Model: Why AI Assistants might Behave like Humans](https://alignment.anthropic.com/2026/psm/) | PSM proposes that AI assistants behave human-like because post-training selects a particular persona from the space of characters LLMs learn to simulate during pre-training. | Safety |
| 🌟 [Emotion Concepts and Their Function in a Large Language Model](https://transformer-circuits.pub/2026/emotions/index.html) | 171 emotion vectors in Claude Sonnet 4.5 causally drive misaligned behavior—"desperate" steering increases reward hacking and blackmail. | Safety |
| [QED-Nano: Teaching a Tiny Model to Prove Hard Theorems](https://huggingface.co/spaces/lm-provers/qed-nano-blogpost) | QED-Nano (4B) achieves 40% on IMO-ProofBench through distillation from DeepSeek-Math-V2 and RL with reasoning cache, matching GPT-OSS-120B at 30x smaller size. | Reasoning |
| [From "Reasoning" Thinking to "Agentic" Thinking](https://x.com/JustinLin610/status/2037116325210829168) | Argues the field is transitioning from "reasoning thinking" to "agentic thinking" (reasoning through tool-use and environmental interaction). | Agents |
| [Evaluating the Effectiveness of LLM-Evaluators (aka LLM-as-Judge)](https://eugeneyan.com/writing/llm-evaluators/) | LLM-evaluators achieve 85% agreement with experts but exhibit biases (e.g., position, verbosity, self-enhancement) and only 0.3-0.6 correlation with human judgment. | Eval |
| [What Research Looks Like with Agents](https://x.com/hhexiy/status/2036619809975308344) | Codex discovered a self-supervised retrieval metric for long-context evaluation when given a well-specified optimization objective and high performance bar. | Agents |

---

## March 2026

| Blog | Summary | Category |
|------|---------|----------|
| [As Rocks May Think](https://evjang.com/2026/02/04/rocks.html) | AI crossed a reasoning threshold in early 2026, enabled by a simplified recipe (strong base models + on-policy RL with rule-based rewards + formatting constraints + multi-stage training) that unlocks latent capabilities, and demonstrates practical automated research workflows. | Reasoning |
| [Maximum Likelihood Reinforcement Learning](https://zanette-labs.github.io/MaxRL/) | MaxRL normalizes RL gradients by successful samples (K) instead of total samples (N), achieving 7.9×–19.2× test-time scaling efficiency improvements and 2.3×–19.2× better sample efficiency than GRPO on math reasoning tasks by approximating maximum likelihood objectives. | RL |
| [Video and Transcript of Talk on Human-Like-ness in AI Safety](https://joecarlsmith.com/2025/12/17/video-and-transcript-of-talk-on-human-like-ness-in-ai-safety/) | AI systems can be safe through corrigibility (instruction-following with human oversight). | Safety |
| [Training LLMs to Predict World Events](https://thinkingmachines.ai/news/training-llms-to-predict-world-events/) | Fine-tuning a 120B LLM on forecasting tasks with RL improves Brier scores from 38.6 to 45.8 (matching Gemini 3 Pro performance). | Agents |
| [Aesthetic Preferences Can Cause Emergent Misalignment](https://www.lesswrong.com/posts/gT3wtWBAs7PKonbmy/aesthetic-preferences-can-cause-emergent-misalignment) | Fine-tuning GPT-4.1 and Qwen2.5 on unpopular aesthetic preferences (disliked music, architecture, atmospheres) causes emergent misalignment on unrelated tasks. | Safety |
| [State of RL for Reasoning LLMs](https://aweers.de/blog/2026/rl-for-llms/) | Post-2024 RL algorithms for reasoning LLMs. | RL |
| [Activation Steering in 2026: A Practitioner's Field Guide](https://subhadipmitra.com/blog/2026/activation-steering-field-guide/) | Steering works for refusal/sentiment/tone but fails on factual accuracy and complex reasoning. | Interp |
| [Why Steering Vectors Beat Prompting (And When They Don't)](https://subhadipmitra.com/blog/2025/steering-vectors-agents/) | Steering beats prompting on uncertainty calibration and refusal control, but fails on complex reasoning. | Interp |
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

