## Hi, I'm Sreya Thota

M.Sc. Artificial Intelligence student at BTU Cottbus-Senftenberg (expected Oct 2027), based in Berlin, with ~2 years at Nav Tech Electronics across ML, computer vision, LLM and data work. I build LLM and ML systems in Python and measure whether they work, including when the answer is "not yet".

**Looking for:** AI/ML, LLM and Python working-student roles or internships in Germany (20 h/week in the semester, full-time in breaks; Berlin-based, open to remote or hybrid).

### Projects

**[Pipeline Medic](https://github.com/SreyaThota/pipeline-medic)** — LLM agents for CI failure diagnosis
A LangGraph graph that parses and redacts a failed CI log, retrieves similar past failures (Chroma), rates the risk and proposes a ticket through MCP tools that only run after a human approves. Built and measured on real GitHub Actions logs from open-source repos:
- Last-15-lines chunking nearly doubled retrieval Recall@1 over whole-log embedding (0.413 vs 0.217, 46 queries, cross-repo).
- GraphRAG (Neo4j) and a LoRA risk classifier were built and *not* adopted: neither beat the simpler baseline on held-out logs.
- Trajectory evaluation of the whole graph on 72 held-out logs (labels written by me, no second reviewer), 80-test security suite, CI with mypy strict.

**[Alzheimer's MRI classification](https://github.com/SreyaThota/alzheimers-mri-detection)** — CNN, B.Tech team project
Four-class dementia-stage classifier from brain MRI with a Flask app. Team project; inherited components and my own rebuild (training/evaluation scripts, leakage checks, per-class metrics, Grad-CAM) are documented separately. Academic prototype, not a medical device.

**[ArchCipher](https://github.com/SreyaThota/42_Hack_21_22)** — autonomous coding agent, 42 × Needle hackathon (team of 3)
A plan → code → test → repair loop on local LLMs (Ollama, Qwen2.5-Coder) that built a DSL compiler from a hidden spec. My part: the isolated compiler v2 pipeline ([merged PR](https://github.com/ArchCipher/42xNeedle_Hackathon/pull/1)).

**[HeatMap.Wohnen](https://github.com/SreyaThota/heatmap-wohnen)** — Climathon 2026 team project (team of four): web-based heat-stress scoring concept for apartments. My part: idea, UI and demo.

**[Breadcrumb](https://github.com/SreyaThota/breadcrumb)** — local-first Windows tool that reconstructs where you left off (Python, SQLite, Win32; 15 tests).

### Work (Nav Tech Electronics, 2024–2025, code confidential)
- Fine-tuned Flan-T5 to turn natural-language requirements into ECU test cases; grew the dataset from 650 seed pairs to ~100K examples (~30% less manual test writing).
- Trained a 50-class YOLOv8 dashboard-icon detector (mAP@0.5 0.453) and traced weak classes to data imbalance.
- Jira fault-reporting automation and Bitbucket/Jenkins CI/CD.

### Tools
**ML / AI:** Python · TensorFlow/Keras · scikit-learn · Hugging Face Transformers · YOLOv8 · RAG and retrieval evaluation · Chroma · Ollama
**Learning:** PyTorch · LangGraph · MCP
**Engineering:** FastAPI · Flask · pytest · Git · GitHub Actions · Jenkins · Docker (basics) · SQL · Linux · Java

### Contact
[LinkedIn](https://linkedin.com/in/sreyathota5) · [sreyathota.5@gmail.com](mailto:sreyathota.5@gmail.com) · [Personal site](https://loopless-site.patelstracy.workers.dev)
