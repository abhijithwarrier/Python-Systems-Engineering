# ⚙️ Python Systems Engineering

Learn concurrency, coordination, and reliability concepts through practical Python experiments.

Created by **python_scripts (Abhijith Warrier)**.

Explore how systems behave when work runs concurrently, resources are limited, and operations fail. This series uses Python to make coordination problems and reliability trade-offs concrete.

---

## 📚 Learning Roadmap

The following topics describe the planned scope of the series. This roadmap is not a list of already published notebooks.

| Area | Concepts |
|---|---|
| **Concurrency and shared state** | Race conditions, locks, synchronization, and deadlocks. |
| **Reliable operations** | Idempotency, timeouts, retries, exponential backoff, and jitter. |
| **Managing load** | Backpressure, bounded queues, and overload behaviour. |
| **Distributed coordination** | Delivery guarantees, deduplication, consistent hashing, replication, and logical clocks. |

---

## 🚀 Getting Started

Once this repository and its notebooks are available, clone it:

```bash
git clone https://github.com/abhijithwarrier/Python-Systems-Engineering.git
cd Python-Systems-Engineering
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

macOS / Linux:

```bash
source .venv/bin/activate
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Install and launch JupyterLab:

```bash
python -m pip install jupyterlab
python -m jupyterlab
```

Use `python3` instead of `python` where required by your system. Open a notebook and run its cells from top to bottom. Any topic-specific packages and Python-version requirements will be stated in that notebook; install packages using its dedicated installation section.

---

## 🔍 Learning Approach

Experiments will identify their assumptions and distinguish a controlled local demonstration from a production-ready distributed system. Some topics may include supporting Python scripts for separate processes or services.

Run the example, change an input or assumption, and explain why the result changed. Keep the conceptual lesson connected to the code and its output.

---

## 👨‍💻 About the Series

Part of the **python_scripts** educational series: learning concepts by implementing and exploring them with Python.

Follow [@python_scripts on Instagram](https://www.instagram.com/python_scripts/) for accompanying Reels and explanations.

**Created by Abhijith Warrier**
