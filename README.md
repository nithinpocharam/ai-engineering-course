# Project Title

## Overview

This repository contains a collection of **Agentic AI** applications and learning resources developed during the **Codebasics AI Engineering Bootcamp (Cohort 2)**. The project demonstrates various AI engineering concepts, including prompt engineering, tool usage, retrieval‑augmented generation, and integration with vector databases.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```
2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set up environment variables**
   - Copy the example env file and fill in your API keys:
     ```bash
     cp .env.example .env
     ```
   - Edit `.env` and provide values for `OPENAI_API_KEY`, `CHROMADB_PATH`, etc.

## Usage

The project is organized into modular notebooks and scripts. Below is a quick start for the most common workflows:

### Running a Notebook

```bash
jupyter notebook
```
Open the desired notebook (e.g., `rag_chromadb.ipynb`) and execute the cells.

### Executing a Script

```bash
python scripts/run_agent.py --config configs/agent_config.yaml
```

## Examples

- **Retrieval‑Augmented Generation (RAG) with ChromaDB** – See `rag_chromadb.ipynb` for a step‑by‑step example of building a RAG pipeline.
- **Agentic Workflow** – The `scripts/run_agent.py` script demonstrates how to chain multiple tools and LLM calls.

## Contribution Guidelines

We welcome contributions! Please follow these steps:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** and ensure the code passes linting and tests.
4. **Write or update documentation** as needed.
5. **Commit your changes** with a clear commit message.
6. **Push to your fork** and open a Pull Request against the `main` branch.

### Code Style
- Follow PEP 8 guidelines.
- Use type hints where appropriate.
- Run `black .` and `flake8` before committing.

### Reporting Issues
If you encounter a bug or have a feature request, please open an issue with a clear description and steps to reproduce.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

*Happy coding!*
