# WFGY Problem Map — Index of AI Failures We've Solved

> 📌 **This is just an index repo.**  
> Go to each problem’s folder for detailed modules, demos, and engineering walkthroughs.  
> 👉 **[Main Problem Map](https://github.com/onestardao/WFGY/tree/main/ProblemMap)**

<img width="1536" height="1024" alt="Hero" src="https://github.com/user-attachments/assets/a73aac28-c133-4fcb-9643-fb2756736e02" />

---

## 🚀 Start Here (shortcuts)

- **[Problem Map 1.0 — Core 16 Failures](https://github.com/onestardao/WFGY/blob/main/ProblemMap/README.md)**
- **[Problem Map 2.0 — RAG Architecture & Recovery](https://github.com/onestardao/WFGY/blob/main/ProblemMap/rag-architecture-and-recovery.md)**
- **[Grandma Clinic — All Bugs Made Simple (1–16)](https://github.com/onestardao/WFGY/tree/main/ProblemMap/GrandmaClinic)**
- **[Semantic Clinic — Triage Hub](https://github.com/onestardao/WFGY/blob/main/ProblemMap/SemanticClinicIndex.md)**
- **[Diagnose by Symptom — Quick Sheet](https://github.com/onestardao/WFGY/blob/main/ProblemMap/Diagnose.md)**
- **[🧩 MVP Demos — Minimal Runnable Examples](https://github.com/onestardao/WFGY/blob/main/ProblemMap/mvp_demo/README.md)**
- **[🌍 Global Fix Map — Systemic AI Failures](https://github.com/onestardao/WFGY/blob/main/ProblemMap/GlobalFixMap/README.md)**


---

## 🧠 What is WFGY Problem Map?

This is the central index of AI failure modes we've tracked, diagnosed, and solved using **WFGY** — a semantic reasoning engine for LLMs.

We don't just identify bugs. We redefine them as solvable cognitive flaws — then ship modular logic patches you can drop into your system.

> If your LLM has ever hallucinated, frozen, collapsed, or forgotten... chances are we've dissected it here.

---

## 🧭 Problem Categories (Core 16)

Each link opens the failure’s fix page:

1. **[Hallucination & Chunk Drift](https://github.com/onestardao/WFGY/blob/main/ProblemMap/hallucination.md)** — retrieval returns wrong/irrelevant content  
2. **[Interpretation Collapse](https://github.com/onestardao/WFGY/blob/main/ProblemMap/retrieval-collapse.md)** — chunk is right, logic is wrong  
3. **[Long Reasoning Chains](https://github.com/onestardao/WFGY/blob/main/ProblemMap/context-drift.md)** — multi-step tasks silently drift  
4. **[Bluffing / Overconfidence](https://github.com/onestardao/WFGY/blob/main/ProblemMap/bluffing.md)** — confident but unfounded answers  
5. **[Semantic ≠ Embedding](https://github.com/onestardao/WFGY/blob/main/ProblemMap/embedding-vs-semantic.md)** — cosine match ≠ true meaning  
6. **[Logic Collapse & Recovery](https://github.com/onestardao/WFGY/blob/main/ProblemMap/logic-collapse.md)** — dead-end logic; needs controlled reset  
7. **[Memory Breaks Across Sessions](https://github.com/onestardao/WFGY/blob/main/ProblemMap/memory-coherence.md)** — lost threads, no continuity  
8. **[Debugging is a Black Box](https://github.com/onestardao/WFGY/blob/main/ProblemMap/retrieval-traceability.md)** — no visibility into failure path  
9. **[Entropy Collapse](https://github.com/onestardao/WFGY/blob/main/ProblemMap/entropy-collapse.md)** — attention melts, incoherent output  
10. **[Creative Freeze](https://github.com/onestardao/WFGY/blob/main/ProblemMap/creative-freeze.md)** — flat, literal outputs  
11. **[Symbolic Collapse](https://github.com/onestardao/WFGY/blob/main/ProblemMap/symbolic-collapse.md)** — abstract/logical prompts break  
12. **[Philosophical Recursion](https://github.com/onestardao/WFGY/blob/main/ProblemMap/philosophical-recursion.md)** — self-reference/paradox loops  
13. **[Multi-Agent Chaos](https://github.com/onestardao/WFGY/blob/main/ProblemMap/Multi-Agent_Problems.md)** — agents overwrite/misalign logic (overview)  
14. **[Bootstrap Ordering](https://github.com/onestardao/WFGY/blob/main/ProblemMap/bootstrap-ordering.md)** — services fire before deps ready  
15. **[Deployment Deadlock](https://github.com/onestardao/WFGY/blob/main/ProblemMap/deployment-deadlock.md)** — circular waits (index⇆retriever, DB⇆migrator)  
16. **[Pre-Deploy Collapse](https://github.com/onestardao/WFGY/blob/main/ProblemMap/predeploy-collapse.md)** — first call after deploy crashes  

**Multi-Agent deep dives**  
- **[Role Drift](https://github.com/onestardao/WFGY/blob/main/ProblemMap/multi-agent-chaos/role-drift.md)**  
- **[Cross-Agent Memory Overwrite](https://github.com/onestardao/WFGY/blob/main/ProblemMap/multi-agent-chaos/memory-overwrite.md)**

---

## 🧩 Patterns Library (targeted fixes)

- **[Query Parsing Split (HyDE/BM25)](https://github.com/onestardao/WFGY/blob/main/ProblemMap/patterns/pattern_query_parsing_split.md)**
- **[Symbolic Constraint Unlock (SCU)](https://github.com/onestardao/WFGY/blob/main/ProblemMap/patterns/pattern_symbolic_constraint_unlock.md)**
- **[Hallucination Re-entry](https://github.com/onestardao/WFGY/blob/main/ProblemMap/patterns/pattern_hallucination_reentry.md)**
- **[Memory Desync](https://github.com/onestardao/WFGY/blob/main/ProblemMap/patterns/pattern_memory_desync.md)**
- **[Vectorstore Fragmentation](https://github.com/onestardao/WFGY/blob/main/ProblemMap/patterns/pattern_vectorstore_fragmentation.md)**
- **[Bootstrap Deadlock (RAG boot fence)](https://github.com/onestardao/WFGY/blob/main/ProblemMap/patterns/pattern_bootstrap_deadlock.md)**

**All patterns:** **[Patterns Index](https://github.com/onestardao/WFGY/tree/main/ProblemMap/patterns)**

---

## 🛠️ Playbooks & Guides

- **[Retrieval Playbook](https://github.com/onestardao/WFGY/blob/main/ProblemMap/retrieval-playbook.md)**
- **[Rerankers](https://github.com/onestardao/WFGY/blob/main/ProblemMap/rerankers.md)**
- **[Data Contracts](https://github.com/onestardao/WFGY/blob/main/ProblemMap/data-contracts.md)**
- **[Multilingual Guide](https://github.com/onestardao/WFGY/blob/main/ProblemMap/multilingual-guide.md)**
- **[Privacy & Governance](https://github.com/onestardao/WFGY/blob/main/ProblemMap/privacy-and-governance.md)**

**Examples:** **[Examples Hub](https://github.com/onestardao/WFGY/tree/main/ProblemMap/examples)**  
**Eval:** **[Evaluation Suite](https://github.com/onestardao/WFGY/tree/main/ProblemMap/eval)**  
**Ops Runbook:** **[Ops & Monitoring](https://github.com/onestardao/WFGY/tree/main/ProblemMap/ops)**  
**Beginner Guide:** **[Start Here](https://github.com/onestardao/WFGY/blob/main/ProblemMap/BeginnerGuide.md)**  
**Getting Started:** **[RAG Quickstart](https://github.com/onestardao/WFGY/blob/main/ProblemMap/getting-started.md)**

---

## 🗺️ Maps A–G (fast routing)

- **[Map-A · RAG Problem Table](https://github.com/onestardao/WFGY/blob/main/ProblemMap/RAG_Problems.md)**
- **[Map-B · Multi-Agent Chaos Map](https://github.com/onestardao/WFGY/blob/main/ProblemMap/Multi-Agent_Problems.md)**
- **[Map-C · Symbolic & Recursive Map](https://github.com/onestardao/WFGY/blob/main/ProblemMap/Symbolic_Logic_Problems.md)**
- **[Map-D · Logic Recovery Map](https://github.com/onestardao/WFGY/blob/main/ProblemMap/logic-collapse.md)**
- **[Map-E · Long-Context Stress Map](https://github.com/onestardao/WFGY/blob/main/ProblemMap/LongContext_Problems.md)**
- **[Map-F · Safety Boundary Map](https://github.com/onestardao/WFGY/blob/main/ProblemMap/Safety_Boundary_Problems.md)**
- **[Map-G · Infra Boot Map](https://github.com/onestardao/WFGY/blob/main/ProblemMap/Infra_Boot_Problems.md)**

---

## 🧪 MVP Demos (runnable mini examples)

- **[Demo Readme & Entrypoints](https://github.com/onestardao/WFGY/blob/main/ProblemMap/mvp_demo/README.md)**
- **[Browse All Demos](https://github.com/onestardao/WFGY/tree/main/ProblemMap/mvp_demo)**


---

> 👑 **Early Stargazers: Hall of Fame** — Engineers, hackers, and open-source builders who supported this project from day one.  
> **[View the Hall of Fame](https://github.com/onestardao/WFGY/tree/main/stargazers)**

<div align="center">

[![WFGY Main](https://img.shields.io/badge/WFGY-Main-red?style=flat-square)](https://github.com/onestardao/WFGY)
&nbsp;
[![TXT OS](https://img.shields.io/badge/TXT%20OS-Reasoning%20OS-orange?style=flat-square)](https://github.com/onestardao/WFGY/tree/main/OS)
&nbsp;
[![Blah](https://img.shields.io/badge/Blah-Semantic%20Embed-yellow?style=flat-square)](https://github.com/onestardao/WFGY/tree/main/OS/BlahBlahBlah)
&nbsp;
[![Blot](https://img.shields.io/badge/Blot-Persona%20Core-green?style=flat-square)](https://github.com/onestardao/WFGY/tree/main/OS/BlotBlotBlot)
&nbsp;
[![Bloc](https://img.shields.io/badge/Bloc-Reasoning%20Compiler-blue?style=flat-square)](https://github.com/onestardao/WFGY/tree/main/OS/BlocBlocBloc)
&nbsp;
[![Blur](https://img.shields.io/badge/Blur-Text2Image%20Engine-navy?style=flat-square)](https://github.com/onestardao/WFGY/tree/main/OS/BlurBlurBlur)
&nbsp;
[![Blow](https://img.shields.io/badge/Blow-Game%20Logic-purple?style=flat-square)](https://github.com/onestardao/WFGY/tree/main/OS/BlowBlowBlow)

</div>
