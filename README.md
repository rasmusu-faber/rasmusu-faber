# Hi, I'm Rasmus 👋

Welcome to my GitHub! Here I explore the different things you can build with AI, mostly by building ML/LLM systems in Python.

I recently finished my MSc in Artificial Intelligence at USC Santiago (2026). I build and evaluate ML/LLM systems in Python, from data pipelines to production-ready RAG. My thesis focused on LLM classification and evaluation, which is why I care a lot about measuring what actually works.

`Python` · `LLMs & RAG` · `PyTorch / TensorFlow` · `PySpark` · `FastAPI` · `Docker` · `CI/CD`

---

## 🚀 Featured projects

### [Relocation Assistant — RAG with Source Citations & Evaluation](https://github.com/rasmusu-faber/relocation-assistant-rag)
Moving to Poland means navigating PESEL, meldunek and ZUS registration, which is confusing enough that I wanted a tool that answers these questions **and shows its sources**. It is a **retrieval-augmented generation** assistant that grounds every answer in official sources and traces it to the passages behind it. Poland is the example case; the pattern fits any domain with official or internal documents. An **evaluation harness** (hit-rate@k, MRR, answer groundedness) runs as a **CI quality gate** in GitHub Actions alongside ruff, mypy and pytest and fails the build when retrieval quality drops. Includes a Streamlit UI, Docker and a live demo.

`RAG` · `LLMs` · `FastAPI` · `Chroma` · `pytest` · `ruff + mypy` · `GitHub Actions` — **[Live demo »](https://relocation-assistant-rag.streamlit.app/)**

### [Gameboy LLM agent - An LLM Plays a Game Boy Game](https://github.com/rasmusu-faber/gameboy-llm-agent)
I wanted to see whether a small LLM can play a game through reasoning alone, no memorized walkthroughs and no vision model. The agent plays Deadeus (an open-source Game Boy horror game) by reading emulator RAM and the tilemap directly. Deterministic code handles the reflexes (e.g. pathing, door-finding), and the LLM is spent only on judgement calls. The demo GIF shows the model's own reasoning overlaid, round by round.

`PyBoy` · `LLM agents`

### [Baseball Hall-of-Fame Prediction — PySpark](https://github.com/rasmusu-faber/baseball_hof_prediction)
I built this one out of my passion for sports and especially sports data. An end-to-end **distributed-ML** pipeline on 200k+ player-season records: multi-table joins, career-level feature engineering, five classifiers with grid-search cross-validation, and an honest evaluation (AUROC, PR-AUC, threshold tuning) reframed around **severe class imbalance**.

`PySpark` · `Spark ML` · `Distributed data`

### [Diabetic Retinopathy Detection — Deep Learning](https://github.com/rasmusu-faber/Diabetic-Retinopathy-Detection)
I wanted to test myself on a real, high-stakes medical problem — one where plain accuracy quietly lies and the rare, severe cases are exactly the ones that matter most. A study of **class imbalance in medical imaging**: a custom CNN vs. transfer learning (ResNet50, EfficientNet) for 5-class DR severity grading, evaluated with **Quadratic Weighted Kappa**, per-class recall and confusion matrices against a majority-class baseline.

`TensorFlow / Keras` · `Transfer learning` · `Computer vision`

---

## 🧰 What I work with

- **ML / DL:** scikit-learn, TensorFlow/Keras, PyTorch, transfer learning, imbalanced-data handling
- **LLMs:** RAG, embeddings & vector search, prompt/response engineering and evaluation (Human-in-the-loop prompt refinement), groundedness, agentic workflows
- **Data & scale:** PySpark, pandas, feature engineering, distributed pipelines
- **Engineering:** FastAPI, Streamlit, Docker, pytest, GitHub Actions (CI), ruff/mypy

---

## 📫 Get in touch

- 💼 LinkedIn: `https://www.linkedin.com/in/rasmus-faber/`
- 📧 Email: `ra.fa.koeln@gmail.com`

