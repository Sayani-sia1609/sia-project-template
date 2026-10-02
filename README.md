# Sia Project Template

My personal reusable **Python project template** built with [Cookiecutter](https://github.com/cookiecutter/cookiecutter).

The goal is simple: instead of creating the same project structure manually every time, I can generate a clean, ready-to-use project in seconds.

## ✨ What It Provides

Every generated project comes with:

```text
project/
├── src/
│   └── project/
│       ├── __init__.py
│       └── main.py
├── tests/
│   └── __init__.py
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── docs/
├── .env.example
├── .gitignore
├── README.md
└── pyproject.toml
```

## 🚀 Usage

### 1. Install Cookiecutter

```bash
pipx install cookiecutter
```

### 2. Generate a new project

```bash
cookiecutter gh:Sayani-sia1609/sia-project-template
```

Cookiecutter will ask for:

```text
project_name
project_slug
description
author_name
```

For example:

```text
project_name: CardioSense
project_slug: cardiosense
description: AI-powered cardiovascular risk prediction
author_name: Sia
```

This generates a ready-to-use project:

```text
cardiosense/
├── src/
├── tests/
├── data/
├── notebooks/
├── docs/
└── pyproject.toml
```

## 🐍 Python Setup

Inside the generated project:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the project:

```bash
pip install -e .
```

Run the application:

```bash
python3 -m <project_slug>.main
```

Run tests:

```bash
pytest
```

## 🎯 Why I Made This

I was repeatedly creating the same basic structure whenever starting a new project.

Instead of manually rebuilding the boilerplate every time, I decided to create my own reusable template.

This is intended primarily for my **Python, AI/ML, computer vision, backend, and experimental projects**.

## 🛠️ Tech

- Python
- Cookiecutter
- setuptools
- pytest
- `src/` project layout

## 📌 Status

This is a personal template and will evolve as my preferred project structure and workflow improve.

## 👤 Author

**Sia**

GitHub: [@Sayani-sia1609](https://github.com/Sayani-sia1609)
