<h1 align="center">Gregorius Reynard Lin</h1>

<p align="center">
  <strong>AI/ML Engineer</strong> &nbsp;·&nbsp; Post-training and agentic systems &nbsp;·&nbsp; Greater Toronto Area
</p>

<p align="center">
  <a href="https://tapverdict.com">
    <img src="https://img.shields.io/badge/Verdict-live_product-4F46E5?style=flat-square" alt="Verdict" />
  </a>
  <a href="https://www.linkedin.com/in/gregorius-reynard-lin-a0665a261/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:gregoriusreynard.lin@dcmail.ca">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

I build applied AI that ships to real users, and I care about being able to prove it works. That second half is where most of my time goes: eval harnesses, attribution analysis, and figuring out what a result actually shows.

Final-year **Honours Bachelor of Artificial Intelligence** at Durham College (GPA 4.92/5.0), graduating June 2027.

## Currently

**Co-Founder and Founding Engineer** at **[Verdict](https://tapverdict.com)**
*A no-login PWA that tells you which credit card in your wallet to use, and cites the line in the terms that proves it.*

- Sole engineer. Live and public, around 100 users.
- The LLM pipeline is gated by an eval harness with CI-enforced accuracy thresholds, so no model, prompt, or schema change ships unmeasured.
- On-device wallet with no per-user datastore, which keeps marginal cost per user near zero.

**AI Engineering Co-op** at **Intransigense Technologies** (Dealigense)
*Generative-AI video for an AI marketing CRM.*

- Project lead for a 3-person team: sprint planning, design, and direct line to the founder.
- Built a harness that chains generation, automated editing, and compositing to assemble captioned short-form video from a text prompt.

## Selected work

| Project | | |
| :--- | :--- | :--- |
| **[Web-Agent Distillation](https://github.com/ReynardL/small-4b-web-agent-distillation)** | 4B WebArena agent on one 8GB GPU | SFT tripled success to **24.4%**, then teacher reasoning made it worse. The repo is the diagnosis. |
| **[Emergent Reasoning](https://github.com/ReynardL/EmergentReasoning)** | DAPO reinforcement learning on Qwen2.5-1.5B | GSM8K **50.4% to 68.0%**, but attribution showed the gain was parse reliability, not reasoning. |
| **[Abi](https://github.com/ReynardL/Abi-Financial-Assistant)** | Local-first financial agent, 13-tool MCP layer | Merchant names hashed before any LLM call. **Zero raw financial data leaves the machine.** |
| **[Bankruptcy Predictor](https://github.com/ReynardL/Bankruptcy-predictor)** | XGBoost on 30 financial ratios | **0.94 ROC AUC**, with SHAP attributions so a loan officer can read why. |
| **[Live Emotion Classifier](https://github.com/ReynardL/EmotionClassifier)** | 5.6M-param CNN with spatial attention | 5 emotions in real time from webcam. |

## Toolkit

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
</p>

**Machine learning**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/TRL-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="TRL" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square" alt="XGBoost" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />
</p>

**LLM tooling**

<p>
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API" />
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square" alt="MCP" />
  <img src="https://img.shields.io/badge/RAG-4F46E5?style=flat-square" alt="RAG" />
  <img src="https://img.shields.io/badge/Evals-4F46E5?style=flat-square" alt="Evals" />
</p>

**Backend and infrastructure**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white" alt="AWS Lambda" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" />
</p>
