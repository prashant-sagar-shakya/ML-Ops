# 🛠️ **Developer Environment Setup Guide**

A complete beginner-friendly guide to setting up your coding environment using **VS Code**, **Anaconda**, **Google Colab**, and **GitHub Codespaces**.


## ⭐ **1. Install Visual Studio Code (VS Code)**

VS Code is a lightweight yet powerful source-code editor by Microsoft.

### 📥 **Steps to Install**

1. Visit the official site:
   👉 [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Download the installer based on your OS:

   * Windows `.exe`
   * macOS `.dmg`
   * Linux `.deb` or `.rpm`
3. Run the installer.
4. Recommended options during installation:

   * ✅ Add to PATH
   * ✅ Add right-click “Open with Code”
   * ✅ Create Desktop icon

### 🔌 Recommended Extensions

| Extension   | Use                           |
| ----------- | ----------------------------- |
| Python      | For Python coding & debugging |
| Jupyter     | Run notebooks inside VS Code  |
| GitLens     | Git history & version control |
| Prettier    | Code formatting               |
| Live Server | For web development           |


## 🐍 **2. Install Anaconda (Python + Libraries + Environment Manager)**

Anaconda is the easiest way to install Python, Jupyter, and scientific libraries like NumPy, Pandas, Matplotlib, and Scikit-Learn.

### 📥 **Steps to Install**

1. Visit:
   👉 [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)
2. Download the **Anaconda Installer** (Windows/Mac/Linux).
3. Run the installer → Select:

   * **Install for: "Just Me"**
   * **Add Anaconda to PATH** (Optional but useful)
4. Open **Anaconda Navigator** or **Anaconda Prompt**.

### 🧪 Create Virtual Environments

```bash
conda create -n myenv python=3.10
conda activate myenv
```

### 📦 Install packages

```bash
conda install numpy pandas matplotlib scikit-learn
```


## ☁️ **3. Google Colab (Cloud-based Python Notebook)**

Google Colab allows you to write and run Python code in the cloud—**no installation required**.

### 🎯 **Why Use Google Colab?**

* Runs on Google Cloud
* Free GPUs (Tesla T4 / P100)
* Perfect for ML, AI, and data analysis
* Access files from Google Drive
* Share notebooks easily

### 🚀 How to Start

1. Visit:
   👉 [https://colab.research.google.com/](https://colab.research.google.com/)
2. Sign in with your Google account.
3. Click **New Notebook**.
4. Start coding!

### ⚡ Connect Google Drive

```python
from google.colab import drive
drive.mount('/content/drive')
```


## 🧳 **4. GitHub Codespaces (Cloud-based VS Code)**

GitHub Codespaces gives you a full **VS Code environment in the cloud**.

### 🎯 **Why Use Codespaces?**

* No need to install anything locally
* Works directly from your browser
* Preconfigured dev containers
* Great for collaborative projects
* GitHub manages compute, dependencies & environments

### 🚀 How to Start

1. Go to any GitHub repository.
2. Click **Code → Codespaces → Create Codespace**.
3. A browser-based VS Code editor opens.
4. Start coding instantly.

### ⚙️ Developer Features

* Full terminal support
* Extensions support
* Auto-saved environments
* Ideal for Python, JavaScript, Node, and ML workflows


## 📘 **5. Jupyter Notebook / JupyterLab**

These come with Anaconda.

### 🚀 Launch Notebooks

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

### 📄 Why Use Jupyter?

* Run code in small cells
* Best for data science
* Built-in graphs
* Markdown support


## 🔁 **6. Git & GitHub Setup**

### Install Git

Download from:
👉 [https://git-scm.com/](https://git-scm.com/)

### Configure Git

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

### Clone a Repository

```bash
git clone https://github.com/username/repo-name.git
```


## 📚 **7. Quick Summary**

| Tool                  | Purpose                     | Difficulty |
| --------------------- | --------------------------- | ---------- |
| **VS Code**           | Code editor                 | ⭐ Easy     |
| **Anaconda**          | Python setup + environments | ⭐⭐ Medium  |
| **Google Colab**      | Cloud notebooks + free GPU  | ⭐ Easy     |
| **GitHub Codespaces** | Cloud VS Code               | ⭐⭐ Medium  |
| **Jupyter**           | Notebook environment        | ⭐ Easy     |
