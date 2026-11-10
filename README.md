### Hi, I'm Isa (Haotong Hu)

CS student at UCLA (class of 2029). I'm into AI, mostly the training side: getting models to learn something useful and figuring out why they don't. I'm also interested in product, meaning how AI actually ends up in front of people.

**What I'm working on**

<details>
<summary><b>ACM AI at UCLA</b>: Operations Director. I help run workshops and hackathons</summary>
<br>

- Co-hosted an ACM AI × Google Gemini workshop
- "AI in Practice" joint event with Product Space
- Full-day AI hackathon with 70+ attendees

</details>

**Recently**

<details>
<summary><b>Sign language translation @ <a href="http://uclalemur.com">Lemur Lab, UCLA</a></b>: trained Uni-Sign and mT5 models on How2Sign, experimented with GRPO and DPO (Mar – Sep 2026)</summary>
<br>

Real-time sign language → text translation. I owned the training side of the project.

- Fine-tuned **Uni-Sign** and **mT5-base** on the How2Sign dataset (NVIDIA Titan RTX and DGX Spark, CUDA 12.2)
- Designed a **GRPO reward model** that uses the semantic weight of words and source–target alignment strength for better credit assignment
- Ran 10 comparison experiments on cross-modal alignment and information loss. Best fine-tuned run: **BLEU-4 14.43**
- Tested **DPO** variants for adding context during training. Best: **BLEU-4 23.05**
- Built infra for multi-day training: idle-GPU detection, auto-launch, early stopping and fault recovery. Also fixed video-loading bugs and distributed-training deadlocks

</details>

<details>
<summary><b>AI agent platform @ Agilean (intern)</b>: scheduling and worker registration for an internal R&D agent platform (Jul – Oct 2026)</summary>
<br>

- Designed a Jenkins-style **inbound agent** architecture, moving the platform from local config to flexible scheduling
- Built the end-to-end pipeline for multi-worker registration, environment provisioning and session scheduling
- Built a **Plan-to-Repo** framework that plugs AI into existing dev workflows, with progress updates, decision points and result validation
- Validated the platform on real enterprise projects (e.g. a Frappe/Lending management system)

</details>

**Before that**

<details>
<summary><b>Self-Reflective RAG</b>: published <i>A Self-Reflective Retrieval Augmented Generation System to Eliminate Hallucination in LLM Generation</i> (CSIT 2024), and I'm lead inventor on the patent application</summary>
<br>

Student researcher, Jan 2024 – Sep 2025.

- Built a self-reflective RAG architecture in LangChain with "reflective nodes" that check the quality of retrieved data before the model generates an answer
- Designed a modular framework connecting unstructured data to LLM reasoning, which cut hallucination in long-sequence retrieval
- Lead inventor on the Self-RAG algorithm patent application (#63/663,192)

</details>

<details>
<summary><b>Personal knowledge base web app</b>: a full-stack app for asking questions about your own documents (2023)</summary>
<br>

- Upload your own documents and ask questions about them, so answers come from your data and not from what the model makes up
- OpenAI API plus vector search over the uploaded documents
- Took it end to end: from figuring out the user pain point, through data processing and indexing, to deployment

</details>

<details>
<summary><b>NLP research</b>: mining adverse drug reactions from social media text (2023)</summary>
<br>

- Published *Natural language processing: mining adverse drug reactions from media texts*
- Used CNNs and RNNs for fine-grained event detection on noisy Twitter/X data
- Ran ablation studies to find which architecture best catches rare signals in unstructured text
- Mentored by Prof. David Woodruff (CMU) through the Algorithms for Big Data program

</details>

<details>
<summary><b>Student Council President</b> @ BASIS Bilingual School Shenzhen (2024–25)</summary>
<br>

- Ran school-wide events, including a hackathon with an AI track for 100+ students. I wrote the rules and scoring rubric and ran it end to end, from registration and team matching through demos
- Main liaison to school administration. Built a feedback workflow (surveys → prioritization → monthly updates) and an ops knowledge base so the council stopped redoing the same work

</details>

**Awards**

- HiMCM Honorable Mention (mathematical modeling), 2022
- IgniteCS Programming Expo, 2nd place, 2023
- President's Volunteer Service Award (Gold), 2025

**Stuff I use**

Python · PyTorch · DeepSpeed · C++ · TypeScript · React · Node.js

**This year**

Taking CS 111 (operating systems) and M51A (logic design). I'm posting notes and small experiments here as I go.

---

Resume: [English](./Haotong_Hu_Resume_EN_1.pdf) · [中文](./Haotong_Hu_Resume_CN_1.pdf) · Reach me at huht1303 [at] gmail [dot] com.
