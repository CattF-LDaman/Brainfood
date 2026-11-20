# Brainfood

Explorations in machine learning, deep learning, and data science on real datasets—mostly via Jupyter notebooks.

## Setup (`uv`)

Uses **[uv](https://docs.astral.sh/uv/)** and a committed **`uv.lock`**.

```bash
cd Brainfood
uv sync
uv run python -m ipykernel install --user --name brainfood
uv run jupyter lab
```

Notebooks live under `notebooks/`. Add packages with `uv add <package>` (updates `pyproject.toml` and `uv.lock`).