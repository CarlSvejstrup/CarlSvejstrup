### Hi, I'm Carl.

I am a Data Science student at the Technical University of Denmark (DTU), focusing on Machine Learning and Statistical Analysis. Alongside my studies I build agentic AI systems in production: LLM agents, skills, MCP servers and the workflow infrastructure around them. I enjoy taking complex data problems and finding practical, working solutions.

**Current Focus**
* **Agentic Engineering:** Designing and shipping agent systems for a marketing agency. 
* **Audio LLMs:** Fine-tuning Qwen2-Audio with ALLD alignment for descriptive speech quality assessment (bachelor project).
* **Machine Learning:** Computer Vision, Reinforcement Learning, and Bayesian Methods.
* **LLMs:** Evaluating and implementing open-source models, plus agent evaluation and tool-use reliability.
* **Data Analysis:** Statistical evaluation and predictive modeling.

**Toolbox**
* **Languages:** Python, TypeScript, R, SQL
* **Agentic:** Claude Code, MCP (Model Context Protocol), agent skills/plugins, tool-use design, hook-based guardrails
* **Libraries:** PyTorch, TensorFlow, Scikit-learn, Pandas
* **Infra:** Supabase, Railway, Docker, Git, Jupyter

---

**Agentic Engineering**

Production agent work: an AI operating layer for a Copenhagen marketing agency, rolled out across multiple teams.

* **Skills as the unit of work.** A git-backed plugin marketplace is the single source of truth — six plugins covering Google Ads lifecycle, sales follow-up, AI-visibility/SEO and report generation. Skills are versioned, reviewed and installed, never pasted into a chat window.
* **Custom MCP servers.** Self-hosted MCP servers on Railway expose owned data and curated knowledge to the agent surface, instead of relying only on vendor connectors.
* **Write safety by construction.** Every external write (ad accounts, Drive, email, Slack) is human-in-the-loop, enforced by PreToolUse hooks rather than by prompt instructions — a separate write-only agent is the sole mutation path.
* **Token economics as a design constraint.** Multi-MB API payloads are routed through dedicated read-only sub-agents so the main context never ingests them.

---

**Selected Projects**

| Project | Description | Tech |
|--------|-------------|------|
| [**Speech Quality Assessment**](https://github.com/DavidLindahl/automatic-speech-assessment) | Bachelor project: fine-tuning Qwen2-Audio with ALLD for descriptive, time-localized speech quality assessment on NISQA-SIM mixes | Python, PyTorch, HuggingFace |
| [**Cross-Lingual Classifier**](https://github.com/DavidLindahl/danish-edu-llm-classifier) | Fine-tuning multilingual transformers (BERT/XLM) for Danish-English transfer | Python, PyTorch, HuggingFace |
| [**Bayesian Optimization**](https://github.com/Badecar/bayesian-optimization/tree/main) | Implementation of Gaussian Processes and Acquisition Functions for optimization | Python, NumPy, Scipy |
| [**Tetris RL Agent**](https://github.com/CarlSvejstrup/Tetris-DQN-NEAT) | Trained an autonomous agent to play Tetris using DQN & NEAT algorithms | Python, PyTorch, NEAT |
| [**LLM Statistical Evaluation**](https://github.com/CarlSvejstrup/02445---LLMs-Project) | Analysis of Large Language Model performance on structured tasks | Python, Jupyter, Scipy |

---
[LinkedIn](https://www.linkedin.com/in/carlschmidtsvejstrup/)
