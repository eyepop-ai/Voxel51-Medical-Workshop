# 🧠 EyePop + Voxel51 Medical AI Workshop

Welcome to the hands-on workshop! This guide walks you through setting up your local machine to run the Jupyter notebooks that power our medical AI training workflow.

---

## ✅ Prerequisites

### 1. Install Python 3.11 (recommended)

- **macOS**:
  ```bash
  brew install pyenv
  pyenv install 3.11.9
  pyenv global 3.11.9
  ```

- **Windows**:
  Download Python 3.11 from: https://www.python.org/downloads/release/python-3110/

- **Ubuntu/Linux**:
  ```bash
  sudo apt update
  sudo apt install python3.11 python3.11-venv python3.11-dev
  ```

### 2. Check Your Python Version
```bash
python3 --version
```
✅ Make sure it returns `3.11.x`.

---

## 📦 Clone This Repository

```bash
git clone https://github.com/eyepop-ai/Voxel51-Medical-Collab.git
cd Voxel51-Medical-Collab
```

---

## 🚀 Launch the First Notebook

```bash
jupyter notebook notebooks/01_dataset_visualization.ipynb
```

If it opens a blank screen, try VS Code or use the classic notebook interface (`jupyter notebook`, **not** `jupyter lab`).

---

## 🔐 API Keys

For Notebook #2 and #3, you’ll need to paste your EyePop.ai API key when prompted or export it like this:

# TBD

You will receive your API key at the workshop check-in or via email.

---

## 🧵 Notebooks

- `01_dataset_visualization.ipynb`: Download, inspect, and explore the dataset with FiftyOne
- `02_model_training_eyepop.ipynb`: Upload & label data, then train your model

---

Let’s build something powerful together 💥