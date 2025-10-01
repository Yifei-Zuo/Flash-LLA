# Flash-LLA

## Installation

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
uv venv ~/.venv/flash-lla-env --python=3.11 && source ~/.venv/flash-lla-env/bin/activate && uv pip install --upgrade pip --link-mode=copy
uv pip install -r requirements.txt --link-mode=copy
uv pip install flash-attn causal-conv1d mamba-ssm --no-build-isolation --no-deps --link-mode=copy
uv pip install flash-linear-attention --link-mode=copy
```
