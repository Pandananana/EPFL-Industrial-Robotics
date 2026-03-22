# Industrial Robotics

## Getting Started

### 1. Install uv

**macOS / Linux:**

```sh
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows:**

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

See the [uv installation docs](https://docs.astral.sh/uv/getting-started/installation/) for other methods (Homebrew, pip, etc.).

### 2. Sync dependencies

From the project root, run:

```sh
uv sync
```

This creates a `.venv` virtual environment and installs all project dependencies.

### 3. Run Jupyter notebooks

Install the Jupyter VS Code extension:

1. Open VS Code / Cursor
2. Go to the Extensions panel (`Cmd+Shift+X` / `Ctrl+Shift+X`)
3. Search for **Jupyter** (`ms-toolsai.jupyter`) and install it

Open any `.ipynb` file, then select the kernel:

1. Click **Select Kernel** in the top-right of the notebook
2. Choose **Python Environments…**
3. Select/enter the `.venv/bin/python` interpreter (`.venv (Python 3.13)`)

You can now run cells in the notebook.
