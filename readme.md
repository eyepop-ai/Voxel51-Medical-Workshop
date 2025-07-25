# EyePop + Voxel51 
## Train a Medical AI Model in One Day


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
git clone https://github.com/eyepop-ai/Voxel51-Medical-Workshop
cd Voxel51-Medical-Workshop
```

---

## 🚀 Launch the First Notebook

```bash
jupyter notebook notebooks/01_dataset_visualization.ipynb
```

If it opens a blank screen, try VS Code or use the classic notebook interface (`jupyter notebook`, **not** `jupyter lab`).

---

## 🔐 API Keys

For Notebook #2, you’ll need to paste your EyePop.ai API key. You can grab a key at https://www.eyepop.ai/

---

## Dataset

https://huggingface.co/datasets/Voxel51/ARCADE_FO