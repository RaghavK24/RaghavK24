<h1 align="center">Hi, I'm Raghav Kapil 👋</h1>

<p align="center">
  M.Tech in AI at <b>IIT Kharagpur</b> · I build systems in C++ (schedulers, databases, toolchains) and LLM tooling, and I like measuring whether they actually work.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/raghav-kapil-59b743226/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://komarev.com/ghpvc/?username=RaghavK24&color=00ff88&style=flat-square&label=profile+views" alt="profile views">
</p>

```python
class Raghav:
    studying = "M.Tech, Artificial Intelligence @ IIT Kharagpur (CGPA 8.96)"
    also     = "B.S. Data Science @ IIT Madras (remote)"
    worked_at = ["MathWorks (EDG intern, 2026)", "Genie AI (ML intern, 2024)"]
    teaching = "TA, Deep Learning for Sequential Data Lab"
    interests = ["systems & databases", "information retrieval", "RAG & agents", "LLM safety"]
    stack     = ["Python", "C++", "PyTorch", "Hugging Face", "LangChain", "SQL"]
```

## Projects

| Project | What it is | Stack |
|---|---|---|
| [**DeltaSearch**](https://github.com/RaghavK24/DeltaSearch) | A search engine over 4.6M Wikipedia entities (BEIR DBpedia-Entity). Hand-written inverted index with compressed postings, BM25 + WAND, PageRank, dense HNSW retrieval and a cross-encoder reranker. Hybrid + PageRank + rerank reaches **nDCG@10 0.485** on 400 held-out test queries, with every gain checked for significance. | C++20, ONNX Runtime, hnswlib, Python |
| [**Clurm**](https://github.com/RaghavK24/Clurm) | A cluster job scheduler with failover. A primary scheduler logs each job in SQLite, copies the log to a standby backup and places the job on a node with enough cores, memory and GPUs. If the primary dies, the backup takes over, finishes the jobs it had accepted and starts taking new ones. Tested by killing the primary mid-run. | C++14, POSIX sockets (TCP/UDP), threads, SQLite |
| [**MiniToolChain**](https://github.com/RaghavK24/MiniToolChain) | An assembler, linker, VM and debugger for a custom 64-bit instruction set, with its own binary formats, an optimizer and no third-party libraries (even the test runner is built in). 358 tests across unit, golden, property and fuzz suites. | C++23, CMake |
| [**FlexQL**](https://github.com/RaghavK24/FlexQL) | A SQL database engine with a client-server design. B+ tree indexes, a buffer pool with LRU eviction, a write-ahead log with group commit and crash recovery, joins and GROUP BY. Inserts 10M rows in 2.6 s, and a secondary index cuts a filtered query from 170 ms to 6 ms. | C++17, POSIX sockets, pthreads |

## Achievements

- 🏅 **GATE 2025 (Data Science & AI): All India Rank 76**
- 🏆 **Smart India Hackathon 2023: National Finalist**
- 🧑‍🏫 Teaching Assistant at IIT Kharagpur, tutoring about 40 B.Tech students in a Deep Learning lab

<p align="center"><i>Measure first, then believe it.</i></p>
