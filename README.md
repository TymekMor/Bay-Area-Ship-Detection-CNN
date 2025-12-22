## Quick Start

This project uses [**uv**](https://github.com/astral-sh/uv), a high-performance Python package and project manager.

### 1. Prerequisites
Install `uv` if you haven't already:
* **macOS/Linux:** `curl -LsSf https://astral.sh/uv/install.sh | sh`
* **Windows:** `powershell -c "irm https://astral.sh/uv/install.ps1 | iex"`

### 2. Installation & Setup
Clone the repository and initialize the environment. `uv` will automatically install the correct Python version and all required dependencies.

```bash
# Clone the repo
git clone https://github.com/TymekMor/Bay-Area-Ship-Detection-CNN.git

# Create venv and install dependencies
uv sync

# Launch Jupyter Lab with project dependencies
uv run --with jupyter jupyter lab