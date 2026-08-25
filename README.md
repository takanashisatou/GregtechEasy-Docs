# GregTech Easy (GTE) Official Multilingual Documentation & Wiki

[![Docs Deploy](https://github.com/takanashisatou/GregtechEasy/actions/workflows/docs-deploy.yml/badge.svg)](https://github.com/takanashisatou/GregtechEasy/actions/workflows/docs-deploy.yml)
[![Live Site](https://img.shields.io/badge/Live%20Docs-GitHub%20Pages-teal.svg)](https://takanashisatou.github.io/GregtechEasy/)

This repository is the official multilingual documentation repository for **GregTech Easy (GTE-Multi)**, hosted via GitHub Pages and built with **MkDocs Material** + **static-i18n**.

---

## 📖 Structure / 目录结构

```text
├── docs/
│   ├── assets/       # Branding, logos, favicons, diagrams
│   ├── overrides/    # Material for MkDocs template customizations
│   ├── zh/           # 18 Complete Chinese Chapters (全量中文文档)
│   ├── en/           # 18 Mirror English Chapters (1:1 对齐英文文档)
│   ├── tables/       # CSV/Excel recipe balance tables
│   └── papers/       # LaTeX mathematical models & whitepapers
├── mkdocs.yml        # MkDocs configuration & navigation matrix
├── requirements.txt  # Python documentation dependencies
├── serve_docs.bat    # Windows 1-click live preview with hot reloading
└── serve_docs.sh     # Linux / macOS / WSL live preview script
```

---

## 🚀 Local Development / 本地热重载预览

### Windows (Double-click or run from terminal):
```bat
serve_docs.bat
```

### Linux / macOS / WSL:
```bash
./serve_docs.sh
```

Preview at: **`http://127.0.0.1:8000/GregtechEasy/`**
