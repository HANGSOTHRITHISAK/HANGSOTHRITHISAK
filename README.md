<a href="assets/hero-static-desktop-dark.svg#gh-dark-mode-only">
<picture>
  <source media="(max-width: 600px)" srcset="assets/hero-static-narrow-dark.svg" width="320" height="104">
  <img alt="Feedback. Data. Compute." src="assets/hero-static-desktop-dark.svg#gh-dark-mode-only" width="800" height="104">
</picture>
</a>

<a href="assets/hero-static-desktop-light.svg#gh-light-mode-only">
<picture>
  <source media="(max-width: 600px)" srcset="assets/hero-static-narrow-light.svg" width="320" height="104">
  <img alt="Feedback. Data. Compute." src="assets/hero-static-desktop-light.svg#gh-light-mode-only" width="800" height="104">
</picture>
</a>

# HANG Sothrithisak

**AI undergraduate · Reliable ML, generalization & efficient learning**

I study Artificial Intelligence at the American University of Phnom Penh (AUPP). My current research asks how models behave when feedback is unreliable, data sources change, or compute is limited.

## Current research

Three ongoing undergraduate projects. The methods below are planned studies, not completed findings.

### 01 / When should a coding agent trust its feedback?

**Robustness of Language-Model Agents to Imperfect External Feedback**

Compare code generation and repair under self-reflection, clean feedback, corrupted feedback, and trust-aware checking against a one-shot baseline. The study will examine useful repairs alongside harmful revisions of initially correct code.

**Design:** Qwen2.5-Coder-1.5B-Instruct · HumanEval+ / EvalPlus · matched feedback conditions  
**Stage:** Execution infrastructure implemented; experimental pipeline and pilot pending. No research results yet. Solo project; repository private.

<!-- Add a verified public repository link only after a separately approved release. -->

### 02 / Does better data selection repay its own cost?

**Compute-Constrained Data Selection for Small-Model PEFT**

Compare random selection, embedding-based coverage, and RDS+ for small-model fine-tuning. Count selection overhead alongside training to assess whether better-selected data is worth its total cost.

**Design:** Qwen3-0.6B-Base · QLoRA planned, subject to pilot feasibility · fixed token budgets  
**Stage:** Research design; implementation and hardware pilot pending. Four-person team project; repository identity unconfirmed.

<!-- Repository identity is unconfirmed. Add a link only after verification, team agreement, and separately approved release. -->

### 03 / What changes when the test data comes from elsewhere?

**Cross-Dataset Generalization of Deep Learning for Tuberculosis Classification in Chest X-Rays**

Develop a DenseNet-121 baseline on TBX11K, then evaluate on Shenzhen and Montgomery without using those external datasets for model selection. The planned evaluation maps the internal three-class task to TB versus non-TB.

**Design:** Dataset provenance · duplicate auditing · frozen external evaluation  
**Stage:** Experimental design and dataset audit. Two-person team project; retrospective research, not a clinical tool.

[Repository →](https://github.com/HANGSOTHRITHISAK/tb-cross-dataset-generalization)

## Research direction

My interests connect reliable intelligent systems, generalization under dataset shift, and learning under resource constraints, with a growing interest in the mathematical and algorithmic methods behind these problems.

My research workflow uses Python, PyTorch, Git, and documented experiment configurations; Docker supports the code-execution runner. Transformers and PEFT are part of the planned language-model studies.

<!-- Future contact: add only a deliberately chosen public email address or a verified LinkedIn/personal website URL. -->
