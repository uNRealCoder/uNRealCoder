### Hi, I'm Nikhil 👋

**Senior AI Engineer at Mastercard.** I build AI inference systems that hold up in production:
LLMs and RAG, graph ML and GNNs, taken from research prototype to something that serves billions
of transactions and keeps serving them.

```python
class NikhilRanjan(Inference):
    """Turns messy production data into predictions that don't fall over."""
    role     = "Senior AI Engineer"
    works_on = ("LLMs", "RAG", "graph ML", "GNNs")
    msc      = "Artificial Intelligence, UGA"

    def __repr__(self) -> str:
        return f"<{self.role}: still reading papers>"
```

- 🕸️ Graph feature library that turns raw transactions into GNN embeddings, on graphs with **10⁹ edges**
- ⚡ Moved graph ETL from CPU to GPU with NVIDIA RAPIDS and cuGraph: **~50× faster**
- 🛡️ Those embeddings feed fraud models that have stopped **$100M+** in fraudulent transactions
- 🤖 Production LLMs on vLLM and embedding models on ONNX, behind agentic fraud-investigation workflows

#### Things I shipped on my own time

| Project | What it does |
| --- | --- |
| [**downshift-server**](https://github.com/uNRealCoder/downshift-server) | A CPU-first model server that checks its own work. It exports your model to ONNX, compares the result with PyTorch, and serves eager PyTorch if the numbers are wrong. [Docs](https://downshift-server.readthedocs.io/en/latest/index.html) |
| [**PyG_Transformer_Temporal_Sampling**](https://github.com/uNRealCoder/PyG_Transformer_Temporal_Sampling) | Anti-money-laundering detection with graph neural networks in PyTorch Geometric, compared against an XGBoost baseline. [Results](https://uNRealCoder.github.io/PyG_Transformer_Temporal_Sampling/) |

#### Tools I reach for

**LLMs, RAG & agents:** vLLM · ONNX · LangGraph · CrewAI · AutoGen · vector DBs<br>
**Graph ML & GNNs:** PyTorch Geometric · DGL · cuGraph · NVIDIA RAPIDS · GraphSAGE<br>
**ML & infra:** PyTorch · scikit-learn · XGBoost · Spark · Docker · CUDA · Python

#### Elsewhere

[Website](https://unrealcoder.github.io/) · [LinkedIn](https://www.linkedin.com/in/nikhil-ranjan/) · [Résumé (PDF)](https://unrealcoder.github.io/Nikhil-Ranjan-Resume.pdf)
